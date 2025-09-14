🚀 Getting-Started-with-PyTorch-on-GPU

Predicting car fuel efficiency (MPG) using the Auto MPG dataset with PyTorch.  
The project covers data preprocessing, one-hot encoding, and training a neural network for regression with GPU acceleration.  
A beginner-friendly introduction to deep learning on tabular data.  

---

📌 Project Overview
This project demonstrates how to:
- Prepare tabular data for deep learning (normalize numeric features, one-hot encode categorical features).
- Build and train a regression model using **PyTorch**.
- Implement a custom training loop (forward pass → loss → backpropagation → optimizer update).
- Use **GPU acceleration (CUDA)** for efficient training.

The dataset used is the **UCI Auto MPG dataset**, which contains car attributes like cylinders, displacement, horsepower, weight, acceleration, and origin.

---

⚙️ Tech Stack
- **Python 3.8+**
- **PyTorch** (for model training and GPU acceleration)
- **scikit-learn** (for splitting dataset and preprocessing)
- **pandas** & **NumPy** (for data handling)
- **Jupyter Notebook** (for development)

---

🚀 How to Run

1. **Clone this repository**
   ```bash
  git clone https://github.com/satyamk1234/Getting-Started-with-PyTorch-on-GPU.git
  cd Getting-Started-with-PyTorch-on-GPU

2. Install dependencies
  pip install -r requirements.txt

3. Run the notebook
  jupyter notebook fuel_eff.ipynb

📊 Results

Built a regression model to predict car MPG with good accuracy.

Demonstrated how GPU training reduces computation time, even for small datasets.

Showed a complete workflow for applying neural networks to tabular regression problems.

🎯 Learning Outcomes

Data preprocessing: normalization & one-hot encoding

Neural network regression in PyTorch

Custom training loop implementation

GPU utilization with CUDA

📂 Project Structure 
├── fuel_eff.ipynb # Main notebook 
├── requirements.txt # Python dependencies 
├── README.md # Project documentation

🙌 Acknowledgments 
Dataset: UCI Auto MPG Dataset 
Book Reference: Machine Learning with PyTorch and Scikit-Learn by Sebastian Raschka et al.
