# Firewall

## What is a Firewall?

Firewalls are the software programs(hardware or software) that behave like a gateway between our system and outside internet to protect us from viruses, malwares or hackers to reach out to our system from internet.

Firewalls collect traffic and filter it, by apporving trusted data packets and blocking untrusted and unapproved ones. It also regulates the flow of firewall between computer network different levels.

Firewalls are typically divided into two types - Software firewall and Hardware firewall. 

So we can say that firewall is a hardware and software tool that limits the access of networks in our system.

Internal Network(Private Network) --> Trusted
            |
            |
            |
        FIREWALL --> gateway for security
            |
            |
            |
External Network(Public Network) --> Untrusted

### Software Firewall(also called Host based Firewall)

1. Firewall that are installed in our PCs are known are software firewall.
2. As it will present inside the system, so it will consume software resources like computer processors, RAMs etc
3. Software firewalls only protect system and also filters the traffic in which it is installed.

### Hardware Firewall(also called Applicance Firewall)

1. Firewalls that are placed between our system and untrusted network(internet) is known as hardware firewall.
2. As it is placed outside the system so it has it own hardware and software, it didn't use our system resource.
3. Hareware firewalls protect all the computers and filter entire traffic that are present in its network.

NOTE: When more than one computer is connected to an untrusted network, it is necessary to place hardware firewall between them.

## What are Data Packets?
Information generally don't pass as we have or we recive, it pass in encryted form or in small chunks.

Information divided into small chunks that are sent over network from one system to another known as data packets.

For network communication, they are important aspect that allow data to transmit easily.

Data packets contain two things-
1. Data Headers - Ip address of sender and reciver with port numbers.
2. Data Payloads - some part of data in encryted form.

## How do firewall help us to not become a victim of online hacking?
(How do Firewall works?)

### Filtering Networks: 
Firewall works with security cretaria or set of rules that are generally set by IT and network manager, and according to those rules it will filter out the unwanted requests.

Network managers can also set or block some traffic from unknown site if they want.

### Packet Filtering:
Data do not transfer or recieve directly as we sending or getting data, it divide into small chunks known as packets, so everytime it pass through firewall, firewall checks it and block it if it is from some unwanted sites or banned internet location.

### Stateful Inopection: 
Firewall maintains the list of allowed and not allowed servers or IP addresses known as Access List, that help in filtering better.

Firewells also records the conversation list in which it saves your computer IP address and name of the website you are curently visiting. So if any unwanted site send some malicious data, it will block it as it know which sites you are currently accessing.

It will also do TCP inspection at each stage.

### Provide History:
It not only prevent us from unwanted hacks but also keeps the history of all the data that passed through or blocked.

## Types of Firewalls

### Packet Filtering Firewall
 
1. Works on 4-layers - Physical layer, Data link layer, Network layer and transpost layer.
2. That's why, this type of firewall only checks for ip address of sender and reciver with port number in data packets(IP header and TCP Header) but do not check data payloads.
3. It filter packets according to Access List or security cretaria, and it block the IPs or maybe whole networks of untrusted sites if found any malicious activity.
4. The packet filtering firewall present in our internet router - so they are the cheapest and quickest way of implementing.
5. As they don't check for data payloads, so hacker can send the malicious code through data packed in that area, hence we can say that it is low security firewall.

### Application/Proxy Firewall

1. Works on 5-layers - Physical layer, Data link layer, Network layer, transpost layer and Application layer.
2. This firewall adds up the extra layer of seperation, that's why it deep scans both header and data through it.
3. It filters packets by checking both data headers and data payloads, and block the untrusted sites if found anything malicious.
4. As it checks both, it will take more time - hence is slower than packet filtering firewall.
5. It also hides the client IP address from the server. Basically it creates encapsulation between client and server as present in between.

### Hybrid Firewall

1. It is a combination of packet filtering and application firewall.
2. Provide better secuiry overall.

Internal Network(Private Network) --> Trusted
            |
            |
            |
    Network/Packet Filtering Firewall
            |
            |
            |
    Application/Proxy Firewall
            |
            |
            |
External Network(Public Network) --> Untrusted

## Conclusion

Firewalls are essentail for every network as they save our system from DDos attack, Backdoor malwares, remote hijacking or viruses that comes with external software or programs.

So we have to make sure that we are choosing newer version(update them regularly) of firewall software rather than outdated ones so our nework protection will be maintained storngly.

Also along with firewalls, we need antivirus protection so we protect our system against masquerades. This will help to secure our system more.

### Reference

1. Youtube - https://youtube.com/playlist?list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6&si=rxz7xSyp2gQ8-ZEe
2. Some Blogs
    1. https://whatismyipaddress.com/firewalls-work
    2. https://www.kaspersky.com/resource-center/definitions/firewall
    3. https://nordlayer.com/learn/firewall/how-firewall-work/







