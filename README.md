# Zeus-GameOver-synthetic-dataset
The repository contains a synthetic Zeus GameOver dataset generated in a testbed. 
This is a compressed file containing the Zeus GameOver botnet traffic flow simulation.
A Zeus bot software was created by studying the characteristics of Zeus  GameOver from technical reports "ZeuS-P2P monitoring and analysis", by  CERT Polska, published in June 2013 (https://www.cert.pl/en/uploads/2015/12/2013-06-p2p-rap_en.pdf),  as well as "An analysis of the Zeus peer-to-peer protocol" by Dennis  Andriesse and Herbert Bos, technical report, VU University Amsterdam,  The Netherlands, April 2014 (URL:https://syssec.mistakenot.net/papers/zeus-tech-report-2013.pdf). 
A testbed has been set up with 101 virtual hosts. 
Each host has a piece of bot software installed. 
The bots then communicate with one another. 
The network traffic was captured for 24 hours. 
tcpdump tool is used to capture the raw trafffic. 
The captured traffic is then used to generate netflow records using the  nprobe tool. 
The source and destination IP addresses are then extracted from the  resulting flow dataset. 
The dataset uploaded here is a text file. 
The file contains the communication information of the bot nodes. 
It  has two fields: source IP address and destination IP address.
