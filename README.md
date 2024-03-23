# Early Alzheimer's MRI Image Classifier
This repository contains two Jupyter notebooks that demonstrate the development of an image classification model to identify stages of Alzheimer's disease using MRI images. The project showcases two approaches: building a convolutional neural network (CNN) model from scratch and applying transfer learning using MobileNetV2. This codebase was developed as part of the 2023 Fusemachines AI Fellowship as my capstone project.

## Project Structure
from_scratch_model.ipynb - This notebook contains the code for building and training a CNN model from scratch. It includes data preprocessing, model construction, training, and evaluation.
transfer_learning_model.ipynb - This notebook demonstrates the application of transfer learning using the pre-trained MobileNetV2 model to classify early Alzheimer's disease stages from MRI images. It covers data preprocessing adapted for MobileNetV2, model customization, training, and evaluation.

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- scikit-learn
- PIL

### Installation
Clone the repository to your local machine:

```
git clone https://github.com/your-username/alzheimers-mri-classifier.git
cd alzheimers-mri-classifier
```
Install the required Python packages:

```
pip install -r requirements.txt
```

### Usage
Open the desired notebook in Jupyter Notebook or JupyterLab:

```
jupyter notebook from_scratch_model.ipynb
# or
jupyter notebook transfer_learning_model.ipynb
```

Follow the instructions and code cells in each notebook to recreate the models.

## Data
The dataset used in this project consists of MRI images categorized into four classes representing different stages of Alzheimer's disease. 
The dataset is around 1.23GB. It is the work of Nina Daithal and her team. It can be found at:

https://www.kaggle.com/datasets/ninadaithal/imagesoasis/data

The team behind it worked it on a dataset that is part of The Open Access Series of Imaging Studies (OASIS). You can access the originals and learn more about the project at its website:

https://oasis-brains.org/

Note: The actual dataset is not included in this repository due to size and privacy concerns. Users should obtain and prepare their dataset according to the instructions provided in the notebooks.

## Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the AGPL-3.0 License - see the LICENSE file for details.

## Acknowledgments

Special thanks to the people behind the AI Fellowship at Fusemachines. I'm still learning a lot these days, and it's thanks to them that I had the chance to get started.

Thank you to all researchers and practitioners working in the field of Alzheimer's disease and neuroimaging.
