# LinkedIn network insight
LinkedIn is a type of social network but it doesn't get you any specific information about your connections and network. In this notebook, I use pandas and group my connections by companies and positions. I define some keywords for companies and positions and group persons in my network by them also.

You can get a copy of your Linkedin data as a CSV file from [Settings & Privacy](https://www.linkedin.com/psettings/) page. (we just need Connections and check it)

In the Connections.csv we have "First Name", "Last Name", "Email", "Company", "Position" and "Connected On" columns. First, we read this file using pandas then drop rows with the "NaN" value, and finally, drop "Email" and "Connected On" columns. our data frame is ready and we can group persons by columns.

In the end, I use [this](https://towardsdatascience.com/visualizing-my-linkedin-network-c4b232ab2ad0) to visualize my network using plotly.
