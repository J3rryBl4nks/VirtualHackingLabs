## Virtual Hacking Labs ##

So after passing OSCP and doing some other certs that aren't specifically infosec related (for school) I wanted to get back into hacking non-work related stuff. So I started doing Virtual Hacking Labs and received the certificate of completion for both the normal and Advanced + certificates.

https://www.virtualhackinglabs.com/


I started working with https://twitter.com/HackingHomebre1 on the boxes.

They are seperated into three difficulties:
1. Beginner
2. Advanced
3. Advanced +

I'll approach this as a workshop to prepare for OSCP (I have my OSCP certification).

My approach to boxes was to use Autorecon : https://github.com/Tib3rius/AutoRecon for enumeration of the boxes.

Autorecon runs a lot of enum tools.

The most useful results were: nmap, nikto, gobuster.

I didn't need scan results outside of these so far (All Beginner, Advanced, and Advanced + boxes (That are in the reset panel) complete at time of writing).

The variation of host types and OSes is very interesting.

Once you start into the Advanced + machines, you get into interesting vectors and privesc.

Since a lot of people who know about this Github are preparing for OSCP, I thought I would break the boxes down by their relative difficulty compared to OSCP lab and exam boxes. (Caveat is that I took the OSCP exam once, so my impressions are biased by my exam host pod.) Also, the 10 point machines in the exam are as difficult as a normal PWK lab host, so I'll cover 20 pt and 25 pt exam hosts.

## It should be noted that there are only 2-3 real Windows privesc vectors covered in the labs. For a somewhat more involved Windows Privesc document, see my LPE Workshop writeup. ##

## VHL Boxes on par with 20 pt OSCP Exam hosts ##
Natural
Dolphin
BackupAdmin
TechBlog
Helpdesk
Aaron
Trails

## VHL Boxes on par with 25 pt OSCP Exam hosts ##
Teamspeak (except for Privesc)
Trace
Fed
CMS02
MON02
JS01
WebSvr01

There is a LOT of kernel privesc in VHL (as I mentioned before), and I didn't find any nearly as much Kernel Privesc in PWK or the OSCP exam.

I decided to do two of the Advanced + machines manually for the certification. I ended up doing the initial exploit, and the privilege escalation manually. I found it not too difficult to do the boxes both 100% manually, but I chose boxes I understood well. Some of the SQL Injection boxes would have been very tiresome to do manually.

Overall I found the boxes to be interesting and entertaining. I feel like VHL is a great investment for OSCP prep and for anyone who is trying to polish their enumeration skills.

