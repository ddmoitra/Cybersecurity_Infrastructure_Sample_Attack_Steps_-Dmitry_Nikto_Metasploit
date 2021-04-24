### Title

* Cybersecurity Infrastructure Sample Attack Walkthrough using Dmitry Nikto Metasploit tools

### About / Synopsis

* The purpose of this project is to demonstrate a hypothetical cybersecurity attack using the testing tools available within the popular Kali Linux distribution - Dmitry (Information Gathering), Nikto (Vulnerability Reporting) and Metasploit (Exploitation). A sample intentionally vulnerable Metasploitable virtual machine (VM) is also spun up in Oracle VirtualBox. A range of scanning and exploit activities are then executed on the vulnerable target VM to gain access remotely.

### Detailed Description 

*The Kali Linux VM (a.k.a. KaliDeepto) and target Metasploitable VM are installed and setup on Oracle VirtualBox

*The IP addresses of the both VMs are retrieved for future reference


*Dmitry tool is executed on Kali Linux using the target vulnerable VM's IP address and performs information gathering. Log file is included in project folder.


*Nikto is then run to gather and report all potential vulnerabilites on the Metasploitable VM. Log file is included in project folder.

*Metasploit on Kali Linux is executed and a backdoor exploit (exploit/unix/irc/unreal_ircd_3281_backdoor) is selected as the choice of attack

*The payloads available for the backdoor exploit are reviewed 


*The selected payload (cmd/unix/reverse) and additonal parameters of the attack are setup

*The exploit is executed on the vulnerable Metasploitable VM showing how remote access can be obtained by running the 'whoami' and hostname commands and finally exiting out of the remote shell. Log file is included in project folder.



### Installation / Software Requirements

* The following tools were used in this project:

*Oracle VirtualBox 6.1
*Debian Ubuntu i386 CD ISO image
*Kali Linux VM 2021.1
*Metasploitable Ubuntu vmdk image
*Dmitry
*Nikto v2.1.6
*Metasploit v6.0.30-dev


### Support

* This project is a standalone development initiative without any ongoing support

