前言
====

If you have picked this book off the shelf and opened the cover, you probably already
know what OSSEC is, but just in case you don’t know, as it states on the OSSEC web page,
“OSSEC HIDS is an Open Source Host-based Intrusion Detection System. It performs log
analysis and correlation, file integrity checking, rootkit detection, time-based alerting and
active response.” Linuxworld, who rated OSSEC the number one of five tools used in production
in an enterprise environment said, “The OSSEC HIDS project has been gaining widespread
use and is quickly being deployed within organizations around the world as a method of
protecting systems at the host level after attacks have made it past network defenses.” OSSEC
runs on most operating systems, including Linux, OpenBSD, FreeBSD, Solaris and Windows.”
Since its launch in October 2003, OSSEC has gained momentum to the tune of 10,000
downloads each month from all over the world.

People love it! One user wrote, “I do PCI (payment card industry) consulting, and every
client needs to have a centralized log server and file integrity solution.” Well-known security
researcher Anton Chuvakin wrote, “that it was an awesome move for OSSEC to incorporate
database log alerts for MySQL and PostreSQL. I think this will help bringing database logging
into the mainstream much faster!” OSSEC is one of those rare open source tools that meets
or exceeds the capabilities of its commercial counterparts, if indeed OSSEC really does have
a commercial counterpart. Commercial host-based intrusion detection solutions range from
$60 to as high as thousands of dollars. Because there is no free host-based intrusion detection
solution that can match the functionality, scalability, and simplicity of OSSEC, it stands in a
class by itself. “This is a piece of software that literally springs to life,” Richard Bejtlich wrote
on his blog. “Yesterday morning I installed OSSEC on the one system I expose to the Internet.
OSSEC is really amazing in the sense that you can install it and immediately it starts parsing
system logs for interesting activity.”


Each chapter begins with a story to illustrate the important material in the chapter. The
book starts with a fictional story about a hacker, Byung-Soon, an expert in the electronic
theft of corporate information and asserts, that with the right technology and process, everything
he tries to do can be detected and logged. His software even sends the information it collects
to different servers to make detection harder. He then runs a script to collect the information
from each of the servers and has it sent to him.The book compares Network Intrusion Detection,
the technology that we have counted on for years, with Host Based Intrusion Detection,
which might be the future. For instance, with OSSEC installed it would have been possible
to track all of the bits of information being sent to the different servers in the story. The pervasive
deployment of wireless, Bluetooth, and EVDO means that perimeter checkpoints are not as
effective as they once were and puts a tremendous amount of pressure on the endpoint system
for security. Perhaps the most promising assertion in the first part of the book is the discussion
on rootkit detection. Rootkits are the biggest problem the security community has to face
over the next couple of years.


This book is the definitive guide on the OSSEC Host-based Intrusion Detection system
and frankly, to really use OSSEC you are going to need a definitive guide. Documentation
has been available since the start of the OSSEC project but, due to time constraints, no formal
book has been created to outline the various features and functions of the OSSEC product.
This has left very important and powerful features of the product undocumented ...until now!
The book you are holding will show you how to install and configure OSSEC on the operating
system of your choice and provide detailed examples to help prevent and mitigate attacks on
your systems. Included with the book is a DVD containing the latest OSSEC software for
Windows and Linux/Unix, a pre-configured Ubuntu VMware image with OSSEC already
installed, and a step-by-step video detailing how to get OSSEC up-and-running on your system.
In the story line of the book, the people involved decide to install OSSEC after they have
been compromised with a rootkit and had their software stolen:

“What about that open source HIDS tool that we saw on that SANS Institute webinar a few
weeks back?” said Marty. “Do you think that would do the trick?” Simran remembered that OSSEC
sounded like a very capable and feature rich HIDS and jotted some notes down in her notebook to follow
up on it at a later time. “Good idea Marty.” said Simran, thinking to herself that this was the exact
reason why you should always surround yourself with smart people.

Then the book takes you into the pragmatics of installation I have already described. When
you pick up a book like this, you want to understand what the value add is. The author
team, Bray, Cid, and Hay is quite experienced. The team brings a true security and analysis
perspective to the pages of this book. Rory Bray is senior software engineer at Q1 Labs Inc.
Daniel Cid is the creator and main developer of the OSSEC HIDS. Daniel has been working
in the security area for many years, with a special interest in intrusion detection, log analysis,
and secure development. He also works at Q1 Labs Inc. as a software engineer. Andrew Hay
also works at Q1 Labs Inc., leading the team that Rory and Daniel are on. Together, they
deal with security related issues day in and day out when integrating 3rd party event and 
vulnerability data into Q1 Labs’ flagship product, QRadar. These guys have been working in
the security industry for a long time. From helping people with OSSEC they have a great
understanding into the questions people have about configuration, rule writing, and the
management of a host based IDS system. This is where your real investment is made. Take a
look at this fragment from the story the starts chapter 3 and see if it doesn’t sound familiar:

“OK,” said David “how does this OSSEC HIDS thing communicate between the agents and the
server? I don’t want to have to open up all kinds of special ports just so that these things can communicate.”
Marty did his best not to roll his eyes, sigh, or react negatively in any way. In dealing with David before
he knew that his primary concern was always opening new ports between network segments to allow
communication between client and server application deployments.

In the story, David is the department head of operations and he wants to support security,
but he understands the true cost of added complexity in a perimeter environment. In the
same way, the experience Bray, Cid, and Hay have earned supporting users is reflected in this
book. They understand what it means to run OSSEC in the real world. If you have picked
this book up, you have probably heard of OSSEC and are thinking about running it. Let me
encourage you to give it a try, as it is a very promising software distribution. And take a few
minutes to leaf through this book. Can you find the answers you need without this book?
Probably! Is your installation and implementation likely to be more effective with this book?
Almost certainly.

And to the authors, I am sure I speak for the security community when I say thank you,
thanks for all the time creating and testing OSSEC, for your willingness to help us on the
mailing lists and for the sacrifice of time to create this very useful book. You have done your
part to make security a bit more attainable by those that seek greater assurance and we
appreciate that.

								Stephen Northcutt, President
								The SANS Technology Institute,
								a post graduate security college
								www.sans.edu





















































