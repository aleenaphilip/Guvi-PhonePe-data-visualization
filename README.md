# Data Visualization and Exploration : A User-Friendly Tool Using Streamlit and Plotly

The PhonePe Pulse website showcases more than 2000+ Crore transactions by consumers on an interactive map of India. With over 45% market share, PhonePe's data is representative of the country's digital payment habits. The insights on the website and in the report have been drawn from two key sources - the entirety of PhonePe's transaction data combined with merchant and customer interviews. The report is available as a free download on the PhonePe Pulse website and GitHub.

Required Libraries/Modules

1. Plotly - (To plot and visualize the data)
2. Pandas - (To Create a DataFrame with the scraped data)
3. Streamlit - (To Create Graphical user Interface)
4. json - (To load the json files)
5.git.repo.base - (To clone the GitHub repository)
6. Mysql connector


Workflow

1. Importing the Libraries  :   import all those libraries. If the libraries are not installed already use the below piece of code to install.
2. Data extraction : Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON.
3. Data transformation : In this step the JSON files that are available in the folders are converted into the readeable and understandable DataFrame format by using the for loop and 
                         iterating file by file and then finally the DataFrame is created. 
4. Database insertion : To insert the datadrame into SQL first I've created a new database and tables using "mysql-connector-python" library in Python to connect to a MySQL database and 
                        insert the transformed data using SQL commands.
5. Dashboard creation : Create colourful and insightful dashboard. Plotly's built-in Pie, Bar, Geo map functions are used to display the data on a charts and map and Streamlit is used 
                        to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.
6. Data retrieval : Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.
