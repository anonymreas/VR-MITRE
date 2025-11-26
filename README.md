<script src="https://s.pageclip.co/v1/pageclip.js" charset="utf-8"></script>
<script>
  var form = document.querySelector('.pageclip-form')
  Pageclip.form(form, {
    onSubmit: function (event) { },
    onResponse: function (error, response) { },
    successTemplate: '<span>Thank you!</span>'
  })
</script>
<style>
form {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  overflow: hidden;
}

label {display: block;}

input[type=text], input[type=email], select, textarea {
  width: 100%;
  padding: 12px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  background-color: #0366d6;
  color: white;
  padding: 14px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=submit]:hover {
  background-color: #45a049;
}
</style>

<h1>Attack Overview on Extended Reality Systems Based on MITRE ATT&CK® Classification Scheme</h1>


<table>
<tr><th>Tactic</th><th>Technique</th><th>Subtechnique</th><th>Attack</th><th>Reference</th></tr>
<tr>
<tr>
<td rowspan='21'>Collection</td><td rowspan='8'> Input Capture</td><td>Keylogging</td><td>side channel 3D Vision Attack</td><td> [1]</td>
</tr>
<tr>
<td>Movement Capture</td><td>Exploitation of Sensor Data</td><td> [6]</td>
</tr>
<tr>
<td>Metaverse Input Capture</td><td>Spyware</td><td> [20]</td>
</tr>
<tr>
<td>Credential API Hooking</td><td>Exploitation of the GamePad API</td><td> [21]</td>
</tr>
<tr>
<td>VR Movement Pattern Analysis</td><td>De-anonymization Attacks Metaverse</td><td> [34]</td>
</tr>
<tr>
<td></td><td>Inference attack</td><td> [48]</td>
</tr>
<tr>
<td></td><td>mmWave radar attack</td><td> [55]</td>
</tr>
<tr>
<td></td><td>Side-channel attack</td><td> [56]</td>
</tr>
<tr>
<td rowspan='1'>Data from Cloud Storage</td><td></td><td>Data Privacy and Personal Information Attacks in Metaverse</td><td> [11]</td>
</tr>
<tr>
<td rowspan='2'>Video Capture</td><td></td><td>Exploiting 2D Video Capture</td><td> [12]</td>
</tr>
<tr>
<td></td><td>Eavesdropping video</td><td> [18], [31]</td>
</tr>
<tr>
<td rowspan='1'>Audio Capture</td><td></td><td>Eavesdropping audio</td><td> [18], [31], [19], [33]</td>
</tr>
<tr>
<td rowspan='2'>Adversary-in-the-Middle</td><td></td><td>Eavesdropping</td><td> [32], [43], [44], [16]</td>
</tr>
<tr>
<td>LLMNR/NBT-NS Poisoning and SMB Relay</td><td>Eavesdropping</td><td> [24]</td>
</tr>
<tr>
<td rowspan='1'>Automated Data Collection</td><td></td><td>Unauthorized Access</td><td> [42]</td>
</tr>
<tr>
<td rowspan='3'>Behavioral Mimicry</td><td></td><td>Mimicking Genuine User Actions</td><td> [12]</td>
</tr>
<tr>
<td></td><td>Mimicking Genuine User Actions/inference</td><td> [38]</td>
</tr>
<tr>
<td></td><td>Mimicking Genuine User Actions</td><td> [43]</td>
</tr>
<tr>
<td rowspan='1'>Spatial Data Inference</td><td></td><td>Location Inference Attack</td><td> [30]</td>
</tr>
<tr>
<td rowspan='1'>Physical Interaction Capture</td><td></td><td>Thermal Residue Attacks</td><td> [44]</td>
</tr>
<tr>
<td rowspan='1'>Data From Removable Media</td><td></td><td>Charging cable attack</td><td> [60]</td>
</tr>
<tr>
<td rowspan='4'>Resource Development</td><td rowspan='2'> Develop Capabilities</td><td>Train a machine learning model</td><td>Training machine learning model</td><td> [39]</td>
</tr>
<tr>
<td>Cross system data matching</td><td>Cross-System and Cross-Session Attacks</td><td> [12]</td>
</tr>
<tr>
<td rowspan='1'>Acquire Access</td><td></td><td>Unauthorized Access</td><td> [4]</td>
</tr>
<tr>
<td rowspan='1'>Obtain Capabilities</td><td>Avatar Duplication</td><td>Impersonation Metaverse</td><td> [20]</td>
</tr>
<tr>
<td rowspan='1'>Command and Control</td><td rowspan='1'> Content Injection</td><td></td><td>Botnet</td><td> [18]</td>
</tr>
<tr>
<td rowspan='4'>Execution</td><td rowspan='1'> User Execution</td><td>Malicious File</td><td>malware infections</td><td> [2]</td>
</tr>
<tr>
<td rowspan='2'>Command and Scripting Interpreter</td><td>JavaScript</td><td>Remote code execution</td><td> [18]</td>
</tr>
<tr>
<td>Unix Shell</td><td>Reverse Shell Attack</td><td> [62]</td>
</tr>
<tr>
<td rowspan='1'>Software Deployment Tools</td><td></td><td>Cyber-Physical Attacks</td><td> [15], [20], [27]</td>
</tr>
<tr>
<td rowspan='16'>Impact</td><td rowspan='1'> Network Denial of Service</td><td>Direct Network Flood</td><td>sync pulses attack</td><td> [3]</td>
</tr>
<tr>
<td rowspan='2'>Data Manipulation</td><td>Stored Data Manipulation</td><td>Data Manipulation</td><td> [4]</td>
</tr>
<tr>
<td>Runtime Data Manipulation</td><td>Multi-modal Spatiotemporal Attacks</td><td> [10]</td>
</tr>
<tr>
<td rowspan='1'>Virtual Reality Manipulation</td><td>Environment Manipulation</td><td>Immersive attack</td><td> [8]</td>
</tr>
<tr>
<td rowspan='2'>User Manipulation</td><td></td><td>The Man-In-The-Room Attack</td><td> [8]</td>
</tr>
<tr>
<td></td><td>Human Joystick Attack</td><td> [28]</td>
</tr>
<tr>
<td rowspan='1'>Endpoint Denial of Service</td><td>Application or System Exploitation</td><td>jamming attack</td><td> [3]</td>
</tr>
<tr>
<td rowspan='6'>Defacement</td><td></td><td>Overlay Attack</td><td> [8]</td>
</tr>
<tr>
<td></td><td>Video forgery attack</td><td> [43]</td>
</tr>
<tr>
<td></td><td>Video forgery attack (Obscuring Virtual Content)</td><td> [46]</td>
</tr>
<tr>
<td></td><td>Obscuring important real-world content (perception hacking)</td><td> [25], [46]</td>
</tr>
<tr>
<td></td><td>Overlay Attack</td><td> [5]</td>
</tr>
<tr>
<td>Internal Defacement</td><td>Immersive attack</td><td> [16]</td>
</tr>
<tr>
<td rowspan='1'>Data Encrypted for Impact</td><td></td><td>Ransomware</td><td> [20], [22]</td>
</tr>
<tr>
<td rowspan='1'>Sensory Manipulation</td><td></td><td>Mismatching Attacks</td><td> [28]</td>
</tr>
<tr>
<td rowspan='1'>Spoof Sensor Data or Telemetry</td><td>Replay of CSI Data</td><td>Time-Shift Attack</td><td> [41]</td>
</tr>
<tr>
<td rowspan='3'>Credential Access</td><td rowspan='1'> Input Capture</td><td></td><td>Shoulder Surfing</td><td> [21], [53], [54]</td>
</tr>
<tr>
<td rowspan='2'>Brute Force</td><td>Password Cracking</td><td>Hash Collision Attack</td><td> [24]</td>
</tr>
<tr>
<td>Password Guessing</td><td>Brute-force attack</td><td> [56]</td>
</tr>
<tr>
<td rowspan='1'>Discovery</td><td rowspan='1'> Process Discovery</td><td></td><td>Inferring Information about Concurrent Applications</td><td> [25]</td>
</tr>
<tr>
<td rowspan='8'>Initial Access</td><td rowspan='1'> Wireless Compromise</td><td></td><td>Insecure Data Transmission</td><td> [9]</td>
</tr>
<tr>
<td rowspan='5'>Exploit Public-Facing Application</td><td></td><td>Remote Control and System Compromise</td><td> [16]</td>
</tr>
<tr>
<td></td><td>Man-in-the-Room Attack</td><td> [18]</td>
</tr>
<tr>
<td></td><td>VR-specific Worm</td><td> [18]</td>
</tr>
<tr>
<td></td><td>Vulnerability Exploitation (sql injection)</td><td> [49]</td>
</tr>
<tr>
<td></td><td>Exploitation of SDK Vulnerabilities</td><td> [16]</td>
</tr>
<tr>
<td rowspan='1'>Trusted Relationship</td><td></td><td>Malicious Insider Threats</td><td> [17]</td>
</tr>
<tr>
<td rowspan='1'>Valid Accounts</td><td>Default Accounts</td><td>Impersonation Metaverse</td><td> [18]</td>
</tr>
<tr>
<td rowspan='1'>Lateral Movement</td><td rowspan='1'> Remote Service Session Hijacking</td><td>SSH Hijacking</td><td>Session Hijacking</td><td> [20]</td>
</tr>
<tr>
<td rowspan='2'>Persistance</td><td rowspan='1'> Compromise Host Binary</td><td></td><td>Algorithm Replacement Attacks</td><td> [29]</td>
</tr>
<tr>
<td rowspan='1'>Server Software Component</td><td>Web Shell</td><td>Malware Attacks (code injection)</td><td> [49], [51]</td>
</tr>
<tr>
<td rowspan='4'>Reconnaissance</td><td rowspan='1'> Phishing for Information</td><td>Spearphishing Link</td><td>Social Engineering</td><td> [27]</td>
</tr>
<tr>
<td rowspan='2'>Gather Victim Network Information</td><td>IP Addresses</td><td>Network Traffic Analysis (sniffing)</td><td> [51]</td>
</tr>
<tr>
<td></td><td>Website Fingerprinting</td><td> [51]</td>
</tr>
<tr>
<td rowspan='1'>Gather Victim Identity Information</td><td>Machine Learning Inference</td><td>Re-identification attack</td><td> [58]</td>
</tr>
<tr>
<td rowspan='1'>Remote Service Session Hijacking</td><td rowspan='1'> SSH Hijacking</td><td>Lateral Movement</td><td>Session Hijacking</td><td> [49]</td>
</tr>
<tr>
<td rowspan='1'>Defense Evasion</td><td rowspan='1'> Biometric Signal Forgery</td><td></td><td>Statistical Analysis for Detection</td><td> [38]</td>
</tr>
<tr>
<td rowspan='1'>Exfiltration</td><td rowspan='1'> Exfiltration Over Alternative Protocol</td><td>Cryptographic Subversion</td><td>Cryptographic Reverse Firewall Attack</td><td> [29]</td>
</tr>
</tr>
</table>

<br><br>

<h1>Submit a new Attack</h1>

<form action="https://send.pageclip.co/SlV6iY6tGiwn6CKLqnvHmb5ypq3vGGBQ/VR-MITRE" class="pageclip-form" method="post">
  <!-- Replace these inputs with your own. Make sure they have a "name" attribute! -->
  <label for="Name">Name:</label>
  <input type="text" name="Name" value="" />
  <label for="email">Email:</label>
  <input type="email" name="email" value="" />
  <br>
  <label for="Tactic">Tactic:</label>
  <input type="text" name="Tactic" value="" />
  <label for="Technique">Technique:</label>
  <input type="text" name="Technique" value="" />
  <label for="Subtechnique">Subtechnique:</label>
  <input type="text" name="Subtechnique" value="" />
  <br>
  <label for="AttackName">Attack Name:</label>
  <input type="text" name="AttackName" value="" />
  <br>
  <label for="Reference">Reference (paper/website):</label>
  <input type="text" name="Reference" value="" />
  <br>
  <label for="AttackDescription">Attack Description:</label>
  <textarea name="AttackDescription" value="" rows="5" cols="33"></textarea>
  <br>
  <!-- This button will have a loading spinner. Keep the inner span for best results. -->
  <input type="submit" value="Send">
</form>

<br><br>

<h1>References</h1>
[1] S. Chen, Z. Li, F. Dangelo, C. Gao, and X. Fu, “A Case Study of Security and Privacy Threats from Augmented Reality (AR),” in 2018 International Conference on Computing, Networking and Communications (ICNC), Mar. 2018, pp. 442–446. doi: 10.1109/ICCNC.2018.8390291.<br>
[2] M. Ishihara and T. Kanayama, “Visualization Technologies of Information Security Support System Using Haptic Devices,” in Human Aspects of Information Security, Privacy and Trust, T. Tryfonas, Ed., Cham: Springer International Publishing, 2017, pp. 329–338. doi: 10.1007/978-3-319-58460-7_23.<br>
[3] M. U. Rafique and S. S. Cheung, “Tracking Attacks on Virtual Reality Systems,” IEEE Consumer Electronics Magazine, vol. 9, no. 2, pp. 41–46, Mar. 2020, doi: 10.1109/MCE.2019.2953741.<br>
[4] S. Valluripally et al., “Detection of Security and Privacy Attacks Disrupting User Immersive Experience in Virtual Reality Learning Environments,” IEEE Transactions on Services Computing, vol. 16, no. 4, pp. 2559–2574, July 2023, doi: 10.1109/TSC.2022.3216539.<br>
[5] C. Zhao, X. Li, and R. Younes, “Self-supervised Multi-Modal Video Forgery Attack Detection,” in 2023 IEEE Wireless Communications and Networking Conference (WCNC), Mar. 2023, pp. 1–6. doi: 10.1109/WCNC55385.2023.10118664.<br>
[6] Y. Wu et al., “Privacy Leakage via Unrestricted Motion-Position Sensors in the Age of Virtual Reality: A Study of Snooping Typed Input on Virtual Keyboards,” in 2023 IEEE Symposium on Security and Privacy (SP), May 2023, pp. 3382–3398. doi: 10.1109/SP46215.2023.10179301.<br>
[7] Ü. Meteriz-Yıldıran, N. F. Yıldıran, A. Awad, and D. Mohaisen, “A Keylogging Inference Attack on Air-Tapping Keyboards in Virtual Environments,” in 2022 IEEE Conference on Virtual Reality and 3D User Interfaces (VR), Mar. 2022, pp. 765–774. doi: 10.1109/VR51125.2022.00098.<br>
[8] P. Casey, I. Baggili, and A. Yarramreddy, “Immersive Virtual Reality Attacks and the Human Joystick,” IEEE Transactions on Dependable and Secure Computing, vol. 18, no. 2, pp. 550–562, Mar. 2021, doi: 10.1109/TDSC.2019.2907942.<br>
[9] M. Gazzari, A. Mattmann, M. Maass, and M. Hollick, “My(o) Armband Leaks Passwords: An EMG and IMU Based Keylogging Side-Channel Attack,” Proc. ACM Interact. Mob. Wearable Ubiquitous Technol., vol. 5, no. 4, p. 157:1-157:24, Dec. 2022, doi: 10.1145/3494986.<br>
[10] Y. Chandio, N. Bashir, and F. M. Anwar, “Stealthy and Practical Multi-modal Attacks on Mixed Reality Tracking,” in 2024 IEEE International Conference on Artificial Intelligence and eXtended and Virtual Reality (AIxVR), Jan. 2024, pp. 11–20. doi: 10.1109/AIxVR59861.2024.00010.<br>
[11] R. C. Sharma and A. Zamfiroiu, “Cybersecurity Threats and Vulnerabilities in the Metaverse,” in 2023 International Conference on Intelligent Metaverse Technologies & Applications (iMETA), Sept. 2023, pp. 1–7. doi: 10.1109/iMETA59369.2023.10294950.<br>
[12] R. Miller, N. K. Banerjee, and S. Banerjee, “Using External Video to Attack Behavior-Based Security Mechanisms in Virtual Reality (VR),” in 2022 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW), Mar. 2022, pp. 684–685. doi: 10.1109/VRW55335.2022.00193.<br>
[13] Z. Ling, Z. Li, C. Chen, J. Luo, W. Yu, and X. Fu, “I Know What You Enter on Gear VR,” in 2019 IEEE Conference on Communications and Network Security (CNS), June 2019, pp. 241–249. doi: 10.1109/CNS.2019.8802674.<br>
[14] A. M. Awadallah, E. Damiani, J. Zemerly, and C. Y. Yeun, “Identity Threats in the Metaverse and Future Research Opportunities,” in 2023 International Conference on Business Analytics for Technology and Security (ICBATS), Mar. 2023, pp. 1–6. doi: 10.1109/ICBATS57792.2023.10111122.<br>
[15] B. Bütün, A. T.-J. Akem, M. Gucciardo, and M. Fiore, “Fast Detection of Cyberattacks on the Metaverse through User-plane Inference,” in 2023 IEEE International Conference on Metaverse Computing, Networking and Applications (MetaCom), June 2023, pp. 350–354. doi: 10.1109/MetaCom57706.2023.00067.<br>
[16] O. Nnamonu, M. Hammoudeh, and T. Dargahi, “Metaverse Cybersecurity Threats and Risks Analysis: The case of Virtual Reality Towards Security Testing and Guidance Framework,” in 2023 IEEE International Conference on Metaverse Computing, Networking and Applications (MetaCom), June 2023, pp. 94–98. doi: 10.1109/MetaCom57706.2023.00028.<br>
[17] H. Khan, U. Hengartner, and D. Vogel, “Augmented Reality-based Mimicry Attacks on Behaviour-Based Smartphone Authentication,” in Proceedings of the 16th Annual International Conference on Mobile Systems, Applications, and Services, in MobiSys ’18. New York, NY, USA: Association for Computing Machinery, June 2018, pp. 41–53. doi: 10.1145/3210240.3210317.<br>
[18] M. Vondráček, I. Baggili, P. Casey, and M. Mekni, “Rise of the Metaverse’s Immersive Virtual Reality Malware and the Man-in-the-Room Attack & Defenses,” Comput. Secur., vol. 127, no. C, Apr. 2023, doi: 10.1016/j.cose.2022.102923.<br>
[19] D. K. Yadav, B. Ionascu, S. V. Krishna Ongole, A. Roy, and N. Memon, “Design and Analysis of Shoulder Surfing Resistant PIN Based Authentication Mechanisms on Google Glass,” in Financial Cryptography and Data Security, M. Brenner, N. Christin, B. Johnson, and K. Rohloff, Eds., Berlin, Heidelberg: Springer, 2015, pp. 281–297. doi: 10.1007/978-3-662-48051-9_21.<br>
[20] E. C. Nkoro, C. I. Nwakanma, J.-M. Lee, and D.-S. Kim, “Detecting cyberthreats in Metaverse learning platforms using an explainable DNN,” Internet of Things, vol. 25, p. 101046, Apr. 2024, doi: 10.1016/j.iot.2023.101046.<br>
[21] J. Lee, H. Kim, and K. Lee, “VRKeyLogger: Virtual keystroke inference attack via eavesdropping controller usage pattern in WebVR,” Computers & Security, vol. 134, p. 103461, Nov. 2023, doi: 10.1016/j.cose.2023.103461.<br>
[22] M. Z. Tahat, W. B. Glisson, and B. Al Smadi, “VR Headset Ransomware Attack Vulnerability,” in 2024 IEEE Canadian Conference on Electrical and Computer Engineering (CCECE), Aug. 2024, pp. 740–745. doi: 10.1109/CCECE59415.2024.10667339.<br>
[23] Y. Abdrabou et al., “Understanding Shoulder Surfer Behavior and Attack Patterns Using Virtual Reality,” in Proceedings of the 2022 International Conference on Advanced Visual Interfaces, in AVI ’22. New York, NY, USA: Association for Computing Machinery, June 2022, pp. 1–9. doi: 10.1145/3531073.3531106.<br>
[24] I. Sluganovic, M. Serbec, A. Derek, and I. Martinovic, “HoloPair: Securing Shared Augmented Reality Using Microsoft HoloLens,” in Proceedings of the 33rd Annual Computer Security Applications Conference, in ACSAC ’17. New York, NY, USA: Association for Computing Machinery, Dec. 2017, pp. 250–261. doi: 10.1145/3134600.3134625.<br>
[25] Y. Zhang, C. Slocum, J. Chen, and N. Abu-Ghazaleh, “It’s all in your head(set): side-channel attacks on AR/VR systems,” in Proceedings of the 32nd USENIX Conference on Security Symposium, in SEC ’23. USA: USENIX Association, Aug. 2023, pp. 3979–3996.<br>
[26] Y. Meng, Y. Zhan, J. Li, S. Du, H. Zhu, and X. Shen, “De-Anonymizing Avatars in Virtual Reality: Attacks and Countermeasures,” IEEE Transactions on Mobile Computing, vol. 23, no. 12, pp. 13342–13357, Dec. 2024, doi: 10.1109/TMC.2024.3426046.<br>
[27] A. Yeboah-Ofori and A. Hawsh, “Effects of Cyberattacks on Virtual Reality and Augmented Reality Technologies for People with Disabilities,” in 2023 IEEE International Smart Cities Conference (ISC2), Sept. 2023, pp. 1–7. doi: 10.1109/ISC257844.2023.10293659.<br>
[28] W.-J. Tseng et al., “The Dark Side of Perceptual Manipulations in Virtual Reality,” in Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems, in CHI ’22. New York, NY, USA: Association for Computing Machinery, Apr. 2022, pp. 1–15. doi: 10.1145/3491102.3517728.<br>
[29] Y. Zhao, Y. Pang, X. Ke, B. Wang, G. Zhu, and M. Cao, “A metaverse-oriented CP-ABE scheme with cryptographic reverse firewall,” Future Generation Computer Systems, vol. 147, pp. 195–206, Oct. 2023, doi: 10.1016/j.future.2023.04.025.<br>
[30] J. A. de Guzman, A. Seneviratne, and K. Thilakarathna, “Unravelling Spatial Privacy Risks of Mobile Mixed Reality Data,” Proc. ACM Interact. Mob. Wearable Ubiquitous Technol., vol. 5, no. 1, p. 14:1-14:26, Mar. 2021, doi: 10.1145/3448103.<br>
[31] S. Luo, X. Hu, and Z. Yan, “HoloLogger: Keystroke Inference on Mixed Reality Head Mounted Displays,” in 2022 IEEE Conference on Virtual Reality and 3D User Interfaces (VR), Mar. 2022, pp. 445–454. doi: 10.1109/VR51125.2022.00064.<br>
[32] V. Gandhi, K. R. Ramkumar, A. Kaur, P. Kaushal, J. K. Chahal, and J. Singh, “Security and privacy in IoT, Cloud and Augmented Reality,” in 2021 6th International Conference on Signal Processing, Computing and Control (ISPCC), Oct. 2021, pp. 131–135. doi: 10.1109/ISPCC53510.2021.9609520.<br>
[33] H. Althebeiti, R. Gedawy, A. Alghuried, D. Nyang, and D. Mohaisen, “Defending AirType Against Inference Attacks Using 3D In-Air Keyboard Layouts: Design and Evaluation,” in Information Security Applications, H. Kim and J. Youn, Eds., Singapore: Springer Nature, 2024, pp. 159–174. doi: 10.1007/978-981-99-8024-6_13.<br>
[34] Y. Meng, Y. Zhan, J. Li, S. Du, H. Zhu, and X. Shen, “De-Anonymizing Avatars in Virtual Reality: Attacks and Countermeasures,” IEEE Transactions on Mobile Computing, vol. 23, no. 12, pp. 13342–13357, Dec. 2024, doi: 10.1109/TMC.2024.3426046.<br>
[35] A. A. Arafat, Z. Guo, and A. Awad, “VR-Spy: A Side-Channel Attack on Virtual Key-Logging in VR Headsets,” in 2021 IEEE Virtual Reality and 3D User Interfaces (VR), Mar. 2021, pp. 564–572. doi: 10.1109/VR50410.2021.00081.<br>
[36] C. Kreider, “THE DISCOVERABILITY OF PASSWORD ENTRY USING VIRTUAL KEYBOARDS IN AN AUGMENTED REALITY WEARABLE: AN INITIAL PROOF OF CONCEPT,” SAIS 2018 Proceedings, Mar. 2018, [Online]. Available: https://aisel.aisnet.org/sais2018/23<br>
[37] Y. Zhang, C. Slocum, J. Chen, and N. Abu-Ghazaleh, “It’s all in your head(set): side-channel attacks on AR/VR systems,” in Proceedings of the 32nd USENIX Conference on Security Symposium, in SEC ’23. USA: USENIX Association, Aug. 2023, pp. 3979–3996.<br>
[38] S. Luo, A. Nguyen, C. Song, F. Lin, W. Xu, and Z. Yan, “OcuLock: Exploring Human Visual System for Authentication in Virtual Reality Head-mounted Display,” in Proceedings 2020 Network and Distributed System Security Symposium, San Diego, CA: Internet Society, 2020. doi: 10.14722/ndss.2020.24079.<br>
[39] C. Shi et al., “Face-Mic: inferring live speech and speaker identity via subtle facial dynamics captured by AR/VR motion sensors,” in Proceedings of the 27th Annual International Conference on Mobile Computing and Networking, in MobiCom ’21. New York, NY, USA: Association for Computing Machinery, Oct. 2021, pp. 478–490. doi: 10.1145/3447993.3483272.<br>
[41] J. Liu, Y. He, C. Xiao, J. Han, and K. Ren, “Time to Think the Security of WiFi-Based Behavior Recognition Systems,” IEEE Transactions on Dependable and Secure Computing, vol. 21, no. 1, pp. 449–462, Jan. 2024, doi: 10.1109/TDSC.2023.3261328.<br>
[42] M. Langfinger, M. Schneider, D. Stricker, and H. D. Schotten, “Addressing security challenges in industrial augmented reality systems,” in 2017 IEEE 15th International Conference on Industrial Informatics (INDIN), July 2017, pp. 299–304. doi: 10.1109/INDIN.2017.8104789.<br>
[43] H. Khan, U. Hengartner, and D. Vogel, “Mimicry Attacks on Smartphone Keystroke Authentication,” ACM Trans. Priv. Secur., vol. 23, no. 1, p. 2:1-2:34, Feb. 2020, doi: 10.1145/3372420.<br>
[44] R. Düzgün, P. Mayer, and M. Volkamer, “Shoulder-Surfing Resistant Authentication for Augmented Reality,” in Nordic Human-Computer Interaction Conference, in NordiCHI ’22. New York, NY, USA: Association for Computing Machinery, Oct. 2022, pp. 1–13. doi: 10.1145/3546155.3546663.<br>
[45] M. Abraham, P. Saeghe, M. Mcgill, and M. Khamis, “Implications of XR on Privacy, Security and Behaviour: Insights from Experts,” in Nordic Human-Computer Interaction Conference, in NordiCHI ’22. New York, NY, USA: Association for Computing Machinery, Oct. 2022, pp. 1–12. doi: 10.1145/3546155.3546691.<br>
[46] K. Lebeck, K. Ruth, T. Kohno, and F. Roesner, “Securing Augmented Reality Output,” in 2017 IEEE Symposium on Security and Privacy (SP), May 2017, pp. 320–337. doi: 10.1109/SP.2017.13.<br>
[47] C. Slocum, Y. Zhang, N. Abu-Ghazaleh, and J. Chen, “Going through the motions: AR/VR keylogging from user head motions,” in Proceedings of the 32nd USENIX Conference on Security Symposium, in SEC ’23. USA: USENIX Association, Aug. 2023, pp. 159–174.<br>
[48] H. Wang, Z. Zhan, H. Shan, S. Dai, M. Panoff, and S. Wang, “GAZEploit: Remote Keystroke Inference Attack by Gaze Estimation from Avatar Views in VR/MR Devices,” in Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security, in CCS ’24. New York, NY, USA: Association for Computing Machinery, Dec. 2024, pp. 1731–1745. doi: 10.1145/3658644.3690285.<br>
[49] S. Valluripally, A. Gulhane, K. A. Hoque, and P. Calyam, “Modeling and Defense of Social Virtual Reality Attacks Inducing Cybersickness,” IEEE Transactions on Dependable and Secure Computing, vol. 19, no. 6, pp. 4127–4144, Nov. 2022, doi: 10.1109/TDSC.2021.3121216.<br>
[50] B. Odeleye, G. Loukas, R. Heartfield, and F. Spyridonis, “Detecting framerate-oriented cyber attacks on user experience in virtual reality,” Aug. 2021.<br>
[51] G. Meyer-Lee, J. Shang, and J. Wu, “Location-leaking through Network Traffic in Mobile Augmented Reality Applications,” in 2018 IEEE 37th International Performance Computing and Communications Conference (IPCCC), Nov. 2018, pp. 1–8. doi: 10.1109/PCCC.2018.8711065.<br>
[52] M. Sabra, N. Vinayaga-Sureshkanth, A. Sharma, A. Maiti, and M. Jadliwala, “De-anonymizing VR Avatars using Non-VR Motion Side-channels,” in Proceedings of the 17th ACM Conference on Security and Privacy in Wireless and Mobile Networks, in WiSec ’24. New York, NY, USA: Association for Computing Machinery, May 2024, pp. 54–65. doi: 10.1145/3643833.3656135.<br>
[53] M. Corbett, B. David-John, J. Shang, and B. Ji, “ShouldAR: Detecting Shoulder Surfing Attacks Using Multimodal Eye Tracking and Augmented Reality,” Proc. ACM Interact. Mob. Wearable Ubiquitous Technol., vol. 8, no. 3, p. 97:1-97:23, Sept. 2024, doi: 10.1145/3678573.<br>
[54] Y. Weiss, S. Villa, J. W. Grootjen, M. Hoppe, Y. Kale, and F. Müller, “Exploring Redirection and Shifting Techniques to Mask Hand Movements from Shoulder-Surfing Attacks during PIN Authentication in Virtual Reality,” Proc. ACM Hum.-Comput. Interact., vol. 8, no. MHCI, p. 257:1-257:24, Sept. 2024, doi: 10.1145/3676502.<br>
[55] L. Mei et al., “mmSpyVR: Exploiting mmWave Radar for Penetrating Obstacles to Uncover Privacy Vulnerability of Virtual Reality,” Proc. ACM Interact. Mob. Wearable Ubiquitous Technol., vol. 8, no. 4, p. 172:1-172:29, Nov. 2024, doi: 10.1145/3699772.<br>
[56] G. Xiao et al., “Pivot: Panoramic-Image-Based VR User Authentication against Side-Channel Attacks,” ACM Trans. Multimedia Comput. Commun. Appl., vol. 21, no. 2, p. 54:1-54:19, Jan. 2025, doi: 10.1145/3694975.<br>
[57] Y. Siriwardhana, P. Porambage, M. Liyanage, S. Marchal, and M. Ylianttila, “Robust Aggregation Technique Against Poisoning Attacks in Multi-Stage Federated Learning Applications,” in 2024 IEEE 21st Consumer Communications & Networking Conference (CCNC), Jan. 2024, pp. 956–962. doi: 10.1109/CCNC51664.2024.10454789.<br>
[58] V. Nair et al., “Inferring Private Personal Attributes of Virtual Reality Users from Ecologically Valid Head and Hand Motion Data,” in 2024 IEEE Conference on Virtual Reality and 3D User Interfaces Abstracts and Workshops (VRW), Mar. 2024, pp. 477–484. doi: 10.1109/VRW62533.2024.00094.<br>
[59] M. R. Miller et al., “Effect of Duration and Delay on the Identifiability of VR Motion,” in 2024 IEEE 25th International Symposium on a World of Wireless, Mobile and Multimedia Networks (WoWMoM), June 2024, pp. 70–75. doi: 10.1109/WoWMoM60985.2024.00023.<br>
[60] J. Li, Y. Meng, Y. Zhan, L. Zhang, and H. Zhu, “Dangers Behind Charging VR Devices: Hidden Side Channel Attacks via Charging Cables,” IEEE Transactions on Information Forensics and Security, vol. 19, pp. 8892–8907, 2024, doi: 10.1109/TIFS.2024.3465026.<br>
[61] Y.-S. Wei, Y.-C. Sun, S.-Y. Zheng, H.-F. Hsu, C.-Y. Huang, and C.-H. Hsu, “Mitigating Privacy Threats Without Degrading Visual Quality of VR Applications: Using Re-Identification Attack as a Case Study,” in 2024 IEEE 7th International Conference on Multimedia Information Processing and Retrieval (MIPR), Aug. 2024, pp. 214–220. doi: 10.1109/MIPR62202.2024.00040.<br>
[62] A. Jafar, A. Yeboah-Ofori, T. Abisogun, I. Hilton, O. Oguntoyinbo, and O. Oyetunji, “The Impact of Social Engineering Attacks on the Metaverse Platform,” in 2024 11th International Conference on Future Internet of Things and Cloud (FiCloud), Aug. 2024, pp. 201–208. doi: 10.1109/FiCloud62933.2024.00038.<br>
[63] M. Vondráček, I. Baggili, P. Casey, and M. Mekni, “Rise of the Metaverse’s Immersive Virtual Reality Malware and the Man-in-the-Room Attack & Defenses,” Comput. Secur., vol. 127, no. C, Apr. 2023, doi: 10.1016/j.cose.2022.102923.<br>
[64] Ü. Meteriz-Yıldıran, N. F. Yıldıran, A. Awad, and D. Mohaisen, “A Keylogging Inference Attack on Air-Tapping Keyboards in Virtual Environments,” in 2022 IEEE Conference on Virtual Reality and 3D User Interfaces (VR), Mar. 2022, pp. 765–774. doi: 10.1109/VR51125.2022.00098.<br>
[65] S. Luo, A. Nguyen, H. Farooq, K. Sun, and Z. Yan, “Eavesdropping on controller acoustic emanation for keystroke inference attack in virtual reality,” in The Network and Distributed System Security Symposium (NDSS), 2024.<br>
[66] V. Nair, G. M. Garrido, D. Song, and J. F. O’Brien, “Exploring the Privacy Risks of Adversarial VR Game Design,” PoPETs, vol. 2023, no. 4, pp. 238–256, Oct. 2023, doi: 10.56553/popets-2023-0108.<br>
