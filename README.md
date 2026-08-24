# networkwalks-B082-week2-Task3-PENETRATION-TESTING-REPORT
<div align="center">

# 🔐 Cybersecurity PENETRATION-TESTING REPORT

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ver-Virtualbox%20v7.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Kali%20Linux-v2026.2-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Linux-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Network-10.0.0.0%2F24-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Penetration%20Testing-C00000?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Skill-Virtualization-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/GitHub-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali%20Linux-404040?style=flat-square&labelColor=C00000&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000&logo=kalilinux&logoColor=white" />
</p>

 ##  PENETRATION TESTING REPORT
##   FOOTPRINTING & NETWORK SCANNING PHASES
##    W2-PM-FINAL | CYBERSECURITY | NETWORKWALKS

| **Report Information** | **Details**                                                                   |
| ---------------------- | ----------------------------------------------------------------------------- |
| Pentester Name         | Rabi Chaudhary                                                                |
| Program / Batch        | B082-Networkwalks                                                             |
| Date                   | 24 August 2026                                                                |
| Modules Completed      | W2-PM3 (Maltego-based Footprinting); W2-PM5 (Zenmap-based Network Scanning)   |
| Client / Target        | networkwalks.com (authorized training target) and my own local LAN for Zenmap |
| Permission Secured     | Yes — activities performed only within the authorized educational scope       |
| Phases Covered         | Phase 1: Reconnaissance & Footprinting; Phase 2: Scanning & Network Discovery |

##  1. Liability Disclaimer

All activities documented in this report were performed only against systems, domains, or network devices for which I had appropriate authorization or that I personally own/control. The work was conducted for educational and cybersecurity training purposes. The techniques described in this report must therefore be used only within an explicitly authorized scope. and authorized.

## 2. Introduction

This report documents the Week 2 practical work completed for the penetration-testing and cybersecurity training program. The selected modules were W2-PM3, Maltego-based Footprinting Attacks, and W2-PM5, Zenmap-based Network Scanning. Together, these activities demonstrate two foundational stages of a security assessment: collecting information about an authorized target and discovering active systems within an authorized local network.

Maltego was used to visualize relationships between entities and publicly available information associated with the authorized footprinting target. Zenmap, the graphical interface for Nmap, was used to discover live hosts on my own local network and to visualize the resulting network topology. The exercises focused on information gathering and host discovery; no exploitation was performed as part of these two modules.

## 3. Objectives
   
•	Understand the role of reconnaissance and footprinting in a penetration-testing workflow.

•	Use Maltego to identify email addresses related to the authorized target organization domain networkwalks.com.

•	Understand how publicly available email information can contribute to an authorized target profile.

•	Identify the local IP address and subnet before performing network discovery.

•	Use Zenmap to identify active hosts on the authorized local network.

•	Review IP and MAC-address information returned by the scan where available.

•	Generate and interpret a basic network topology.

•	Document observations, potential risks, evidence, and recommendations professionally.

## 4. Scope and Methodology

| **Module** | **Scope**                                 | **Method**                                                                      | **Expected Output**                                   |
| ---------- | ----------------------------------------- | ------------------------------------------------------------------------------- | ----------------------------------------------------- |
| W2-PM3     | Authorized target domain networkwalks.com | Maltego installation, configuration, Domain entity and email-related transforms | Related email addresses and footprinting observations |
| W2-PM5     | My own local LAN                          | Host discovery and topology visualization using Zenmap/Nmap                     | Live hosts, IP/MAC details where available, topology  |


The methodology followed a non-destructive sequence: define the authorized scope, collect information, record evidence, interpret observations, assess potential security relevance, and document recommendations. Findings in this report are observations unless explicitly validated as vulnerabilities.

## 5. Tools Used

| **Tool**                       | **Purpose**                                                                                    |
| ------------------------------ | ---------------------------------------------------------------------------------------------- |
| Maltego                        | Identify and visualize information related to an authorized target, including email addresses. |
| Zenmap                         | Graphical interface for Nmap used for network discovery and scan-result visualization.         |
| Nmap                           | Underlying scanning engine used by Zenmap for host discovery.                                  |
| Windows ipconfig               | Identify the local IP address, subnet information, and default gateway before scanning.        |
| Web browser / evidence capture | Record Maltego, ipconfig, Zenmap results and screenshots for the final report.                 |


## 6. Activities Performed
   
## 6.1 W2-PM3 — Maltego-Based Footprinting

The first activity focused on reconnaissance and footprinting using Maltego. The objective was to install and configure Maltego, create a Maltego account, investigate the authorized domain networkwalks.com, and identify related email addresses using email-focused transforms.

## 6.1.1 Maltego Setup

Maltego was downloaded and installed on a Windows computer. After installation, Maltego was opened and configured, and a free Maltego account was created and used to complete the setup. The Domain entity was then added to the main graph area and changed to networkwalks.com.
<img width="775" height="591" alt="Screenshot 2026-08-24 171518" src="https://github.com/user-attachments/assets/066f7195-fb80-49aa-82d4-5ab97d24df6c" />
<img width="776" height="602" alt="Screenshot 2026-08-24 171534" src="https://github.com/user-attachments/assets/19983652-e3bb-4a67-9529-a2d434790cc8" />
<img width="753" height="578" alt="Screenshot 2026-08-24 171547" src="https://github.com/user-attachments/assets/7b92649a-ced2-4183-b4b1-212b2332b0ec" />
<img width="753" height="586" alt="Screenshot 2026-08-24 171701" src="https://github.com/user-attachments/assets/d931b43b-1bc6-4e0f-b91c-4ee0aed666db" />
<img width="750" height="575" alt="Screenshot 2026-08-24 171810" src="https://github.com/user-attachments/assets/7b97e6b1-2c7e-4890-a284-a238a786f90f" />
<img width="744" height="577" alt="Screenshot 2026-08-24 171900" src="https://github.com/user-attachments/assets/83610145-4dc3-423d-83c6-19f6cef880cc" />
<img width="743" height="582" alt="Screenshot 2026-08-24 171947" src="https://github.com/user-attachments/assets/1297530f-86ae-42de-a89d-c5cf94e0b55a" />
<img width="846" height="992" alt="Screenshot 2026-08-24 172018" src="https://github.com/user-attachments/assets/4124ed29-daea-462d-a443-c714e10d44f7" />
<img width="960" height="792" alt="Screenshot 2026-08-24 172039" src="https://github.com/user-attachments/assets/78a1cb4f-ec74-4a72-a9e4-d24f02215459" />
<img width="1832" height="993" alt="Screenshot 2026-08-24 172127" src="https://github.com/user-attachments/assets/02aaf189-1008-4523-bbfe-65824bc569c0" />
<img width="1821" height="990" alt="Screenshot 2026-08-24 172155" src="https://github.com/user-attachments/assets/d176a526-40c1-49dc-99e8-d210837efe88" />
<img width="13" height="2" alt="Screenshot 2026-08-24 172225" src="https://github.com/user-attachments/assets/28da8cd3-b829-42f9-b8b6-f22b3e317184" />
<img width="1826" height="992" alt="Screenshot 2026-08-24 172236" src="https://github.com/user-attachments/assets/889ce169-0561-4cae-af57-06705515efe1" />
<img width="1242" height="961" alt="Screenshot 2026-08-24 173206" src="https://github.com/user-attachments/assets/23a6aeb8-e7dd-4358-b7d3-12e4efe10d3f" />
<img width="850" height="368" alt="Screenshot 2026-08-24 175342" src="https://github.com/user-attachments/assets/8dd77dde-0be3-4c6a-868c-c661789444fb" />
<img width="848" height="373" alt="Screenshot 2026-08-24 175358" src="https://github.com/user-attachments/assets/e02ba8c8-af17-4e4f-a7fc-95b1a86715fb" />
<img width="846" height="371" alt="Screenshot 2026-08-24 175409" src="https://github.com/user-attachments/assets/13734e3c-2456-4705-b78c-b6689c958125" />
<img width="929" height="345" alt="Screenshot 2026-08-24 175436" src="https://github.com/user-attachments/assets/b7baece4-850c-46f1-ba1e-a0972e88ec98" />
<img width="929" height="346" alt="Screenshot 2026-08-24 175449" src="https://github.com/user-attachments/assets/1ab08b7f-9719-421a-bee3-1d225989436f" />
<img width="1070" height="507" alt="Screenshot 2026-08-24 175502" src="https://github.com/user-attachments/assets/c0ff67fd-bdc7-4e9c-a2d1-f27b0008fbc8" />
<img width="1063" height="556" alt="Screenshot 2026-08-24 175512" src="https://github.com/user-attachments/assets/5563b305-b2ac-4586-9b19-3213e1be4459" />
<img width="681" height="397" alt="Screenshot 2026-08-24 175525" src="https://github.com/user-attachments/assets/baaa4bbf-16fb-4241-a380-ca2ddec3795f" />
<img width="915" height="492" alt="Screenshot 2026-08-24 175539" src="https://github.com/user-attachments/assets/d9297038-a0a2-4443-8d37-11f122d9966d" />
<img width="1031" height="556" alt="Screenshot 2026-08-24 175550" src="https://github.com/user-attachments/assets/a8be5d81-dbf1-4c69-adf6-564f277e8c79" />

## 6.1.2 Footprinting Process

The investigation started by double-clicking the Domain entity and changing its name to networkwalks.com. The entity was then right-clicked, email-related transforms were filtered, and the relevant transforms were run. The resulting graph displayed email addresses related to the target domain.

The important lesson from this activity was that reconnaissance can reveal useful information before any direct access is attempted. Email addresses associated with a domain can help security professionals understand the publicly exposed contact surface of an organization.
    <img width="1919" height="1011" alt="Screenshot 2026-08-24 155623" src="https://github.com/user-attachments/assets/72aeda3a-ae68-43bf-8ac7-99864e7171e8" />
<img width="1234" height="552" alt="Screenshot 2026-08-24 155659" src="https://github.com/user-attachments/assets/0d76b81d-1c0f-4460-8d01-ccf666141886" />
<img width="1222" height="557" alt="Screenshot 2026-08-24 155717" src="https://github.com/user-attachments/assets/230e659c-ad13-42fe-9e97-67f1577d3745" />
<img width="1220" height="554" alt="Screenshot 2026-08-24 155755" src="https://github.com/user-attachments/assets/036f57bf-04a3-401a-9c14-d41679c9f13e" />


## 6.1.3 Observations

•	The Maltego graph provided a visual representation of email relationships associated with the authorized target domain.

•	The Domain entity and email-related transforms provided complementary information about the target's publicly exposed email surface.

•	Publicly observable email information can contribute to target profiling without attempting unauthorized access.

•	The exact email addresses discovered should be taken from the Maltego evidence screenshots and recorded accurately in the final submission.

## 6.1.4 Security Relevance

From an attacker's perspective, publicly exposed email addresses can support targeted research and later technology-specific attacks. From a defender's perspective, the same process helps identify information that an external party may collect. The presence of an email address is not itself proof of a vulnerability; its security significance depends on how it may be combined with other information.

## 6.2 W2-PM5 — Zenmap-Based Network Scanning

The second activity focused on discovering active hosts on my own local network using Zenmap. Before scanning, the local network configuration was identified so that the scan could remain within the authorized subnet.

## 6.2.1 Identify Local Network Configuration

On Windows, the ipconfig command was used to identify the local IPv4 address, subnet configuration, and default gateway. The exact values below must be replaced with the results from my own machine.

| **Item**             | **My Result** |
| -------------------- | ------------- |
| Local IPv4 Address   | 192.168.1.66  |
| Subnet Mask / Prefix | 255.255.255.0 |
| Default Gateway      | 192.168.1.254 |
| Scan Range           | 10.0.0.0/24   |

## Windows ipconfig output:
<img width="1706" height="874" alt="Screenshot 2026-08-24 181911" src="https://github.com/user-attachments/assets/559ff324-c7e8-4730-a36b-d3cf0848d43f" />

 
## 6.2.2 Zenmap Host Discovery

The identified local subnet was entered into Zenmap. A host-discovery/Ping Scan profile was used to identify devices that responded during the scan. The scan was limited to the user's own local network.
       <img width="1166" height="547" alt="Screenshot 2026-08-24 182802" src="https://github.com/user-attachments/assets/8bc0dc60-1935-467a-b48d-52951475e37a" />
 <img width="1068" height="576" alt="Screenshot 2026-08-24 182939" src="https://github.com/user-attachments/assets/74150bcc-6c24-473b-9c06-9be3dd178605" />
<img width="1054" height="520" alt="Screenshot 2026-08-24 182951" src="https://github.com/user-attachments/assets/75af6887-8143-41bb-8b5f-c721a60603cb" />
<img width="516" height="826" alt="Screenshot 2026-08-24 183011" src="https://github.com/user-attachments/assets/9cb40f2f-acae-4a78-9935-0d97c4a79470" />
<img width="1048" height="488" alt="Screenshot 2026-08-24 183023" src="https://github.com/user-attachments/assets/2d8a816c-ccab-4b07-9604-51ae6662a941" />
<img width="1052" height="474" alt="Screenshot 2026-08-24 183035" src="https://github.com/user-attachments/assets/b8421db4-5c9f-4a3f-9bd4-fca6fe1b9c44" />
<img width="1045" height="466" alt="Screenshot 2026-08-24 183049" src="https://github.com/user-attachments/assets/4bfe83bb-8da9-46fc-8bea-cf87d77f5648" />
<img width="1063" height="515" alt="Screenshot 2026-08-24 183105" src="https://github.com/user-attachments/assets/1bacee95-90a8-46da-b59f-37c9152f6f34" />
<img width="1919" height="1003" alt="Screenshot 2026-08-24 183250" src="https://github.com/user-attachments/assets/0d2635af-fa7a-40c4-bd71-ee5d9f339062" />

## 6.2.3 Live Host Results

| **Host #** | **IP Address** | **MAC Address**   | **Observed Device / Notes**                |
| ---------- | -------------- | ----------------- | ------------------------------------------ |
| 1          | 192.168.1.66   | 14:58:08:FA:13:00 | (Taicang T&W Electronics)                  |
| 2          | 192.168.1.70   | AC:73:52:6E:AF:2B | (Guangdong Oppo Mobile Telecommunications) |
| 3          | 192.168.1.72   | B4:BA:6A:C8:21:83 | (Tecno Mobile Limited)                     |
| 4          | 192.168.1.254  | 4C:BB:6F:87:1D:40 | (Infinix mobility limited)                 |


## 6.2.4 Network Topology

After completing host discovery, the Zenmap Topology view was reviewed to visualize the relationship between the local scanning host, gateway, and discovered devices. The topology provides a concise visual representation of the observed network structure.

 ## Zenmap Topology view:
 <img width="1686" height="709" alt="whatsapp" src="https://github.com/user-attachments/assets/e0ad2240-8e01-410f-b3ea-c7691e0e3126" />

 
## 7. Findings and Risk Analysis

| **#** | **Finding / Observation**                                    | **Evidence**                   | **Potential Impact**                                                                            | **Risk**   |
| ----- | ------------------------------------------------------------ | ------------------------------ | ----------------------------------------------------------------------------------------------- | ---------- |
| 1     | Publicly observable target relationships                     | Maltego graph                  | May help an external party build an infrastructure profile.                                     | Low–Medium |
| 2     | Infrastructure information correlated through reconnaissance | Maltego entities/relationships | Combined information may reduce uncertainty during later authorized testing.                    | Low–Medium |
| 3     | Multiple live hosts visible on the local network             | Zenmap scan results            | Unexpected devices may represent unmanaged or unauthorized assets.                              | Medium     |
| 4     | IP/MAC information available for discovered local hosts      | Zenmap results                 | Can assist asset identification and network inventory.                                          | Low        |
| 5     | Network topology can be inferred from scan results           | Zenmap Topology                | Improves understanding of network structure but may expose unmanaged devices if not controlled. | Low–Medium |


Risk ratings above are preliminary and represent the potential security relevance of the observations. They are not confirmed vulnerability ratings. A confirmed vulnerability would require additional authorized validation.

## 8. Recommendations

1. Review publicly available organizational information and remove unnecessary technical details where practical.
   
2. Maintain an accurate external asset inventory so that domains, subdomains, and infrastructure relationships are known and authorized.
   
3. Regularly perform defensive reconnaissance of the organization's public footprint to identify unintended exposure.
  
4. Maintain an accurate internal network inventory and compare discovered hosts against approved assets.
   
5. Investigate unknown or unexpected devices identified during authorized network discovery.
   
6. Segment sensitive systems and apply appropriate access controls so that discovery of a host does not imply unrestricted access.
   
7. Keep network documentation and topology diagrams current.
 
8. Use monitoring and asset-management processes to identify newly connected devices.
   
9. Repeat reconnaissance and network-discovery checks periodically as infrastructure changes.
  
10. Perform all reconnaissance and scanning only within documented authorization and scope.
  
## 9. Lessons Learned

•	Footprinting is an important first step because later security testing depends on understanding the target and its publicly exposed information.

•	Maltego demonstrates how transforms and relationship-based analysis can reveal publicly exposed email information.

•	Network scanning provides a practical way to identify active assets and compare observed devices with an approved inventory.

•	A scan result is an observation and should not automatically be treated as a vulnerability.

•	Evidence collection and clear documentation are essential parts of professional penetration testing.

•	Authorization and scope must be established before reconnaissance or scanning is performed.

## 10. Conclusion

During Week 2, I completed practical activities covering reconnaissance, footprinting, and network discovery through the W2-PM3 and W2-PM5 modules. Maltego was installed and configured, then used to investigate networkwalks.com and identify related email addresses, while Zenmap was used to discover active devices on my own local network and visualize the observed topology.

These exercises demonstrated that meaningful security information can be obtained before any exploitation is attempted. They also reinforced the importance of distinguishing between information exposure, security-relevant observations, and confirmed vulnerabilities. Professional security testing requires accurate evidence, scope control, and clear documentation of both findings and limitations.

The next step in a controlled penetration-testing workflow would be to use the documented reconnaissance and scanning results to guide further authorized assessment, subject to the rules and scope defined by the lab or client.

## 11. Submission Checklist

☐  the actual Maltego screenshots and graph evidence.

☐  the actual Windows ipconfig screenshot.

☐ the actual Zenmap scan configuration and results.

☐ the actual Zenmap topology screenshot/export.

☐ Verify that all IP addresses, MAC addresses, the networkwalks.com domain, email results, and observations match your evidence.

☐ Rabi Chaudhary, B082-Networkwalks , PENETRATION-TESTING REPORT
, and 24 August 2026.

LinkedIn:https://lnkd.in/p/gc-jC7un

## 📌 Project Information

Program Name: Cybersecurity program at Networkwalks | Week: 02 | Repository: GitHub


— End of Report —
