# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/user-attachments/assets/1beff205-b78b-4bc8-977d-d2161ef917a1)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/c5a80b34-0083-4b03-b6be-4eeb7085d0ab)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/33536563-d629-4b45-a5ed-9e64478811dd)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/ccf416f9-16b7-4a6a-ad41-e7b7b5612f66)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/d6d7f3b5-9d24-4237-bc23-d67e9578db1a)


It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/e78c9174-d255-4ccd-8288-72d839fdae20)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/b7d65028-f82f-4e2c-b973-50c47555eb16)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/97531842-8cf9-4e06-8d9f-f590fd2c67ae)


SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/b5193c3a-8522-4667-8ea5-8a6c0706a7df)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
