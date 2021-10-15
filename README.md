# CS7641_HW2
This is the project for CS7641 HW2. 
1. Environment to run the code.
python version: 3.9.4
all the packages required for this project are in requirement.txt
use the following command to install all the required packages:
pip install -r requirements.txt

2. Structure of the project

three folders under  folder CS7641_HW2:
data/
	breast_cancer_dataset.csv
scripts/
	randomized_optimization.ipynb

3. How to run the script
1)install the packages required for this project using above mentioned command.
2)install jupyter notebook
3)open the randomized_optimization.ipynb under the folder of scripts in jupyter notebook
Note: the data were loaded using the relative path. If you change the structure of the project,
please change the relative path to read the csv files respectively. It took several hours to 
run the script since genetic algorithm needs a long time to converge when optimizing weights
of the neural network.
