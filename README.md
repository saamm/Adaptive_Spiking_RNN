# Adaptive_Spiking_RNN

Adaptive-Spiking-RNN/
│
├── README.md
├── requirements.txt
├── environment.yml
├── LICENSE
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── download_data.py
│
├── configs/
│   ├── baseline.yaml
│   ├── adaptive.yaml
│   └── noise_experiment.yaml
│
├── models/
│   ├── lif.py
│   ├── alif.py
│   ├── recurrent_snn.py
│   ├── adaptive_snn.py
│   ├── surrogate.py
│   └── utils.py
│
├── datasets/
│   ├── shd_dataset.py
│   ├── noise.py
│   └── transforms.py
│
├── training/
│   ├── trainer.py
│   ├── losses.py
│   ├── metrics.py
│   └── scheduler.py
│
├── evaluation/
│   ├── evaluate.py
│   ├── robustness.py
│   ├── energy.py
│   ├── spike_statistics.py
│   └── explainability.py
│
├── visualization/
│   ├── raster.py
│   ├── membrane.py
│   ├── latent_space.py
│   └── plots.py
│
├── experiments/
│   ├── baseline.py
│   ├── adaptation.py
│   ├── robustness.py
│   └── ablation.py
│
├── notebooks/
│   ├── DataExploration.ipynb
│   ├── Visualizations.ipynb
│   └── Analysis.ipynb
│
└── outputs/
    ├── checkpoints/
    ├── figures/
    └── logs/
