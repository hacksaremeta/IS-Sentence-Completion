# IS-Sentence-Completion

The goal of this project is to implement a sentence completion mechanism based on a recurrent neural network in Python and evaluate the quality and problems of this approach.

## Project structure

📦IS-Sentence-Completion  
 ┣ 📂doc  
 ┃ ┣ 📂baseline  
 ┃ ┣ 📂datasets  
 ┃ ┣ 📂models  
 ┃ ┣ 📂optimization  
 ┃ ┗ 📂tokenizer  
 ┣ 📂logs  
 ┃ ┗ 📂training  
 ┣ 📂res  
 ┃ ┣ 📂datasets  
 ┃ ┃ ┗ 📜...  
 ┃ ┣ 📂models  
 ┃ ┃ ┣ 📜...  
 ┃ ┃ ┗ 📜readme.txt  
 ┃ ┗ 📂tokenizers  
 ┃   ┗ 📜...  
 ┣ 📜is_autocomplete.ipynb  
 ┗ 📜README.md  

The resources and diagrams used in the documentation can be found in the `doc` folder. The `logs/training` folder contains TensorBoard logs (including network graph and metric data) for visualization. **Datasets**, **models** and corresponding **tokenizers** are saved in the `res` folder and the code as well as markdown documentation can be found in `is_autocomplete.ipynb`.

## Installation / How to run

First open a Terminal / Powershell window in the project folder.

1) Install Jupyter Notebook:
   - Linux & Windows: `pip install notebook`
2) **Optional**: Installing dependencies manually:
   - Linux & Windows: `pip install -r requirements.txt`
3) **Optional**: Tensorflow-directml for training on GPU:
   - Linux & Windows: `pip install tensorflow-directml`
4) Run the notebook
   - Linux: `jupyter notebook`
   - Windows: `jupyter-notebook.exe .`
