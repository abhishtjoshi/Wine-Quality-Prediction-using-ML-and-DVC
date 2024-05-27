create env
'''
conda create -n wineq python=3.7 -y
'''

activate env
'''
conda activate wineq
'''
Create requierement.txt file
'''
pip install -r requiements.txt
'''

git init

dvc init 

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

Lets test Git Branching - Nidhi


Abhisht here added a comment in the main branch