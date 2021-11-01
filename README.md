#Correlation between Salaries and different attributes of an individual in the STEM field

Using a dataset I found on kaggle ( https://www.kaggle.com/jackogozaly/data-science-and-stem-salaries ) to find the correlation between total yearly compensation and various other attributes related to an individual. However, any other variables could've been used to find the correlation with rest of the attributes.

I cleaned the dataset in excel to remove unwanted columns/attributes. The final dataset has been uploaded to the github repo for this project. Then I checked the percentage of missing data. Since this is a correlation project and the percentage of missing data is very low, I skipped deleting or replacing empty records.

I then proceeded to store the dataframe into decending order of totalyearlycompensation to see what other records have higher values too. This gave a rough idea as to which attributes have a positive correlation with totalyearlycompensation. The findings were that Years of experience, base salary, stock grant value, bonus, years at company, masters degree, doctorate degree will have a postive corelation with totalyearly compensation. 


The scatter plot for totalyearlycompensation and these attributes was plottted individually to see the relation. Finally, we computer the correlation table for the dataframe using pearson method. We visualize this table into a correlation matrix heatmap for better understanding.

Interesting findings:
Stock grant value has the highest correlation with yearly compensation. This could mean that the companies that have the most compensation give a lot of it through stocks and shares on the company.
Base salary and bonus have high corelation with yearly compensation as expected.
The more the experience you have in the field, the more paid you get. This is true in most cases and this can be seen with the corelation findings too.
The most surprising fact is the low corelation with masters and doctorate degree. One would expect that the more qualified a person is, the more compensation they get. However, this doesn't seem to be the case here. This goes to show that your skills and experience matters more than your qualifications.
