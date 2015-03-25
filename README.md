# security-101
learning about computer security and testing 

# Other Peoples work repos, blogs
* https://github.com/ClickSecurity/data_hacking
* https://github.com/zigoo0/webpwn3r
* https://github.com/packetloop/packetpig

# Books


# Reference Sites


- - - -

# Random Stuff  

## Pen Test
There are a few basic steps to a pen test – there is a nice little write-up [here](http://www.infosecwriters.com/text_resources/pdf/PenTest_MSaindane.pdf) for this but I’ll outline the highlights below  

1. Footprinting
	- What you can find on the internet. It’s more than you think. DNS lookups. Whois records. There is a tool on kali called The Harvester that I like to use.
2. Scanning and Enumeration
	- This is doing a full scan on the network range or IP. The only tool that should be used here is NMAP. A nice GUI version for Windows called ZenMap exists and is very user friendly. I’ll give you hints and tricks when you get there. This is a fairly major part of it as this is telling you what you should see.
	 - There is also a very new tool called Sparta which is a python GUI scanner. I’ve used it lightly and am very impressed with it. It mixes nmap, screen capture and other ideas all into one. Honestly this might be a great springboard for you to combine your skills and desires.  It of course has a github
	 - http://sparta.secforce.com/
	 - https://github.com/SECFORCE/sparta
3. Vulnerability Analysis
	- Again there are multiple tools, but to be real there is a clear leader with Nessus, IMO. I believe this is included with Kali and does a fantastic job. There are small tweaks that can be done, but the default is pretty solid. I highly recommend Nessus. However, be careful when doing the vulnerability scanning if you are scanning a really old shitty network that is running on shit hardware and shit software. You can tip over servers with these scans as they are fairly aggressive sometimes. Honestly though, if your network tips over because of a vulnerability scan it was just a matter of time before someone else got to it before you did. 


4. Exploitation
	- This is where you get your hands dirty. You use the appropriate exploit from Metasploit (Kali) to take it to the next level. You show that you can get into a system and ‘poke around’. 
5. Escalation of privileges
	- This is self-explanatory. Obviously the bad guys are going to want to get in there and take information from you… hopefully  you don’t have a ‘flat’ network and you have separation of administrative privileges from normal users. If you don’t you have way bigger fish to fry then doing a pen test and you should go back to that.
6. Pwnage
	- This is where you c:format. Or set up a bot to call out to your server and upload information. 
7. Writing up what you find 
	 - This is the part that is boring. I have some templates that I can sanitize and send to you

## Book list
 - [Violent python](http://mirror7.meh.or.id/Programming/Violent_Python_A_Cookbook_for_Hackers_Forensic_Ana.pdf) – This is exactly what you were asking for last night; scripting with python to hack into a network. I am currently working through it right now, just very poorly. 
 - [The Hacker Playbook](http://www.look2linux.com/wp-content/uploads/2014/09/The-Hacker-Playbook-Practical-Guide-To-Penetration-Testing-look2linux-com.pdf) – This is a great intro that steps you through ever ‘phase’ of a pen test. They say that you need a bit of security experience, but I think that’s a bit of a stretch. I think you need computer experience and this would be a great book for you. This is a great place to get started, and they’ll offer far better explanations than I can. I’ll be happy to answer any questions along the way.  
 - [Red Team Field Manual](http://www.amazon.com/Rtfm-Red-Team-Field-Manual/dp/1494295504/ref=sr_1_1?s=books&ie=UTF8&qid=1427287831&sr=1-1&keywords=red+team+field+manual) - If you have an extra 10 bucks to spend on Amazon, spend it on this. It looks totally awesome. It’s got a lot of fun little tips and tricks and some python ‘cheats’ in there. It’s not super user friendly, but for the price it’s really worth it.
 - [Hacking, The Art of Exploitation](https://leaksource.files.wordpress.com/2014/08/hacking-the-art-of-exploitation.pdf ) – This book is fantastic. A lot of the programming goes right over my head. It might actually do you more good than me. If you decide to pass on this do yourself (and me) a favor and read the intro. It’s a short read and fun. I agree with the author on a lot of his points, if not all them. 
 - [Metasploit Penetration Testers Guide](ftp://ftp.fixme.ch/free_for_all/Ebook/IT%20eBooks/Security/Penetration%20Testing/Software%20&%20System/Metasploit,%20Penetration%20Testers%20Guide.pdf) – The title says it all. This is all about Metasploit, which is considered ‘the’ tool for exploiting vulnerable servers. Probably a bit more advanced than you are looking for, but I thought I would offer it in the listing anyway. 

## URL List
www.reddit.com/r/netsec - active experts posting the cool stuff they do

www.reddit.com/r/asknetsec - Place to ask your questions, they are usually pretty friendly. Usually.

www.darkreading.com – industry news

http://dfir.org/?q=node/8 - this is a list of recommended reading by one of the top security guys in the field.

http://dhs-daily-report.blogspot.com/ - This is mostly unrelated but it’s a national security report that I read every day, it’s pretty interesting.

