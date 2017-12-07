If you want to **view** this project you can do one of two things:
- You can either go to https://github.com/AbdulSaleh2020/CS50-Project and open CS50 Project.ipynb
   
- OR you can go to https://mybinder.org/, build this repository https://github.com/AbdulSaleh2020/CS50-Project
  and then open CS50 Project.ipynb. This is not very different from jsut viewing the project on GitHub but 
  binder makes the tables look a little bit nicer.

  If you follow the instrucitions above you will be able to view the project directly in your browser,
  but you won't be able to run any of the code. 

If you want to actaully run the code you have to follow these steps instead:

- The libraries required for this project are listed in the beginning of the CS50 Project.ipynb notebook in the GitHub
  repository linked above. I think you can download these libraries directly using pip if you already have Python
  but that's not what I did so I don't know if this would work. 

- If getting the libraries with pip doesn't work, you can just download Anaconda from https://www.anaconda.com/download/
  Anaconda is a Python distribution that comes with Jupyter, pandas, numpy, seaborn, and matplotlib.
- You can then install H2O from https://www.h2o.ai/download/
- Note that H2O requires Java which you can get from https://java.com/en/download/ 
- You can install fancyimpute by running pip install fancyimpute 
- Note that fancyimpute requires Visual C++ Build Tools for some reason. http://landinghub.visualstudio.com/visual-cpp-build-tools
- After you have all these libraries installed you can just run "jupyter notebook" in command prompt and run 
  CS50 Project.ipynb which is one of the files in our submission. 
- Now you can just select the cells and run the code but make sure to run the code **in order** so don't run any cell before running the one before 
  otherwise you might skip some important steps by mistake. 
- Note that running grid search might take anywhere between 10 mins to hours depending on your computer. So I don't really 
  recommend trying to train the machine learning algorithms again. 