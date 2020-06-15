# Predicting-the-Network-Intrusion

### Background
The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
●	Normal 
●	Anomalous

Data basically represents the packet data for a time duration of 2 seconds.
1-9 Columns: basic features of packet (type 1)
10-22 columns: employ the content features (type 2)
23-31 columns: employ the traffic features with 2 seconds of time window (type 4)
32-41 columns: employ the host based features
C: Continuous data
D: Discrete data
