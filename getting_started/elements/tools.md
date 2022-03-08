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

**NOTE** - When requesting a certificate, use **Chrome**, as Firefox has an issue. Once the certificate is ready, use **Firefox** to import it and use for any pages where a certificate is necessary, as Chrome has issues. 

1. **For Canadian users**: Go to [this website](https://cert.gridcanada.ca/cgi-bin/pub/pki?cmd=getStaticPage&name=homePage)
2. Choose **2 - Request a Certificate**, choose **User Request** and enter your home instititution name and email. note you must use your instituational email. (MAKE NOTE OF THE PIN USED)
3. **For users from other countries**, please follow the instructions [here](https://snopl.us/docs/rat/grid_manual/html/certificates_and_initial_setup.html).
4. After receiving the response, folloy the instructions carfuly to download and import the certificate into Firefox. While downloading the certificate the page will ask for a password associated with your key - input the **PIN** that was created in step 2. you need a .p12 file not a .pem file.
5. Finally, you need to [apply to join the SNO+ virtual organisation (VO)](https://voms.gridpp.ac.uk:8443/voms/snoplus.snolab.ca). **Remember to use Firefox with an imported certificate.** 

---

### **SSH Key**
**For Linux/macOS/GitBash**
1. Run `cd ~/.ssh` to navigate to your ssh directory. In case you do not have the directory, you can run `mkdir ~/.ssh`.
2. Run `ssh-keygen`, it will ask you to enter the name and the keyphrase (password for the key file) if you want one.

**For Windows**
1. Follow the directions using PuTTY [here](https://www.ssh.com/ssh/putty/windows/puttygen).

After the generation, you will see two files; one is the `<name>` you entered before, this one is your **private** ssh key; the other is `<name>.pub`. `<name>.pub` contains the public ssh key that you need to make connections. Try `cat <name>.pub` to see your public ssh key.

**NEVER share your PRIVATE SSH key with anyone - remote sites only need to have your public key installed in order for you to connect using your private key**

---

### **VPN**
A VPN is required to access Buffer1 and various other SNO+ resources; please follow the instructions to install it.
1. Go to [this link](https://www.snolab.ca/docushare/dsweb/HomePage) which is the internal site for SNOLAB
2. In **IT Services**, choose **Computing Support Page**
3. In **Work Tools** section, select **VPN - Virtual Private Network** (a direct link to the VPN page can be found [here](https://snolab.sharepoint.com/sites/ITSupport/SitePages/Access-to-VPNs.aspx))
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
