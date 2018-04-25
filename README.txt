1) Create a database on your machine.
2) liquibase.properties-file, use the same db and credentials

3) log in as root to mysql
3.1) mysql> CREATE database liquibasesample;
3.2) mysql> GRANT ALL PRIVILEGES ON liquibasesample.* To 'liquibasesample'@'localhost' IDENTIFIED BY 'root';

4)   Execute the 'database project by running :
4.1) $mvn clean install
