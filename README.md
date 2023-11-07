# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows:

### Step 3:
Open terminal and try execute some kali linux commands.

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/f06fef0d-7fd3-4b13-ad0a-cd885c8de008)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/25f9f3a0-eb69-4b41-8277-b709ce462fd8)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/89a26615-727e-4e2d-8d58-cb5acc0adb40)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/a458539a-8e97-4fd9-85f1-b2eb965585e6)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/51bda9ab-b7ed-44bd-a345-234dba04223f)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/236e3083-d188-498f-a6e6-7cbd741f251f)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/dcb4465d-6ff3-484c-958a-759d0398e261)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/e7031cd7-dd87-4738-9ec1-bc2afe1113f5)

SET logs the information regarding the Google credentials:
![image](https://github.com/Priya-Loganathan/creating-a-backdoor-with-SET/assets/121166075/1cb07278-445c-4651-9f31-7ce36ed27a4d)

SET logs the information in the xml file under /root/.set directory:

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
