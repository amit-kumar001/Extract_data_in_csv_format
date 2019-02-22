# Extract_data_in_csv_format  
![sql](https://user-images.githubusercontent.com/47202519/53243001-8559e480-36cc-11e9-9b34-6bd820554173.jpg)
  
  
## Key feature
<ol>
<li>In this code, We extract a data from database <strong>phpmyadmin</strong> in two format using <strong> python language.</strong> </li> 
  
   <strong>1) csv format</strong>   
   
   <strong>2) excel format</strong>    
  
    
<li> To make a connection between database <strong>phpmyadmin</strong> and <strong>python language</strong>, we import <strong> mysql-connector. </strong> </li>
<li><strong>xlsxwriter</strong> is a python module for creating XLSX files. <strong>xlsxwriter</strong> is used to write text, numbers, formulas and hyperlinks to multiple worksheets in an Excel 2007+ XLSX file. </li>
<li>Workbook is a package and is used to write data into spreadsheets.</li>
<li>CSV module is use to read and write tabular data in<strong> CSV format.</strong></li>
<li><strong>mysql.connect.connector</strong> is use to make the connection with database by providing database details like:- host,username,password and name_of_database.</li>
<li>Define object via using object() method.</li>
<li>Define variable to show the table content from database.</li>
<li>Now, we have to execute the variable in which we have access the table content.</ UTF-8li>
<li>Use <strong>fetchall()</strong> function Since this is a python file, hence it can be run using following command

python n_dict.py
python3 n_dict.pyto fetch all the attributes and entities from the table.</li>
<li>Define another variable in which we use description method to fetch all the column name for the <strong>csv format.</strong></li>
<li>Take empty list and append all the rows and columns of the table in empty list by using <strong>append() method.</strong></li>
<li>Now we have to store data into .csv format.</li>
<li>Use <strong>open() method</strong> in which we define the name of csv file and Unicode-based encoding such as <strong>UTF-8</strong> can support many languages and can accomodate pages and forms in any language. </li>
<li>Python CSV only accept <strong>lineTerminator</strong> as '\r\n', '\n' or '\r lineTerminator use to split text when it find new line.</li>
<li><strong>Workbook</strong> use to create sSince this is a python file, hence it can be run using following command

python n_dict.py
python3 n_dict.pypreadsheet which will be stored by .csv extension.</li>
<li><strong>Sheet</strong> variable use to call worksheet from workbook.</li>
<li><strong>Enumerate()</strong> method adds a counter to an iterable and returns it in a form of enumerate object. Enumerate object can be used directly in a <strong>for loop</strong> </li>
</ol>

### Output


![table jpg](https://user-images.githubusercontent.com/47202519/53170323-df43a700-3605-11e9-904c-f63435a10c84.png)




## Required package
<ol>
<li>csv</li>
<li>xlsxwriter</li>
<li>workbook</li>
</ol>

### How to use these packages
~~~
import csv
import mysql.connector
from xlsxwriter.workbook import Workbook
~~~

### how to use this code  

To use this code, one have to use the jupyter notebook. To install jupyter notebook on either windows or linux, pip is a package which can perform this work easily. Please execute the below command

```
pip/pip3 install jupyter
```  
pip3 means for python3 whereas pip2 is for python2. Please check the version of python you are using and install it accordingly. Please remember that if you are in ubuntu and you need to install the package in .local in the home folder, please execute the below command

```
pip/pip3 install jupyter --user
```

## how to run this file    

To run this file, download the repository in a specific folder and run the following command in the terminal

```
jupyter notebook
```

 


