# Website-Cloning for Phishing-Awareness
This project focusses on website cloning and phishing attacks which involves using a tool to clone a website that requires a username and password where the cloned website will be used to capture the victim's login credentials. This can be achieved by creating a fake login page that looks identical to the original website and prompting the victim to enter their login information. Once the victim enters their credentials, the attacker tool will record the information for later use. It is important to note that such activities should only be carried out for ethical purposes and with proper authorization. The second question involves creating a phishing email to lure the victim into filling out a form with four fields of the attacker's interest. This can be achieved by creating a convincing email that appears to come from a legitimate source, such as a bank or social media platform. The email will contain a link that leads to a fake website designed to look like the legitimate site, where the victim will be prompted to enter their personal information. The attacker can then collect this information and use it for nefarious purposes. It is important to note that phishing attacks are illegal and can result in severe legal consequences.
## Website Cloning: 
Website cloning is the process of creating a copy of an existing website with the intention of making it appear identical to the original website. This can be done for various reasons, including stealing sensitive information, phishing, or creating fake websites to scam people.
To clone a website, a hacker or attacker typically uses software tools or scripts to copy the entire website's contents, including HTML, CSS, JavaScript, images, and other files. They may also use social engineering techniques to trick users into visiting the cloned website, such as sending phishing emails or using similar domain names and URLs.
Once a user visits the cloned website, the attacker can steal their login credentials, personal information, or install malware on their computer. This can lead to serious consequences, such as identity theft, financial fraud, or loss of data.
To protect against website cloning, it is important to use secure passwords, enable two-factor authentication, and always verify the authenticity of a website before entering any sensitive information. Website owners can also take measures to protect their website, such as using SSL encryption, monitoring their website for unauthorized access, and regularly backing up their website's data.

In this project the tool Used is Kali Linux and the website that is cloned is xyz. The implementation is directed in the following steps.

## Kali Linux: 
Kali Linux is a Debian-based Linux distribution designed for digital forensics, penetration testing, and security auditing. It is maintained and funded by Offensive Security, a cybersecurity training company.
Kali Linux comes with a wide range of pre-installed tools for various tasks related to cybersecurity, such as scanning networks for vulnerabilities, cracking passwords, analyzing malware, and conducting social engineering attacks. The tools included in Kali Linux are organized into categories such as information gathering, vulnerability analysis, wireless attacks, web applications, and exploitation tools.
Kali Linux works like any other Linux distribution, with the added benefit of pre-installed cybersecurity tools. It can be installed on a computer or run as a live system from a USB drive. Kali Linux can also be used in virtual environments such as VMware or VirtualBox.
Some of the common uses of Kali Linux include:

1.Penetration Testing: Penetration testing involves simulating a cyberattack to identify vulnerabilities in a system or network. Kali Linux provides a wide range of tools to perform penetration testing on various systems and networks.

2.Digital Forensics: Kali Linux can be used to collect and analyze digital evidence from a computer or network. It includes tools for disk imaging, data recovery, and memory analysis.

3.Network Security: Kali Linux can be used to test the security of a network by scanning for vulnerabilities, identifying unauthorized devices, and testing the strength of passwords and encryption.

4.Malware Analysis: Kali Linux includes tools for analyzing malware, such as disassemblers, debuggers, and sandboxing tools.

## Implementation: 

Step 1: Login to Kali Linux 

<img width="469" height="240" alt="image" src="https://github.com/user-attachments/assets/dd3d8ca0-91e8-4047-a2e7-537cfd1e697b" />

Step 2 : Click on the terminal and go to home directory.

<img width="360" height="168" alt="image" src="https://github.com/user-attachments/assets/35727995-ff43-461e-a8cd-a6257078ef17" />


Step 3: Enter setoolkit and it takes to verification. Enter the username and password for Kali.

<img width="360" height="165" alt="image" src="https://github.com/user-attachments/assets/b20a1158-a874-4858-a1d0-c8a6727cf03a" />

Step 4: After the details are given, From the menu choose option 1 to perform website cloning as it falls under Social Engineering attack.

<img width="360" height="154" alt="image" src="https://github.com/user-attachments/assets/816dcb1f-d6ee-40cd-8478-81a96109b08c" />

Step 5: Now choose option 2 Website Attack Vectors which is used to clone a website.

<img width="360" height="160" alt="image" src="https://github.com/user-attachments/assets/94bf1786-8f20-430a-bd2d-dd07d45f0d21" />

Step 6: Select option 3 Credential Harvest Method as it is used to capture the credentials given by the victim.

<img width="360" height="168" alt="image" src="https://github.com/user-attachments/assets/fe911b07-5db1-4288-adf0-9d636bd8e967" />

Step 7: Choose Option 1 Web Template for cloning of the website and once done need to paste the URL of the website that you want to clone.

<img width="360" height="151" alt="image" src="https://github.com/user-attachments/assets/dec0849d-8b76-4731-9997-96e93ec168e4" />


Step 8: : Now go to Firefox browser and enter the ip address as 10.0.x.x in the search bar and once the cloned website opens the victim enters their credentials.

(Have not included the screenshot of the cloned website for security reasons)


Step 9 : Now go to Firefox browser and enter the ip address as 10.0.x.x in the search bar and once the cloned website opens the victim enters their credentials.

(Have not included the screenshot of the cloned website for security reasons)

Step 10: 
Once the credentials are given by the victim on the cloned website, Kali captures the same details as shown below.
<img width="342" height="20" alt="phishing" src="https://github.com/user-attachments/assets/ce1bd45e-4171-45e5-aa62-835510e3a2dd" />

Hence by using Kali Linux as a tool and  as a cloned website an attacker can capture the details of the victim.

## Phishing email : 
Phishing is a type of cyber-attack where a fraudster or attacker creates a fake website or email that appears to be from a legitimate source, such as a bank or a social media website, in order to trick people into providing sensitive information like login credentials, credit card numbers, or other personal information. The purpose of phishing is typically to steal information or money from unsuspecting victims.
A phishing email is a type of email that is designed to look like it comes from a legitimate source but is actually sent by an attacker in order to obtain sensitive information or gain access to a victim's computer system. These emails often contain links or attachments that, when clicked on, direct the user to a fake website or install malware on their computer.
Phishing emails can be very convincing and may use techniques such as urgency, fear, or incentives to entice victims to click on links or provide personal information. It's important to be cautious when receiving emails from unknown sources or from sources that appear suspicious, and to always verify the legitimacy of the source before providing any sensitive information.

In this project, Using Kali Linux and Social Engineering Toolkit performed the attack by sending phishing email to the victim and requested to fill out the details. The implementation is as follows.

SET (Social Engineering Toolkit) is a tool that can be used for phishing attacks. It is a penetration testing framework that includes various tools and techniques for social engineering attacks, including phishing. It can be used by security professionals to test the security of their organization's systems and educate employees on the risks of social engineering attacks. However, it can also be misused by individuals with malicious intent to conduct phishing attacks against unsuspecting victims. It is important to use such tools only for ethical purposes and with proper authorization.

## Implementation: 

Step 1:  Deployed a phishing tool in Kali Linux called SeToolkit.

<img width="468" height="240" alt="image" src="https://github.com/user-attachments/assets/a3f547ef-a728-4bb5-8e69-8056bef02cc3" />

Step 2 : From the above menu, option 2 , Website Attack Vectors is chosen. 

<img width="468" height="297" alt="image" src="https://github.com/user-attachments/assets/6ca11f5e-106a-429c-8472-bacd98c9ba82" />

Step 3: Select option 3 Credential Harvester Attack Method as it is used to capture the credentials given by the victim. Moving Site Cloner i.e., option 2 is selected which is helpful to clone a website of your choice.

<img width="468" height="321" alt="image" src="https://github.com/user-attachments/assets/9435a708-a85b-4f65-aee0-1f1e278a8f82" />

Step 4: Now send a customized email to the victim by including the cloned website link for entering credentials such as username and password 

Step 5: Once the victim opens the link, they are directed to enter details.

Step 6: After the information entered by victim, Kali Linux makes it easier to capture the details.


By the above-mentioned procedure, a phishing attack can be performed by sending an email to the victim .












