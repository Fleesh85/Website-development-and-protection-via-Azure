<h1>JWebsite development and protection via Azure</h1>

https://feliciafernresume.azurewebsites.net/ (Link no longer valid as subscription has expired)

<h2>Description</h2>

I used Microsoft Azure to build and host my own “cyber-blog” web application. I secured it with a SSL certificate, and applied Azure’s security features to protect it. 


<b>Our requirements included:</b>

- Hosting the web application using Azure’s Cloud Services
- Using Azure’s App Service resource to create the web application
- Choosing a domain with “godaddy or Azure” (choose what you selected)
- Deploying a Docker container which had a framework for a blog webpage
- SSHing  into the container to customize the webpage
- Creating a Self-signed certificate with OpenSSL 
- Storing the certificate in Azure’s Key vault
- Binding the certificate to the website (If you didn't select the free option)
- After determining the security issues with a self-signed certificate, creating and bound a managed CA approved certificate to the web application
- Deploying Azure’s Front Door, and configuring a WAF rule to restrict traffic from certain countries
- Analyzing the Azure’s Security Center recommendations and applying the recommend fix
 
<b>This project covered a wide range of topics including:</b> 

- Systems administration
- Networking
- Network security
- Cryptography
- Virtualization
- Cloud deployment
- Web development

<br />


<h2>Technologies Used</h2>

- Azure: {Keyvaults, App Services, Front Door, WAF}
- PHP 
- HTML
- Docker
- OpenSSL


<h2>Environments Used </h2>

- Windows 10 Virtual Machine 
- Azure account

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
