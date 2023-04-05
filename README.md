# kafka-stock-market-project
This project was made using Python libraries , aws cloud architecture and kafka tech stack . 


--> In this project a sample stock market data was taken as the dataset and was simulated to be sent to the EC2 server as realtime streaming.Then analaysis was done using AWS Athena .
1) First , We installed the kafka streaming platform on the EC2 instance , Then launched zookeeper in EC2 instance. After that we launch the producer and consumer part on the EC2 instance itself.
2) Now using python we simulate realtime streaming of data into AWS S3 
3) From there on we use AWS crawler so that we can fetch the data from the bucket to do the required analysis on AWS Athena(SQL) . 

The architecture diagram for the above process is given below 


![null](https://user-images.githubusercontent.com/86833210/230042182-ff90e84a-6066-4219-a749-ea064ac014a0.png)

You can check on the procedure textfile to find the codes which I ran to install kafka and zookeeper related stuff on the EC2 instance in the repo.
