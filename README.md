## Virtual Hacking Labs ##

So after passing OSCP and doing some other certs that aren't specifically infosec related (for school) I wanted to get back into hacking non-work related stuff. So I started doing Virtual Hacking Labs:

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

I didn't need scan results outside of these so far (All Beginner and Advanced boxes complete at time of writing).

The variation of host types and OSes is very interesting.

Once you start into the Advanced + machines, you get into interesting vectors and privesc.

I did find a recent exploit for an Advanced+ machine that made it trivial, and bypasses the "unhackable" nature of the setup.
