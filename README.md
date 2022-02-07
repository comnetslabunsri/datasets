# COMNETS Lab dataset for research by Department of Computer Engineering. Faculty of Computer Science. Universitas Sriwijaya
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
<a href="https://github.com/comnetslabunsri/datasets" target="_blank"><img alt="alwinw" src="https://badges.pufler.dev/visits/alwinw/alwinw?logo=GitHub&label=visits&color=success&logoColor=white&style=flat-square"/></a>
<img alt="Stars" src="https://img.shields.io/github/stars/comnetslabunsri/datasets?style=flat-square&labelColor=343b41"/>
<img alt="Forks" src="https://img.shields.io/github/forks/comnetslabunsri/datasets?style=flat-square&labelColor=343b41"/>
[![GitHub twseptian](https://img.shields.io/github/followers/comnetslabunsri?label=follow&style=social)](https://github.com/comnetslabunsri)
[![GitHub stars](https://img.shields.io/github/stars/comnetslabunsri?logo=GitHub&style=social)](https://github.com/comnetslabunsri)
[![Gmail Badge](https://img.shields.io/badge/-comnets@unsri.ac.id-c14438?style=social&logo=Gmail&logoColor=red&link=mailto:comnets@unsri.ac.id)](mailto:comnets@unsri.ac.id)

COMNETS lab dataset is a collection of datasets from the Department of Computer Engineering. Faculty of Computer Science. Universitas Sriwijaya.
For further more information, kindly to contacted at **comnets@unsri.ac.id** or our page [github page](https://comnetslabunsri.github.io/datasets/)

## Contents
- [Internet of Things dataset](#internet-of-things-dataset)
- [License](#license)

## Internet of Things dataset
### Contents
- [TCP FIN flood and zbassocflood Dataset](#tcp-fin-flood-and-zbassocflood-dataset)
- [Ping Flood Attack Pattern Recognition on Internet of Things Network Dataset](#ping-flood-attack-pattern-recognition-on-internet-of-things-network-dataset)
- [UDP Flood Attack Pattern on Internet of Things Network Dataset](#udp-flood-attack-pattern-on-internet-of-things-network-dataset)
- [Constrained Application Protocol Internet of Things Protocol Dataset](#constrained-application-protocol-internet-of-things-protocol-dataset)
- [Message Queue Telemetry Transport Protocol on Internet of Thing Dataset](#message-queue-telemetry-transport-protocol-on-internet-of-thing-dataset)

### TCP FIN flood and zbassocflood Dataset

This dataset is available at Zenodo, kindly to download it throught [TCP FIN Flood and Zbassocflood Dataset](https://zenodo.org/record/4431541#.X_623HUzaNc)


#### Publications: 
**The Development of an Internet of Things (IoT) Network Traffic Dataset with Simulated Attack Data.**

_Abstract_— This research focuses on the requirements for and the creation of an intrusion detection system (IDS) dataset for an Internet of Things (IoT) network domain. 
A minimal requirements Internet of Things (IoT) network system was built to produce a dataset according to IDS testing needs for IoT security. Testing was performed with 12 scenarios and resulted in 24 datasets which consisted of normal, attack and combined normal-attack traffic data. 
Testing focused on three denial of service (DoS) and distributed denial of service (DDoS) attacks—“finish” (FIN) flood, User Datagram Protocol (UDP) flood, and Zbassocflood/association flood—using two communication protocols, IEEE 802.11 (WiFi) and IEEE 802.15.4 (ZigBee). A preprocessing test result obtained 95 attributes for the WiFi datasets and 64 attributes for the Xbee datasets

**TCP FIN Flood Attack Pattern Recognition on Internet of Things with Rule Based Signature Analysis**

_Abstract_-Focus of this research is TCP FIN flood attack pattern recognition in Internet of Things (IoT) network using rule based signature analysis method. Dataset is taken based on three scenario normal, attack and normal-attack. The process of identification and recognition of TCP FIN flood attack pattern is done based on observation and analysis of packet attribute from raw data (pcap) using a feature extraction and feature selection method. 
Further testing was conducted using snort as an IDS. The results of the confusion matrix detection rate evaluation against the snort as IDS show the average percentage of the precision level.

#### Citing
Citation data : [TCP FIN Flood Attack Pattern Recognition on Internet of Things with Rule Based Signature Analysis](https://online-journals.org/index.php/i-joe/article/view/9848)

```
@article{article,
author = {Stiawan, Deris and Wahyudi, Dimas and Heryanto, Ahmad and Sahmin, Samsuryadi and Idris, Yazid and Muchtar, Farkhana and Alzahrani, Mohammed and Budiarto, Rahmat},
year = {2019},
month = {04},
pages = {124},
title = {TCP FIN Flood Attack Pattern Recognition on Internet of Things with Rule Based Signature Analysis},
volume = {15},
journal = {International Journal of Online and Biomedical Engineering (iJOE)},
doi = {10.3991/ijoe.v15i07.9848}
}
```

**Features Extraction on IoT Intrusion Detection System Using Principal Components Analysis (PCA)**

Feature extraction solves the problem of finding the most efficient and comprehensive set of features. A Principle Component Analysis (PCA) feature extraction algorithm is applied to optimize the effectiveness of feature extraction to build an effective intrusion detection method. This paper uses the Principal Components Analysis (PCA) for features extraction on intrusion detection system with the aim to improve the accuracy and precision of the detection. The impact of features extraction to attack detection was examined. Experiments on a network traffic dataset created from an Internet of Thing (IoT) testbed network topology were conducted and the results show that the accuracy of the detection reaches 100 percent.

#### Citing
Citation data : [Features Extraction on IoT Intrusion Detection System Using Principal Components Analysis (PCA)](https://ieeexplore.ieee.org/document/9251292)

```
@inproceedings{inproceedings,
author = {Sharipuddin, and Purnama, Benni and Kurniabudi, Kurniabudi and Winanto, Eko and Stiawan, Deris and Hanapi, Darmawiiovo and Idris, Mohd and Budiarto, Rahmat},
year = {2020},
month = {10},
pages = {114-118},
title = {Features Extraction on IoT Intrusion Detection System Using Principal Components Analysis (PCA)},
doi = {10.23919/EECSI50503.2020.9251292}
}
```

### Ping Flood Attack Pattern Recognition on Internet of Things Network Dataset

This dataset is available at Zenodo, kindly to download it throught [Ping Flood Attack Pattern Recognition on Internet of Things Network dataset](https://zenodo.org/record/4436208#.X_7PmHUzaNc)

#### Publications:
**Ping Flood Attack Pattern Recognition using K-Means Algorithm in Internet of Things (IoT) Network** _`status: on repository`_

_Abstract_ — This work investigates ping flood attack pattern recognition on Internet of Things (IoT) network. Experiments are conducted on WiFi communication with three different scenarios: normal traffic, attack traffic, and normal-attack combination traffic to create normal dataset, attack dataset, and normal attack (combined) dataset. The datasets are grouped into two clusters i.e.: (i) normal cluster and (ii) attack cluster. Clustering results using implemented K-Means algorithm show the average number of packets on the cluster of attack in total is 95,931 packets, and the average packets on normal cluster in total is 4,068 packets. 
Accuracy level of the clustering results then is calculated using confusion matrix equation. Based on the confusion matrix calculation, accuracy of clustering using implemented K-Means algorithm was 99.94%. The true negative rate reaches up to 98.62%, true positive rate is 100%, the false negative rate is 0%, and the false positive rate reaches 1.38%.

### UDP Flood Attack Pattern on Internet of Things Network Dataset

This dataset is available at Zenodo, kindly to download it throught [UDP Flood Attack Pattern on Internet of Things Network Dataset](https://zenodo.org/record/4436127#.X_7DJXUzaNc)

#### Publications:
**Investigating UDP Flood Attack Pattern on Internet of Things Network** _`status: on review`_

_Abstract_: UDP does not have mechanism for retransmission when a transmitting error happens, it makes this protocol to be used as a DDoS attack tool against Internet of Things (IoTs) networks. This research work attempts to analyze the UDP Flood attacks packets dataset captured from an Io|T testbed network by Wireshark. 
A feature extraction process on generated CSV file was performed and then the feature extraction result are examined to find patterns of UDP flood attack packet. Lastly, the patterns are visualized to provide easy pattern recognition.

### Constrained Application Protocol Internet of Things Protocol Dataset

This dataset is available at Zenodo, kindly to download it throught [Constrained Application Protocol (CoAP) Internet of Things Protocol Dataset](https://zenodo.org/record/4436043#.X_68SHUzaNc)

#### Publications
**Implementation of Constrained Application Protocol on IoT using Constrained RESTful Environments Constrained Device** _`status : on repository`_

This study discusses the implementation of the Constrained Application Protocol (CoAP) using Constrained RESTful Environments (CoRE) on RFC 7252 which is used as a research parameter. 
The implementation of this Limited Application Protocol uses Internet of Things (IoT) technology. The testing technique is carried out offline and the device used is based on the constrained device. Network performance testing parameters in this study are UDP throughput, UDP delay, UDP packet loss and UDP packet delivery ratio. Testing network performance with LED and Buzzer output produces the largest average UDP throughput, namely 4.5737 Kbps while the smallest average throughput is 1.2293 Kbps, the largest average UDP delay result is 2 seconds and the smallest average is 0.6 seconds, then the average UDP packet loss yield is 0% while the average successful packet delivery ratio is 100%. From the results of this test, the Constrained Application Protocol (CoAP) has smaller network performance results than the HyperText Transfer Protocol (HTTP) to be implemented in Internet of Things (IoT) technology.

### Message Queue Telemetry Transport Protocol on Internet of Thing Dataset

This dataset is available at Zenodo, kindly to download it throught [Message Queue Telemetry Transport (MQTT) Protocol on Internet of Thing Dataset](https://zenodo.org/record/4436172#.X_7KtHUzaNc)

#### Publications
**Performance Analysis of Message Queue Telemetry Transport (MQTT) Protocol on Internet of Thing (IoT)** _`status : on review`_

Internet of Things (IoT) is a system where devices are connected and allows information exchange among them. It also allows devices/objects to interact directly with other objects or commonly refers to Machine-to-Machine (M2M) communication. Message Queue Telemetry Transport (MQTT) is machine-to-machine connectivity protocol, which is designed as messages delivery service that gives different level of Quality of Service (QoS) i.e.: level 0, 1 and 2 for variety of use cases, provides architecture of publish/subscribe and supports multicasting message. The importance feature of MQTT is low overhead for efficient communication between devices. 
This work implements MQTT using Mosquito Broker, which has a function to regulate the delivery of messages between Publisher and Subscriber using poll system call to handle multiple network socket in one thread. With a scenario of increasing number of nodes at each experiment, MQTT Protocol has an average overall delay of 0.0029 seconds, an average throughput of 218 Kbps, average of packet loss of 0.2% and average of packet delivery ratio of 99.7%. Of experiment results obtained, the MQTT Protocol has potential to be able to meet the needs of the use of a limited bandwidth network, which can be adjusted with the level of service provided by the MQTT and low packet loss rate.

## License
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

You may redistribute, republish, and mirror all of the COMNETS Lab datasets in any form. However, any use or redistribution of the data must include a citation to our publications or the COMNETS Lab dataset.

[![ForTheBadge built-with-science](http://ForTheBadge.com/images/badges/built-with-science.svg)](https://github.com/comnetslabunsri)
