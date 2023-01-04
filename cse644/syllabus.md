# Syllabus: CSE 488/644

[Home](./index.md) &nbsp;&nbsp;&nbsp; [Syllabus](./syllabus.md)  &nbsp;&nbsp;&nbsp; [Labs](./labs.md) &nbsp;&nbsp;&nbsp; [Schedule](./schedule.md)

## Learning Objectives

This course provides an in-depth study of various network attacks techniques
and methods to defend against them. A number of threats and vulnerabilities of
the Internet will be covered, including various vulnerabilities of TCP/IP
protocols, denial of service (DOS), attacks on BGP, attacks on DNS servers,
and so on. This course will also cover defense mechanisms,
including firewalls, VPN, and cryptography.
The basics of the TCP/IP protocols will also be covered in the course.

The course emphasizes "learning by doing",
and requires students to conduct a series of lab exercises. Through these labs,
students can enhance their understanding of the principles, and be able to
apply those principles to solve real problems.


## Required Textbook

Wenliang Du. [Internet Security: A Hands-on Approach, 3rd Edition](https://www.handsonsecurity.net/).


## Grading (subject to change)

 - Quizzes and Exams: Total 50%
   - Quizzes (bi-weekly, 10 - 20 minutes): 20%
   - Final Exam Part 1: 10%  (April 27, in class)
   - Final Exam Part 2: 20%  (May 05, 10:15AM - 12:15PM, Link 105)

 - Labs: 50%
   - Late Homework Policy: 10% penalty per business day.


## Topics

- Introduction and Network Security Basics
  - Internet Architecture
  - How the Internet works (high-level overview)
  - IP Address
  - Packet sniffing and spoofing

- TCP/IP Protocols, Vulnerabilities, Attacks, and Countermeasures
  - Data Link Layer: ARP protocol and ARP cache poisoning

  - Network Layer:
      - IP protocols, IP fragmentation attacks
      - ICMP protocol and ICMP misbehaviors
      - IP routing protocols and Attacks

  - Transport Layer: 
      - TCP protocol 
      - TCP SYN flooding, reset, and session hijacking attacks
      - Mitnick attack

  - Domain Name System (DNS): 
      - DNS protocol
      - Local DNS attack, the Kaminsky (remote) attack, DNS rebinding attack
      - DNSSEC

  - Border Gateway Protocol (BGP) and Attacks


- Network Security Mechanisms

  - IP tunneling and SSH tunneling
  - Virtual Private Networks (VPN)
  - Firewalls and Firewall evasion 
  - Public Key Infrastructure (PKI)
  - Transport Layer Security (TLS/SSL)
  - Darknet (Tor)

- Other Network Attacks
  - Internet worms
  - Ransomware

