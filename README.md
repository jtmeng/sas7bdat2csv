Title: sas7bdat2csv README
Author: Jintao Meng, He Liu
Affiliation: Webank
==========================

sas7bdat2csv
==========================
This is a java program which can change the sas7bdat format into csv format using parso 2.0. This program is fast and efficient, it can 
support the compressed data structure and binary data structure in sas7bdat.


Usage 
===========================
This program need Java 1.7+, and we have test it successfully in Java 1.7 and 1.8. 

Download these three java package, and run it with the following command:
java -cp sas7bdat2csv.jar:parso-2.0.jar:slf4j-api-1.7.5.jar test.test.App input.sas7bdat output.csv
