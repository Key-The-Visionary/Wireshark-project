# Wireshark Project

## Objective

- Understand and learn the basics of networking and common networking protocols.
- View packets in Wireshark.
- Filter traffic in Wireshark using various criteria.
- Analyze packets collected by the pfSense firewall using TCPDump.
- Completed lab exercises to deepen understanding of the concepts discussed

### Skills Learned

- Ability to naviagte and configure pfsense firewall
- Proficiency in analyzing and interpreting network traffic.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- pfsense firewall
- tcpdump tool

## Steps

This Project incorporated 2 lab exercises that included using the Wireshark tool to analyze packets from an ARP spoofing attack. The first lab I will login to pfSense through the web interface and explore its features. The second lab I will use Wireshark to analyze packets from an ARP spoofing attack. 

-------------------------------------------------------------------------------------------------------------------------------------------------
**Lab 1 Exercise-Pfsense Familiarity**

--------------------------------------------------------------------------------------------------------------------------------------------------
Step 1: In the Kali Linux browser, log in to pfSense by entering the router’s IP address into the URL bar. You will see a security warning saying that the security certificate is not valid. Select the option to add an exception. The pfSense firewall uses a self-signed certificate.
Next, it Prompted me to change password which I did.


![Screenshot 2024-11-22 172912](https://github.com/user-attachments/assets/5922a99d-329e-46ee-b39c-c81e76027562)

-------------------------------------------------------------------------------------------------------------------------------------------------

Password Changed


![Screenshot 2024-12-03 181345](https://github.com/user-attachments/assets/5156456f-6bbc-4b25-a1f4-bc614889263a)

![Screenshot 2024-11-22 173436](https://github.com/user-attachments/assets/0e9c131d-ada5-45dd-a178-34b05ecf8922)

-------------------------------------------------------------------------------------------------------------------------------------------------
The Pfsense dashboard with Traffic graphs and System Information

![Screenshot 2024-11-22 173513](https://github.com/user-attachments/assets/02e2bc01-7c70-4bfe-960a-3c11c287dabc)

-------------------------------------------------------------------------------------------------------------------------------------------------
**Excercise 2- Exploring packets in a arp spoofing attack using wireshark**

Download the Wireshark capture of our ARP spoofing attack (arpspoof.pcap) provided with this assignment. Open the file in Wireshark and try answering the following questions: 
1. What are the MAC and IP addresses of the victim’s and attacker’s machines? 
2. What is the MAC address of the local network’s router? Hint: the local router’s IP address is 192.168.1.1.


-------------------------------------------------------------------------------------------------------------------------------------------------
The below screenshots show the packets that are being analyzed in this arp spoofing attack. In the screenshots, you can see that I utilized the filter bar to only look for the arp protocol in this particular network capture. Lastly, in the screenshots below you get the answers to the above questions for this excercise. 



![Screenshot 2024-11-22 175101](https://github.com/user-attachments/assets/de2b60cf-c6e6-4b06-b771-071bae406a9d)


![Screenshot 2024-11-22 175232](https://github.com/user-attachments/assets/ad888803-6782-48be-9f20-738870c9c8d2)

-------------------------------------------------------------------------------------------------------------------------------------------------

Conclusion

 In conclusion, The key is that seeing two IP addresses assigned to the same MAC address is an indicator of an ARP spoofing attack. This was another great learning experience for me being able to capture network traffic and use a tool that allows me to see ip addresses, MAC addresses, different protocols, and many more network activity flows. I also learned how to configure a pfsense firewall and utilize it to monitor network traffic.

