## Read and Write File with Buffers, AWS
File read and write in Java <br />
Using Java NIO Buffer and Direct Buffer <br />
Measure time of reading and writing files of different sizes <br />
Logging results to a file <br />

Add Terraform project <br />
Test on AWS EC2 instance with Ubuntu <br />

Add Log4j2 Logger <br />


### Technologies
JSE, Buffer, Direct Buffer, FileChannel <br />
Log4j2 <br />
AWS, Terraform <br />


### Steps
Compile and package program: <br />
*mvn clean compile package* <br />

Run program: <br />
*java -jar target/io-file-copy-1.0-SNAPSHOT.jar* <br />

Run program on AWS with Terraform: <br />
*terraform apply* <br />


### Results
Results for 2 platforms in logFiles: <br />
Windows Subsystem for Linux (WSL Ubuntu 16.04) <br />
AWS EC2 Linux Ubuntu 6.04 
