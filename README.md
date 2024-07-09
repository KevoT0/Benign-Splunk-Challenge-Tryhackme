# Tryhackme: SOC Level 1
# Benign-Splunk-Challenge-Tryhackme

<H2>Description</H2>
This is a hands-on SIEM challenge provided by Tryhackme. Using Splunk a commonly used SIEM to find solution to the compromised host.
<br/>

<h2>Unilities Used</h2>
<b>Splunk Enterprise</b>

<h2>Enviroments Used</h2>
<b>Tryhackme Virtual Machine</b>

<h2>Walkthrough</h2>
<h3><b>QUESTION AND STEPS TAKEN TO ANSWER</h3>
<img src="https://i.imgur.com/feEKOcs.png" height="80%" width="80%" alt="Benign"/>

<img src="https://i.imgur.com/RDbuMxE.png" height="80%" width="80%" alt="Benign"/>

<h3>Here are the steps taking to solve the challenges</h3>

Q1. How many logs are ingested from the month of March, 2022?

To get this answer I selected a time range fro the month of march 2022.

<img src="https://i.imgur.com/z2s007q.png" height="80%" width="80%" alt="Benign"/>

Answer

<img src="https://i.imgur.com/D1pDfgz.png" height="80%" width="80%" alt="Benign"/>

Q2. Imposter Alert: There seems to be an imposter account observed in the logs, what is the name of that user?

<img src="https://i.imgur.com/40ZtrR2.png" height="80%" width="80%" alt="Benign"/>

Answer

<img src="https://i.imgur.com/2XGGsbQ.png" height="80%" width="80%" alt="Benign"/>

Q3. Which user from the HR department was observed to be running scheduled tasks?

<img src="https://i.imgur.com/O4jSIcB.png" height="80%" width="80%" alt="Benign"/>

Answer

<img src="https://i.imgur.com/eBHmdv6.png" height="80%" width="80%" alt="Benign"/>

Q4. Which user from the HR department executed a system process (LOLBIN) to download a payload from a file-sharing host.

<img src="https://i.imgur.com/Gj0lPTU.png" height="80%" width="80%" alt="Benign"/>

Using the splunk Query to find the user

<img src="https://i.imgur.com/KejDpE4.png" height="80%" width="80%" alt="Benign"/>

Q5. To bypass the security controls, which system process (lolbin) was used to download a payload from the internet?

<img src="https://i.imgur.com/iLjFlAX.png" height="80%" width="80%" alt="Benign"/>

Q6. What was the date that this binary was executed by the infected host? format (YYYY-MM-DD)

<img src="https://i.imgur.com/xqY9ksD.png" height="80%" width="80%" alt="Benign"/>

Q7. Which third-party site was accessed to download the malicious payload?

<img src="https://i.imgur.com/VUIQ6ju.png" height="80%" width="80%" alt="Benign"/>

Q8. What is the name of the file that was saved on the host machine from the C2 server during the post-exploitation phase?

<img src="https://i.imgur.com/1fVbl6w.png" height="80%" width="80%" alt="Benign"/>

Q9. The suspicious file downloaded from the C2 server contained malicious content with the pattern THM{..........}; what is that pattern?

<img src="https://i.imgur.com/1fVbl6w.png" height="80%" width="80%" alt="Benign"/>

Q10. What is the URL that the infected host connected to?

<img src="https://i.imgur.com/BjjGe4p.png" height="80%" width="80%" alt="Benign"/>
