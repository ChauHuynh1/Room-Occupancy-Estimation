# Room Occupancy Estimation
RMIT University Vietnam \
Course: 	*EEET2485  Research Method for Engineers* \
Semester: *2022B* \
Assessment name: *Group Project* \
Team members: 
1. Nguyen Dang Huynh Chau - s3777214
2. Truong Phu Khang - s3814172
3. Le Anh Quan - s3777351

# INTRODUCTION:
This is a data analysis project on the room occupancy estimation. In this project, we exhibited several data analysis approaches on a synthetic predictive maintenance dataset in this research. Many questions about the dataset, as well as the hypotheses we made while working on the data exploration process, were answered. The parameters' correlations were investigated and tested with the Spearman’s rho. The main factors causing the number of room occupancy are also discovered by factor analysis and tested with a decision tree model. Finally, the relationship of the room occupancy and the main factos is also explored by plots and tested with the Man-Whitney testing method. Thanks to the project, we learnt how to use various research methodologies and statistical analysis to evaluate our grasp of the subject and test hypotheses throughout the project. Furthermore, designing tests and determining outcomes has broadened our knowledge and has become a necessary ability for our young engineering team.

# COMPONENTS:
* **Jupyter notebook**: We use the Jupyter notebook to perform our data analysis project

# How to use this app:
python version 3.8.8

1. Install Conda
   by [following these instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Add Conda
   binaries to your system `PATH`, so you can use the `conda` command on your terminal.

2. Install jupyter lab and jupyter notebook on your terminal

+ `pip install jupyterlab`
+ `pip install jupyter notebook`

### Jupyter Lab

1. Download the 3879312 zipped project folder. Unzip it by double-clicking on it.

2. In the terminal, navigate to the directory containing the project and install these packages and libraries

```
pip install -r requirements.txt
```

3. Enter the newly created directory using `cd directory-name` and start the Jupyter Lab.

```
jupyter lab
```

You can now access Jupyter's web interface by clicking the link that shows up on the terminal or by
visiting http://localhost:8888 on your browser.

4. Click on assignment2.ipynb in the browser tab. This will open up my main file in the Jupyter Lab.

### Note: If the Jupyter Notebook is not responding due to many requests

Error [(The page is not responding)](https://stackoverflow.com/questions/48615535/jupyter-notebook-takes-forever-to-open-and-then-pages-unresponsive-mathjax-i)

I had to restart the notebook; and it did not work. This is because I was printing out too much and the following
scripts resolved the issue by clear out all the output to run through the whole kernal:

1. `conda install -c conda-forge nbstripout` or `pip install nbstripout`

2. `nbstripout filename.ipynb`

## Repository Structure

```
├── LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── Occupancy_Estimation.csv       <- Data from third party sources.
│
├── EEET2485_GroupProject.ipynb          <-This is the data analysis source code
|
|── ResearchMethod_Report.docx           <-This is the data analysis report
|
|── Research_Questions.docx              <-This is the research question list
|
|── Group10_Research.pptx     <-This is the research question presentation slide


```

# Acknowledgement
* Dr. Dao Vu Truong Son - our lecturer