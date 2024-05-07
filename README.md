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

![image](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/6b68b987-340f-4cc5-a7d9-a52e5d11186e)

 It displays the following menu and select 2 for Website Attack Vectors:

![Screenshot 2024-04-30 093349](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/1ec7df8c-158b-4e75-967d-c5eab5a0b25b)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2024-04-30 093800](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/80423d70-3a2f-44d7-9473-6ffaa1a1a56a)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![Screenshot 2024-04-30 093810](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/61404410-3402-4b5d-8515-41dd2d639ad7)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2024-04-30 093830](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/103d83ae-d605-4de8-aea1-18bc9653bc39)

It shows the following screen in which the option Google can be selected:

![Screenshot 2024-04-30 093843](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/04a00f38-e295-40ba-8fc6-f4a135b6be8e)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-04-30 093138](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/4b57e1d4-94ae-4b0b-b888-a7e99b007487)

In windows IE, on giving the url http://192.168.43.135, the fake Google page is displayed. The victim can enter the username and password:

![Screenshot 2024-04-30 092624](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/b287ebed-96d7-4fad-91c3-a1e16d461280)

SET logs the information regarding the Google credentials:

![Screenshot 2024-04-30 093138](https://github.com/Vanitha-SM/creating-a-backdoor-with-SET/assets/119557985/22fcbe4a-2686-4428-a78a-3dc4ea3437d9)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
