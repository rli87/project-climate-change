# Project 1 Final Draft ##
### Project title: The Effect of Climate Change on Population Growth: a Machine Learning Approach
#### Note
Professor Handlan has permitted me to not upload my dataset given its gigantic size and data privacy restriction. 
#### Folder/File Instructions
1. Draft history: the "draft1.ipynb" file and "draft1.pdf" file are unupdated draft versions of the project
2. Final draft: the "project1_code.ipynb" file and "Project1_final.pdf" file are final papers and final codes for grading
3. Output folder: The "output" folder contains all figures, graphs, and tables from the project. The sub-folder "summary_tables" exports .csv files of the 5 PCAs on crop-suitability, moisture, thermal, soil-growth, and baseline variables."latex_tables" folder includes all latex code to tables in the project.
#### Code Instructions
The .ipynb file has three key subsections: summary statistics, PCA, Neural Networks, and LASSO regression.
1. The first section cleans the dataset by dropping 13 grid cell observations that do not have measurements on population density, and selectively filter out the most econometrically-feasible independent variables following the working paper by Henderson, Storeygard, and Weil (2022). It also renames the variables. The reasons for dropping certain variables are well-explained in Jupyter documentation.
2. The second section reduces the dimensionaly of 44 climate variables to 5 principle components, and further runs a Poisson specification on the principle components. 
3. The third section is an exploratory section of neural networks, for the scope of the class project not included in the final paper
4. The fourth section runs LASSO.
This is the final draft to the project.
#### Acknowledgement
This project greatly benefited from the shared data from Professor Weil and Bo-Yeon Jang. I am greatful to them and encourage interested readers to visit Prof. Weil's website for more information on his own projects.
