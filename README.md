
## Instructions to be followed for executing the application.

1. Start the Database using the below command

    **Command:**  java -cp ../lib/hsqldb.jar org.hsqldb.Server -database.0 file:mydb -dbname.0 xdb

       Command to be executed from the directory where hsqldb/lib is stored

    **Database Details**
    
       Setting Name : HSQL Database Engine

       DBType : HSQL DataBase Engine Server 

       Driver : org.hsqldb.jdbc.JDBCDriver

       URL : jdbc:hsqldb:hsql://localhost/xdb

       Username : SA

       password :


2. Execute the jar file on command line.

    **Command:**  java -jar ApplicationFinal.jar %path%/logfile.txt 

        (Pass absolute path along with logfile.txt). 
        Command to be executed from the directory ApplicationFinal.jar is downloaded.
