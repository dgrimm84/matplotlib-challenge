<font size="2.5">
  
# Pymaceuticals Inc. Analysis

### Primary functions of files included in this repository
> - The file named "main.ipynb" is in the main directory of this repository.  This is a jupyter notebook document containing python code<br>
> which analyzes the data, runs calculations, and creates visualizations of this data<br><br>
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
> > regimens fared better than the mice on the Infubinol and Ceftamin regimens. This is because the tumor volume<br>
> > at the final / latest timepoint for the mice on the regimens was on average quite a bit smaller on<br>
> > Capomulin and Ramicane than they were on Infubinol and Ceftamin<br><br><br>
> - Based on the line plot of mouse B128 on the Capomulin treatment, a decrease in tumor volume over time is<br>
> > very noticeable within the first 35 days. However, the last 10 days there is what seems to be tumor rebound growth.<br>
> > This may seem to indicate that Campomulin is an effective treatment for a certain period of time,<br>
> > but the tumor may become resistant to the treatment after long enough exposure to the regimen<br><br>
> - Visually, one could initially determine that a positive and noticeable correlation between increase in mouse weight<br>
> > causes an increase in average tumor volume. This is because the scatter plot of the regression model does look<br>
> > like a very positive correlation at first glance<br><br>
> - However, once the regression calculation, slope, intercept r-value, and r-squared value are calculated and<br>
> > plotted onto the scatter plot, a correlation coefficient of under 1 (0.7) shows a positive correlation,<br>
> > but an imperfect one. <br><br>
