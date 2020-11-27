# COMNETS Lab dataset for research by Department of Computer Engineering. Faculty of Computer Science. Universitas Sriwijaya

![comnets](logo-dataset.png)
COMNETS lab dataset is a collection of datasets by undergraduate students (Bachelor Computer) in Department of computer engineering. Faculty of Computer Science. Universitas Sriwijaya.

If you have any questions and more information, please feel free to contact our email comnets@unsri.ac.id

## Contents
- [Internet of Things dataset](#internet-of-things-dataset)
- [License](#lisence)

## Internet of Things dataset
### Contents
- [TCP FIN flood dan zbassocflood dataset](#tcp-fin-flood-dan-zbassocflood-dataset)
- [Ping flood Attack dataset](#ping-flood-attack-dataset)
- [Protocol IoT CoAP dataset](#protocol-iot-coap-dataset)
- [IoT MQTT Protocol dataset](#iot-mqtt-protocol-dataset)

### TCP FIN flood dan zbassocflood dataset
[Download](https://drive.google.com/drive/folders/1R4-WjjJfop_9yvi1vIo1GR5yeYOc3-ea?usp=sharing)

#### Publications: 
**The Development of an Internet of Things (IoT) Network Traffic Dataset with Simulated Attack Data.**

Abstract— This research focuses on the requirements for and the creation of an intrusion detection system (IDS) dataset for an Internet of Things (IoT) network domain. 
A minimal requirements Internet of Things (IoT) network system was built to produce a dataset according to IDS testing needs for IoT security. Testing was performed with 12 scenarios and resulted in 24 datasets which consisted of normal, attack and combined normal-attack traffic data. 
Testing focused on three denial of service (DoS) and distributed denial of service (DDoS) attacks—“finish” (FIN) flood, User Datagram Protocol (UDP) flood, and Zbassocflood/association flood—using two communication protocols, IEEE 802.11 (WiFi) and IEEE 802.15.4 (ZigBee). A preprocessing test result obtained 95 attributes for the WiFi datasets and 64 attributes for the Xbee datasets

**TCP FIN Flood Attack Pattern Recognition on Internet of Things with Rule Based Signature Analysis**

Abstract-Focus of this research is TCP FIN flood attack pattern recognition in Internet of Things (IoT) network using rule based signature analysis method. Dataset is taken based on three scenario normal, attack and normal-attack. The process of identification and recognition of TCP FIN flood attack pattern is done based on observation and analysis of packet attribute from raw data (pcap) using a feature extraction and feature selection method. 
Further testing was conducted using snort as an IDS. The results of the confusion matrix detection rate evaluation against the snort as IDS show the average percentage of the precision level.

#### Citing
if use this data in a publication please cite the following [paper](https://online-journals.org/index.php/i-joe/article/view/9848)

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

### Ping flood Attack dataset
[Download](https://drive.google.com/drive/folders/1XGwlOCxnd3ozAhVAgUInfLR5l7W_uM9y?usp=sharing)

#### Publications:
**Ping Flood Attack Pattern Recognition using K-Means Algorithm in Internet of Things (IoT) Network** _`status: on repository`_

Abstract — This work investigates ping flood attack pattern recognition on Internet of Things (IoT) network. Experiments are conducted on WiFi communication with three different scenarios: normal traffic, attack traffic, and normal-attack combination traffic to create normal dataset, attack dataset, and normal attack (combined) dataset. The datasets are grouped into two clusters i.e.: (i) normal cluster and (ii) attack cluster. Clustering results using implemented K-Means algorithm show the average number of packets on the cluster of attack in total is 95,931 packets, and the average packets on normal cluster in total is 4,068 packets. 
Accuracy level of the clustering results then is calculated using confusion matrix equation. Based on the confusion matrix calculation, accuracy of clustering using implemented K-Means algorithm was 99.94%. The true negative rate reaches up to 98.62%, true positive rate is 100%, the false negative rate is 0%, and the false positive rate reaches 1.38%.

### UDP flood Attack dataset
[Download](https://drive.google.com/drive/folders/1a5tLZ01pR71X9-lf0H3B2Y-OIvVtei5Z?usp=sharing)

#### Publications:
**Investigating UDP Flood Attack Pattern on Internet of Things Network** _`status: on review`_

Abstract: UDP does not have mechanism for retransmission when a transmitting error happens, it makes this protocol to be used as a DDoS attack tool against Internet of Things (IoTs) networks. This research work attempts to analyze the UDP Flood attacks packets dataset captured from an Io|T testbed network by Wireshark. 
A feature extraction process on generated CSV file was performed and then the feature extraction result are examined to find patterns of UDP flood attack packet. Lastly, the patterns are visualized to provide easy pattern recognition.

### Protocol IoT CoAP dataset
[Download](https://drive.google.com/drive/folders/1JATdG-QrNFmb6DWPPW7FWs6g7Fc-GiQz?usp=sharing)

#### Publications
**Implementation of Constrained Application Protocol on IoT using Constrained RESTful Environments Constrained Device** _`status : on repository`_

This study discusses the implementation of the Constrained Application Protocol (CoAP) using Constrained RESTful Environments (CoRE) on RFC 7252 which is used as a research parameter. 
The implementation of this Limited Application Protocol uses Internet of Things (IoT) technology. The testing technique is carried out offline and the device used is based on the constrained device. Network performance testing parameters in this study are UDP throughput, UDP delay, UDP packet loss and UDP packet delivery ratio. Testing network performance with LED and Buzzer output produces the largest average UDP throughput, namely 4.5737 Kbps while the smallest average throughput is 1.2293 Kbps, the largest average UDP delay result is 2 seconds and the smallest average is 0.6 seconds, then the average UDP packet loss yield is 0% while the average successful packet delivery ratio is 100%. From the results of this test, the Constrained Application Protocol (CoAP) has smaller network performance results than the HyperText Transfer Protocol (HTTP) to be implemented in Internet of Things (IoT) technology.

### IoT MQTT Protocol dataset
[Download](https://drive.google.com/drive/folders/10QP4RnbIpNMC9p0NLPDFFwlPvEBhvER6?usp=sharing)

#### Publications
**Performance Analysis of Message Queue Telemetry Transport (MQTT) Protocol on Internet of Thing (IoT)** _`status : on review`_

Internet of Things (IoT) is a system where devices are connected and allows information exchange among them. It also allows devices/objects to interact directly with other objects or commonly refers to Machine-to-Machine (M2M) communication. Message Queue Telemetry Transport (MQTT) is machine-to-machine connectivity protocol, which is designed as messages delivery service that gives different level of Quality of Service (QoS) i.e.: level 0, 1 and 2 for variety of use cases, provides architecture of publish/subscribe and supports multicasting message. The importance feature of MQTT is low overhead for efficient communication between devices. 
This work implements MQTT using Mosquito Broker, which has a function to regulate the delivery of messages between Publisher and Subscriber using poll system call to handle multiple network socket in one thread. With a scenario of increasing number of nodes at each experiment, MQTT Protocol has an average overall delay of 0.0029 seconds, an average throughput of 218 Kbps, average of packet loss of 0.2% and average of packet delivery ratio of 99.7%. Of experiment results obtained, the MQTT Protocol has potential to be able to meet the needs of the use of a limited bandwidth network, which can be adjusted with the level of service provided by the MQTT and low packet loss rate.

## Lisence
You may redistribute, republish, and mirror all of the COMNETS Lab datasets in any form. However, any use or redistribution of the data must include a citation to our publications or the COMNETS Lab dataset.