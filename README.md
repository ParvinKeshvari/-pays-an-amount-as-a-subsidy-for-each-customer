👩‍💻 About Me : 👋 Hi, I’m @ParvinKeshvari. I am a Backend Developer from Iran. 
👀 I’m interested in C#, Java ,Sql Server, Asp.Net and WPF 
🔭 I’m working as a Software Engineer and backend for building web and windows applications. 
⚡ my .google scholar is: https://scholar.google.com/citations?user=zHxRND0AAAAJ&hl=en 
📫 How to reach me: https://www.linkedin.com/in/parvin-keshvari-960516152

In order to target subsidies, the Iranian government pays an amount as a subsidy for each customer. In this regard, each bank is obliged to process the list of customers and accounts that are given to them and deposit the amounts specified in the account file to the people who are in the customer file.Finally, prepare a report of the database and present it in the form of XML and JSON files.
In this regard, I have written a project in Java as an example that which the principles of Object-oriented are fully observed and it is an idea to do it quickly.
In this project, we are dealing with the CSV file, Xml file, JSON files, Multi-Threading, SQL Server database, and  Predicates.
This project consists of three modules as follows:
The first module is called the input. In this module, two input files in CSV format are taken for customer and account information. In this module, we have several Threads. Each Thread processes a chunk of data. We check a series of validations using Predicates. If the validations are violated, the errors will be placed in the JSON file in the specified format. If the validation of customers and accounts is correct, each data fragment will be stored in the SQL database. In this example, we have defined three jobs.
In the second module, called Share, I put the common operations that we want to use in the other two modules. This common operation involves connecting to a database as well as writing information to a file
The third module is called Output. In this module, we query the SQL database and save the output in a JSON file and XML file.
