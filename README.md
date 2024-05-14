## Diabetic Retinopathy Detection using ResNet

This project focuses on the detection of diabetic retinopathy using deep learning techniques, specifically utilizing the ResNet (Residual Network) architecture. The dataset used for training and testing is sourced from Kaggle, providing a comprehensive set of retinal images labeled with diabetic retinopathy severity levels.

### Dataset
The dataset used in this project is available on Kaggle and consists of retinal fundus images categorized into different stages of diabetic retinopathy severity. The images are labeled with grades ranging from 0 (no retinopathy) to 4 (severe retinopathy).

- **Dataset Source:** [Kaggle Diabetic Retinopathy Detection](https://www.kaggle.com/c/diabetic-retinopathy-detection/data)

### Project Structure
The repository is structured as follows:

- **`data/`**: Directory to store the dataset (not included in this repository due to size).
- **`models/`**: Contains trained ResNet models (not included in this repository).
- **`notebooks/`**: Jupyter notebooks for data exploration, model training, and evaluation.
- **`src/`**: Python scripts for data preprocessing, model architecture, training, and testing.

### Requirements
Ensure you have the following dependencies installed to run the project:

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pandas

You can install the required packages using pip:

```bash
pip install -r requirements.txt
```

### References
- Dataset: [Kaggle Diabetic Retinopathy Detection](https://www.kaggle.com/c/diabetic-retinopathy-detection/data)
- TensorFlow: [tensorflow.org](https://www.tensorflow.org/)
- Keras: [keras.io](https://keras.io/)

### Acknowledgements
- The dataset is sourced from the Kaggle competition "Diabetic Retinopathy Detection" organized by the Kaggle community.

### License
This project is licensed under the [MIT License](LICENSE).
