# Project-climate-change ##
### Project title: The Effect of Climate Change on Population Growth: a Machine Learning Approach
#### Note
Due to data privacy restriction, the csv file cannot be shared. I would recommend going to https://gaez.fao.org/ for data details. 
#### Folder/File Instructions
1. This is a coding and research writing demonstration
2. Final paper:  "paper_ml.pdf" 
3. Final code (python): "project1_code.ipynb" 

The .ipynb file has three key subsections: summary statistics, PCA, Neural Networks, and LASSO regression.
1. The first section cleans the dataset by dropping 13 grid cell observations that do not have measurements on population density, and selectively filter out the most econometrically-feasible independent variables following the working paper by Henderson, Storeygard, and Weil (2022). It also renames the variables. The reasons for dropping certain variables are well-explained in Jupyter documentation.
2. The second section reduces the dimensionaly of 44 climate variables to 5 principle components, and further runs a Poisson specification on the principle components. 
3. The third section is an exploratory section of neural networks, for the scope of the class project not included in the final paper
4. The fourth section runs LASSO.
This is the updated as of 3/27/2023.
#### Acknowledgement
This project greatly benefited from Professor Weil and Bo-Yeon Jang. I am greatful to them and encourage interested readers to visit Prof. Weil's website for more information on his own projects.
