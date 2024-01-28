# Multitask-Representation-Learning-with-Temporal-Attention-for-Zero-Shot-Time-Series-AD
Source code of the research paper "Multitask Representation Learning with Temporal Attention for Zero-Shot Time Series Anomaly Detection"

# Method
We propose a multi-task LSTM autoencoder with temporal attention mechanism (MTL-LATAM) framework for timeseries anomaly detection.

# Datasets
Experimental evaluation is performed on two datasets: a real-world photovoltaic inverter dataset(PID) and on an open-source Skoltech Anomaly Benchmark ([SKAB](https://github.com/waico/SKAB)) dataset.

# File Structure
```
├── utils.py
├── PID_Dataset_Models
│ ├── CONVAE_and_CONVATTNAE.ipynb
│ ├── TCNAE_and_TCNATTNAE.ipynb
│ ├── CONV-LSTMAE_and_CONV-LSTMATTNAE.ipynb
│ ├── LSTMAE_and_LSTMATTNAE.ipynb
│ └── AttentionWeights_Visualization.ipynb
├── SKAB_Dataset_Models
│ ├── CONVAE_and_CONVATTNAE.ipynb
│ ├── TCNAE_and_TCNATTNAE.ipynb
│ ├── CONV-LSTMAE_and_CONV-LSTMATTNAE.ipynb
│ ├── LSTMAE_and_LSTMATTNAE.ipynb
│ └── AttentionWeights_Visualization.ipynb
└── README.md
```

├── utils.py
├── PID_Dataset_Models/
│   ├── CONVAE_and_CONVATTNAE.ipynb
│   ├── TCNAE_and_TCNATTNAE.ipynb
│   ├── CONV-LSTMAE_and_CONV-LSTMATTNAE.ipynb
│   ├── LSTMAE_and_LSTMATTNAE.ipynb
│   └── AttentionWeights_Visualization.ipynb
├── SKAB_Dataset_Models/
│   ├── CONVAE_and_CONVATTNAE.ipynb
│   ├── TCNAE_and_TCNATTNAE.ipynb
│   ├── CONV-LSTMAE_and_CONV-LSTMATTNAE.ipynb
│   ├── LSTMAE_and_LSTMATTNAE.ipynb
│   └── AttentionWeights_Visualization.ipynb
└── README.md



