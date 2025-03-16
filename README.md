### 📌 **Reinforcement Learning for Optimal Policy**

🚀 This project implements **Reinforcement Learning (RL)** to optimize decision-making using **Q-Learning**. The dataset consists of state-action pairs, where the agent learns the best actions based on rewards.

---

## 📂 **Project Structure**
```
📁 Reinforcement-Learning
│── 📄 README.md          # Project documentation
│── 📄 reinforcement_learning.ipynb  # Jupyter Notebook with implementation
│── 📄 OptimalPolicy_angletol45.csv   # Dataset used for training
│── 📂 results/            # Visualizations & outputs
```

---

## 📊 **Dataset Overview**
The dataset contains **1,140 rows** and **11 columns**, including:
- 🏷 **State Variables**: `state_x`, `state_y`
- 🎯 **Actions**: `move_dir`, `throw_dir`, `Action`
- 📈 **Movement Data**: `move_x`, `move_y`, `u`, `v`

🛠 **Preprocessing Steps:**
- ✅ Label Encoding for categorical values.
- ✅ Min-Max Scaling for numerical values.
- ✅ Data visualization for better understanding.

---

## 🔥 **Reinforcement Learning Approach**
This project implements **Q-Learning**, where the agent:
1. **Explores** new actions 🤖  
2. **Exploits** the best learned actions ✅  
3. Updates a **Q-Table** based on rewards 📊  

📌 **Key Visualizations:**
- 📈 **Rewards per Episode**
- 🔥 **Q-Table Heatmap**
- 🎯 **Policy Comparison (RL vs. Random)**

---

## 📦 **Installation & Usage**
### 🔹 **1. Clone the Repository**
```bash
git clone https://github.com/your-username/Reinforcement-Learning.git
cd Reinforcement-Learning
```
### 🔹 **2. Install Dependencies**
```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```
### 🔹 **3. Run the Jupyter Notebook**
```bash
jupyter notebook Reinforcement Learning.ipynb
```

---

## 📌 **Results & Insights**
🔹 The agent learns optimal actions by balancing **exploration** & **exploitation**.  
🔹 The **Q-Table** shows structured values, proving that the agent has successfully learned.  
🔹 The **cumulative reward plot** confirms improved decision-making over time.  

