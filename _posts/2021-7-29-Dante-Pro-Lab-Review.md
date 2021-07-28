---
title: Dante Pro Labs Review
date: 2021-7-29 03:27:00 +0530
categories: [HackTheBox]
tags: [hackthebox, ctf, penetration testing, pentest]
image: /assets/img/Posts/dantelabs.jpeg
---


## Introduction:

Hey security friends, I'm gonna talk about dante pro lab from hack the box. For those who don't know dante pro lab, It's a lab that simulate the penetration testing engagement and the lab provid some of real-world scenario.
the lab contains 3 networks that include 14-machines. Which you have to hack it all.

# Summary:
To summarize the review, I will not just talk about dante pro lab, i am gonna talk about the dante pro lab side by penetration testing in general and how to go further with your penetration testing skills.

# Who can take this lab ?:
- Anybody want to take security certificates such as ( OSCP & eCPPT )
- Anybody want to practice on penetration testing and prove his own skills
- Anybody who is not getting enough with machines and wanna break a real-world scenario

# What the lab covers:

- Enumeration
- Network Pentesting
- Web Applications Pentesting
- Activce Directory Pentesting
- Password Cracking & Brute Forcing
- Exploit Development 
- Exploition & Post-Exploition
- Privilage Escalation
- Lateral Movement

# Lab topics:

Before we cover any topics if you are into penetration testing you got to know some standars to work with for ex PTES ( Penetration Testing & Execution standard ).

- Enumeration:

	You have to learn about enumeration very well cause its the first phase of your pentest which is like the home essentials. 
	So, if you didn't enumerate well you gonna miss a lot of things and maybe your pentest fails.
	Some resources for enumration:
	- https://www.youtube.com/watch?v=WvSEkPU1n0I
	- https://www.youtube.com/watch?v=947o1ySWU2w
	- don't forget to do more search about enumeration

- Network Pentesting:

	You have to learn about network protocols & technologies sideby enumerate most common protocols and pentest it also check the services cause it might be vulnerable and have a public exploit.
	Also, using pivoting & portforwarding to move from network to another.
	Some Resources for network pentesting:
	- https://book.hacktricks.xyz/pentesting/pentesting-network
	- https://www.youtube.com/watch?v=3Kq1MIfTWCE
	- https://nullsweep.com/pivot-cheatsheet-for-pentesters/
	- https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Network%20Pivoting%20Techniques.md
	- https://www.youtube.com/watch?v=S7oMiQw4kIM
	- https://www.hackingarticles.in/port-forwarding-tunnelling-cheatsheet/
	- https://book.hacktricks.xyz/tunneling-and-port-forwarding
	- https://sushant747.gitbooks.io/total-oscp-guide/content/port_forwarding_and_tunneling.html
	- You can find the network protocols pentesting topic in the hacktricks (https://book.hacktricks.xyz) blog sideby your own search
	- don't forget to do more search

- Web Applications Pentesting:
	
	You have to learn how to do enumeration & exploit common web applications vulnerabilities such as OWASP top 10.
	Some Resources for web applications pentesting:
	- https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/01-Information_Gathering/README
	- https://owasp.org/www-project-top-ten/
	- https://www.youtube.com/watch?v=X4eRbHgRawI
	- don't forget to do more search

- Activce Directory Pentesting:

	Active directory is widely used by companies so you must know how to pentest it.
	Some Resources for activce directory pentesting:
	- https://www.youtube.com/playlist?list=PLAC2CBE898D01029E
	- https://www.youtube.com/playlist?list=PLCLxMnnAnGinh7JKcV3dBnTDW8dhNG96N
	- https://www.youtube.com/playlist?list=PLziMzyAZFGMf8rGjtpV6gYbx5hozUNeSZ
	- https://adsecurity.org/
	- https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet
	- https://github.com/infosecn1nja/AD-Attack-Defense
	- don't forget to do more search

- Password Cracking & Brute Forcing:
	
	Sometimes while you are doing penetration testing you will find some encrypted passwords.
	In this case you have to get the clear-text ( the creds before encryption ) so in this case you gonna to preform password cracking.
	Some Resources for password cracking & brute forcing:
	- https://www.youtube.com/watch?v=XjVYl1Ts6XI
	- https://www.youtube.com/watch?v=z4_oqTZJqCo
	- don't forget to do more search

- Exploit Development:

	This topic is one of the best topics at all cause exploit develpment about finiding zero-days and develop exploits for common protocols, softwares and more. 
	But we will cover the basic one and its buffer overflows.
	Some Resources for buffer overflows (windows & linux):
	- https://github.com/gh0x0st/Buffer_Overflow
	- https://www.youtube.com/watch?v=yJF0YPd8lDw
	- https://hex-men.tech/vulnserver_buffer_overflow/
	- https://www.ired.team/offensive-security/code-injection-process-injection/binary-exploitation/64-bit-stack-based-buffer-overflow
	- https://www.coalfire.com/the-coalfire-blog/september-2020/the-basics-of-exploit-development-5-x86-64-buffer
	- don't forget to do more search

- Exploition & Post-Exploition:

	Exploitation & Post-Exploitation phases are important phases of penetration testing lifecycle to gain access to the vulnerable system by exploiting a vulnerability.
	Some Resources for exploition & post-exploition:
	- https://www.youtube.com/watch?v=IJ4M2DDMjgY
	- https://www.youtube.com/watch?v=ELimzgVr3To
	- https://www.youtube.com/watch?v=mcuNn7q8nuY
	- https://github.com/mubix/post-exploitation-wiki
	- https://pentestlab.blog/category/post-exploitation/
	- don't forget to do more search

- Privilage Escalation:
	
	This topic about gainning high privilages on the compromised system to get high control on the system.
	Some Resources for privilage escalation:
	- https://www.youtube.com/playlist?list=PLjG9EfEtwbvIrGFTx4XctK8IxkUJkAEqP
	- https://www.youtube.com/playlist?list=PLDrNMcTNhhYrBNZ_FdtMq-gLFQeUZFzWV
	- https://book.hacktricks.xyz/windows/windows-local-privilege-escalation
	- https://book.hacktricks.xyz/linux-unix/privilege-escalation
	- https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md
	- https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Windows%20-%20Privilege%20Escalation.md
	- don't forget to do more search

- Lateral Movement:

	After gaining initial access, to move deeper into a network in search of sensitive data and other high-value assets.
	Some Resources for lateral movement:
	- https://www.ired.team/offensive-security/lateral-movement
	- https://github.com/MicrosoftDocs/ATADocs/blob/master/ATPDocs/playbook-lateral-movement.md
	- https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/ATT%26CK-Stuff/ATT%26CK/Lateral%20Movement.md
	- https://riccardoancarani.github.io/2019-10-04-lateral-movement-megaprimer/
	- https://kjohn333.gitbook.io/offsec-journey/active-directory/lateral-movement
	- https://pentestlab.blog/2020/07/21/lateral-movement-services/
	- https://cheats.philkeeble.com/active-directory/lateral-movement
	- don't forget to do more search

# Books & Courses:

- https://academy.tcm-sec.com/p/practical-ethical-hacking-the-complete-course
- https://academy.tcm-sec.com/p/windows-privilege-escalation-for-beginners
- https://academy.tcm-sec.com/p/linux-privilege-escalation
- https://academy.tcm-sec.com/p/movement-pivoting-and-persistence-for-pentesters-and-ethical-hackers
- https://www.amazon.com/Penetration-Testing-Hands-Introduction-Hacking/dp/1593275641
- https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1494932636/
- https://www.amazon.com/Hacker-Playbook-Practical-Penetration-Testing/dp/1512214566/
- https://www.amazon.com/Mastering-Linux-Advanced-Penetration-Testing/dp/178934056X
- https://www.amazon.com/Art-Network-Penetration-Testing-company/dp/1617296821
- https://www.amazon.com/Advanced-Penetration-Testing-Hacking-Networks/dp/1119367689
- You can search for more books & courses.

# Outer:

At the end, I would like to say that i have fun while playing thios lab and i became more familiar with a lot of attacks and techniques.
In my opanion the lab containes arond 60% of real-world scenarios. 
Another point about the differince between the normal machines and the labs in general that the labs teach you about the full penetration testing lifecycle & engagement.
For example the labs contains an enterprise network when you hack into a machine you have to show your skills in moving further than hacking a machine and get root then stop,
You have to move and note every single point to reuse the creds or whatever you got in moving inside the enterprise.
Last thing to do is to practice more and never stop research don't just put in your mind to just finish the lab but you have to think about gainning more knowledge and sharping your skills.
