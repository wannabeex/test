[[https://user-images.githubusercontent.com/743886/33368642-3d352df2-d518-11e7-8d2a-3d0144c25125.jpg]]

#########################################################################
Vulnerable Router Project (VRP)
#########################################################################

Wi-Fi routers like every other embedded device are not subject to the same level of security scrutiny in most organizations. What most IT teams don't realize is that todays modern Wi-Fi routers are full blown Linux platforms with web interfaces running on reasonably powerful frameworks. However, most embedded devices are not security tested as a major web application would be today! This is compounded by the fact that most embedded programmers are not web application security experts and end up making the same mistakes most inexperienced web developers do. 

The Vulnerable Router Project (VRP) was created to help train pentesters, application developers and testers on finding common application vulnerabilities on Wi-Fi router platforms. This release has over 21 vulnerabilities to exploit almost all of which have been inspired by published real world vulnerabilities! Our current focus is vulnerabilities which you can exploit once you have IP layer connectivity but soon we will also have Wi-Fi only vulnerabilities as well. 

Technically, VRP is an OpenWRT Chaos Calmer based vulnerable router firmware. We are providing the project in .ova file which can run on both VMware and VirtualBox. This makes it easy for pentesters to quickly run the firmware on their x86 based personal computers without worrying about getting actual hardware. 

VRP 1.0 contains 21 challenges covering 4 vulnerability categories.

These categories are:
 - Misconfiguration vulnerabilities
 - Backdoor vulnerabilities
 - Web vulnerabilities
 - Code based (Non-web) vulnerabilities

The challenges are:
 - Weak Password
 - Maintaining SSH Access
 - Weak File Share Password
 - Misconfigured File Transfer Service
 - Credential Stealing 
 - Authentication Bypass
 - Code Execution
 - Stored XSS
 - Reflected XSS
 - CSRF
 - Arbitrary File Download
 - Open Redirect
 - Unauthenticated Open ports
 - Sensitive Information Leakage
 - File Sharing Service Backdoor
 - Hardcoded Password
 - Hardcoded User Agent
 - Port knocking UDP backdoor
 - Shellshock
 - Heap Overflow Challenge
 - Command Execution Challenge

Detailed challenge list can be downloaded from `here <https://github.com/pentesteracademy/vrp/files/1517655/Challenges.list.pdf>`_
 
##############
Documentation
##############
The documentation manual for VRP can be downloaded from `here <https://github.com/pentesteracademy/vrp/files/1517656/Vulnerable.Router.Project.-.Manual.pdf>`_
 
#############################
Vulnerable Router CTF Videos
#############################

We are Pentester Academy and we love making videos :) 

If you need hints or want to check how we solved the challenges then please head out to:

http://www.PentesterAcademy.com/xxxxxx

########
Authors
########
 - Nishant Sharma, Technical Manager, Pentester Academy (`@wifisecguy <http://twitter.com/wifisecguy>`_)
 - Ashish Bhangale, Sr. Technical Engineer, Pentester Academy (`@Hax0rGuy <http://twitter.com/Hax0rGuy>`_)
 - Yashin Mehaboobe (`@YashinMehaboobe <http://twitter.com/YashinMehaboobe>`_)

################
Acknowledgement
################
Six of our challenges are taken from iv-wrt project. We thank iv-wrt team for their wondeful contribution to security community.
Github: https://github.com/iv-wrt/iv-wrt

Challenges taken from iv-wrt project:
 - Authentication Bypass
 - Code Execution
 - Stored XSS
 - Reflected XSS
 - CSRF
 - Sensitive Information Leakage 
 
#############
Screenshots
#############
VRP VM booting up

.. image:: https://user-images.githubusercontent.com/743886/33368623-327149dc-d518-11e7-935c-5cbc2a760ef4.jpg

Startup banner

.. image:: https://user-images.githubusercontent.com/743886/33368627-35146d36-d518-11e7-9cc4-cded30dc13d7.jpg

LuCI web UI

.. image:: https://user-images.githubusercontent.com/743886/33368617-2e0ff4ce-d518-11e7-9ae8-00a04080f198.jpg

Custom challenge

.. image:: https://user-images.githubusercontent.com/743886/33368636-38f97482-d518-11e7-919e-762346358bb9.jpg
