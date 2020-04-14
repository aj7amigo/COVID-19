# COVID-19
Web scrapping COVID-19 data using python, plotting pie charts using pandas and matplotlib, send emails with the plots as attachment

## Website used for fetching data
https://worldometers.info/coronavirus/

## Workflow
1. Fetch the data from the website using web scrapping tool (BeautifulSoup).
2. Arrange the data as a pandas data frame.
3. Plot the data using pandas and matplotlib. Save the plot.
4. Set up SMTP to send the plot as an attachment in an email. (gmail used in the code)

## Note
You will need to point the location of the 'email.txt' file in the jupyter notebook or keep the file in the same execution folder. In the 'email.txt' file, you will have to replace the lines with the senders email address, password and the receivers email address.
