# Fundamentals-of-Data-Analysis-Assessment-2019
My project for Fundamentals of Data Analysis, Assessment 2019

See here for the instructions: https://github.com/ianmcloughlin/project-2019-fundda/raw/master/project.pdf. 

Resources and references which were used during the course of this project are listed in the references section at the end of this Readme file.


About this Project    

This project deals with the well known tips dataset and the Python packages Seaborn and Jupyter. For this project I import the tips dataset and use the Python packages Seaborn and Jupyter to analyse the dataset in an attempt to to explain the details contained within the dataset. I also analyse the relationships between some of the variables.  Finally I have included a section on machine learning and attempting to calculate the expected tip paid by customers when inputting certain parameters.    

How to download this repository    
Go to GitHub.    
Go to my repository: https://github.com/bexiturley/Fundamentals-of-Data-Analysis-Assessment-2019    
Click the clone/download button.    
Save the repository locally to a folder location on your machine.    
Navigate to local folder location on the command line in order to run the program.    

How to view jupyter notebook    
On the command line, navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.    
Type jupyter notebook on the command line and press return.  Jupyter is a python package and comes by default installed with Anaconda. If Anaconda is not already installed it will have to be done so separately.    
Jupyter notebook will open in your web browser.  Google chrome is better than Microsoft edge to use for this.     
Open the .ipynb notebook in the browser and the notebook containing the code and comments will be displayed.    
In Jupyter notebook go to Kernel, restart and run all.  To execute the code in a single cell; hold down the shift key, press return and the command will run with the output displayed in the following cell.    
To toggle between edit and read mode press the ESC key.    
Save changes, if any, before closing. Shut down the web browser, return to the command line. Ctrl + C on the command line will terminate the session.       
    
    
Plan to complete the assignment:

Create git repository, send link to lecturer and make it available online.   Create jupyter notebook within the repository.    
Import/download dataset.    
Begin descriptive analysis via summary of statistics and plots.  Check to see if any data is corrupt/missing.    
    
Reacquaint myself with regression and what it means.    
Create the plots.    
Describe the output of the plots and see if there is a relationship between the total bill and tip amount.    
    
Analyse different variables within the data.  Create the code and comment on them.    
What does the data tell me.      
Is there any unusual observations?    
Can I predict a tip amount if I input my own parameters.    
What did I learn. Is this a good dataset. Any shortcomings.    
     
In addition to the above, keep detailed list of all references I looked up or read.     
    
    
Things of note.    
I have used graph and plot interchangeably.  They mean very different things usually but for this I ignored that.    
    
You can enter an unlimited number of arguments in a cell but only the last command will be returned.  Either put each one in a new cell or put a print command after each one.    
    
Markdown was used for comments and code for scripting. There is a white box near the top of the page which tells you which is which.

If I close the notebook then go back in and enter a new argument it may not run  if it is dependant on previous ones also executing first.  I can then go to CELL and RUN ALL or KERNEL and RESTART & RUN ALL.  RESTART & CLEAR OUTPUT starts the code from the beginning and the numbering on the left hand side will go in sequence.

It is very important to save as you go along but if the worst happens and the notebook wont load for whatever reason there are checkpoints when you save it.  You can rebuild from there.

CTRL+Z is undo. Very handy.  Other shortcuts are here https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/  It is very useful to print out and keep to hand.








    
*by Rebecca Turley*    
    
    
References and additional reading material     
    
How to import csv files:    
https://www.youtube.com/watch?v=eEIr70i8vbs    
    
https://dfrieds.com/data-analysis/groupby-python-pandas   
Contains a mistake. States that the sex column is in reference to the server. In other documents I viewed it stated the sex refers to the person paying the bill.     
    
https://towardsdatascience.com/    10-simple-hacks-to-speed-up-your-data-analysis-in-python-ec18c6396e6b    
     
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv     
Where I imported the tips.csv file from and called it df instead of the other variable one I used.    
     
Data Visualization    
https://amitkushwaha.co.in/data-visualization-part-1.html    
https://amitkushwaha.co.in/data-visualization-part-2.html    
https://blog.insightdatascience.com/    data-visualization-in-python-advanced-functionality-in-seaborn-20d217f1a9a6    
https://seaborn.pydata.org/tutorial/distributions.html    
    
Histograms in Python    
https://plot.ly/python/histograms/    
    
Building structures multi-plot grids    
https://seaborn.pydata.org/tutorial/axis_grids.html    
    
Seaborn    
https://towardsdatascience.com/    analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e    
https://analyticsindiamag.com/    a-simple-introduction-to-pythons-seaborn-library/    
https://towardsdatascience.com/matplotlib-seaborn-basics-2bd7b66dbee2    
    
Jointplot    
https://python-graph-gallery.com/82-marginal-plot-with-seaborn/    
    
Swarmplot    
https://stackoverflow.com/questions/44615759/      how-can-box-plot-be-overlaid-on-top-of-swarm-plot-in-seaborn      
    
Facetplot    
https://blog.insightdatascience.com/    data-visualization-in-python-advanced-functionality-in-seaborn-20d217f1a9a6    
    
KDE and violin plot using seaborn    
http://benalexkeen.com/kde-and-violin-plots-using-seaborn/    
https://seaborn.pydata.org/generated/seaborn.kdeplot.html    
https://blog.bioturing.com/2018/05/16/      5-reasons-you-should-use-a-violin-graph/    
https://seaborn.pydata.org/generated/seaborn.violinplot.html    
    
FacetGrid    
https://www.tutorialspoint.com/seaborn/seaborn_facet_grid.htm    
https://seaborn.pydata.org/generated/seaborn.FacetGrid.html    
    
Countplot    
https://www.tutorialspoint.com/seaborn/seaborn_quick_guide.htm    
    
Pointplot    
https://seaborn.pydata.org/generated/seaborn.pointplot.html    
     
Linear regression information    
https://www.geeksforgeeks.org/linear-regression-python-implementation/    
https://seaborn.pydata.org/tutorial/regression.html    
    
Seaborn regression plots    
https://www.geeksforgeeks.org/seaborn-regression-plots/    
    
Seaborn Categorical plots    
https://www.geeksforgeeks.org/seaborn-categorical-plots/    
     
Data Frame Info    
https://pandas.pydata.org/pandas-docs/stable/reference/api/    pandas.DataFrame.info.html    
    
Machine Learning Model    
https://devarea.com/python-machine-learning-example-linear-regression/    #.XdMC4uj7SUk    
    
Background on dataset    
https://datasciencechalktalk.com/2019/11/03/    interactive-analytics-and-predictions-on-restaurant-tips/    
    
Seaborn charts    
https://www.dataquest.io/blog/advanced-jupyter-notebooks-tutorial/    
    
Tips percent    
https://stackoverflow.com/questions/39439692/jupyter-qtpython-errors    
https://books.google.ie/books?id=BCc3DwAAQBAJ&pg=PA304&lpg=PA304&dq=%27tip_pct%27+jupyter+tips&source=bl&ots=bAqG76l0a3&sig=ACfU3U1RoDT_OpCaSUfO9ei_TIkC9s-qdQ&hl=en&sa=X&ved=2ahUKEwiToZ_X4vnlAhUoURUIHeCFD0oQ6AEwCnoECAoQAQ#v=onepage&q='tip_pct'%20jupyter%20tips&f=false    
    
Seaborn regplot    
https://seaborn.pydata.org/generated/seaborn.regplot.html    
    
Jupyter shortcuts
https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/