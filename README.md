## DATASET LINK IS OF IDS 2017 

[LINK](https://www.unb.ca/cic/datasets/ids-2017.html) to download the dataset

## About Dataset
- Intrusion Detection Systems (IDSs) and Intrusion Prevention Systems (IPSs) are the most important defense tools against the sophisticated and ever-growing network attacks. Due to the lack of reliable test and validation datasets, anomaly-based intrusion detection approaches are suffering from consistent and accurate performance evolutions.
- Our evaluations of the existing eleven datasets since 1998 show that most are out of date and unreliable. Some of these datasets suffer from the lack of traffic diversity and volumes, some do not cover the variety of known attacks, while others anonymize packet payload data, which cannot reflect the current trends. Some are also lacking feature set and metadata.
- CICIDS2017 dataset contains benign and the most up-to-date common attacks, which resembles the true real-world data (PCAPs). It also includes the results of the network traffic analysis using CICFlowMeter with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack (CSV files). Also available is the extracted features definition.
- Generating realistic background traffic was our top priority in building this dataset. We have used our proposed B-Profile system (Sharafaldin, et al. 2016) to profile the abstract behavior of human interactions and generates naturalistic benign background traffic. For this dataset, we built the abstract behavior of 25 users based on the HTTP, HTTPS, FTP, SSH, and email protocols.
- The data capturing period started at 9 a.m., Monday, July 3, 2017, and ended at 5 p.m. on Friday, July 7, 2017, for a total of 5 days. Monday is the normal day and only includes benign traffic. The implemented attacks include Brute Force FTP, Brute Force SSH, DoS, Heartbleed, Web Attack, Infiltration, Botnet and DDoS. They have been executed both morning and afternoon on Tuesday, Wednesday, Thursday and Friday.
- In our recent dataset evaluation framework (Gharib et al., 2016), we have identified eleven criteria that are necessary for building a reliable benchmark dataset. None of the previous IDS datasets could cover all of the 11 criteria. In the following, we briefly outline these criteria:
- Complete Network configuration: A complete network topology includes Modem, Firewall, Switches, Routers, and presence of a variety of operating systems such as Windows, Ubuntu, and Mac OS X.
- Complete Traffic: By having a user profiling agent and 12 different machines in Victim-Network and real attacks from the Attack-Network.
- Labelled Dataset: Section 4 and Table 2 show the benign and attack labels for each day. Also, the details of the attack timing will be published on the dataset document.
- Complete Interaction: As Figure 1 shows, we covered both within and between internal LAN by having two different networks and Internet communication as well.
- Complete Capture: Because we used the mirror port, such as a tapping system, all traffics have been captured and recorded on the storage server.
- Available Protocols: Provided the presence of all commonly available protocols, such as HTTP, HTTPS, FTP, SSH an and email protocols.
- Attack Diversity: Included the most common attacks based on the 2016 McAfee report, such as Web-based, Brute force, DoS, DDoS, Infiltration, Heart-bleed, Bot, and Scan covered in this dataset.
- Heterogeneity: Captured the network traffic from the main Switch and memory dump and system calls from all victim machines, during the execution of the attack.
- Feature Set: Extracted more than 80 network flow features from the generated network traffic using CICFlowMeter and delivered the network flow dataset as a CSV file. See our PCAP analyzer and CSV generator.
- MetaData: Completely explained the dataset which includes the time, attacks, flows and labels in the published paper.
- The full research paper outlining the details of the dataset and its underlying principles:
- Iman Sharafaldin, Arash Habibi Lashkari, and Ali A. Ghorbani, “Toward Generating a New Intrusion Detection Dataset and Intrusion Traffic Characterization”, 4th International Conference on Information Systems Security and Privacy (ICISSP), Purtogal, January 2018

## PreProcessing and combining of all data is done 
in [tejus Preprocessing.ipynb](https://github.com/Major-Project-8th-Sem/Backend/blob/main/Tejus_Preprocessing.ipynb) to check...

## Data after Data preprocessing
1GB csv data
[download link](https://drive.google.com/file/d/1Qk4KJCAAF5uPNjYLjqtdGqE7a7IGuqOx/view?usp=share_link)

## Balanced Data after UnderSampling
800MB csv data
[Download link](https://drive.google.com/file/d/1Blp6nQlGyocfiPWXcREvoCaCr7LiBfvk/view?usp=sharing)

## Data after minMax Scaler , Standardization && One Hot Encoding
(No errors + lot of data with uneven data distribution in labels =)-
4GB csv data 
[download link](https://drive.google.com/file/d/1CmY8kpLB8Dr1wmFJi3NruWkFwvWO163N/view?usp=sharing)

## Techniques for this project .... 
![TECHNIQUES]('https://raw.githubusercontent.com/Major-Project-8th-Sem/Backend/main/a.jpg')
<p align="center">
  <a href="#"><img alt="tech" src="https://raw.githubusercontent.com/Major-Project-8th-Sem/Backend/main/a.jpg" /></a>
  <h3 align="center"><b>techniques</b></h3>
</p>
