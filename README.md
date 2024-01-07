### 1. .txt file contains the necessary python packages
### 2. .ipynb file contains data preprocess, data visualization and some baseline methods like LR,LASSO and XGBoost.
### 3. Other .py files are about the core model, neural network.
### 4. Folder models/ contains checkpoints of models.
### 5. Folder logs/ contains the log file of experiments.
### 6. Here is how to launch the neural network:
  - python main.py --epoch 50 --lr 0.005 --batch 2048 --hidden_size 32 --num_layers 4
  - python main.py --epoch 50 --lr 0.005 --batch 512 --hidden_size 64 --num_layers 5
### 7. More parameters and its implication can be found in args.py
