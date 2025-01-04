# anomaly-detection
##Context :

The data presented here was obtained in a Kali Machine from University of Cincinnati,Cincinnati,OHIO by carrying out packet captures for 1 hour during the evening on Oct 9th,2023 using Wireshark.This dataset consists of 394137 instances were obtained and stored in a CSV (Comma Separated Values) file.This large dataset could be used utilised for different machine learning applications for instance classification of Network traffic,Network performance monitoring,Network Security Management , Network Traffic Management ,network intrusion detection and anomaly detection.

The dataset can be used for a variety of machine learning tasks, such as network intrusion detection, traffic classification, and anomaly detection.

##Content :

This network traffic dataset consists of 7 features.Each instance contains the information of source and destination IP addresses, The majority of the properties are numeric in nature, however there are also nominal and date kinds due to the Timestamp.

The network traffic flow statistics (No. Time Source Destination Protocol Length Info) were obtained using Wireshark (https://www.wireshark.org/).

##Dataset Columns:

No : Number of Instance.
Timestamp : Timestamp of instance of network traffic
Source IP: IP address of Source
Destination IP: IP address of Destination
Portocol: Protocol used by the instance
Length: Length of Instance
Info: Information of Traffic Instance

##Acknowledgements :

I would like thank University of Cincinnati for giving the infrastructure for generation of network traffic data set.

Ravikumar Gattu , Susmitha Choppadandi

Inspiration : This dataset goes beyond the majority of network traffic classification datasets, which only identify the type of application (WWW, DNS, ICMP,ARP,RARP) that an IP flow contains. Instead, it generates machine learning models that can identify specific applications (like Tiktok,Wikipedia,Instagram,Youtube,Websites,Blogs etc.) from IP flow statistics (there are currently 25 applications in total).

**Dataset License: ** CC0: Public Domain

Dataset Usages : This dataset can be used for different machine learning applications in the field of cybersecurity such as classification of Network traffic,Network performance monitoring,Network Security Management , Network Traffic Management ,network intrusion detection and anomaly detection.

ML techniques benefits from this Dataset :

This dataset is highly useful because it consists of 394137 instances of network traffic data obtained by using the 25 applications on a public,private and Enterprise networks.Also,the dataset consists of very important features that can be used for most of the applications of Machine learning in cybersecurity.Here are few of the potential machine learning applications that could be benefited from this dataset are :

Network Performance Monitoring : This large network traffic data set can be utilised for analysing the network traffic to identifying the network patterns in the network .This help in designing the network security algorithms for minimise the network probelms.

Anamoly Detection : Large network traffic dataset can be utilised training the machine learning models for finding the irregularitues in the traffic which could help identify the cyber attacks.

3.Network Intrusion Detection : This large dataset could be utilised for machine algorithms training and designing the models for detection of the traffic issues,Malicious traffic network attacks and DOS attacks as well.
