# Air-Object-Path-predection-and-Collision-Avoidance-System
The Air Object Path Prediction and Collision Avoidance System is an AI-based solution designed to enhance aerial safety by predicting future trajectories of flying objects and proactively preventing mid-air collisions.
The system leverages Machine Learning, Kalman Filtering, and LSTM neural networks to forecast motion paths and trigger collision avoidance strategies in real time.

This project is developed as part of the B.Tech CSE (AI & ML) curriculum at SRM Institute of Science and Technology 

ML_REPORT

.

🎯 Problem Statement

Traditional air traffic and UAV monitoring systems are reactive and depend heavily on human supervision. They detect collisions only when objects are already close, leaving very little time for corrective action.

With the rapid growth of drones, UAVs, and autonomous aerial systems, there is a strong need for a predictive, intelligent, and automated collision avoidance system.

🚀 Proposed Solution

This project introduces an AI-driven predictive framework that:

Predicts future flight paths using LSTM neural networks

Filters noisy sensor data using Kalman Filters

Detects potential collisions in advance

Computes safe avoidance maneuvers

Visualizes trajectories and collision alerts in 3D

🧠 Technologies & Tools Used

Programming Language: Python

Machine Learning: LSTM (TensorFlow / Keras)

Filtering Technique: Kalman Filter

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib

Visualization: 3D trajectory plotting (Matplotlib)

Classifier: Logistic Regression (Collision Risk Prediction)

🏗️ System Architecture

Data Collection – Position (X, Y, Z), velocity, and orientation data

Preprocessing – Noise reduction using Kalman Filter

Trajectory Prediction – Future path prediction using LSTM

Collision Detection – Distance-based collision risk analysis

Avoidance Strategy – Path adjustment (altitude/direction)

Visualization – 3D real-time path and collision display

📂 Project Structure
├── ML FINAL CODE.ipynb        # Main implementation notebook
├── ML_REPORT.docx            # Project report
├── dataset.txt / csv         # Input trajectory data
└── README.md                 # Project documentation

⚙️ How to Run the Project
1️⃣ Install Dependencies
pip install numpy pandas matplotlib scikit-learn tensorflow

2️⃣ Open the Notebook
jupyter notebook "ML FINAL CODE.ipynb"

3️⃣ Upload Dataset

When prompted in the notebook, upload the trajectory dataset file.

4️⃣ Execute Cells Sequentially

The notebook performs:

Data preprocessing

LSTM training

Trajectory prediction

Collision detection

Classification & evaluation

3D visualization

📊 Results

Trajectory Prediction Accuracy: ~94.8%

Collision Detection Time: ~0.87 seconds

Avoidance Response Time: ~1.02 seconds

Visualization: Real-time 3D predicted vs actual paths

The system successfully predicts future paths and avoids collisions before they occur 

ML_REPORT

.

📈 Key Features

✔ Predictive (not reactive) collision detection
✔ Handles multiple aerial objects
✔ Autonomous avoidance decision-making
✔ Robust against sensor noise
✔ Clear 3D visualization

🔍 Applications

UAV and Drone Traffic Management

Autonomous Aerial Navigation

Military and Defense Air Systems

Urban Air Mobility (UAM)

Intelligent Air Traffic Control Systems

⚠️ Limitations

Simulation-based (real UAV integration pending)

Depends on sensor data quality

High computational cost for LSTM training

Weather effects not fully modeled

🔮 Future Enhancements

Real-time UAV hardware integration

Weather-aware trajectory prediction

Reinforcement Learning for adaptive avoidance

Multi-UAV swarm coordination

Cloud & satellite-based air traffic integration

👩‍💻 Authors

Mythri Panugatla

Prakhya Pranuthy Sri

SandhuHri Sindhu

Guided by Dr. S. Joseph James,
Assistant Professor, SRM IST 

ML_REPORT

📜 License

This project is developed for academic and research purposes
