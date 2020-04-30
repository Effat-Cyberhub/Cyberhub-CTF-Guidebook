# Cyberhub-CTF-Guidebook

This is an English translation of the important CTF guidebook provided by @SAFCSP's Cyberhub initiative for all university students who are interested in Cybersecurity. There will be more collegiate-level CTFs supported by Cyberhub initiative in the future where you can compete with fellow students and win different prizes. I will also provide some add-ons to the guidebook and asnwer some of the most frequent asked questions and correct the false conceptions that most students tend to say and ask about before participating in a CTF competetion for the first time. I hope you find it useful! 

## Content

- About CTF competetions 
- Common types of CTFs competetions
- Types of CTF challenges
- Important resources to get started in CTF
- Knowing your favorite type of challenges
- Hacking lab setup
- Frequently asked questions (FAQ)

## About CTF Competetions 

CTF competetions are a gamified learning experience designed to help contestants gain cybersecurity skills and hack in a safe, rewarding environment. The contestants could form or join a team in order to apply and improve their gained skills and by capturing the flag, they can confirm their solution to the challenge.

#### The Flag Format

Flags are usually hidden in various locations, they might be placed in a file, a database, or stuck into a source code; but there are so many other ways and different places of where you can hide and find a flag. Your goal as a contestant would be to hunt them all down. The flag can be a phrase with a text that appears in a specific format to the contestant after solving a challenge. Below are examples of some of those flags formats:

- ctf{this_is_a_flag} 
- safcsp{this_is_a_flag}
- cyberhub{this_is_a_flag}
- You_successfully_got_the_flag

After capturing the flag, the contestant should submit it, and if it was correct; the contestants will get rewarded by points that confirms their achievement.

## Common types of CTFs competetions

#### Jeopardy-style CTFs 

It's usually a combination of computer security challenges that comes in a different range of categories, and each cantegory will have several challenges. For example, you may have forensics, web, reverse engineering, and exploitation categories. The difficulty will range from one challenge to another and each particular challenge will have a score representing its difficulty. 


#### Attack-defence 

In this type of competetion, contestants should protect their own servers for defence points and hack opponents for attack points, and it's usually a simulation of a real environment that contains multiple servers in which competitors can compete to enhance their blueteaming and redteaming skills. 


#### Mixed 

A mixture of challenges spread over the previous two types.


## Types of CTF challenges

#### Cryptography challenges:

Cryptography can be defined as the science of protecting information by transforming it into a secure format which can be accessable by those who owns the decryption key. Cryptography is the reason we can protect our privacy. However, CTF cryptography challenges is used to raise awareness of encryption schemes that are improperly implemented and can put our privacy at risk. 

To learn more about Cryptography, you can check this [resource](https://my.eng.utah.edu/~nmcdonal/Tutorials/EncryptionResearchReview.pdf).

#### Web hacking challenges:

This category is based on exploiting web vulnerabilities to find the hidden flag. It usually covers any sort of web-based vulnerabilities and exploits. 

##### Common vulnerabilities to see in CTF challenges:

- [SQL Injection](https://portswigger.net/web-security/sql-injection)
- [Command Injection](https://portswigger.net/web-security/os-command-injection)
- [Directory Traversal](https://portswigger.net/web-security/file-path-traversal)
- [Cross Site Request Forgery](https://portswigger.net/web-security/csrf)
- [Cross Site Scripting](https://portswigger.net/web-security/cross-site-scripting)
- [Server Side Request Forgery](https://portswigger.net/web-security/ssrf)

To learn more about web vulnerabilities, you can check this [resource](https://portswigger.net/web-security/all-materials).

#### Reverse Engineering Challenges:

Reverse engineering (RE) is the process of taking a compiled (machine code) program and reverse engineering it to understand its functionality and possibely find the hidden flag. Some reverse engineering challenges requires the competitor to know Assembly/Machine code regardless of the device’s architecture, and to have a solid understanding of Operating System/Computer Architecture. 

To know more about reverse engineering:

- [LiveOverflow Binary Hacking](https://www.youtube.com/watch?v=iyAyN3GFM7A&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)
- [Introduction to Reverse Engineering Software](http://opensecuritytraining.info/IntroductionToReverseEngineering.html)
- [Modern Binary Exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/)
- [Dennis Yurichev’s Reversing Challenges](https://challenges.re/)

#### Forensics challenges:

Computer forensics is the science of recovering a digital clue on a computer. Forensics challenges can include file format analysis, steganography, memory dump analysis, or network packet capture analysis. 

Solving forensics challenges would be easier if one was familair with the following topics:

- [File Formats](https://en.wikipedia.org/wiki/File_format)
- [EXIF data](https://en.wikipedia.org/wiki/Exif)
- [PCAPs](https://en.wikipedia.org/wiki/Pcap)
- [Wireshark](https://www.wireshark.org/)
- [Stegonagraphy](https://en.wikipedia.org/wiki/Steganography)
- [Disk Imaging](https://en.wikipedia.org/wiki/Disk_image)

##### The challenges can be related to the following topics: 

- Recovering deleted files from corrupt disks and extracting data from them, such as temporary e-mail files. 
- Analyzing system files to find evidence of cybercrime, such as checking web browsing records. 
- Extracting evidence hidden in multimedia files or in system and program logs.
- Analysis of multimedia files in optical devices. 
- Analysis of network files and logs to find the attack starting point.

#### Programming challenges:

The programming challenges will depend on how to solve security problems by using your programming skills. It can prove your logical thinking skills by either finding logical errors or writing code that can establish a specefic task that cannot be accomplished manually.


You can practice by solving challenges at [codeforces](codeforces.com).

#### Ad-hoc challenges:
Various challenges that do not depend on a specific knowledge and depend mainly on the compitetor research skill and solving puzzles.

##### Examples:

- Base 64 challenges
- Hex challenges
- Encoded messages 
- Puzzles
- Ancient languages

## Resources to get started in CTF:

[Trail of Bits CTF Guide](https://trailofbits.github.io/ctf/): – one of the best guides for newbies
[Practice CTF List / Permanent CTF List](https://captf.com/practice-ctf/): – a good collection and resource of CTFs that are long-running
[Awesome CTF](https://github.com/apsdehal/awesome-ctf): – a curated list of Capture The Flag (CTF) frameworks, libraries, resources and software
[Vulnhub](https://www.vulnhub.com/): – vulnerable machines you can practice or for your pentest laboratory
[CTF Resources](http://ctfs.github.io/resources/): – a repository and an archive of general topics for CTF and is somehow the same with Trail of Bits CTF Guide
[Reddit’s securityCTF](https://www.reddit.com/r/securityCTF/): – /r/securityCTF
[Forensics Wiki(http://forensicswiki.org/wiki/Main_Page): – a wiki designed for computer forensics

## Knowing your favorite type:

As you pick up new skills during CTF competetions, you’ll likely find out which type of challenges you’re strong with and which category you enjoy the most. Once you have found your favorite type of problems to solve, start to dig deeper into the subject and specialize in it. It’s absolotely recommended to go deep into one subject and become really good at it than to waste your time learning about everything and never become profecient.


## Hacking lab setup:




