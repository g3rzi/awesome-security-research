# 📑 Articles

A curated collection of **vulnerability research articles and blog posts**.  
This file contains the **full list** of articles — the main [README](README.md) only highlights selected ones.


---   

## 📝 Table of Contents
- [AI](#AI)
- [Windows](#-windows)
- [Linux](#-linux)
- [Kubernetes & Cloud](#%EF%B8%8F-kubernetes--cloud)
- [Containers](#-containers)
- [Android & Mobile](#-android--mobile)
- [Web](#web)
- [Bug Bounty](#bug-bounty)
- [Identity](#-identity)
- [Supply Chain & Secrets](#-supply-chain--secrets)
- [Memory & Exploitation](#-memory--exploitation)
- [Cryptography](#-cryptography)
- [Miscellaneous](#-miscellaneous)

---  

## AI  
- [security researchers are doomed.](https://www.linkedin.com/pulse/security-researchers-doomed-roni-carta-1roze/?trackingId=DprtY12rc3hOC%2BNz79cPSQ%3D%3D) by Roni Carta, August 13, 2026  
- [Building An Ai Based Vulnerability Detection Workflow](https://blog.cykor.kr/2026/06/Building-an-AI-Based-Vulnerability-Detection-Workflow) by CyKor, Korea University Hacking Club, Jun 1, 2026  ([tweet](https://x.com/CyKorKU/status/2061320972700147765?s=20))  
- [Finding Zero-Days with Any Model](https://www.provos.org/p/finding-zero-days-with-any-model/) by Niels Provos, Apr 29, 2026   
- [Olama Path Traversal - CVE-2026-7020](https://davidrochester.com/posts/cve-2026-7020/) by David Rochester, Apr 25, 2026
- [The Boy That Cried Mythos: Verification is Collapsing Trust in Anthropic](https://www.flyingpenguin.com/the-boy-that-cried-mythos-verification-is-collapsing-trust-in-anthropic/) by Davi Ottenheimer, Apr 13, 2026  
- [Jenny was a Friend of Mine - MCPs and Friends](https://blog.zsec.uk/bullyingllms/) by Andy Gill, Apr 4, 2026  
- [Enhancing your Vulnerability Research LLM Agent](https://www.linkedin.com/pulse/enhancing-your-vulnerability-research-llm-agent-andrea-b-inume/) by Andrea B, March 31, 2026
- [Needle in the haystack: LLMs for vulnerability research](https://devansh.bearblog.dev/needle-in-the-haystack/) (🔥) by Devansh Batham, Mar 9, 2026  
- [Caught in the Hook: RCE and API Token Exfiltration Through Claude Code Project Files | CVE-2025-59536 | CVE-2026-21852](https://research.checkpoint.com/2026/rce-and-api-token-exfiltration-through-claude-code-project-files-cve-2025-59536/) by Aviv Donenfeld and Oded Vanunu, Feb 25, 2026  
- [N8Scape (Pyodide sandbox escape): 9.9 Critical Post-Auth RCE in n8n (CVE-2025-68668)](https://www.cyera.com/research-labs/n8scape-pyodide-sandbox-escape-9-9-critical-post-auth-rce-in-n8n-cve-2025-68668) by Vladimir Tokarev Ofek Itach, Jan 13, 2026
- [BodySnatcher (CVE-2025-12420): A Broken Authentication and Agentic Hijacking Vulnerability in ServiceNow](https://appomni.com/ao-labs/bodysnatcher-agentic-ai-security-vulnerability-in-servicenow/) by Appomni, Jan 13, 2026  
- [Ni8mare  -  Unauthenticated Remote Code Execution in n8n (CVE-2026-21858)](https://www.cyera.com/research-labs/ni8mare-unauthenticated-remote-code-execution-in-n8n-cve-2026-21858) by Dor Attias, Jan 7, 2026  
- [Securing Perplexity’s AI Browser from a One-Click UXSS](https://www.hacktron.ai/blog/perplexity-comet-uxss) by s1r1us and sudi, November 24, 2025  
- [Anatomy of an LLM RCE](https://www.cyberark.com/resources/threat-research-blog/anatomy-of-an-llm-rce) (🔥) by Shaked Reiner, Oct 28, 2024  


## 🪟 Windows   
- [BTR Reforged: Weaponizing Defender’s Remediation Driver as a Kernel Operation Primitive](https://research.checkpoint.com/2026/btr-reforged-weaponizing-defenders-remediation-driver-as-a-kernel-operation-primitive/) by  Jiří Vinopal (@vinopaljiri), August 20, 2026
- [SCCM-CVE-2026-47301-Remote-Code-Execution-Exploit](https://github.com/omribaso/sccm-cve-2026-47301-remote-code-execution-exploit) by Omri Baso, August 3, 2026  
- [CVE-2026-40369: Twelve Bytes to Escape the Browser Sandbox](https://voidsec.com/cve-2026-40369-browser-sandbox-escape/) by voidsec, May 20, 2026  
- [0x00 - Introduction to Windows Kernel Exploitation](https://wetw0rk.github.io/posts/0x00-introduction-to-windows-kernel-exploitation/) by Milton V (wetw0rk), Mar 17, 2026  
- [Microsoft Windows Cloud Files Minifilter TOCTOU Privilege Escalation](https://blog.exodusintel.com/2025/10/20/microsoft-windows-cloud-files-minifilter-toctou-privilege-escalation/) by Michele Campa, Oct 20, 2025
- [Dynamic Debugging of dotnet Without Source Code](https://pulsesecurity.co.nz/articles/dotnet-dynamic-analysis) by Denis Andzakovic, May 15, 2023  
- [Finding Running RPC Server Information with NtObjectManager](https://www.tiraniddo.dev/2022/06/finding-running-rpc-server-information.html) by James Forshaw, Jun 26, 2022  
- [Abusing Arbitrary File Deletes to Escalate Privilege and Other Great Tricks](https://www.zerodayinitiative.com/blog/2022/3/16/abusing-arbitrary-file-deletes-to-escalate-privilege-and-other-great-tricks) (🔥) by Simon Zuckerbraun, ,March 17, 2022  
- [Windows Drivers Reverse Engineering Methodology](https://voidsec.com/windows-drivers-reverse-engineering-methodology/) by voidsec, Jan 20, 2022  
- [Pentester’S Windows NTFS Tricks Collection](https://sec-consult.com/blog/detail/pentesters-windows-ntfs-tricks-collection/)
- [Offensive Windows IPC Internals 2: RPC](https://csandker.io/2021/02/21/Offensive-Windows-IPC-2-RPC.html#the-series) by [Carsten Sandker](https://x.com/0xcsandker), Feb 21, 2021  
- [Offensive Windows IPC Internals 1: Named Pipes](https://csandker.io/2021/01/10/Offensive-Windows-IPC-1-NamedPipes.html) by [Carsten Sandker](https://x.com/0xcsandker), Jan 10, 2021  
- [Zerologon: Unauthenticated domain controller compromise by subverting Netlogon cryptography (CVE-2020-1472) (PDF)](https://cybersecurity.bureauveritas.com/uploads/whitepapers/Zerologon.pdf) (🔥) by Tom Tervoort (Secura), Sep, 2020  
- [Windows Exploitation](https://web.archive.org/web/20200507040017/https://fullpwnops.com/windows-exploitation-pathway.html) by [Fu11Shade](https://web.archive.org/web/20200713114317/https://github.com/fullshade/), May, 2020  
- [Beware of the GIF: Account Takeover Vulnerability in Microsoft Teams](https://www.cyberark.com/resources/threat-research-blog/beware-of-the-gif-account-takeover-vulnerability-in-microsoft-teams) by Omer Tsarfati, Apr 27, 2020
- [Calling Local Windows RPC Servers from .NET](https://googleprojectzero.blogspot.com/2019/12/calling-local-windows-rpc-servers-from.html) by James Forshaw, Decemeber 17, 2019
- [Windows‌ ‌Exploitation‌ ‌Tricks:‌ ‌Spoofing‌ ‌Named‌ ‌Pipe‌ ‌Client‌ ‌PID](https://googleprojectzero.blogspot.com/2019/09/windows-exploitation-tricks-spoofing.html) by James Forshaw, Sep 25, 2019‌
- [The Definitive Guide on Win32 to NT Path Conversion](https://googleprojectzero.blogspot.com/2016/02/the-definitive-guide-on-win32-to-nt.html) Feb 29, 2016  
- [WATCHING THE WATCHDOG: PROTECTING KERBEROS AUTHENTICATION WITH NETWORK MONITORING (PDF)](https://blackhat.com/docs/eu-15/materials/eu-15-Beery-Watching-The-Watchdog-Protecting-Kerberos-Authentication-With-Network-Monitoring-wp.pdf) by Tal Be’ery and Michael Cherny, Nov 2015  


### Privilege Escalation  
- [PhantomRPC: A new privilege escalation technique in Windows RPC](https://securelist.com/phantomrpc-rpc-vulnerability/119428/) by Haidar Kabibo, Apr 26, 2026  
- [CVE-2026-20817 - Windows Error Reporting Service EoP](https://itm4n.github.io/cve-2026-20817-wersvc-eop/) by Clément Labro(itm4n), March 22, 2026  
- [RIP RegPwn (CVE-2026-24291)](https://www.mdsec.co.uk/2026/03/rip-regpwn/) by Filip Dragovic (MDSec), March 13, 2026
- [Total Recall – Retracing Your Steps Back to NT AUTHORITY\SYSTEM](https://www.mdsec.co.uk/2026/02/total-recall-retracing-your-steps-back-to-nt-authoritysystem/) by Filip Dragovic (MDSec), Feb 27, 2026  
- [Who’s on the Line? Exploiting RCE in Windows Telephony Service](https://swarm.ptsecurity.com/whos-on-the-line-exploiting-rce-in-windows-telephony-service/) by Sergey Bliznyuk (PT Swarm), Jan 19, 2026  
- [Windows LPE Bug Hunting, Served by the Team’s Youngest: Part 1 (EN) ](https://hackyboiz.github.io/2025/12/28/banda/WHS3-bughunting/en/), Dec 28, 2025  
- [The Guest Who Could: Exploiting LPE in VMWare Tools](https://swarm.ptsecurity.com/the-guest-who-could-exploiting-lpe-in-vmware-tools/) by Sergey Bliznyuk (PT Swarm), Jul 22, 2025   
- [Hijacking the Windows "MareBackup" Scheduled Task for Privilege Escalation](https://itm4n.github.io/hijacking-the-windows-marebackup-scheduled-task-for-privilege-escalation/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), May 20, 2025  
- [A Practical Guide to PrintNightmare in 2024](https://itm4n.github.io/printnightmare-exploitation/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Jan 28, 2024  
- [From NETWORK SERVICE to SYSTEM](https://decoder.cloud/2020/05/04/from-network-service-to-system/) by [decoder](https://x.com/decoder_it), May 4, 2020
- [Faxing Your Way to SYSTEM — Part Two](https://windows-internals.com/faxing-your-way-to-system/) (🔥🔥) by [Yarden Shafir](https://x.com/yarden_shafir) & [Alex Ionescu](https://x.com/aionescu), Apr 30, 2020  - [Faxhell tool](https://github.com/ionescu007/faxhell)  
- [Windows DLL Hijacking (Hopefully) Clarified](https://itm4n.github.io/windows-dll-hijacking-clarified/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 24, 2020  
- [CVE-2020-0729: Remote Code Execution Through .LNK Files](https://www.zerodayinitiative.com/blog/2020/3/25/cve-2020-0729-remote-code-execution-through-lnk-files) by Trend Micro Research Team, March 26, 2020
- [CVE-2020-0863 - An Arbitrary File Read Vulnerability in Windows Diagnostic Tracking Service](https://itm4n.github.io/cve-2020-0863-windows-diagtrack-info-disclo/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), March 18, 2020  
- [CVE-2020-0787 - Windows BITS - An EoP Bug Hidden in an Undocumented RPC Function](https://itm4n.github.io/cve-2020-0787-windows-bits-eop/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), March 11, 2020  
- [From dropbox(updater) to NT AUTHORITY\SYSTEM](https://decoder.cloud/2019/12/18/from-dropboxupdater-to-nt-authoritysystem/) by [decoder](https://x.com/decoder_it), December 18, 2019  
- [Windows Privilege Escalation - DLL Proxying](https://itm4n.github.io/dll-proxying/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 18, 2019  

### Symbolic Links  
- [Piping Hot Fortinet Vulnerabilities (PDF)](https://pentera.io/wp-content/uploads/2024/11/pentera_labs_fortinet_cves-1.pdf) by Nir Chacko, November 2024
- [Breaking Barriers and Assumptions: Techniques for Privilege Escalation on Windows: Part 2](https://www.zerodayinitiative.com/blog/2024/7/30/breaking-barriers-and-assumptions-techniques-for-privilege-escalation-on-windows-part-2) by Michael DePlante and Nicholas Zubrisky, July 31, 2024  
- [Breaking Barriers and Assumptions: Techniques for Privilege Escalation on Windows: Part 1](https://www.zerodayinitiative.com/blog/2024/7/29/breaking-barriers-and-assumptions-techniques-for-privilege-escalation-on-windows-part-1) by Michael DePlante and Nicholas Zubrisky, July 30, 2024  
- [Avast Anti-Virus privileged arbitrary file create on virus quarantine (CVE-2023-1585 and CVE-2023-1587)](https://the-deniss.github.io/posts/2023/04/26/avast-privileged-arbitrary-file-create-on-quarantine.html) by Denis Skvortcov, April 26, 2023
- [Breaking Docker Named Pipes SYSTEMatically: Docker Desktop Privilege Escalation – Part 2](https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-2) by Eviatar Gerzi, Apr 19, 2023
- [Breaking Docker Named Pipes SYSTEMatically: Docker Desktop Privilege Escalation – Part 1](https://www.cyberark.com/resources/threat-research-blog/breaking-docker-named-pipes-systematically-docker-desktop-privilege-escalation-part-1) by Eviatar Gerzi, Feb 2, 2023  
- [Breaking Antivirus: Arbitrary file deletion using Symbolic link](https://nixhacker.com/breaking-antivirus-arbitrary-delete-using-symbolic-link/) Apr 28, 2020  
- [An introduction to privileged file operation abuse on Windows](https://offsec.almond.consulting/intro-to-file-operation-abuse-on-Windows.html) by @clavoillotte
- [Avira Optimizer Local Privilege Escalation](https://enigma0x3.net/2019/08/29/avira-optimizer-local-privilege-escalation/) by enigma0x3, August 29, 2019  
- [CVE-2019-13382: Local Privilege Escalation in SnagIt](https://enigma0x3.net/2019/07/24/cve-2019-13382-privilege-escalation-in-snagit/) by enigma0x3, July 24, 2019  
- [CVE-2019-13142: Razer Surround 1.1.63.0 EoP](https://enigma0x3.net/2019/07/05/cve-2019-13142-razer-surround-1-1-63-0-eop/) by enigma0x3, July 5, 2019
- [Avira VPN (2.15.2.28160) Elevation of Privilege through Insecure Update location](https://enigma0x3.net/2019/03/20/avira-vpn-2-15-2-28160-elevation-of-privilege-through-insecure-update-location/) by enigma0x3, March 20, 2019
- [Razer Synapse 3 Elevation of Privilege](https://enigma0x3.net/2019/01/) by enigma0x3, January 21, 2019  
  
  
---  

## 🐧 Linux  
- [Off By !: Exploiting a Use-after-Free in the Linux Kernel - CVE-2026-23111.](https://blog.exodusintel.com/2026/06/08/off-by-exploiting-a-use-after-free-in-the-linux-kernel/) by Oliver Sieber, Jun 8, 2026  
- [Copy Fail: 732 Bytes to Root on Every Major Linux Distribution](https://xint.io/blog/copy-fail-linux-distributions) by Xint Code Research Team, Apr 29, 2026  
- [CVE-2021-22555: Turning \x00\x00 into 10000$](https://google.github.io/security-research/pocs/linux/cve-2021-22555/writeup.html) by Andy Nguyen (theflow@), 2021    
--- 

## ☁️ Kubernetes & Cloud   
- [CVE-2026-76092: How I Discovered a Critical Vulnerability in Docker MCP with a CVSS 9.2](https://gikaku.net/2026/08/20/cve-2026-76092/) by HE WEI, August 20, 2026
- [Red Hat CVE-2026-63622: libvirt swtpm symlink privilege escalation](https://gikaku.net/2026/08/12/cve-2026-63622/) by HE WEI, August 12, 2026  
- [CosmosEscape: Taking Over Every Database in Azure Cosmos DB](https://www.wiz.io/blog/cosmosescape-taking-over-every-database-in-azure-cosmos-db) (🔥) by Yuval Avrahami and Lior Maman, July 30, 2026  
- [StubZero: $148,337 RCE in Google Cloud Production](https://brutecat.com/articles/google-cloud-rce/) by Arvin Shivram, May 22, 2026 
- [CVE-2026-2006: Encoding bug in PostgreSQL pgcrypto leads to Remote Code Execution](https://www.zeroday.cloud/blog/postgresql-cve-2026-2005-deep-dive) by Team Bugz Bunnies, May 4, 2026  
- [Kicking the Bucket: Critical RCE and Cross-Tenant Exploits in 3 Different GCP Products](https://focalsecurity.io/blog/kicking-the-bucket-gcp-cross-tenant/) by Omer Amiad, Apr 14, 2026  
- [Mitigating Bucket Squatting in Google Cloud](https://focalsecurity.io/blog/mitigating-bucket-squatting-gcp/) by Omer Amiad, Apr 14, 2026  
- [Double Agents: Exposing Security Blind Spots in GCP Vertex AI](https://unit42.paloaltonetworks.com/double-agents-vertex-ai/) by Ofir Shaty, Mar 31, 2026
- [AppArmor and Seccomp in Kubernetes: What the Docs Don’t Tell You](https://platformwale.blog/2026/03/20/apparmor-and-seccomp-in-kubernetes-what-the-docs-dont-tell-you/) March 20, 2026  
- [Unpatchable Vulnerabilities of Kubernetes: CVE-2020-8561](https://securitylabs.datadoghq.com/articles/unpatchable-kubernetes-vulnerabilities-cve-2020-8561/) by Rory McCune, March 27, 2026
- [Kubernetes Remote Code Execution Via Nodes/Proxy GET Permission](https://grahamhelton.com/blog/nodes-proxy-rce) by Graham Helton, Jan 26, 2026
- [What a Cluster: Local Volumes Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-local-volumes-command-injection-vulnerability-rce-system-privileges) by Tomer Peled, March 13, 2024
- [Azure HDInsight: The Sequel – Unveiling 3 New Vulnerabilities That Could Have Led to Privilege Escalations and Denial of Service](https://orca.security/resources/blog/azure-hd-insight-vulnerabilities-privilege-escalation/) by Lidor Ben Shitrit (Orca), Feb 6, 2024
- [ModeLeak: Privilege Escalation to LLM Model Exfiltration in Vertex AI](https://unit42.paloaltonetworks.com/privilege-escalation-llm-model-exfil-vertex-ai/) by Ofir Balassiano and Ofir Shaty, Nov 12, 2024  
- [Can't Be Contained: Finding a Command Injection Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-critical-vulnerability-command-injection) by Tomer Peled, September 13, 2023
- [Azure HDInsight Riddled With XSS Vulnerabilities via Apache Services](https://orca.security/resources/blog/cross-site-scripting-vulnerabilities-in-apache-services-azure-hd-insight/) by Lidor Ben Shitrit (Orca), Sep 13, 2023
- [Two XSS Vulnerabilities in Azure with Embedded postMessage IFrames](https://orca.security/resources/blog/examining-two-xss-vulnerabilities-in-azure-services/) by Lidor Ben Shitrit (Orca), Jun 14, 2023
- [Azure DevOps CICD Pipelines - Command Injection with Parameters, Variables and a discussion on Runner hijacking](https://pulsesecurity.co.nz/advisories/Azure-Devops-Command-Injection) by Sana Oshika, May 1, 2023
- [Super FabriXss: From XSS to an RCE in Azure Service Fabric Explorer by Abusing an Event Tab Cluster Toggle (CVE-2023-23383)](https://orca.security/resources/blog/super-fabrixss-azure-vulnerability/) by Lidor Ben Shitrit (Orca), Mar 30, 2023   
- [Mitigating RBAC-Based Privilege Escalation in Popular Kubernetes Platforms](https://unit42.paloaltonetworks.com/kubernetes-privilege-escalation/) by Yuval Avrahami, January 27, 2023  
- [Authenticated SSRF Vulnerability on Azure API Management Service](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-api-management/) by Lidor Ben Shitrit (Orca), Jan 17, 2023  
- [Unauthenticated SSRF Vulnerability on Azure Functions](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-functions-app/) by Lidor Ben Shitrit (Orca), Jan 17, 2023
- [Unauthenticated SSRF Vulnerability on Azure Digital Twins Explorer](https://orca.security/resources/blog/ssrf-vulnerabilities-azure-digital-twins/) by Lidor Ben Shitrit (Orca), Jan 17, 2023
- [How Orca Found Server-Side Request Forgery (SSRF) Vulnerabilities in Four Different Azure Services](https://orca.security/resources/blog/ssrf-vulnerabilities-in-four-azure-services/) by Lidor Ben Shitrit (Orca), Jan 17, 2023  
- [CosMiss: Azure Cosmos DB Notebook Remote Code Execution Vulnerability](https://orca.security/resources/blog/cosmiss-vulnerability-azure-cosmos-db/) by Lidor Ben Shitrit (Orca), Nov 1, 2022
- [All Roads leads to GKE's Host : 4+ Ways to Escape (PDF)](https://media.defcon.org/DEF%20CON%2030/DEF%20CON%2030%20presentations/Billy%20Jheng%20%20%20Muhammad%20Alifa%20Ramdhan%20-%20All%20Roads%20leads%20to%20GKEs%20Host%20%204%2B%20Ways%20to%20Escape.pdf) by Billy and Ramdhan, Oct 20, 2022  
- [FabriXss (CVE-2022-35829): How We Managed to Abuse a Custom Role User Using CSTI and Stored XSS in Azure Fabric Explorer ](https://orca.security/resources/blog/fabrixss-vulnerability-azure-fabric-explorer/) by Lidor Ben Shitrit (Orca) and Roee Sagi, Oct 19, 2022
- [Supply Chain Attack: CTX Account Takeover and PHPass Hijack Explained](https://orca.security/resources/blog/python-supply-chain-attack-ctx-phpass/) by Lidor Ben Shitrit (Orca), Jun 13, 2022  
- [Kubernetes Pod Escape Using Log Mounts](https://www.aquasec.com/blog/kubernetes-security-pod-escape-log-mounts/) by Daniel Sagi (from Aqua)   
- [Dirty DAG: New Vulnerabilities in Azure Data Factory’s Apache Airflow Integration](https://unit42.paloaltonetworks.com/azure-data-factory-apache-airflow-vulnerabilities/) by Ofir Balassiano and David Orlovsky (Palo)  
- [SynLapse – Technical Details for Critical Azure Synapse Vulnerability](https://orca.security/resources/blog/synlapse-critical-azure-synapse-analytics-service-vulnerability/) by Tzah Pahima
- [Container breakout: CAP_SYS_ADMIN via Creating a cgroup and using unshare utility](https://pswalia2u.medium.com/container-breakout-cap-sys-admin-via-creating-a-cgroup-daf8e4c7767f) by n00, May 6, 2022  
- [Kubernetes container runtime CRI-O has make-me-root flaw](https://www.theregister.com/2022/03/15/cr8escape_container_runtime_bug/) by Jessica Lyons, March 15, 2022  
- [Container Escape to Shadow Admin: GKE Autopilot Vulnerabilities](https://unit42.paloaltonetworks.com/gke-autopilot-vulnerabilities/) by Yuval Avrahami, March 8, 2022
- [Oracle Server Side Request Forgery (SSRF) Metadata](https://orca.security/resources/blog/oracle-server-side-request-forgery-ssrf-attack-metadata/) by Lidor Ben Shitrit (Orca), Feb 8, 2022  
- [Finding Azurescape – Cross-Account Container Takeover in Azure Container Instances](https://unit42.paloaltonetworks.com/azure-container-instances/) by Yuval Avrahami, September 9, 2021
- [Escaping Virtualized Containers (PDF)](https://i.blackhat.com/USA-20/Thursday/us-20-Avrahami-Escaping-Virtualized-Containers.pdf) by Yuval Avrahami, May 14, 2021  
- [Gaining Persistency on Vulnerable Lambdas](https://unit42.paloaltonetworks.com/gaining-persistency-vulnerable-lambdas/) by Yuval Avrahami, September 2, 2019
- [Securing Jenkins: Active Directory and LDAP Services in a Jenkins Environment](https://www.cyberark.com/resources/threat-research-blog/securing-jenkins-active-directory-and-ldap-services-in-a-jenkins-environment) by Nimrod Stoler, Jan 29, 2019  
- [Tripping the Jenkins Main Security Circuit-Breaker: An Inside Look at Two Jenkins Security Vulnerabilities](https://www.cyberark.com/resources/threat-research-blog/tripping-the-jenkins-main-security-circuit-breaker-an-inside-look-at-two-jenkins-security-vulnerabilities) by Nimrod Stoler, Oct 12, 2018  
- [Jenkins Plugins – Aladdin’s Lamp and the Sultan of Threats](https://www.cyberark.com/resources/threat-research-blog/jenkins-plugins-aladdin-s-lamp-and-the-sultan-of-threats) by Nimrod Stoler, Sep 26, 2018  
- [CyberArk Labs Research: Securing Jenkins Java Web Start Agents](https://www.cyberark.com/resources/threat-research-blog/cyberark-labs-research-securing-jenkins-java-web-start-agents) by Nimrod Stoler, Sep 11, 2018   
- [Configuring and Securing Credentials in Jenkins](https://www.cyberark.com/resources/threat-research-blog/configuring-and-securing-credentials-in-jenkins) by Nimrod Stoler, Aug 15, 2018
- [False Boundaries and Arbitrary Code Execution](https://forums.grsecurity.net/viewtopic.php?f=7&t=2522) by spender, Jan 2, 2011  
  
### by Wiz  
- [Securing GitHub: Wiz Research uncovers Remote Code Execution in GitHub.com and GitHub Enterprise Server (CVE-2026-3854)](https://www.wiz.io/blog/github-rce-vulnerability-cve-2026-3854) by Sagi Tzadik, Apr 28, 2026  
- [CodeBreach: Infiltrating the AWS Console Supply Chain and Hijacking AWS GitHub Repositories via CodeBuild](https://www.wiz.io/blog/wiz-research-codebreach-vulnerability-aws-codebuild) by Yuval Avrahami, Jan 15, 2026  
- [RediShell: Critical Remote Code Execution Vulnerability (CVE-2025-49844) in Redis, 10 CVSS score](https://www.wiz.io/blog/wiz-research-redis-rce-cve-2025-49844) by Benny Isaacs and Nir Brakha, October 6, 2025  
- [Breaking NVIDIA Triton: CVE-2025-23319 - A Vulnerability Chain Leading to AI Server Takeover](https://www.wiz.io/blog/nvidia-triton-cve-2025-23319-vuln-chain-to-ai-server)  
- [NVIDIAScape - Critical NVIDIA AI Vulnerability: A Three-Line Container Escape in NVIDIA Container Toolkit (CVE-2025-23266)](https://www.wiz.io/blog/nvidia-ai-vulnerability-cve-2025-23266-nvidiascape), July 17, 2025  
- [How Wiz found a Critical NVIDIA AI vulnerability:  Deep Dive into a container escape (CVE-2024-0132)](https://www.wiz.io/blog/nvidia-ai-vulnerability-deep-dive-cve-2024-0132)  
- [IngressNightmare: CVE-2025-1974 - 9.8 Critical Unauthenticated Remote Code Execution Vulnerabilities in Ingress NGINX](https://www.wiz.io/blog/ingress-nginx-kubernetes-vulnerabilities)  
- [Wiz Research finds architecture risks that may compromise AI-as-a-Service providers and consequently risk customer data; works with Hugging Face on mitigations](https://www.wiz.io/blog/wiz-and-hugging-face-address-risks-to-ai-infrastructure)  
- [Probllama: Ollama Remote Code Execution Vulnerability (CVE-2024-37032) – Overview and Mitigations](https://www.wiz.io/blog/probllama-ollama-vulnerability-cve-2024-37032)  
- [GameOver(lay): Easy-to-exploit local privilege escalation vulnerabilities in Ubuntu Linux affect 40% of Ubuntu cloud workloads](https://www.wiz.io/blog/ubuntu-overlayfs-vulnerability)  
- [#BrokenSesame: Accidental ‘write’ permissions to private registry allowed potential RCE to Alibaba Cloud Database Services](https://www.wiz.io/blog/brokensesame-accidental-write-permissions-to-private-registry-allowed-potential-r)  
- [BingBang: How a simple developer mistake could have led to Bing.com takeover](https://www.wiz.io/blog/bingbang)  
- [Wiz Research discovers "ExtraReplica"— a cross-account database vulnerability in Azure PostgreSQL](https://www.wiz.io/blog/wiz-research-discovers-extrareplica-cross-account-database-vulnerability-in-azure-postgresql)  
- [ChaosDB explained: Azure's Cosmos DB vulnerability walkthrough](https://www.wiz.io/blog/chaosdb-explained-azures-cosmos-db-vulnerability-walkthrough)  

--- 

## 🐳 Containers  
- [Container Escape via Inference: CVE-2026-5817 / CVE-2026-5843](https://davidrochester.com/posts/container-escape-via-inference/) by David Rochester, May 20, 2026   
- [Container Escape Telemetry, Part 6: TeamPCP and What the Lab Predicted](https://catscrdl.io/blog/containerescapetelemetry/teampcp/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry, Part 5: Tuning eBPF Tools From Defaults to Detection](https://catscrdl.io/blog/containerescapetelemetry/tuning/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry, Part 4: Volume, Signal-to-Noise, and Choosing a Tool](https://catscrdl.io/blog/containerescapetelemetry/production/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry, Part 3: What Each Tool Actually Captured](https://catscrdl.io/blog/containerescapetelemetry/deepdives/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry, Part 2: Methodology and Tool Architecture](https://catscrdl.io/blog/containerescapetelemetry/methodology/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry, Part 1: Isolation Primitives and the eBPF Observability Model](https://catscrdl.io/blog/containerescapetelemetry/isolation/) by Daniel Wyleczuk-Stern, March 31, 2026  
- [Container Escape Telemetry: Series Overview](https://catscrdl.io/blog/containerescapetelemetry/intro/) by Daniel Wyleczuk-Stern, March 31, 2026
- [Exploiting Docker Model Runner’s OCI Authentication Flow](https://davidrochester.com/posts/cve-2026-33990/) by David Rochester, Mar 29, 2026 
- [Quantifying Frontier LLM Capabilities for Container Sandbox Escape (PDF)](https://arxiv.org/pdf/2603.02277) by [Arxiv](https://arxiv.org/abs/2603.02277) (academic), Mar 1, 2026
- [Container Escape via /proc/sys/kernel/hotplug](https://github.com/Asbatel/hotplug-container-escape) by Asbatel, Feb 11, 2026
- [Google Cloud Shell Container Escape](https://medium.com/@win3zz/google-cloud-shell-container-escape-b69ffb46b5df) by Bipin Jitiya, Dev 14, 2025  
- [HEXACON 2025 - CUDA de Grâce by Valentina Palmiotti & Samuel Lovejoy](https://docs.google.com/presentation/d/1FgfURpMyHhnflGWtxeq8ClPPaB5ZDCzT/edit?slide=id.p1#slide=id.p1) (🔥)  by Valentina Palmiotti & Samuel Lovejoy, Nov 24, 2025 - 🎥 [Talk](https://www.youtube.com/watch?v=Lvz2_ZHj3lo)  
- [Docker Container Escape by Exploiting CGroups](https://medium.com/@indigoshadowwashere/docker-container-escape-by-exploiting-cgroups-e52efab898d3) by Indigo Shadow, Nov 16, 2025  
- [Fun-reliable side-channels for cross-container communication](https://h4x0r.org/funreliable/) by Ivan, Nov 12, 2025
- [container escape via "masked path" abuse due to mount race conditions](https://github.com/opencontainers/runc/security/advisories/GHSA-9493-h29p-rfm2) Nov 5, 2025  
- [container escape with malicious config due to /dev/console mount and related races](https://github.com/opencontainers/runc/security/advisories/GHSA-qw9x-cqr3-wc7r) Nov 5, 2025  
- [container escape and denial of service due to arbitrary write gadgets and procfs write redirects](https://github.com/opencontainers/runc/security/advisories/GHSA-cgrx-mc8f-2prm) Nov 5, 2025  
- [runc container breakouts via procfs writes: CVE-2025-31133, CVE-2025-52565, and CVE-2025-52881](https://seclists.org/oss-sec/2025/q4/138) Nov 5, 2025  
- [Container Escape Techniques: Breaking Out of Docker, Kubernetes, and Beyond](https://danger-team.org/container-escape-techniques-breaking-out-of-docker-kubernetes-and-beyond/#what-are-containers-and-why-should-security-teams-care) by Rasoul, March 17, 2025  
- [Container Escapes 101 - Host memory meddling with ptrace](https://some-natalie.dev/container-escapes-ptrace/) by Natalie Somersall, Sep 5, 2025  
- [Exploit Notes - Docker Escape](https://exploit-notes.hdks.org/exploit/container/docker/docker-escape/) by hdks, Nov 2024  
- [Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/) by Yosef Yaakov and Bar Ben-Michael, July 18, 2024
- [Breaking Free: 26 Advanced Techniques to Escape Docker Containers](https://infosecwriteups.com/breaking-free-26-advanced-techniques-to-escape-docker-containers-530049816b55) by ElNiak  Apr 8, 2024
- [Reversing Windows Container, episode II: Silo](https://blog.quarkslab.com/reversing-windows-container-part-ii-silo-to-server-silo.html) by Lucas Di Martino, March 26, 2024  
- [Buildkit GRPC SecurityMode privilege check: Build-time container breakout (CVE-2024-23653)](https://labs.snyk.io/resources/cve-2024-23653-buildkit-grpc-securitymode-privilege-check/) by Rory McNamara, Jan 31, 2024 
- [Buildkit mount cache race: Build-time race condition container breakout (CVE-2024-23651)](https://labs.snyk.io/resources/cve-2024-23651-docker-buildkit-mount-cache-race/) by Rory McNamara, Jan 31, 2024 
- [Buildkit build-time container teardown arbitrary delete (CVE-2024-23652)](https://labs.snyk.io/resources/cve-2024-23652-buildkit-build-time-container-teardown-arbitrary-delete/) by Rory McNamara, Jan 31, 2024  
- [Vulnerability: runc process.cwd and leaked fds container breakout (CVE-2024-21626)](https://labs.snyk.io/resources/cve-2024-21626-runc-process-cwd-container-breakout/) by Rory McNamara, Jan 31, 2024
- [CVE-2022-0492 (Carpediem) explained](https://www.hackthebox.com/blog/cve-2022-04920-carpe-diem-explained) by [David Glance (CyberMnemosyne)](https://www.hackthebox.com/blog/author/CyberMnemosyne), Dec 26, 2023  
- [Reversing Windows Container, episode I: Silo](https://blog.quarkslab.com/reversing-windows-container-episode-i-silo.html) by Lucas Di Martino, Sep 21, 2023  
- [Docker Security – Step-by-Step Hardening (Docker Hardening)](https://reynardsec.com/en/docker-platform-security-step-by-step-hardening/) by ReynardSec, October 16, 2023  
- [A new method for container escape using file-based DirtyCred](https://starlabs.sg/blog/2023/07-a-new-method-for-container-escape-using-file-based-dirtycred/) by Choo Yi Kai, July 25, 2023  
- [Container breakout (overview)](https://sec.vnpt.vn/2023/07/container-breakout-overview) by Red Team, July 25, 2023
- [Understanding Windows Containers Communication](https://www.cyberark.com/resources/threat-research-blog/understanding-windows-containers-communication) by Eviatar Gerzi, Sep 7, 2022  
- [corCTF 2022 CoRJail: From Null Byte Overflow To Docker Escape Exploiting poll_list Objects In The Linux Kernel](https://syst3mfailure.io/corjail/) by D3vil, Aug 17, 2022
- [Breakout from the Seccomp Unconfined Container](https://tbhaxor.com/breakout-from-seccomp-unconfined-container/) by Gurkirat Singh, May 2, 2022  
- [Container escape using dirtypipe](https://terenceli.github.io/%E6%8A%80%E6%9C%AF/2022/03/19/container-escape-through-dirtypipe), March 19, 2022  
- [Escaping privileged containers for fun](https://pwning.systems/posts/escaping-containers-for-fun/) by Jordy Zomer, March 6, 2022  
- [New Linux Vulnerability CVE-2022-0492 Affecting Cgroups: Can Containers Escape?](https://unit42.paloaltonetworks.com/cve-2022-0492-cgroups/) by Yuval Avrahami, March 3, 2022
- [How Docker Made Me More Capable and the Host Less Secure](https://www.cyberark.com/resources/threat-research-blog/how-docker-made-me-more-capable-and-the-host-less-secure) by Alon Zahavi, Feb 8, 2022  
- [Container escape techniques](https://reaper.gitbook.io/my-penetration-test-guide/privilege-escalation/linux-privilege-escalation/container-escape-techniques)
- [hide the current process executable file](https://scrivano.org/posts/2022-12-21-hide-self-exe/) by Giuseppe Scrivano, Dec 21, 2021
- [Container Host Breakout – Part 2](https://tbhaxor.com/container-host-breakout-part-2/) by Gurkirat Singh, Sep 11, 2021    
- [Container Host Breakout – Part 1](https://tbhaxor.com/container-host-breakout-part-1/)  by Gurkirat Singh, Sep 11, 2021   
- [Container Breakout – Part 2](https://tbhaxor.com/container-breakout-part-2/) by Gurkirat Singh, Sep 10, 2021   
- [Container Breakout – Part 1](https://tbhaxor.com/container-breakout-part-1/) by Gurkirat Singh, Sep 10, 2021  
- [Container escape in 2021 (binfmt_misc) - PDF](https://conference.hitb.org/hitbsecconf2021sin/materials/D2T2%20-%20Ccntainer%20Escape%20in%202021%20-%20Li%20Qiang.pdf) by Li Qiang, Sep 2, 2021
- [The Real-Life Story of the First Mainframe Container Breakout](https://media.defcon.org/DEF%20CON%2029/DEF%20CON%2029%20presentations/Ian%20Coldwater%20Chad%20Rikansrud%20%28Bigendian%20Smalls%29%20-%20The%20Real-Life%20Story%20of%20the%20First%20Mainframe%20Container%20Breakout.pdf) by Ian Coldwater and Chad, Aug 5, 2021  
- [Microsoft Patched the Issue With Windows Containers That Enabled Silosca](https://unit42.paloaltonetworks.com/windows-container-escape-patch/) by Daniel Prizmant, Aug 5, 2021   
- [Siloscape: First Known Malware Targeting Windows Containers to Compromise Cloud Environments](https://unit42.paloaltonetworks.com/siloscape/) by Daniel Prizmant, June 7, 2021
- [Escaping Virtualized Containers (PDF)](https://i.blackhat.com/asia-20/Friday/asia-20-Yuval-Avrahami-Escaping-Virtualized-Containers.pdf) (🔥) by Yuval Avrahami, May 14, 2021 - 🎥 [Talk](https://www.youtube.com/watch?v=jFlqVe11eeM)  
- [Who Contains the Containers?](https://googleprojectzero.blogspot.com/2021/04/who-contains-containers.html) (🔥) by James Forshaw, April 1, 2021   
- [The Strange Case of How We Escaped the Docker Default Container](https://www.cyberark.com/resources/threat-research-blog/the-strange-case-of-how-we-escaped-the-docker-default-container) [archived](https://web.archive.org/web/20260514070933/https://www.cyberark.com/resources/threat-research-blog/the-strange-case-of-how-we-escaped-the-docker-default-container) by Nimrod Stoler and Gilad Reti, March 4, 2021
- [BitBucket Pipelines Kata Containers Virtual Machine Escape](https://blog.ajxchapman.com/posts/2021/02/28/kata-containers-escape.html) by [Alex Chapman](https://github.com/ajxchapman), Feb 28, 2021   
- [Towards Improving Container Security by Preventing Runtime Escapes (PDF)](https://www.osti.gov/servlets/purl/1890908), 2021  
- [Container Breakouts – Part 3: Docker Socket](https://blog.nody.cc/posts/container-breakouts-part3/) by Jan Harrie, July 30, 2020  
- [Container Breakouts – Part 2: Privileged Container](https://blog.nody.cc/posts/container-breakouts-part2/) by Jan Harrie, July 21, 2020  
- [Container Breakouts – Part 1: Access to root directory of the Host](https://blog.nody.cc/posts/container-breakouts-part1/) by Jan Harrie, July 15, 2020
- [Windows Server Containers Are Open, and Here's How You Can Break Out](https://unit42.paloaltonetworks.com/windows-server-containers-vulnerabilities/?pdf=print&lg=en&_wpnonce=49ce28271a) by Daniel Prizmant, July 15, 2020
- [Docker Container Breakout: Abusing SYS_MODULE capability!](https://blog.pentesteracademy.com/abusing-sys-module-capability-to-perform-docker-container-breakout-cf5c29956edd) by Nishant Sharma, May 6, 2020
- [Privileged Container Escape - Control Groups release_agent](https://blog.ajxchapman.com/posts/2020/11/19/privileged-container-escape.html) by [Alex Chapman](https://github.com/ajxchapman), Nov 19, 2020    
- [Privileged Container Escapes with Kernel Modules](https://xcellerator.github.io/posts/docker_escape/) by TheXcellerator, Sep 27, 2020  
- [Security Analysis of User Namespaces and Rootless Containers](https://d-nb.info/1222589206/34) by Anton Semjonov, Jan 2020  
- [What I Learned from Reverse Engineering Windows Containers](https://unit42.paloaltonetworks.com/what-i-learned-from-reverse-engineering-windows-containers/) by Daniel Prizmant, Dec 12, 2019
- [Understanding Docker container escapes](https://blog.trailofbits.com/2019/07/19/understanding-docker-container-escapes/) by Dominik Czarnota, July 19, 2019  
- [CVE-2019-11253: Kubernetes API Server JSON/YAML parsing vulnerable to resource exhaustion attack](https://github.com/kubernetes/kubernetes/issues/83253) by Rory McCune, Sep 27, 2019
- [AppArmor can be bypassed by a malicious image that specifies a volume at /proc](https://github.com/opencontainers/runc/issues/2128), Sep 22, 2019  
- [A Complendium of Container Escapes - PDF](https://i.blackhat.com/USA-19/Thursday/us-19-Edwards-Compendium-Of-Container-Escapes-up.pdf) (🔥) by Brandon Edwards and Nick Freeman from Capsule8, August 2019  
- [Breaking Out of rkt – 3 New Unpatched CVEs](https://unit42.paloaltonetworks.com/breaking-out-of-coresos-rkt-3-new-cves/) by Yuval Avrahami, May 30, 2019  
- [The Route to Root: Container Escape Using Kernel Exploitation](https://www.cyberark.com/resources/threat-research-blog/the-route-to-root-container-escape-using-kernel-exploitation) [archived(https://web.archive.org/web/20260330083248/https://www.cyberark.com/resources/threat-research-blog/the-route-to-root-container-escape-using-kernel-exploitation)] (🔥) by Nimrod Stoler, March 4, 2019
- [Breaking out of Docker via runC – Explaining CVE-2019-5736](https://unit42.paloaltonetworks.com/breaking-docker-via-runc-explaining-cve-2019-5736/) (🔥) by Yuval Avrahami, Feb 21, 2019
- [An Exercise in Practical Container Escapology](https://web.archive.org/web/20210425171222/https://capsule8.com/blog/practical-container-escape-exercise/) by Capsule8, Feb 21, 2019  
- [How I Hacked Play-with-Docker and Remotely Ran Code on the Host](https://www.cyberark.com/resources/secure-third-party-vendor-and-remote-access/how-i-hacked-play-with-docker-and-remotely-ran-code-on-the-host) [archived](https://web.archive.org/web/20260309063549/https://www.cyberark.com/resources/threat-research-blog/how-i-hacked-play-with-docker-and-remotely-ran-code-on-the-host) (🔥) by Nimrod Stoler, Jan 14, 2019  
- [Container Basics and Escapes](https://0xn3va.gitbook.io/cheat-sheets/container/overview/basics) by [0xn3va](https://github.com/0xn3va)
- [Container Breakout Vulnerabilities](https://www.container-security.site/attackers/container_breakout_vulnerabilities.html), by Rory McCune
- [Csw2016 wang docker_escapetechnology](https://www.slideshare.net/slideshow/csw2016-wang-dockerescapetechnology/60387867) by Wang, 2016  
- [Understanding and Hardening Linux Containers - PDF](https://www.nccgroup.com/media/eoxggcfy/_ncc_group_understanding_hardening_linux_containers-1-1.pdf) by NCC Group, Jun 29, 2016  
- [Abusing Privileged and Unprivileged Linux Containers - PDF](https://www.nccgroup.com/media/bjobstnx/_container_whitepaper.pdf) by NCC Group, Jun 29, 2016
- [PoC for Dirty COW (CVE-2016-5195)](https://github.com/scumjr/dirtycow-vdso) by scumjr, 2016  
- [Docker breakout exploit analysis (shocker)](https://medium.com/@fun_cuddles/docker-breakout-exploit-analysis-a274fff0e6b3) by Jen Andre, Jun 19, 2014
- [Shocker / Docker Breakout PoC](https://github.com/gabrtv/shocker) by Gabe Monroy, Jun 18, 2014
- [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c) by Sebastian Krahmer, Jun 18, 2014
- [Memory inside Linux containers](https://fabiokung.com/2014/03/13/memory-inside-linux-containers/) by Fabio Kung, March 13, 2014   


--- 

## 📱 Android & Mobile  

---
## Web  
- [The Internet Is Falling Down, Falling Down, Falling Down (cPanel & WHM Authentication Bypass CVE-2026-41940)](https://labs.watchtowr.com/the-internet-is-falling-down-falling-down-falling-down-cpanel-whm-authentication-bypass-cve-2026-41940/) by Sina Kheirkhah (@SinSinology), Apr 29, 2026  
- [Business, logic, and chains: unauthenticated RCE in Dell Wyse Management Suite](https://swarm.ptsecurity.com/business-logic-and-chains-unauthenticated-rce-in-dell-wyse-management-suite/) by Aleksandr Zhurnakov (PT Swarm), March 23, 2026  
- [GatewayToHeaven: Finding a Cross-Tenant Vulnerability in GCP's Apigee](https://omeramiad.com/posts/gatewaytoheaven-gcp-cross-tenant-vulnerability/) by Omer Amiad, Jan 28, 2026  
- [CVE-2026-23958 Compromises Admin Accounts on DataEase ; Enterprise BI at Risk](https://www.ox.security/blog/blog-dataease-cve-2026-23958-admin-takeover/) by Nir Zadok and Eyal Paz, Jan 21, 2026   
- [Do Smart People Ever Say They’re Smart? (SmarterTools SmarterMail Pre-Auth RCE CVE-2025-52691)](https://labs.watchtowr.com/do-smart-people-ever-say-theyre-smart-smartertools-smartermail-pre-auth-rce-cve-2025-52691/) by Piotr Bazydlo (@chudyPB) and Sina Kheirkhah (@SinSinology), Jan 8, 2026
- [Guest Post: How I Scanned all of GitHub’s “Oops Commits” for Leaked Secrets](https://trufflesecurity.com/blog/guest-post-how-i-scanned-all-of-github-s-oops-commits-for-leaked-secrets) by Sharon Brizinov, Jul, 2025 -> [Linkedin post](https://www.linkedin.com/posts/sharonbrizinov_how-i-scanned-all-of-githubs-oops-commits-activity-7345891171681906690-7DJV?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAVVCOcBn2W8cJUVEZYrwcQtiQOQeUkmp5E).    
- [Breaking Oracle’s Identity Manager: Pre-Auth RCE (CVE-2025-61757)](https://slcyber.io/research-center/breaking-oracles-identity-manager-pre-auth-rce/) by Adam Kues and Shubham Shah, November 20, 2025  
- [How I Found a Critical Password Reset Bug in the BB program(and Got $4,000)](https://medium.com/@s41n1k/how-i-found-a-critical-password-reset-bug-in-the-bb-program-and-got-4-000-a22fffe285e1)
- [Account Takeover via Password Reset without user interactions](https://gitlab.com/gitlab-org/gitlab/-/issues/436084)
- [Shockwave Identifies Web Cache Deception and Account Takeover Vulnerability affecting OpenAI's ChatGPT](https://www.shockwave.cloud/blog/shockwave-works-with-openai-to-fix-critical-chatgpt-vulnerability) by Gal Nagli, July 15, 2024  
- [CVE-2024-25153: Remote Code Execution in Fortra FileCatalyst](https://www.lrqa.com/en/cyber-labs/cve-2024-25153-remote-code-execution-in-fortra-filecatalyst/) by Tom Wedgbury, March 13, 2024
- [ChatGPT Account Takeover - Wildcard Web Cache Deception](https://nokline.github.io/bugbounty/2024/02/04/ChatGPT-ATO.html) (🔥) by [Harel](https://x.com/h4r3l), Feb 4, 2024  
- [Sandwich Attack UUIDv1](https://x.com/0xLupin/status/1745805050562105739) by [0xLupin](https://x.com/0xLupin), Jan 12, 2024
- [Hacking Chess.com and Accessing 50 Million Customer Records](https://samcurry.net/hacking-chesscom) by Sam Curry, Dec 16, 2020  
- [We Hacked Apple for 3 Months: Here’s What We Found](https://samcurry.net/hacking-apple) by Sam Curry, Oct 7, 2020  
- [Old but GOLD Dot Dot Slash to Get the Flag — Uber Microservice](https://ngailong.wordpress.com/2019/04/07/old-but-gold-dot-dot-slash-to-get-the-flag-uber-microservice/) by Ron Chan, April 7, 2019  
- [Tutorial One: Open Url Redirects](https://web.archive.org/web/20190523023839/https://zseano.com/tutorials/1.html) by Zseano, Sep 14, 2017   
- [Tutorials by zseano](https://web.archive.org/web/20190520052806/https://zseano.com/index.html) by Zseano, Sep 14, 2017
- [Web Cache Deception Attack](https://omergil.blogspot.com/2017/02/web-cache-deception-attack.html) (🔥) by Omer Gil, Feburary 27, 2017
---
## Bug Bounty
- [How I made $64k from deleted files — a bug bounty story](https://medium.com/@sharon.brizinov/how-i-made-64k-from-deleted-files-a-bug-bounty-story-c5bd3a6f5f9b) by Sharon Brizinov, Apr 22, 2025  
- [$10,500 Bounty: A Grammarly Account Takeover Vector](https://infosecwriteups.com/10-500-bounty-a-grammarly-account-takeover-vector-974ef90fb00a) by [Monika sharma](https://medium.com/@commanak46)
- [awesome-google-vrp-writeups](https://github.com/xdavidhu/awesome-google-vrp-writeups) by xdavidhu, 2020  
---

## 🌐 Identity  
- [One Token to rule them all - obtaining Global Admin in every Entra ID tenant via Actor tokens](https://dirkjanm.io/obtaining-global-admin-in-every-entra-id-tenant-with-actor-tokens/) by Dirk-jan Mollema, September 17, 2025    
- [Forging Passkeys: Exploring the FIDO2 / WebAuthn Attack Surface](https://nullpt.rs/forging-passkeys) by [vmfunc](https://x.com/vmfunc), June 20, 2025
- [WebAuthn Under Attack: How Trojans Can Compromise Your Credentials (PDF)](https://github.com/w3c/webauthn/files/12640140/WebAuthn.pdf) by Aditya Mitra and Anisha Ghosh, Sep 16, 2023 - [GitHub Issue ](https://github.com/w3c/webauthn/issues/1965)   
- [Bypassing Windows Hello Without Masks or Plastic Surgery](https://www.cyberark.com/resources/threat-research-blog/bypassing-windows-hello-without-masks-or-plastic-surgery) by Omer Tsarfati, Jul 17, 2023  
- [Abusing FIDO2 passkeys to take over Global Administrators in Entra ID](https://cybersecurity.bureauveritas.com/services/information-technology/pentesting-services/what-can-be-pentested/cloud-pentesting/abusing-fido2-passkeys) by Max Rozendaal  




### OAuth  
- [N8N: Shared Credentials and Account Takeover](https://www.imperva.com/blog/n8n-shared-credentials-and-account-takeover/) by Yohann Sillam, Mar 3, 2026  
- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025
- [Millions of Accounts Vulnerable due to Google’s OAuth Flaw](https://trufflesecurity.com/blog/millions-at-risk-due-to-google-s-oauth-flaw) by Dylan Ayrey, Jan 13, 2025 - 🎥 [Talk](https://www.youtube.com/watch?v=yIutY_X2FcU&t=19857s)   
- [Understanding OAuth 2.0 and its Common Vulnerabilities](https://www.vaadata.com/blog/understanding-oauth-2-0-and-its-common-vulnerabilities/) by Vaadata, January 9, 2025   
- [Account hijacking using “dirty dancing” in sign-in OAuth-flows](https://labs.detectify.com/writeups/account-hijacking-using-dirty-dancing-in-sign-in-oauth-flows/) (🔥) by Frans Rosén  
- [OAuth Non-Happy Path to ATO](https://blog.voorivex.team/oauth-non-happy-path-to-ato) by Omid Rezaei  
- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025
- [Third Party Services Takeover using Oauth Misconfiguration](https://infosecwriteups.com/third-party-services-takeover-using-oauth-misconfiguration-8888a0c1ad86) by Ronak Patel, Dec 13, 2024  
- [OAuth Account Hijacking via redirect_uri](https://infosecwriteups.com/oauth-account-hijacking-via-redirect-uri-ae8ca7a66930) by Ryan G. Cox, Dec 10, 2024  
- [The OAuth Oversight: When Configuration Errors Turn into Account Hijacks](https://medium.com/@ProwlSec/the-oauth-oversight-when-configuration-errors-turn-into-account-hijacks-5ed1f9c83d16) by ProwlSec, Nov 4, 2024
- [Uber - Navigating the Complexities of redirect_uri: A Bug Bounty Journey](https://www.novasecurity.co.nz/uber-navigating-the-complexities-of-redirect-uri-a-bug-bounty-journey/) by Ron Chan, Jun 14, 2024  
- [Writeup: Keycloak open redirect (CVE-2023-6927)](https://securityblog.omegapoint.se/en/writeup-keycloak-cve-2023-6927/) (🔥🔥) by Pontus Hanssen and Kasper Karlsson, January 11, 2024  
- [Google OAuth is Broken (Sort Of)](https://trufflesecurity.com/blog/google-oauth-is-broken-sort-of) (🔥) by Dylan Ayrey, December 15, 2023  
- [nOAuth: How Microsoft OAuth Misconfiguration Can Lead to Full Account Takeover](https://www.descope.com/blog/post/noauth) by Omer Cohen, June 20, 2023
- [OAuth 2.0 Hunting Methodology](https://github.com/KathanP19/HowToHunt/blob/master/OAuth/OAuth%202.0%20Hunting%20Methodology.md) by KathanP19, Sep 18, 2022  
- [OAuth 2.0 Vulnerabilities](https://0xn3va.gitbook.io/cheat-sheets/web-application/oauth-2.0-vulnerabilities) by 0xn3va
- [Make Redirection Evil Again: URL Parser Issues in OAuth](https://i.blackhat.com/asia-19/Fri-March-29/bh-asia-Wang-Make-Redirection-Evil-Again-wp.pdf) by Chinese University, March 29, 2019
- [[Google VRP] SSRF in Google Cloud Platform StackDriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/) by Ron Chan, Dec 19, 2019
- [[Uber] redirect_uri is difficult to do it right](https://ngailong.wordpress.com/2017/11/22/uber-redirect_uri-is-difficult-to-do-it-right/) (🔥) by Ron Chan, Nov 22, 2017
- [[Uber 8k Bug] Login CSRF + Open Redirect = Account Take Over](https://ngailong.wordpress.com/2017/08/07/uber-login-csrf-open-redirect-account-takeover/) by Ron Chan, August 7, 2017  
- [Facebook's Moves - OAuth redirect_uri bypass](https://www.evil.blog/2016/06/facebooks-moves-oauth-redirecturi-bypass.html) by Paulos Yibelo, June, 2016
- [Oauth 2.0 redirection bypass cheat sheet](https://nbsriharsha.blogspot.com/2016/04/oauth-20-redirection-bypass-cheat-sheet.html) by N B Sri Harsha, Apr, 2016
- [CSRF Vulnerability in OAuth 2.0 Client Implementations](https://web.archive.org/web/20140806042247/http://stephensclafani.com/2011/04/06/oauth-2-0-csrf-vulnerability/) by Stephen Sclafani, Apr 6, 2011  

### by Aviad Carmel from Salt  
- [Traveling with OAuth — Account Takeover on Booking.com](https://salt.security/blog/traveling-with-oauth-account-takeover-on-booking-com) (🔥) - 🎥 [Talk](https://www.youtube.com/watch?v=BxiL4Vf_umI)
- [Salt Labs exposes a new vulnerability in popular OAuth framework, used in hundreds of online services](https://salt.security/blog/a-new-oauth-vulnerability-that-may-impact-hundreds-of-online-services)  
- [Oh-Auth — Abusing OAuth to take over millions of accounts](https://salt.security/blog/oh-auth-abusing-oauth-to-take-over-millions-of-accounts)  
- [Security Flaws within ChatGPT Ecosystem Allowed Access to Accounts On Third-Party Websites and Sensitive Data](https://salt.security/blog/security-flaws-within-chatgpt-extensions-allowed-access-to-accounts-on-third-party-websites-and-sensitive-data)  
- [Over 1 Million websites are at risk of sensitive information leakage — XSS is dead. Long live XSS](https://salt.security/blog/over-1-million-websites-are-at-risk-of-sensitive-information-leakage---xss-is-dead-long-live-xss)  

--- 
## 🔑 Supply Chain & Secrets 
- [Guest Post: How I Scanned all of GitHub’s “Oops Commits” for Leaked Secrets](https://trufflesecurity.com/blog/guest-post-how-i-scanned-all-of-github-s-oops-commits-for-leaked-secrets)


---

## 🧩 Memory & Exploitation  

---

## 🔐 Cryptography  

---

## 🌀 Miscellaneous  
- [LangDrained: 3 Paths to Your Data Through LangChain, the World’s Most Popular AI Framework](https://www.cyera.com/research/langdrained-3-paths-to-your-data-through-the-worlds-most-popular-ai-framework) by Vladimir Tokarev, March 26, 2026  
- [Code Execution in Jupyter Notebook Exports](https://www.imperva.com/blog/code-execution-in-jupyter-notebook-exports/) by Yohann Sillam, Dec 16, 2025  
- [Trust Me, I’m a Robot: Can We Trust RPA With Our Most Guarded Secrets?](https://www.cyberark.com/resources/threat-research-blog/trust-me-i-m-a-robot-can-we-trust-rpa-with-our-most-guarded-secrets) (🔥) by Nimrod Stoler
- [CVE-2019-1306: Are you my Index?](https://www.zerodayinitiative.com/blog/2019/10/23/cve-2019-1306-are-you-my-index) by [Mikhail Shcherbakov](https://x.com/yu5k3)
- [ANSI Terminal security in 2023 and finding 10 CVEs](https://dgl.cx/) (🔥) by David Leadbeater, October 5, 2023  
---

## CTFs WriteUps
### Containers  
- [Contain Me If You Can - Wiz Cloud CTF July](https://tresscross.blog/contain-me-if-you-can-wiz-cloud-ctf-july/) by Jason Walker, Aug 31, 2025  
---

⭐ Feel free to [contribute](CONTRIBUTING.md) — add new articles under the correct section, keep entries alphabetized, and provide a short description.
