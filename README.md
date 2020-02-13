# mysql-connector-mxj-mac-os-catalina
Add 64 bit executable into the mysql-connector-mxj library

The mysql-connector-mxj library (https://downloads.mysql.com/archives/c-mxj/) has been deprecated and no maintainence has been discontinued.

The mysql-connector-mxj has only 32 bit executables, however MacOS Catalina only supports 64 bit executables.

This repository adds the 64 executables of mysql and mysqld, so that mysql-connector-mxj could works on MacOS Catalina.

You can clone the repo and run the command below inside of the repo

```jar cvf mysql-connector-mxj-db-files-5.0.12.jar .```

After the jar is created, you can copy it to your mvn setting folder, which should be at 

```~/.m2/repository/mysql/mysql-connector-mxj-db-files/5.0.12/```

Otherwise you can download the artifact mysql-connector-mxj-db-files-5.0.12.jar directly and copy it to the folder above.
