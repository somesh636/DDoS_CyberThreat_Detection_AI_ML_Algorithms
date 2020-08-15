
# A Study of AI and ML Algorithms for DDoS Cyberthreats Detection


#### This Project is for detecting Distributed Denial of Service (DDoS) Cyberattacks efficiently using AI and ML algorithms. 

## Abstract: 

Distributed Denial of Service (DDoS) is a type of Cybersecurity threat which is
one of many versions of Denial of Service(DoS) that uses IP addresses to attack
a particular server/victim. DDoS threats are well-coordinated attacks that uses
a compromised secondary victims to target the single or multiple victim systems
may it be a large firm server or a small scale system. The DDoS threats are very
costly in terms of bandwidth and power and they result in loss of confidential
data as well. Therefore it has become of much importance to devise better al-
gorithms to detect different types of DDoS Cyberthreats with higher accuracy
while considering the computation cost in detecting these threats. Most of the
study conducted in literature assumes detection of DDoS threats as a binary clas-
sification problem and their results give out whether an attack was attempted or
not. However, in order to effectively defend the network from causing extensive
damage, it is of paramount importance to know which type of DDoS attack is
targeting the network or the system. This study, presents an Ensemble Classifier
that combines the performance of top 4 performing algorithm and compares it
with different Artificial Intelligence and Machine Learning (AI and ML) algo-
rithms to effectively detect the different types of DDoS threats by converting
the problem to a multilabel classification problem.

* The Dataset used for this project is [CICDDoS2019](https://www.unb.ca/cic/datasets/ddos-2019.html) Dataset: 

CICDDoS2019 contains benign and the most up-to-date common DDoS attacks, which resembles the true real-world data (PCAPs). It also includes the results of the network traffic analysis using CICFlowMeter-V3 with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack (CSV files). Generating realistic background traffic was our top priority in building this dataset. We have used our proposed B-Profile system (Sharafaldin, et al. 2016) to profile the abstract behavior of human interactions and generates naturalistic benign background traffic in the proposed testbed (Figure 2). For this dataset, we built the abstract behaviour of 25 users based on the HTTP, HTTPS, FTP, SSH, and email protocols.

