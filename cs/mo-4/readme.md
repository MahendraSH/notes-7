# MODULE 4:( book 150 )

## **table of contents**

- [Tools and methods used in cybercrime](#tools-and-methods-used-in-cybercrime)
- [Proxy servers and anonymizers](#proxy-severs-and-anonymizes)
- [Phishing](#phishing)
- [Password cracking](#password-cracking)
- [ Key loggers and spywares](#keyloggers-and-spywares)
- [Virus and worms](#virus-and-worms)
- [Trojan horses and backdoors](#trojan-horses-and-backdoors)
- [Steganography](#steganalysis)
- [ DoS and DDoS attacks](#dos-and-ddos-attacks)
- [ SQL injection](#sql-injection)
- [ Buffer overflow ](#buffer-overflow)
- [menu](#menu)

---

- # Tools and methods used in cybercrime

  - Stages of an attack on network

  1. initial covering : two stages
     1. Reconnaissance : social networking websities
     2. Uncovers information on company`s IP
  2. Network probe :

     1. ping sweep -seek out potential targets
     2. port scanning

  3. Crossing the line toward electronic crime :
     1. commits computer crime by exploting possible holes on the target system
  4. Capturing the network :
     1. attackers attempts to own the network
     2. uses tools to remove any evidence of the attack
     3. trojan horses , backdoors
  5. Grab the data :
     1. attacker has captured the network
     2. steal confidential data , customer cc information deface webpages ...
  6. Covering the attack :
     1. extend misuse of the attack without being detected
     2. start a fresh reconnaissance to a related traget system
     3. continue use of resources
     4. remove evidence of hacking

---

- # Various tools used for the attack

## **menu**

1.  [Proxy servers and anonymizers](#proxy-severs-and-anonymizes)

    - [Purpose of a proxy server](#purpose-of-a-proxy-server)
    - [An Anonymizer](#an-anonymizer)

---

2.  [Phishing](#phishing)

    - [ how phishing works](#how-phishing-works)

---

3.  [Password cracking](#password-cracking)

    - [the purpose of password caracking](#the-purpose-of-password-caracking)
    - [manual passowrd cracking algorithm](#manual-password-cracking-algorithm)
    - [ Examples of guessable passowrds](#examples-of-guessable-passowrds)
    - [categories of password attacks](#categories-of-password-cracking-attacks)

      - [online attacks](#online-attacks)
      - [offine-attacks](#offine-attacks)

    - [types-of-password-attacks](#types-of-password-attacks)

      - [weak-passwords](#weak-passwords)
      - [strong-passwords](#strong-passwords)
      - [random-passwords](#random-passwords)

---

4.  [ Key loggers and spywares](#keyloggers-and-spywares)

- [keyloggers](#keyloggers)

  - [softare-based-keyloggers](#softare-based-keyloggers)
  - [hardware-keyloggers](#hardware-keyloggers)
  - [acoustic-keylogging](#acoustic-keylogging)

- [antikeylogger](#antikeylogger)

  - [benefits-of-antikeyloggers](#benefits-of-antikeyloggers)

- [spywares](#spywares)

---

5.  [Virus and worms](#virus-and-worms)

    - [what is a virus ?](#what-is-a-virus)
    - [some-typical-virus-actions](#some-typical-virus-actions)
    - [](#virus-spread-through)
    - [](#difference-between-virus-and-worm)
    - [](#types-of-viruses)

      - [](#boot-sector-viruses)
      - [](#program-viruses)
      - [](#multipartite-viruses)
      - [](#stealth-viruses)
      - [](#polymorphic-viruses)
      - [](#macroviruses)
      - [](#active-x-and-java-contrl)

---

6.  [Trojan horses and backdoors](#trojan-horses-and-backdoors)
7.  [Steganography](#steganalysis)
8.  [ DoS and DDoS attacks](#dos-and-ddos-attacks)
9.  [ SQL injection](#sql-injection)
10. [ Buffer overflow ](#buffer-overflow)

---

1. # Proxy severs and Anonymizes

- A **proxy server** is a dedicated computer or a software system running on a computer that acts as an intermediary between an endpoint device such as a computer , and another server from which a user or client is requesting a service

- A client connects to the proxy server, requesting some service such as a file , connection, web page, or other resource available from a different server and the proxy server evaluates the request as a way to simplify and control its complexity.

- ## Purpose of a proxy server
  - improve performace
  - Filer requests
  - keep system behind the curtain
  - used as ip address mutiplexer
  - its cache memory can serve all users

Attack on this : the attacker first connects to a proxy server- establishes connection with the target through existing connection with the proxy.

- ## An Anonymizer

  - An **anonymizer** or an anonymous proxy is a tool that attempts to make acticity on the internet untraceable .

  - it is a proxy server computer that acts as an intermediary and privacy shield between a client computer and the rest of the internet .

  - It accesses the internet on the user`s behalf, protecting personal information by hiding the client computers identifying informaction .
  - For example large news outlets such as CNN target the viewers according to region and give different information to different populations .

[menu](#menu)

---

2. # Phishing
   - stealing personal and financial data
   - also can infect sysmtem with viruses
   - a method of online ID theft

- ## How Phishing works ?

  1. **Planning** : use mass mailing and address collection techniques - spammers

  2. **Setup** : E-mail/ webpage to collect data about the target

  3. **Attack** : send a phony message to the target

  4. **Collection** : record the information obtained

  5. **Identiy theft and fraud** : use inforation to commit fraud or illegal purchases

[menu](#menu)

---

3.  # Password Cracking

- password cracking is the process of recovering passwords from data that have been stored in or trasmitted by a computer system .

- a common approach (brute-force attack ) is to try guesses repeatedly for the password and check them against an available cryptographic hash of the password .

- ## The purpose of password caracking

- help a user recover a forgotten password
- to gain unauthorized access to a system .
  or as a preventive measure by system administrators to check for easily crackable passwords

- ## Manual Password Cracking Algorithm

  - Find a valid user
  - Create a list of possible passwords
  - Rank the passwords from high probability to low
  - key in each password
  - if the system allows you in - success
  - else try till success

- ## Examples of guessable passowrds

  - Blank
  - words like "passcode" , " password" , "admin"
  - series of letters like " QWERTY"
  - Name of the user or user friend / relavtive / pet
  - user birt place or date of birth .
  - vehicle number , office number ...
    . name of a celebrity
    . simple modification of one of the precedings suffxing

- ## Categories of password cracking attacks :

  - online attacks
  - offline attacks
  - Non-electornic attacks
    - socail engineering
    - shoulder surfing
    - Dumpster diving

- ### online attacks

  - an attacker may create a script- automated program -to try each password

  - Most popular online attack :- main in the middle attack or bucket-brigade attack

  - used to obtain passwords for email accounts on public websites like gmail etc

  - also to get passwords for financial websites

- ### offine attacks

  - are performed from a location other than the target where these passwords reside or are used

  - require physical access to the computer and copying the password

- ## Types of password attacks

  - **password guessing** :

    - attackers can guess passwords localy or remotely using either a manual or automated approach

  - **Dictionary attacks** :

    - work on the assumption that most passwords consist of whole words, dates or numbers taken from a dictinary .

  - **Hybrid password** :

    - assume that network adminstrators push users to make their passwords at least slightly different from a word that appears in a dictionary .

- ## weak passwords
  - the password contains less than eight characters
  - the password is a word found in a dictinary (English or forign )
  - the password is a common usage word such as : names of family, pets , friends ,co-workers , fantasy characters , etc .
  - computer terms and names ,commands , sites , companies, hardware , software .
  - birthdays and other personal information such as address and phone numbers .
  - word or number pattern like aaabbb , qwerty , xyzabc , 123321 etc ...
  - any of the above spelled backwards .
  - any of the above preceded or followed by a digt (eg: secret. I secret )
- ## Strong Passwords

  - contain both upper and lower case characters (eg: a-z , A- Z)
  - have digts and puntuation characters as well as letters eg: 0-9 @#/$() {} ....
  - at least 8 characters long .
  - must not be a word in any language
  - passwords should never be witten down or stored on-line
  - try to create paswords that can be easily remembered .
  - one way to do this is create a password based on a song title affirmation , or other phrase.
  - for example , the phrase might be : " This may be one way to rember "
  - and the password could be: "TmB1w2R!" or"Tmb1W>r~" or some other variation .

- ## Random passwords

[menu](#menu)

---

4. # keyloggers and Spywares

- ## keyloggers

  - **keystoke logging** , often referred to as **keylogging** or **keyboard capturing** , is the action of recording (or logging ) the keys struck on a keyboard, trypically in a covert manner so that the person using the keyboard is unaware that their actions are being monitored .
  - it has uses in the study of human- computer interaction .

  - there are numerous keylogging methods ranging from hardware and software-based approaches to acoustic analysis .

- ## softare-based keyloggers

  - **software-based keyloggers** use the target computers os in various ways, including : imitaiting a virtual machine , acting as the keyboard driver (kernel- based ), using the application programming interface to watch keyboard strokes ( API -based), based forms ( Form Grabber based ) or capturing network traffic associated with HTTP POST events to steal passwords (Packet analyzers).

  - usually consists of two files DLL and EXE

- ## Hardware keyloggers

  - installing a hardware circuit between the keybord and the computer that logs keyboard stroke activity (keyboard hardware).

  Target - ATMs

- ## Acoustic keylogging

  - **acoustic keylogging** monitors the sound created by each individual keystroke and uses the subtly different acoustic signature that each key emits to analyze and determine what the target computers user is typing .

- ## AntiKeylogger

  - an **antikeylogger** ( or anti-keystoke logger) is a type of software specifically logger software ; often, such software will also incorporate the ability to delete or at least immobilize keystroke logger software on your computer .

- ### Benefits of antikeyloggers

  - **keylogger removal**

    - it removes keyloggers that are running or being launched in your computer or mobile

  - **Security**

    - it ensures us that confidentiall information would not be stolen from our hard drives or computer units and , prevents us from being a vitim of cyber crimes and thefts .Financial instiutions are usually targets of keyloggers. AntiKeyloggers perform regular scans in any computer.

  - **keylogger detector**

    - Apart from the "disabling" feature , the antikeylogger provides a warnng whenever a keylogging activity is being launched in your unit

  - **protects privacy**

    - as stated in reviews it prvents your data or activities from being revealed through these keyloggers . Your messages , calls , videos , dowloaded files , emails , website vists and other online transactions remain private unless you would reveal them yourself .

  - **user frindly and reliable**

    - The anti-logger is easy to use and high reliable

- ## spywares

  - **Spyware** is software that aims to gather information about a person or orgnaization without their knowledge and that may send such infromation to another enity without the consuers conesent or that assers control over a computer without the consumers knowledge

[menu](#menu)

---

5. # Virus and worms

- ## what is a virus ?
- A computer virus is a **malware** prograrm that when executed repicates by inserting copies of itself (possibly modified) into other computer programs , data files , or the boot sector of the hard drive ; when this replication succeds the affected areas are then said to be "**infected**"

- ## some typical virus actions

  - display a message to prompt an action
  - delete files in the system
  - scramble data on a hard disk
  - cause erratic screen behavior
  - halt the system
  - replicate themselves to propagate further harm

- ## virus spread through

  - The internet
  - a stand alone pc
  - local networks

- ## difference between virus and worm

  |                                         | Computer  virus                                                                                                             | computer worm                                                                                |
  | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
  | how  does it infect a computer system ? | it inserts itself into a file or  executable program                                                                        | it exploits a weakness in application or operating system by replacing itself                |
  | how can it spread?                      | it has to rely on users transfering files/ programs to other computer systems                                               | it can use a network to replicate itself to other computer systems without user intervention |
  | Does it infects files?                  | yes , it deletes or modfies fiels. soemtimes a virus also changes the location of file                                      | usually not worms usually only monopolize the CPU and memory                                 |
  | whose speed is more?                    | virus is slower than worm                                                                                                   | worm is faster than virus . Eg: the code red worm affected 3 lack pcs in just 14hrs          |
  | Definition                              | The virus is the program code that attacks itself to application program and when application program runs it along with it | The worm is code that repicate itself in order to consume resource to bring it down          |

- ## types of viruses
  - boot sector viruses
  - program viruses
  - mutipartite viruses
  - Stealth viruses
  - macro viruses
  - active x and java contrl
- ### boot sector viruses
- ### program viruses
- ### multipartite viruses
- ### stealth viruses
- ### polymorphic viruses
- ### Macroviruses
- ### Active x and java contrl

[menu](#menu)

---

6. # Trojan horses and Backdoors

- ## Examples of threats by trojans

- ## Backdoors

- ## functions of backdoors

- ## Examples of backdoors trojans

- ## how to protect from Trojan Horses and backdoors

[menu](#menu)

---

7. # Steganography

- ## digital water marking

- ## difference between steganography and cryptography

- ## Steganalysis

[menu](#menu)

---

8. # DOS and DDos attacks

- ## symptooms of Dos attacks

- ## A Dos attack may be because of following

- ## Classification of Dos

  - Bandwidth attacks
  - logic attacks
  - potocol attacks
  - Unintentional Dos attack

- ### Bandwidth attacks

- ### logic attacks

- ### potocol attacks

- ### Unintentional Dos attack

- ## types orlevels of Dos attacks
  - Flood attack
  - ping of death attack
  - syn attack
  - Teardrop attack
  - smurf attack
  - nuke
- ### Flood attack

- ### ping of death attack

- ### syn attack

- ### Teardrop attack

- ### smurf attack

- ### nuke

- ## how to prevent dos/ddos attacks

  - **Filtering** :
  - **Moving** :
  - **Blackholling** :

[menu](#menu)

---

9. # sql injection

- ## what an attacker can do in sql injection ?
- ## steps for sql injection attack
- ## blind sql injection
- ## how to prevent sql injection attacks

[menu](#menu)

---

10. # Buffer overflow

- ## example
- ## Types of buffer overflow

  - stack-based buffer overflow
  - heap buffer overflow
  - NOPs

- ### stack-based buffer overflow
- ### heap buffer overflow
- ### NOPs

- ## how to minimize buffer overflow

  - assessment of secure code manually
  - disable stack execution
  - complier tools
  - dynamic run time checks
  - various tools are used to detect / defend buffer overflow
    - stack Gaurd
    - propolice
    - LibSafe

[menu](#menu)

---
