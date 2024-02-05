# Database_Piano_Service
1.First we created sql files using queries with procedures and triggers and table
2.then open command prompt as administrator
3. and run command sqlplus / as sysdba to connect to oracle as db administrator
4. now locate the file and execute the created sql file to get all the tables and procedues and triggers
5.connect database through ODBC using DSN to get data
6.Open MS Access file and import the data

Used program: Oracle, SSMS (SQL Server Management Studio), mySQL, ODBC, MS ACCESS.
<br>
 Front-end Application: Developed with Microsoft Access for an intuitive user interface
<br>
 Set up reports and forms, merging various entities for effective data representation
<br>
 Created complex relationships through forms to manage intricate connections between different 
entities
<br>
 Utilized Oracle for data creation and linked it seamlessly with MS Access
<br>
 Implemented database elements such as triggers, trigger views, packages, package bodies, 
and stored procedures
<br>
 Maintained timestamp history for changes, using start and end dates to track modifications.
<br>
 Recorded historical data for each field with timestamps
-------------------------------------------------------------------------------------------------------
Instruction
1 - Open CMD, navigate to the SQL file location, and then type 'sqlplus / as dba.' After that, execute the SQL file by typing '@assignment2-create.sql.' This SQL file will create tables.
  ![1](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/7fcdfe2a-0118-4849-8467-cf31b94a9620)
![2](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/8ad68542-d049-49bb-bb78-83a3f5c7e6c0)
<br>
2 - Connect to ODBC and add 'Oracle_in_Instanceclient_21_12.' Write down the following information: Data Source Name: LOCALHOST:1521/ORCL2355, UserID: kang0057, User Password: kang0057Password, and test the connection.
![3](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/02a0a556-ac44-4374-a8ea-ea70343339b8)
![4](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/ffb1d926-a4ab-42c0-9da5-63790a1df327)
![5](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/0e6f665a-2a44-42f9-84dc-35d007a52b7f)
![6](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/839cc51e-126c-4c48-9656-024881aa5906)
<br>
3 - Connect to MS Access, go to 'New Data Source' -> 'From other Source' -> 'ODBC Database,' and click on 'Machine Data Source' to find the ODBC connection you created in step 2. Use the following information: Service Name: LOCALHOST:1521/ORCL2355, User Name: kang0057, User Password: kang0057Password. Import the tables you created using CMD.

![7](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/06bb7702-5442-40b5-9637-5e470ccec2ea)
![8](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/e4ccd209-bdef-4992-b773-667747d01429)
![9](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/784a40ec-9695-403c-8332-2b7b3237c329)
![10](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/351fafb7-ea16-482e-909a-c9beb62b40ad)
![11](https://github.com/hanskkangg/Database_Piano_Service/assets/156132740/24de456c-e5df-444d-b92e-5bc760e4e327)

