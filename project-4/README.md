# Software Development Tools
[Open Web-app](https://tripleten-sda-project.onrender.com/)


This project aims to provide additional practice on common software engineering tasks. These tasks will augment and complement the data skills I've learned.
I'll be developing and deploying a web application to a cloud service so that it is accessible to the public.

## Streamlit Project
Software Development Tools Project: Pokemon Stats Graph

Hello! This web app was built to see the correlation between Pokemon stats up to Generation 6, based on the types.
Based on your selected input, the app will graph either a Scatterplot or a Histogram to show the Data. The input consists of the 
type of Pokemon and the stat on which you would like the graph to show. There's also an individual Pokemon Stat Calculator located on app2.py

Before I made the web-app, I had to to find a dataset that I would be working on. I have decided to work on a Pokemon dataset because I really like the game. I got my dataset from [Kaggle](www.kaggle.com). After obtaining the dataset, I opened the Jupyter  Noetbook and did some Exploratory Data Analysis. [Here's the link to the Jupyter Notebook.](https://github.com/reondaze-a/tripleten-projects/blob/main/project-4/notebooks/EDA%20Pokemon.ipynb) 


The libraries I've used include:
* Streamlit
* Plotly Express
* Numpy
* Pandas

And I also used a self-made module: pkmn_func.py

To launch it on your local machine, pull the repository to your local machine and then use a command shell(CMD, Git Bash, PowerShell)
and direct yourself to the repository's directory.  Go to `.streamlit` directory and disable or delete the `config.toml` file. Then in the command shell, enter the command: `streamlit run app.py` or `streamlit run app2.py`.

**Must have streamlit installed on your machine!**

If you don't you can run the command `pip install streamlit`.
