<font size="2.5">
  
# Pymaceuticals Inc. Analysis

### Primary functions of files included in this repository
> - The file named "main.ipynb" is in the main directory of this repository.  This is a jupyter notebook document containing python code<br>
> which analyzes the data, runs calculations, and creates visualizations of this data
> - In the /data directory, there is are two files:
> > - Mouse_metadata.csv - contains information for each mouse of the study (ID, Drug Regimen each went through, age, and weight (grams)<br>
>> - study_results.csv - contains the results of the study based on the mouse ID and includes timepoints, tumor volume at each timepoint,<br>
>> and metastatic sites measured at each timepoint.


### Analysis of drug regimen results on 248 unique mice in this drug trial
> - Based on the data from the gender pie chart summary calculation, this study had a good and even representation of male vs. female mice<br><br>
> - Based on the Final Tumor Volume box plot, a conclusion could be drawn that mice on the Capomulin and Ramicane regimens fared better than<br>
> the mice on the Infubinol and Ceftamin regimens. This is because the tumor volume at the final / latest timepoint for the mice on the<br>
> regimens was on average quite a bit smaller on Capomulin and Ramicane than they were on Infubinol and Ceftamin<br><br>
> - Based on the line plot of mouse B128 on the Capomulin treatment, a decrease in tumor volume over time is very noticeable within the first<br>
> 35 days. However, the last 10 days there is what seems to be tumor rebound growth.  This may seem to indicate that Campomulin is an effective<br>
> treatment for a certain period of time, but the tumor may become resistant to the treatment after long enough exposure to the regimen<br><br>
> - Visually, one could initially determine that a positive and noticeable correlation between increase in mouse weight causes an increase <br>
> in average tumor volume. This is because the scatter plot of the regression model does look like a very positive correlation at first glance<br><br>
> - However, once the regression calculation, slope, intercept r-value, and r-squared value are calculated and plotted onto the scatter plot,<br>
> a correlation coefficient of under 1 (0.7) shows a positive correlation, but an imperfect one. <br><br>
