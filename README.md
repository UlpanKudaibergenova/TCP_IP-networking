# TCP_IP-networking

### [TCP IP link challenge](https://github.com/becodeorg/DevSecOps-Training/tree/master/content/website/field/TCP_IP)

Questions are answered in Q&A file. 

#### The Mission
As a junior network administrator looking for a first job opportunity, you have applied to a job offer for a company called SecureLink that owns a software platform to provide secure, accountable, and auditable third-party remote access. Following your first telephone contact with the recruiter, he lets you know that it is very important for this position to have a good understanding of the TCP/IP model.

You have been asked to prepare for the interview in two ways, the first one being to complete a quizz to assess your general theoretical understanding of the TCP/IP model. Try to find an answer for each one of the questions below.

- What are the differences between the OSI model and the TCP/IP model?
- How many layers do these two models have?
- What do the acronyms TCP and IP refer to?
- List the different layers of the TCP/IP model.
- Give some examples of protocols and indicate which one of TCP/IP model layer they refer to.
- Explain how a connection gets established, in other words, explain the "3-way handshake" process?
- Explain how a connection is terminated, in other words, explain the "4-way disconnect" process?
- Explain what are the "sequence number" and "acknowledgment number" in TCP.
- What is the fundamental difference between TCP and UDP ?
- What are TCP ports? How many of them are they? What are the three main categories of TCP Ports (with there associated range)?
- Provide three examples of well-know port numbers and tell to which Application layer protocol they refer to.
- Explain the concept of TCP packets and how they are build over the layer flow.

#### Your second task is to analyse a suspicious piece of network traffic captured in the following .pcap [file](https://github.com/markofu/pcaps/blob/master/HoneyNet/0110/attack-trace.pcap_.gz). To visualize it you should use Wireshark, a network protocol analyzer, and answer the questions below to discover what suspicious activity lie within.

- Which systems (i.e. IP addresses) are involved?
- What can you find out about the attacking host (e.g., where is it located)?
- How many TCP sessions are contained in the dump file?
- How long did it take to perform the attack?
- Which operating system was targeted by the attack? And which service? Which vulnerability?
- Can you sketch an overview of the general actions performed by the attacker? Which are the protocols involved? What can you tell about the payload?

In order to validate this challenge you will have to make a pull request with your answer for both sets of questions in this folder of your training's repository. If you have multiple files use a subfolder (<your_name>, snake_cased).

NOTE: In order for you to understand how computers exchange data over a network (LAN or WAN), you must be able to grasp the TCP/IP Model. Therefore, the main purpose of this briefing is for you to correctly conceptualize TCP/IP so that you can explain how it works and what are its key features (TCP segment structure, Connection establishment, Connection termination, ...).

##### Complementary Resources:

Wiki page: [OSI Model](https://en.wikipedia.org/wiki/OSI_model)

Wiki page: [Transmission Control Protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)

Wiki page: [Internet protocol suite](https://en.wikipedia.org/wiki/Internet_protocol_suite)

Video: TCP Fundamentals Part 1 - [Wireshark Talks at Sharkfest](https://www.youtube.com/watch?v=xdQ9sgpkrX8)

Video: TCP Fundamentals Part 2 - [Wireshark Talks at Sharkfest](https://www.youtube.com/watch?v=NdvWI6RH1eo)

Documentation: [Wireshark documentation](https://www.wireshark.org/docs/)

Notes: [Wireshark Cheat Sheet](https://cdn.comparitech.com/wp-content/uploads/2019/06/Wireshark-Cheat-Sheet-1.jpg)

Video: [Wireshark and TCP](https://www.youtube.com/watch?v=HCHFX5O1IaQ&list=PLMLm7-g0V0keOCLWqodqXn56UfcdA0D_Q) 
