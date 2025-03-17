# NILM Using Federated Learning

## Overview
This repository contains a Jupyter Notebook demonstrating **Non-Intrusive Load Monitoring (NILM)** using **Federated Learning**. The goal is to disaggregate household energy consumption data while preserving user privacy by leveraging decentralized machine learning techniques.

## Features
- Implementation of **Federated Learning** for NILM.
- Uses real-world **energy datasets**.
- **Privacy-preserving** approach by keeping user data on local devices.
- Training across multiple clients using **PyTorch/Federated Learning frameworks**.
- **Performance metrics and visualization** for model evaluation.

## Dataset
The notebook supports various publicly available NILM datasets such as:
- [IRISE](https://remodece.isr.uc.pt/)
- [REFIT](https://pureportal.strath.ac.uk/en/datasets/refit-electrical-load-measurements-cleaned)

Users can modify the dataset path in the notebook to work with different datasets.

## Installation
To run the notebook, ensure you have Python installed along with the required dependencies. You can set up the environment using:

```bash
# Clone the repository
git clone https://github.com/yourusername/NILM-Federated-Learning.git
cd NILM-Federated-Learning

# Create a virtual environment (optional)
python -m venv env
source env/bin/activate   # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## Running the Notebook
Start Jupyter Notebook and open the `.ipynb` file:

```bash
jupyter notebook
```

Run the cells step-by-step to train and evaluate the federated learning NILM model.

## Model Architecture
The notebook implements a deep learning model using **CNNs** for NILM disaggregation. 

## Results
- The notebook provides visualizations for training loss, accuracy, and disaggregation results.
- Federated Learning performance is compared with centralized NILM models.
- Metrics include **Mean Absolute Error (MAE), Normalized Root Mean Sqruared Error (NRMSE), and Energy Disaggregation Accuracy**.

## Contributions
Contributions are welcome! Please fork the repository, create a branch, and submit a pull request with improvements.


## Contact (Including Dataset)
For any queries or discussions, feel free to reach out via GitHub Issues or email `Fares.alkhawaja@gmail.com`.

---
Happy Coding! 🚀

