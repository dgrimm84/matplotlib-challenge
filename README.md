<font size="2.5">
  
# Pymaceuticals Inc. Analysis

### Primary functions of files included in this repository
> - The file named "main.ipynb" is in the /Pymaceuticals directory of this repository.  This is a jupyter notebook
> containing python code which analyzes the data, runs calculations, and creates visualizations of this data the
> functions it performs are:
> > - merge two provided csv files to get complete drug regimen study data<br>
> > - calculate the number of mice in the trial<br>
> > - find duplicate mice entries based on Mouse ID and Timepoint columns<br>
> > - capture the data of this duplicate mouse, and then clean the dataframe by removing all rows that reference it<br>
> > - re-count the number of unique mice in the study (248)<br>
> > - calculate mean, median, variance, standard deviation, and standard error for the Tumor Volume (mm3) column, then store in a dataframe<br>
> > - the same calculations as above are performed on one line with the more advanced aggregrate function to show funcionality<br>
> > - create, display, and write to file a bar chart of these results using the pandas.plot.bar function<br>
> > - do the same as above but with the python pyplot function<br>
> > - create, display, and write to file a pie chart using the pandas.plot.pie function<br>
> > - do the same as above but with the python plt.pie function<br>
> > - calculate quartiles and outliers for 4 drugs by using a for loop to cycle through each drug and displaying the results<br>
> > - create a box plot visualizing these calculations<br>
> > - create a line plot of timeplot versus tumor volume for the drug capomulin on one selected mouse<br>
> > - create a scatter plot showing the correlation between mouse weight and average tumor volume and write to file<br>
> > - plot a regression correlation line onto the same scatter plot above and write to file<br><br>
> - In the /data directory, the files contained are:<br>
> > - Mouse_metadata.csv - contains data for each mouse of the study (ID, Drug Regimen each went through, age, and weight (grams)<br>
> > - study_results.csv - contains the results of the study based on the mouse ID and includes timepoints, tumor volume at <br>
> > each timepoint, and metastatic sites measured at each timepoint.<br>
> > - pandas_bar_plot.png - displays the bar plot created using the pandas method<br>
> > - pyplot_bar_plot.png - displays the bar plot created using the python plt method<br>
> > - pandas_pie_plot.png - displays the pie plot created using the pandas pie method<br>
> > - plt_pie_plot.png - displays the pie plot created using the python plt method<br>
> > - box_plot.png - displays the box plot created with the quartile and outliers calculations<br>
> > - line_plot.png - displays the line plot created with tumor volume vs. timepoint data<br>
> > - scatter_plot.png - displays the scatter plot created with mouse weight vs. tumor volume correlation<br>
> > - regression_scatter_plot.png - displays the scatter plot with the regression correlation line plotted as well.<br>

### Analysis of drug regimen results on 248 unique mice in this drug trial
> - Based on the data from the gender pie chart summary calculation, this study had a good and even representation of male vs. female mice<br><br>
> - Based on the Final Tumor Volume box plot, a conclusion could be drawn that mice on the Capomulin and Ramicane
> regimens fared better than the mice on the Infubinol and Ceftamin regimens. This is because the tumor volume<br>
> at the final / latest timepoint for the mice on the regimens was on average quite a bit smaller on<br>
> Capomulin and Ramicane than they were on Infubinol and Ceftamin<br><br><br>
> - Based on the line plot of mouse B128 on the Capomulin treatment, a decrease in tumor volume over time is<br>
> very noticeable within the first 35 days. However, the last 10 days there is what seems to be tumor rebound growth.<br>
> This may seem to indicate that Campomulin is an effective treatment for a certain period of time,<br>
> but the tumor may become resistant to the treatment after long enough exposure to the regimen<br><br>
> - Visually, one could initially determine that a positive and noticeable correlation between increase in mouse weight<br>
> causes an increase in average tumor volume. This is because the scatter plot of the regression model does look<br>
> like a very positive correlation at first glance<br><br>
> - However, once the regression calculation, slope, intercept r-value, and r-squared value are calculated and<br>
> plotted onto the scatter plot, a correlation coefficient of under 1 (0.7) shows a positive correlation,<br>
> but an imperfect one. <br><br>
