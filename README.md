# Linux_WriteUp
## OverTheWire Bandit - Write-Up: My journey through levels 0 to 17

### Introduction:
Starting with wargames, especially OverTheWire: Bandit, has been an eye-opening experience that allowed me to better understand how Linux works behind the graphical interface. The first few levels felt familiar, as remembering commands like `cat`, `ls`, `-ls, -la`, `cd`, and `pwd` was a practical review of basic concepts. However, as I progressed through the levels, I encountered unfamiliar tools that forced me to research independently, using resources like the Internet and the `man` command directly from OverTheWire servers. This is how I incorporated commands such as `sort`, `strings`, `base64`, among others, expanding my technical repertoire.

### My biggest challenge: Level 13:
A level that represented a significant difficulty for me was level 13, not because of the complexity of a particular command, but because it introduced a completely new concept: the use of SSH keys for authentication. Until that moment, the dynamic consisted of searching for passwords stored in files; however, this level required "moving" to a new destination using a private key file, which meant understanding how `ssh` and key-based authentication work instead of passwords.

### Exploring ports and connections: Levels 14 to 17:
From this point on, the following levels up to 17 transformed my analytical approach. I learned to interact with ports using tools like `nc` and `openssl`, and to discover hidden services with `nmap`. Understanding how to send and receive information through specific ports, as well as identifying services running on a host, gave me a new perspective on how networks operate and the importance of port analysis in CTF environments.

### Final reflection:
Although my progress wasn't complete due to the time available for this application phase, I believe that what I learned up to level 17 has laid a solid foundation for what lies ahead. My goal is to finish all Bandit levels and continue with the next challenges that the world of CTFs has to offer. This experience has shown me that curiosity and perseverance are just as important as technical knowledge.
