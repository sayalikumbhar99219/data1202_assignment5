**Executing Basic Python Commands in Jupiter Notebook**

In the world of data, dealing with unstructured data has always been in a challenge. But the simplicity and versatility of programming language like python , has made it easy to dive deeper into the world of data. 
Below are some basic execution operations to introduce the programming language “Python”.

**Getting Started**
The below set of commands have all been executed on the platform of Jupiter Notebook. Jupyter Notebook allows users to compile all aspects of a data project in one place making it easier to show the entire process of a project to your intended audience. Through the web-based application, users can create data visualizations and other components of a project to share with others via the platform.

**Prerequisites**
While Jupyter runs code in many programming languages, Python is a requirement for installing the Jupyter Notebook. There are different ways to install Python and Jupyter on your computer. But especially for new users, it is highly recommended to opt for Anaconda. It will install, not only Python but also the Jupyter Notebook App and many scientific computing and data science packages.

**Installing**
Steps to Installing Jupyter Notebook:
Step 1: Open a Command Prompt (Windows) or Terminal (macOS/Linux):
•	On Windows, press Win + R, type cmd, and press Enter.
•	On macOS/Linux, press Cmd + Space, type Terminal, and press Enter.
Step 2: Install Jupyter using pip:
In the Command Prompt or Terminal, type the following command and press Enter:
bashCopy code
pip install jupyter
This command uses pip, the Python package installer, to download and install Jupyter Notebook and its dependencies.
Step 3: Verify Jupyter Installation:
After the installation is complete, you can check if Jupyter Notebook is installed correctly. In the Command Prompt or Terminal, type:
bashCopy code
jupyter notebook
This command will launch the Jupyter Notebook in your default web browser.
Step 4: Create a Jupyter Notebook:
Once Jupyter Notebook is running, you can create a new notebook by clicking on the “New” button and selecting “Python 3” or another available kernel.
Step 5: Write and Execute Code:
In the notebook, you can write and execute code in individual cells. To execute a cell, press Shift + Enter.
Step 6: Save and Quit:
Save your work by clicking the “Save” button or using Ctrl + S (Windows/Linux) or Cmd + S. To exit Jupyter Notebook, close the browser tab and stop the running Jupyter process in the Command Prompt or Terminal by pressing Ctrl + C.


**Running the tests**
Below are the test commands which are run in the python code :
Executing commands in python starts with importing python libraries. 
Importing libraries is a pre-requisite to execute any command in python, else the file will not be liable to execute any command. Basic library to import is “pandas” which is alias with name “pd”. With command like “import pandas as pd”. 
Next command is then to read a txt file in python. With command like “df_txt=pd.read_csv('Test.txt',sep='|')”.
This is to import or read a dataset to perform further operations. We can even connect to sql server and read a dataset from a database. Reading data from any data source is possible in python.
With command like “df.shape” , we can also find records in the data frame.
Also the size of elements can be found with command “df.size”.
Whereas, the column names could be found with command “df.columns”.
The data type of the columns of the data set could be found with command " df.dtypes”.
And if to check particular column type , it would be with command “df.phd.dtype”.
Also to list the data types for each column, method 1 would be with command “df.dtypes” and method 2 would “df.info()”.
Also if we have to data types to proper format, we can use , below commands , 
“df[["bore", "stroke"]] = df[["bore", "stroke"]].astype("float")
df[["normalized-losses"]] = df[["normalized-losses"]].astype("int")
df[["price"]] = df[["price"]].astype("float")
df[["peak-rpm"]] = df[["peak-rpm"]].astype("float")”
And to check the columns after the conversion, below command can be used “df.dtypes”.
And to display the top 10 rows of the dataset “df.head(10)” can be used , where as to display the last 10 rows of the dataset “df.tail(10)” can be used.

**Break down into end to end tests**
These tests are basically used to examine and analysis a set of data. Here the sample data is quite small, but these set of commands can be helpful to examine a large set of unstructured and structured data. 
For example, finding the dataset column types , can help us understand what kind of data can be imported additionally into the existing dataset.

**Built With**
•	Juptiter Notebook - The web framework used

**Versioning**
This is version v1 code.

**Authors**
•	Sayali Kumbhar - Initial work 

**License**
This project is not licensed.

