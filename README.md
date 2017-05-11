# Coding Contest Managing Server
Can be used for management of coding events

### Requirements
* PHP5
* MySQL Server

## Usage
1. Create tables in the mysql server using the file queries.sql
2. Create required directories and set the values for variables in the following files

    `/include/glob.php`

    `/include/mysq.php`

    `/conur/src/conur/Credentials.java`
  
3. Insert values into the tables(queries can be found inside queries.sql)

    Questions can be added to by executing following java file
  
      `/conur/src/conur/Questions.java`
