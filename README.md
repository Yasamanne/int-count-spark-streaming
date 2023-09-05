# int-count-spark-streaming
 Integer Count Using Spark Streaming

The input is CSV streaming data of floating-point numbers.


This program rounds the input floating number to the nearest integers and counts the occurrences for each distinct integer. 


server.py generates lines of real numbers in CSV format (i.e., each line contains real numbers separated by commas) using socket (i.e., an IP address and a port number between 1024-65535). 


The input data is fed using nc command. 


To view what the server generates, there is a client program (client.py). 


To understand how to run the server (similarly for the client), just do:


     $ python3 server.py -h


You need to run sever.py first before running the integer count jupyter file.

