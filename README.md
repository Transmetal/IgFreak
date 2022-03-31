<h1 align="center">IgFreak</h1>


### ABOUT TOOL :

Igfreak is a advance Instagram Slick Hacking framework that can bruteforcer , phish and send  reports to any account 


### AVAILABLE ON :

* Termux
* Kali Linux
* Debain Based

### TESTED ON :

* Termux
* Kali

### REQUIREMENTS :
* Python3
* tor
* php

### FEATURES :
* [+] 99.99% Works!
* [+] tor proxy !
* [+] Advance ip capturing !
* [+] Easy for Beginners !

### INSTALLATION [Termux] :
* Install Dependices
```
  apt-get update -y 
  apt-get upgrade -y 
  pkg install python -y 
  pkg install git -y 
  pip install lolcat 
```
* Clone Project

```
 git clone https://github.com/Transmetal/IgFreak
 ```
 
* Change Project Dir

```
 cd $HOME 
 ls 
 cd IgFreak
 ls 
 python3 igfeak.py --help
```
# Modes

** COMMAND LINE

* Bruteforce 

`python3 igfreak.py --bruteforce -u [username] -pl [passlist]`

* Phishing

`python3 igfreak.py --phish -t [template]`

```
Available Templates

Template      Description

igbadges       : Hack account by confirming account in get verified badges
instagram      : Instagram simple login page
instafollowers : Get Instagram accounts by seeking followers
```
* Account Reporting

`python3 igfreak.py --report -u <victim's account> -am <amount>  -id <report-id>`

These report ids you can use
```
Choose the type of report :
	
[1] - spam
[2] - violence
[3] - Impersonation
[4] - Sexual activity
[5] - harassment
[6] - Self-harm
[7] - Hate on
```

** UI MODE

It had a simple beginner friendly ui

```
python3 ui.py
```
