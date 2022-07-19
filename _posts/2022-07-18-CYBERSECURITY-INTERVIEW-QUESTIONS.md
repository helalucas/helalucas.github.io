---
layout: post
title: "Cybersecurity Question Bank"
date: 2022-07-18 18:19:00 -0000
author: Hela
---

Since my first year at University, I have been asking everyone I know for a list of questions they got asked at cybersecurity job interviews. This list does not contain the questions I got asked when under an NDA, however I believe most topics I was asked about are tangentially covered.

I am not including answers to any of these questions, as I think doing your own research will lead to a better understanding, and I do not feel like I could give an authoritative answer. Please do not be intimidated by all of these – I have never been required to know how to answer each one.

If you have any questions to add, please get in touch.

A great resource for answering some of these questions is here.

How does the internet work?

What happens when you google “dogs”?

What is DNS and how does it work?

How can you attack DNS?

What is a DNS amplification attack?

How do you protect a network?

What is an IDS and how does it work?

What is the difference between IDS and IPS?

What is a SIEM?

What is an EDR and how does it work?

What is the difference between a router and a switch?

How do you protect an endpoint?

How would you detect malicious activity on a network/endpoint?

An employee tells you her computer has malware '96 how would you determine if it does ?

Describe the most common ways an external attacker today might attempt to gain access to a network.

You just got put in charge of a network after the last sysadmin was fired. What steps would you take to protect the network?

A user forwards you a suspected phishing email. How do you respond and handle it?

What are the primary reason NOT to upload targeted malware to Virus Total?

What is symmetric cryptography? Examples?

What is asymmetric cryptography? Examples?

What'92s the difference between encoding, encryption, hashing and obfuscation?

What percentage of malware in the wild do you think AV can detect?

How would you bypass a network IDS?

A trusted source gives you a 10GB PCAP to analyse. Something bad is in it. What is your methodology for finding it?

How would you secure an endpoint in an enterprise?

What do you believe are the biggest threats to an enterprise network?

Not a question, but make sure you understand subnetting.

A user opens a browser, types google.com into the URL bar and hits enter. What happens?

Describe the layers of the OSI model.

What does ARP do?

Can you explain an attack that would use ARP?

How does NAT work?

Can NAT be used maliciously?

How does DNS work?

Could DNS be used maliciously?

How does traceroute work?

Can traceroute be used maliciously?

What is an HTTP header and what does it look like?

What is an TCP/IP header?

What port does ICMP (ping) run on? (Trick question!)

What'92s the difference between TCP and UDP?

What'92s the sequence for establishing a TCP connection?

What'92s the sequence for terminating a TCP connection?

How does an HTTPS connection work?

Can you name some vulnerabilities one might find in a website or app?

Can you talk about protecting against the above mentioned vulnerabilities?

What is SQL injection and how does it work?

How would you mitigate SQL injection?

What is cross-site scripting?

How would you mitigate cross-site scripting?

What is the difference between data protection in transit and data protection at-rest?

What is the difference between a threat, a vulnerability, and a risk?

How do you go about securing a server?

How do you go about securing a website?

How would you migrate a website from one server to another?

What are the differences between HTTPS, SSL, and TLS?

Describe the TLS handshake in detail.

What sorts of anomalies would you look for to identify a compromised system?

If you had to both compress and encrypt data during a transmission, which would you do first?

How would you strengthen user authentication?

What are the differences between cybersecurity in the cloud and on premises?

Describe PKI.  

What is the difference between UDP and TCP?

As you know there are security issues (like Bufferoverflow) in image parsing libraries, you have to design a secure library that parses images, make sure there must be no security vulnerabilities in it, how will you design it?

Walk me through designing Google'92s single sign on for all google'92s services that requires login, for example youtube?

How do you protect against XSS without having to use encodings and javascript is allowed?

Share your experience of fuzzing?

What is origin in Same-origin-policy?

What is a firewall?

What is a three-way handshake?

How do cookies work?

How do sessions work?

Explain how OAuth works.

What is a public key infrastructure flow and how would I diagram it?

Describe the difference between synchronous and asynchronous encryption.

Describe SSL handshake.

How does HMAC work?

Why HMAC is designed in that way?

What is the difference between authentication vs authorization name spaces?

What'92s the difference between Diffie-Hellman and RSA?

How does Kerberos work?

If you'92re going to compress and encrypt a file, which do you do first and why?

What is the difference between encryption and encoding?

What is the difference between 128 and 256?

How do I authenticate you and know you sent the message?

Should you encrypt all data at rest?

How does threat modeling work?

What is a subnet and how is it useful in security?

What is a subnet mask?

Draw a network, then expect them to raise an issue and have to figure out where it happened.

Write out a Cisco ASA firewall configuration on the white board to allow three networks unfiltered access, 12 networks limited access to different resources on different networks, and 8 networks to be blocked altogether.

Describe the Risk Management Framework process and a project where you successfully implemented compliance with RMF.

How does a packet travel between two hosts connected in same network?

TCP and UDP '96 Which is more secure? Why?

What is the difference between IPSEC Phase 1 and Phase 2?

What are biggest AWS security vulnerabilities?

How do web certificates for HTTPS work?

Is ARP UDP or TCP?

Explain what information is added to a packet at each stop of the 7 layer OSI model.

Walk through a whiteboard scenario for your environment of choice (Win/Linux) in which compromising the network is the goal without use of social engineering techniques (phishing for credential harvesting, etc).

Explain how you would build a web site that could secure communications between a client and a server and allow an authorized user to read the communications securely.

How does an active directory work?

Do you know how Single Sign-On works?

How do you build a tool to protect the entire Apple infra?

How do you harden a system?

How to you elevate permissions?

Differentiate XSS from CSRF

What is the difference between tcp dump and FWmonitor

Do you know what XXE is?

Explain man-in-the-middle attack

How would you attack Microsoft, persist on our network, perform recon, and exfiltration data without being detected? And then how would you write detections for your stated attack path?

Tell me what you know about BGP?

Please describe what spanning tree protocol does in as few words as possible

what do you do to stay relevant in your field as it evolves?

Could you break out 3 /26 subnets from 192.168.0.0/23

Could you start by giving us a few specific examples from your career to date that demonstrates your skillset for this role.

Can you tell us about a technology choice you have had to make. How did you evaluate the choice?

Think about a reasonably complicated technical idea or concept you know a lot about. Please explain that to someone not familiar with it.

This technology can be delivered as both a SaaS product or On-Premise. A potential customer wants to know the difference, can you please explain to them.

Our primary stack is noSQL/mySQL/PHP/JS/Spunk/Elasticsearch and a Webserver (Apache, IIS, Nginx). Can you give us some detail on your level of experience with these technologies and the types of problems you have had to solve using them.

Do you have experience doing testing/qa for reported software bugs? How do you go about this?

Can you describe the difference between a SDK and an API.

Can you describe what a JOIN does and how it's different to a SUBQUERY?

A customer wants to import data from another competing product into ours. Talk us through some of the approaches to this type of problem.

When I click send in my mail client, what happens between that click and the email arriving in the mailbox of the person the email is being sent to.


What is a three-way handshake?

How do cookies work?

How do sessions work?

Explain how OAuth works.

What is a public key infrastructure flow and how would I diagram it?

Describe the difference between synchronous and asynchronous encryption.

Describe the SSL handshake.

How does HMAC work?

Why HMAC is designed in that way?

What is the difference between authentication vs authorization name spaces?

What’s the difference between Diffie-Hellman and RSA?

How does Kerberos work?

If you’re going to compress and encrypt a file, which do you do first and why?

What is the difference between encryption and encoding?

What is the difference between 128 and 256?

How do I authenticate you and know you sent the message?

Should you encrypt all data at rest?

How does threat modeling work?

What is a subnet and how is it useful in security?

What is a subnet mask?

Draw a network, then expect them to raise an issue and have to figure out where it happened.

Write out a Cisco ASA firewall configuration on the white board to allow three networks unfiltered access, 12 networks limited access to different resources on different networks, and 8 networks to be blocked altogether.

Describe the Risk Management Framework process and a project where you successfully implemented compliance with RMF.

How does a packet travel between two hosts connected in same network?

TCP and UDP – Which is more secure? Why?

What is the difference between IPSEC Phase 1 and Phase 2?

What are biggest AWS security vulnerabilities?

How do web certificates for HTTPS work?

Is ARP UDP or TCP?

Explain what information is added to a packet at each stop of the 7 layer OSI model.

Walk through a whiteboard scenario for your environment of choice (Win/Linux) in which compromising the network is the goal without use of social engineering techniques (phishing for credential harvesting, etc).

Explain how you would build a web site that could secure communications between a client and a server and allow an authorized user to read the communications securely.

How does an active directory work?

Do you know how Single Sign-On works?

How do you build a tool to protect the entire *insert compsany name* infra?

How do you harden a system?

How to you elevate permissions?

Differentiate XSS from CSRF

What is the difference between tcp dump and FWmonitor

Do you know what XXE is?

Explain man-in-the-middle attack

How would you attack Microsoft, persist on our network, perform recon, and exfiltration data without being detected? And then how would you write detections for your stated attack path?

Tell me what you know about BGP?

Please describe what spanning tree protocol does in as few words as possible

what do you do to stay relevant in your field as it evolves?

Could you break out 3 /26 subnets from 192.168.0.0/23

Could you start by giving us a few specific examples from your career to date that demonstrates your skillset for this role.

Can you tell us about a technology choice you have had to make. How did you evaluate the choice?

Think about a reasonably complicated technical idea or concept you know a lot about. Please explain that to someone not familiar with it.

This technology can be delivered as both a SaaS product or On-Premise. A potential customer wants to know the difference, can you please explain to them.
Our primary stack is noSQL/mySQL/PHP/JS/Spunk/Elasticsearch and a Webserver (Apache, IIS, Nginx). Can you give us some detail on your level of experience with these technologies and the types of problems you have had to solve using them.

Do you have experience doing testing/qa for reported software bugs? How do you go about this?

Can you describe the difference between a SDK and an API.

Can you describe what a JOIN does and how it’s different to a SUBQUERY?

A customer wants to import data from another competing product into ours. Talk us through some of the approaches to this type of problem.

When I click “Send” in my mail client, what happens between that click and the email arriving in the mailbox of the person the email is being sent to.

Why are you looking to leave your current role. What about your old role do you want to remain in your new role, and what do you want to be different?

What excites you about this role, and why do you think it would be the right role for you?

Compare two popular products or solutions and tell me why you prefer one (eg. LogRythm and Splunk)

A customer wants to onboard logs from an API – what are your considerations before implementing this/what is the effect o the SIEM?

A log source source stops reporting logs – what do you do?

Your SIEM has lots of different log sources, of variable criticality – how do you make this distinction?

Develop a generic use-case for failed login attempts.

What are examples of existing automation solutions you have used?

You want to install botnet on Enterprise: how do you install it? how do you communicate with it (Protocol/port)? how do you maintain the access and make sure you can access it after the reboot of the system?

Why is it more difficult to develop and spread malware on iOS than MacOS?

What are the advantages of running a binary in userland vs kernelland?

Some of these questions have been taken from: Abertay Hackers wiki, Glassdoor, this blog, this github repo and various friends & colleagues – this is a list of the ones I personally have found to come up most based on asking lots of people.

