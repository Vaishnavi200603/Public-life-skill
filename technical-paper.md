# Firewall

## What is a Firewall?

Firewalls are software programs(hardware or software) that behave like a gateway between our system and the outside internet to protect us from viruses, malware, or hackers reaching out to our system from the internet.

Firewalls collect traffic and filter it by approving trusted data packets and blocking untrusted and unapproved ones. They also regulate the flow of firewall traffic between computer networks at different levels.

Firewalls are typically divided into two types - Software firewalls and Hardware firewalls. 

So we can say that a firewall is a hardware and software tool that limits the access of networks in our system.

Internal Network(Private Network - Trusted) --> FIREWALL:gateway for security --> External Network(Public Network - Untrusted)

### Software Firewall(also called Host based Firewall)

1. Firewalls that are installed on our PCs are known as software firewalls.
2. As it will present inside the system, it will consume software resources like computer processors, RAMs etc
3. Software firewalls protect the system and filter the traffic in which it is installed.

### Hardware Firewall(also called Appliance Firewall)

1. Firewalls that are placed between our system and an untrusted network(internet) are known as hardware firewalls.
2. As it is placed outside the system it has its own hardware and software, it doesn't use our system resource.
3. Hardware firewalls protect all the computers and filter the entire traffic that is present in its network.

NOTE: When more than one computer is connected to an untrusted network, it is necessary to place a hardware firewall between them.

## What are Data Packets?
Information generally doesn't pass as we have or receive them, it passes in encrypted form in small chunks.

Information is divided into small chunks that are sent over the network from one system to another known as data packets.

For network communication, they are important aspects that allow data to be transmitted easily.

Data packets contain two things-
1. Data Headers - IP address of sender and receiver with port numbers.
2. Data Payloads - some part of data in encrypted form.

## How do firewalls help us to not become a victim of online hacking?

### Filtering Networks: 
The firewall works with security criteria or a set of rules that are generally set by IT and network managers, and according to those rules, it will filter out unwanted requests.

### Packet Filtering:
Data are not transferred or received directly as we send or get data, it is divided into small chunks known as packets, so every time it passes through a firewall, the firewall checks it and blocks it if it is from some unwanted sites or from banned internet location.

### Stateful Inspection:
Firewall maintains the list of allowed and not allowed servers or IP addresses known as Access List, that help in filtering better.

Firewalls also record the conversation list which saves your computer IP address and name of the website you are currently visiting. So if any unwanted site sends some malicious data, it will block it as it knows which sites you are currently accessing.

It will also do a TCP inspection at each stage.

### Provide History:
It not only prevents us from unwanted hacks but also keeps the history of all the data that passed through or blocked.

## Types of Firewalls

### Packet Filtering Firewall
 
1. Works on 4 layers - Physical layer, Data link layer, Network layer, and transport layer.
2. That's why, this type of firewall only checks for ip address of the sender and receiver with port numbers in data packets(IP header and TCP Header) but do not check data payloads.
3. It filters packets according to Access List or security criteria, and it blocks the IPs or maybe whole networks of untrusted sites if any malicious activity found.
4. The packet filtering firewall is present in our internet router - so they are the cheapest and quickest way of implementing.
5. As they don't check for data payloads, hackers can send the malicious code through data packed in that area, hence we can say that it is low-security firewall.

### Application/Proxy Firewall

1. Works on 5 layers - Physical layer, Data link layer, Network layer, transport layer, and Application layer.
2. This firewall adds up the extra layer of separation, that is why it deep scans both header and data through it.
3. It filters packets by checking both data headers and data payloads and blocks untrusted sites if anything is malicious.
4. As it checks both, it will take more time - hence is slower than a packet filtering firewall.
5. It also hides the client's IP address from the server. Basically, it creates encapsulation between client and server as present in between.
   
### Hybrid Firewall

1. It is a combination of packet filtering and application firewalls.
2. Provide better security overall.

Internal Network(Private Network - Trusted) --> Network/Packet Filtering Firewall --> Application/Proxy Firewall --> External Network(Public Network - Untrusted)

## Conclusion

Firewalls are essential for every network as they save our system from DDoS attacks, Backdoor malware, remote hijacking, or viruses that come with external software or programs.

So we have to make sure that we are choosing newer version(update them regularly) of firewall software rather than outdated ones so our network protection will be maintained strongly.

Also along with firewalls, we need antivirus protection so we protect our system against masquerades. This will help to secure our system more.

### Reference

1. Youtube - https://youtube.com/playlist?list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&si=rxz7xSyp2gQ8-ZEe
2. Some Blogs
    1. https://whatismyipaddress.com/firewalls-work
    2. https://www.kaspersky.com/resource-center/definitions/firewall
    3. https://nordlayer.com/learn/firewall/how-firewall-work/
3. https://www.geeksforgeeks.org/tcp-ip-model/
