### Open Audio, Video and Webpages ###

![Alt text](http://173.0.133.251/images/GitHub/multimedia1.jpg "Integrate with Multimedia Files")

Integrating with SQL and major databases means the ability to export data into a SQL and other major databases, performing update, backup and replication services.



### BUSINESS RISK ###

Keeping two or more separate databases up to date with each other's data changes can be a daunting topic. 

Whether your database solution is simple or complex, there are five key issues to consider:

<ol>
<li>How similar are the structures of the databases to be kept in synch? If they are identical, you are a step ahead in the game. As they become more dissimilar, syncing becomes more difficult and more abstract.</li>
<li>How often do the databases need to be synced?</li>
<li>How will you resolve situations in which the same data has been modified in both (or more) of your databases since the last sync session? There are a number of approaches from fairly simple to quite complex.</li>
<li>How much effort and/or money are you willing to invest in developing your sync system?</li>
<li>How much effort are you willing to put up with at each sync session?</li>
</ol>



### DATABASE CONVERSION / SYNCING POSSIBILITY MATRIX ###

![Alt text](http://173.0.133.251/images/GitHub/synch2a.gif "Integrate with Databases")



### TESTING APPROACH ###

This project includes an ACL script which leverages the new EXECUTE command in ACL Analytics v10 to conduct database conversion between MS SQL database (source) and Access database (destination). The scripts included in the project will:

1.  Run the DBConvert tool (downloadable trial from http://dbconvert.com/convert-access-to-mssql-sync.php) in the script "Integrate_SQL_and_Databases".  The sync progress is shown below:

![Alt text](http://173.0.133.251/images/GitHub/progress.gif "Synchronization Progress")

2.  The software's scheduled service will also perform the conversion at a regular interval.  (See www.dbconvert.com/scheduler-configuration-manual.php for more info.)


Modifications to the scripts may obviously be made to add your own different databases' login credentials, software name and path, etc. The scripts simply illustrate an example of how to conduct a conversion between MS SQL database (source) and Access database (destination).  (For more info, see http://dbconvert.com/faq.php)



#### Methodology ####

![Alt text](http://173.0.133.251/images/GitHub/use-methodology.gif "How I Work")

Email me: patrickong@gmail.com
