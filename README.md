🔦 Chest X-Ray Image Classifications

📌 Discription
open source로 제공되는 CheXpert dataset을 이용해서 classification 하는 모델을 구성해볼 예정

🎁 Directory 구조
chexpert_code
├── config
│   ├── example.json
│   ├── train.csv
│   └── valid.csv
├── data
│   ├── dataset.py
│   ├── imgaud.py
│   └── utils.py
├── model
│   ├── chexpert.py
│   ├── global_pool.py
│   ├── models.py
│   └── utils.py
├── requirement.txt
├── train.py
├── test.py
└── metrics.py
dataset
├── chexpert
│   ├── CheXpert-v1.0
│   │   ├── train
│   │   ├── valid
│   │   ├── train.csv
│   │   └── valid.csv
│   ├── CheXpert-v1.0-small
│   │   ├── train
│   │   ├── valid
│   │   ├── train.csv
│   └── └── valid.csv

📑 notebooks
- 
  
🎫 reference
https://stanfordmlgroup.github.io/competitions/chexpert/
https://github.com/jfhealthcare/Chexpert
https://github.com/thanhtran98/chexpert_pytorch_base
