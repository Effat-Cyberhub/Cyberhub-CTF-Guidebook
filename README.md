
# Cyberhub CTF Guidebook

This is an English translation of the important CTF guidebook provided by SAFCSP's [Cyberhub](https://cyberhub.sa/) initiative for all university students who are interested in Cybersecurity. There will be more collegiate-level CTFs supported by Cyberhub initiative in the future where you can compete with fellow students and win different prizes. I will also provide some add-ons to the guidebook and answer some of the most frequently asked questions and correct the false conceptions that most students tend to say and ask before participating in a CTF competition for the first time. I hope you find it useful! 

## Content

- About CTF competitions 
- Common types of CTFs competitions
- Types of CTF challenges
- Important resources to get started in CTF
- Knowing your favorite type of challenges
- Hacking lab setup
- Frequently asked questions (FAQ)

## About CTF Competetions 

CTF competitions are a gamified learning experience designed to help contestants gain cybersecurity skills and hack in a safe, rewarding environment. The contestants could form or join a team in order to apply and improve their gained skills and by capturing the flag, they can confirm their solution to the challenge.

### The Flag Format

Flags are usually hidden in various locations, they might be placed in a file, a database, or stuck into a source code; but there are so many other ways and different places where you can hide and find a flag. Your goal as a contestant would be to hunt them all down. The flag can be a phrase with a text that appears in a specific format to the contestant after solving a challenge. Below are examples of some of those flags formats:

- ctf{this_is_a_flag} 
- safcsp{this_is_a_flag}
- cyberhub{this_is_a_flag}
- You_successfully_got_the_flag

After capturing the flag, the contestant should submit it, and if it was correct; the contestants will get rewarded by points that confirm their achievement.

## Common types of CTFs competetions

### Jeopardy-style CTFs 

It's usually a combination of computer security challenges that comes in a different range of categories, and each category will have several challenges. For example, you may have forensics, web, reverse engineering, and exploitation categories. The difficulty will range from one challenge to another and each particular challenge will have a score representing its difficulty. 


### Attack-defence 

In this type of competition, contestants should protect their own servers for defense points and hack opponents for attack points, and it's usually a simulation of a real environment that contains multiple servers in which competitors can compete to enhance their blue teaming and red-teaming skills. 


### Mixed 

A mixture of challenges spread over the previous two types.


## Types of CTF challenges

### Cryptography challenges:

Cryptography can be defined as the science of protecting information by transforming it into a secure format that can be accessible by those who own the decryption key. Cryptography is the reason we can protect our privacy. However, CTF cryptography challenges are used to raise awareness of encryption schemes that are improperly implemented and can put our privacy at risk. 

To learn more about Cryptography, you can check this [resource](https://my.eng.utah.edu/~nmcdonal/Tutorials/EncryptionResearchReview.pdf).

### Web hacking challenges:

This category is based on exploiting web vulnerabilities to find the hidden flag. It usually covers any sort of web-based vulnerabilities and exploits. 

### Common vulnerabilities to see in CTF challenges:

- [SQL Injection](https://portswigger.net/web-security/sql-injection)
- [Command Injection](https://portswigger.net/web-security/os-command-injection)
- [Directory Traversal](https://portswigger.net/web-security/file-path-traversal)
- [Cross Site Request Forgery](https://portswigger.net/web-security/csrf)
- [Cross Site Scripting](https://portswigger.net/web-security/cross-site-scripting)
- [Server Side Request Forgery](https://portswigger.net/web-security/ssrf)

To learn more about web vulnerabilities, you can check this [resource](https://portswigger.net/web-security/all-materials).

### Reverse Engineering Challenges:

Reverse engineering (RE) is the process of taking a compiled (machine code) program and reverse engineering it to understand its functionality and possibly find the hidden flag. Some reverse engineering challenges requires the competitor to know Assembly/Machine code regardless of the device’s architecture, and to have a solid understanding of Operating System/Computer Architecture. 

To know more about reverse engineering:

- [LiveOverflow Binary Hacking](https://www.youtube.com/watch?v=iyAyN3GFM7A&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)
- [Introduction to Reverse Engineering Software](http://opensecuritytraining.info/IntroductionToReverseEngineering.html)
- [Modern Binary Exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/)
- [Dennis Yurichev’s Reversing Challenges](https://challenges.re/)

### Forensics challenges:

Computer forensics is the science of recovering a digital clue on a computer. Forensics challenges can include file format analysis, steganography, memory dump analysis, or network packet capture analysis. 

Solving forensics challenges would be easier if one was familiar with the following topics:

- [File Formats](https://en.wikipedia.org/wiki/File_format)
- [EXIF data](https://en.wikipedia.org/wiki/Exif)
- [PCAPs](https://en.wikipedia.org/wiki/Pcap)
- [Wireshark](https://www.wireshark.org/)
- [Stegonagraphy](https://en.wikipedia.org/wiki/Steganography)
- [Disk Imaging](https://en.wikipedia.org/wiki/Disk_image)

### The challenges can be related to the following topics: 

- Recovering deleted files from corrupt disks and extracting data from them, such as temporary e-mail files. 
- Analyzing system files to find evidence of cybercrime, such as checking web browsing records. 
- Extracting evidence hidden in multimedia files or in system and program logs.
- Analysis of multimedia files in optical devices. 
- Analysis of network files and logs to find the attack starting point.

### Programming challenges:

The programming challenges will depend on how to solve security problems by using your programming skills. It can prove your logical thinking skills by either finding logical errors or writing code that can establish a specific task that cannot be accomplished manually.


You can practice by solving challenges at [codeforces](codeforces.com).

### Ad-hoc challenges:
Various challenges that do not depend on specific knowledge and depend mainly on the competitor research skill and solving puzzles.

##### Examples:

- Base 64 challenges
- Hex challenges
- Encoded messages 
- Puzzles
- Ancient languages

## Resources to get started in CTF:

- [Trail of Bits CTF Guide](https://trailofbits.github.io/ctf/): – one of the best guides for newbies
- [Practice CTF List / Permanent CTF List](https://captf.com/practice-ctf/): – a good collection and resource of CTFs that are long-running
- [Awesome CTF](https://github.com/apsdehal/awesome-ctf): – a curated list of Capture The Flag (CTF) frameworks, libraries, resources and software
- [Vulnhub](https://www.vulnhub.com/): – vulnerable machines you can practice or for your pentest laboratory
- [CTF Resources](http://ctfs.github.io/resources/): – a repository and an archive of general topics for CTF and is somehow the same with Trail of Bits CTF Guide
- [Reddit’s securityCTF](https://www.reddit.com/r/securityCTF/): – /r/securityCTF
- [Forensics Wiki](http://forensicswiki.org/wiki/Main_Page): – a wiki designed for computer forensics


## Useful CTF tools

|   Crypto  |   Web     |Networking |   RE         |   Stegano	|Forensics|
|---	      |---	      |---	      |---	            |---	      |---	    |
| FeatherDuster | BurpSuite | Wireshark |   GDB          |   OpenStego | Aircrack-Ng  |
| Hash Extender | Commix    | tshark   |   IDA Pro      |  OutGuess |CFF Explorer |
| PkCrack | Hackbar   |  OpenVPN |Immunity Debugger|  Steghide  |Creddump |
| RSACTFTool | OWASP ZAP | OpenSSL | OllyDbg      | StegFS |Exif Tool|
| Hashpump | Postman   | Tcpdump |  Radare2	| Pngcheck|Extundelete |
| XORTool | SQLMap    |  Netcat | Nm        |  Gimp | Foremost |
| Sage | W3af      |  telnet |  Objdump	| Audacity	| Volatility |
| Cryptool | XSSer   	|  nmap     | Strace  	| MP3Stego	|Wireshark|
| John the Ripper |  DVNA	|    Nikto  	| JD-GUI 	|  Ffmpeg | Audacity|


## Knowing your favorite type of challenges:

As you pick up new skills during CTF competitions, you’ll likely find out which type of challenges you’re strong with and which category you enjoy the most. Once you have found your favorite type of problems to solve, start to dig deeper into the subject and specialize in it. It’s absolutely recommended to go deep into one subject and become really good at it than to waste your time learning about everything and never become proficient.

## Hacking lab setup:

## Virtual Machines
Virtual Machines (VMs) allow you to run multiple computers within your physical computer. This is
useful during a CTF as it allows you to easily run Kali Linux on your existing computer, giving you
many of the tools that may be useful during the CTF. 

### How to install

The following instructions apply to Microsoft Windows. A similar process exists for Mac, using a
VMWare Fusion trial rather than VMware Player.

1. Download VMware Workstation Player from https://www.vmware.com/au/products/workstation-player/workstation-playerevaluation.html.
2. Once downloaded, install VMware Workstation Player on your computer.
3. VMware Workstation Player is free to use for personal use, no software license is required.

## Kali Linux

### What is it?
Kali Linux is an operating system designed for security enthusiasts and professionals. It is developed by Offensive Security. This distro of Linux has many tools that can be used in different security tasks like penetration testing, vulnerability research, computer forensics, and reverse engineering. Kali Linux also comes with most of the tools mentioned above so if you have Kali Linux, you will be almost ready for the competitions.

### How to install:

1. Browse to https://www.kali.org/downloads/.
2. Locate the Kali Linux VMware Images section and choose either the 32-bit or 64-bit and wait for it to download. If you only have 2-4 GB of RAM it's better to install the 32-bit version, and if you have more than 4 GB of RAM available the 64-bit version will be more suitable.
3. The downloaded file is a 7-zip file, you will need to install that from https://www.7-zip.org/download.html.
4. Once the file is downloaded, extract the 7-zip file. There should now be a folder called KaliLinux-2020.1-vm-amd64 or something similar.
5. Launch VMware Workstation Player and choose ```Player, File, Open.``` Locate the Kali Linux VMX file and click Open.
6. Press Power on this virtual machine. A message may pop up click “I copied it”.
7. The below boot screen should appear, simply waiting a few seconds will allow Kali Linux to
boot.
8. After it loads you will be asked for a username and password, the default username is ‘kali’,
and the password is ‘kali’ as well.
9. Because the default Kali password is public, the first thing you want to do after logging in is to change your password. Open the terminal and type in ‘passwd’. You will then be prompted to create a new one. Ensure you enter a unique and complex password.
10. You're all ready! Happy hacking!

## Frequently asked questions (FAQ)

### Many competitors will be skilled and better than me and I’m most likely far from winning a CTF competition now. I have to be professional and skilled to participate, so I will take professional certifications and courses first. Am I right?

False. You don’t have to be skilled nor professional to participate in a CTF competition. Of course taking courses will help you achieve better results but the goal of doing CTF competitions is to simply learn and pick up new skills while you go. The CTF winners will most likely be a group of people who participated in hundreds of CTF challenges before they won their first competition. So be brave!

### Who can join a CTF competition?

CTF should be open for everyone, not just for those who can compete for the first rankings. That being said, getting started on your own will be quite challenging but you can always join a team that can introduce you to the basics of CTFs and learn from them. If there is no one, you can find like-minded individuals inside your community to establish one and learn together!

### What skills should we have to participate in our first CTF?

It will be helpful to have a decent understanding of the administration of Linux/Windows, networking, and web fundamentals.

### How can I solve challenges during the competition if I have no experience? 

Become a Google search expert! To prepare and compete in a CTF competition, you will need to find and read a lot of write-ups. You can find results of past CTF events with various solutions, and you will always find different solutions to the same problems. Try to incorporate some of those techniques into your bag. 

-----------------------------------

I wrote this in one go so it might have some mistakes. I've tried to structure it so you can learn from it, but if you have questions along the way, contact [me](https://twitter.com/majdcs). 

Happy hacking and good luck! :D
