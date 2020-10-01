---
layout: default
title: Tools
parent: Getting Started
nav_order: 2
---

## **Tools**

---

### **GRID Certificate**
You will need a GRID certificate to access many websites and resources within SNO+. The certificate **MUST** be installed in the browser that you will use to view such resources. 

1. **For Canadian users**: Go to [this website](https://cert.gridcanada.ca/cgi-bin/pub/pki?cmd=getStaticPage&name=homePage)
2. Choose **2 - Request a Certificate**, choose **User Request** and enter "snoplusdata.snolab.ca" as the host name
3. **For users from other countries**, please follow the instructions [here](https://snopl.us/docs/rat/grid_manual/html/certificates_and_initial_setup.html)
4. After receiving the response, you can download and import the certificate into the browser you will use (google how to install a certificate in whatever browser you use)
5. Finally, you need to [apply to join the SNO+ virtual organisation (VO)](https://voms.gridpp.ac.uk:8443/voms/snoplus.snolab.ca). **Remember to use the browser with an imported certificate.**

---

### **SSH Key**
**For Linux/macOS**
1. Run `cd ~/.ssh` to navigate to your ssh directory. In case you do not have the directory, you can run `mkdir ~/.ssh`.
2. Run `ssh-keygen`, it will ask you to enter the name and the keyphrase (password for the key file) if you want one.

**For Windows**
1. Follow the directions using PuTTY [here](https://www.ssh.com/ssh/putty/windows/puttygen).

After the generation, you will see two files; one is the `<name>` you entered before, this one is your **private** ssh key; the other is `<name>.pub`. `<name>.pub` contains the public ssh key that you need to make connections. Try `cat <name>.pub` to see your public ssh key.

**NEVER share your PRIVATE SSH key with anyone - remote sites only need to have your public key installed in order for you to connect using your private key**

---

### **VPN**
A VPN is required to access Buffer1 and various other SNO+ resources; please follow the instructions to install it.
1. Go to the [SNOLAB home page](https://www.snolab.ca/), then choose **Internal** to go to the internal site, which requires a snolab account
2. In **IT Services**, choose **Computing Support Page**
3. In **Work Tools** section, select **VPN - Virtual Private Network**
4. Choose the version to install according to your Operating System and follow the rest of the instructions on the page

---

### **Mailing lists**
Once you sign up for a SNOLAB account, you can join various mailing lists. Two of the most important mailing lists are:
* snoplus_vosupport@snolab.ca
* snoplusdata@snolab.ca
  
There are two ways to join the lists:
* Click [here](https://www.snolab.ca/sympa/search_list_request) and search for the mailing list you want to join
* Email sympa@snolab.ca in the following format:
  ```
  subscribe <lists> <First name> <Last name>
  ```