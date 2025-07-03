# Phishing Email Analysis

1. Malware, short for malicious software, refers to any software intentionally designed to cause damage to a computer, server, client, or computer network. Malware can take various forms, including viruses, worms, Trojans, ransomware, spyware, and adware.

2. It can be distributed through various means such as email attachments, infected websites, or through removable media like USB drives. Once installed on a system, malware can steal sensitive information, disrupt operations, or grant unauthorized access to the attacker.

## Phishing Email
1. Phishing is a type of social engineering attack where attackers impersonate legitimate entities, such as banks, companies, or government agencies, to trick recipients into revealing sensitive information, such as usernames, passwords, credit card numbers, or other personal information.

2. Phishing emails often contain urgent messages, alarming statements, or enticing offers to prompt recipients to click on malicious links or download infected attachments. These emails can be highly convincing, often using logos, email templates, and language that mimic those of legitimate organizations. Phishing emails are a common method for distributing malware or gaining unauthorized access to sensitive information.

## Requirements
## Hardware

- Laptop / Computer
- 8 or 8+ GB of Ram
- 100 GB Storage
## Software

- Virtual Box
- Windows 10 install in it
- Sandbox Environment
- One Malware .exe File
- Little bit of Knowledge about Technology

# Introduction

- I downloaded a malware sample to analyze it, and then attempted to send it to another email address using phishing content. This analysis will help me determine whether the email is malicious or genuine, enabling me to better protect people and companies from being hacked.

# What Next

- Now I will show you a live demo of what you can do when you receive an email.
- I will demonstrate how to analyze the mail and check the mail’s IP address.
- Additionally, I’ll show you how to check for documentation and any attached files.
- Let’s get started.

# Practical Demo

- First Download the Virtual Box
- Install the Windows 10 OS in it
- Give it a Decent amount of specification
- Mine is Here
![1](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/1.webp)

- You can give it by our need
- I Suggest you for giving 4Gb+ Ram and 50Gb Storage for better performance

## Creating a Sandbox Environment

- I have made a article on how you can create a sandbox environment- Check it out
- Make sure to take a snapshot in virtual box so if any think happen so you can restore the windows and you will save more time.

## Downloading Malware

- If you want to download a malware so you can check of the git hub repository
- I have downloaded malware from here
![2](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/2.webp)
## Send Email

- If we want to send email so we can send it from our mail box
- But the malicious mail is not send by mail it is send by some different kind of mailbox which contain some additional option for sending mail
- We can hide our email address from it and also hide sender information
- We can add Phishing link to it.

## Sending Malicious Email To Next Person

- Here I have send a malicious email containing subject line
- Subject as Hey You Have Win a Lucky Draw
- Given a Task to Chatgpt to write a content for Email on the topic
![3](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/3.webp)
- Copied email format from chatgpt and paste it on the email sender box.
![4](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/4.webp)
![5](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/5.webp)
- Attached Malware File to it by changing its name to Lucky_Draw_Game
- So user will think that it is a game app but it is a malware

**NOTE : The Mail is not been sent properly scanner has scan malware file and it disable to download the file and so we cannot download the file but we can test it manually**

# Email Analysis

- We can check for the email by just checking for its header
- Lets take an example for WordPress email
![6](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/6.webp)
- First step is to check for the content read it carefully and notice it there are some mistakes
- Note that it contain some attachment with it if yes so don’t open it.
- Check for the Header by clicking on 3 dots
![7](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/7.webp)
- Click on Show Original
![8](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/8.webp)
- Here is a bunch of information about email
![9](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/9.webp)
## IP

- It shows his IP address
![10](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/10.webp)
- Here is information we get from the ip
![11](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/11.webp)
- We get to know that the ip is genuine and comes from original source

## Domain

- Lets Check for the domain name register
![12](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/12.webp)
- Here is the domain of wordpress
- Lets check for more information
![13](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/13.webp)
![14](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/14.webp)
- They have hide much of the information so we are not able to get more information
- So here we have done the basic level of email analysis

# IP & Domain Analysis Websites

- Here are some of the websites where you can do analysis

WHOIS Lookup:
![15](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/15.webp)
- MXToolbox offers a variety of tools for analyzing domains and IP addresses, including DNS lookup, blacklist check, and email header analysis.

**MXToolbox**:
![16](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/16.webp)

- MXToolbox offers a variety of tools for analyzing domains and IP addresses, including DNS lookup, blacklist check, and email header analysis.

**IPVoid**:
![17](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/17.webp)
- IPVoid provides tools for IP and domain analysis, including blacklist check, IP geolocation, and reverse DNS lookup.

**Shodan**:
![18](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/18.webp)

- Shodan is a search engine that lets you find specific types of computers (routers, servers, etc.) connected to the internet using a variety of filters. It’s particularly useful for analyzing devices connected to the internet by their IP addresses.

# Malware Analysis

**VirusTotal:**
![19](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/19.webp)
- VirusTotal is a free online service that analyzes files and URLs for viruses, worms, trojans, and other kinds of malicious content. It aggregates multiple antivirus engines and scan results from various sources to provide comprehensive insights into the potential threats of a file or URL.

**Hybrid Analysis:**
![20](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/20.webp)
- Hybrid Analysis is a dynamic malware analysis service that allows users to submit files and URLs for analysis. It provides detailed reports on the behavior of malware samples in a controlled environment, including information on network activity, file modifications, and system impact.

**Any.Run:**
![21](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/21.webp)
- Any.Run is an interactive malware analysis platform that allows users to execute and observe the behavior of malware samples in real-time. It provides a sandboxed environment where users can interact with malware and monitor its activities, including network connections, file operations, and registry changes.

**Joe Sandbox:**
![22](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/22.webp)
- Joe Sandbox is an automated malware analysis platform that provides in-depth reports on the behavior and characteristics of malware samples. It uses advanced techniques such as code emulation, dynamic instrumentation, and memory analysis to uncover the capabilities and intentions of malicious code.

# Practical Malware Analysis

- Lets Take one Malware and Analysis it with the help of VirusTotal
- I have one malware and lets check it
- Here is Malware

![23](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/23.webp)
- Annabelle.exe

## Lets Check

- Lets Check it by uploading it on VirusTotal
![24](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/24.webp)
![25](https://raw.githubusercontent.com/prakharsec/Phishing-Email-Analysis/main/Phishing%20email%20analysis/25.webp)
