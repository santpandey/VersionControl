# VersionControl
This repository tracks the changes done to the properties file in Java and displays the difference in the properties file for each change.

Approach used in this problem:

1) Create copy of each property file in a seperate package within a Java Project

1) Use WatchServiceApi to track the files which are changed in a repository which is registered to the service.

2) Use the file which is given by the service to do a comparison between the older version and the newer version

3) Track the difference and display them

To Test the code:

1) Run the java code present in src code

2) go to configuration folder and change data inside any of the 3 prop file and save the file

3) Watch the console for the required output

