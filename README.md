<h1>File Integrity Monitor - PCI DSS</h1>

<b>This project aims to provide a clearer intuition of the concept of integrity in cybersecurity. To achieve this goal, we will create a simple File Integrity Monitor (FIM) using PowerShell. FIM is an application that monitors crucial files and can trigger alerts when changes occur. In cybersecurity frameworks like PCI DSS (Payment Card Industry Data Security Standard), FIM is referenced in several controls. Through this project we will build a PowerShell-based FIM, conduct a hands-on demo, and explore how it enhances our comprehension of integrity in the cybersecurity landscape.
</b>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/Zhxegxi.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h4>Technologies Used:</h4>

- <b>PowerShell:</b> Facilitates automation and task execution for efficient scripting in the File Integrity Monitor (FIM) project.
- <b>Hashing Algorithms (SHA-512):</b> Generates unique fingerprints (hashes) to verify file integrity within the FIM system.
- <b>Automation:</b> Enhances efficiency and reliability by automating file hash collection and monitoring processes in the FIM project.

<h2>Description</h2>
Follow this step-by-step process to build a File Integrity Monitor (FIM) using PowerShell. The FIM will serve as a practical demonstration to deepen your understanding of data integrity in the cybersecurity domain.
<br />
<br />
<b>1. Collect Baseline or Begin Monitoring:</b> The script will prompt the user to choose between collecting a new baseline or monitoring files with an existing baseline.If the user selects to collect a new baseline, the script will gather hashes for all monitored files and store them in a baseline text file.
<br />
<br />
<b>2. File Hashing:</b> File hashing involves creating a digital thumbprint (hash) for each file.
The baseline.txt file will contain file names along with their corresponding hashes.
<br />
<br />
<b>3. Monitoring with Baseline:</b> If the user chooses to begin monitoring with a saved baseline, the script loads baseline hash files into a dictionary.
Continuously, the script checks each file's hash against the baseline. Any changes trigger an alert.
<br />
<br />
<b>4. Alert Notification:</b> If a file's hash differs from the baseline, the script notifies the user or administrator about the file change.

<br />
<br />
<b>7. Conclusion:</b> Now that we have an overview, follow the step-by-step process to set up the File Integrity Monitor and deepen your understanding of integrity in the realm of cybersecurity. Happy coding!
<br />
<br />

<h2 align="center">Ensuring File Integrity: Alerting Against Changes and Deletions</h2>

<p align="center">
<img src="https://i.imgur.com/bEjWmmY.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
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
