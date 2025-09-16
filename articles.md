# 📑 Articles

A curated collection of **vulnerability research articles and blog posts**.  
This file contains the **full list** of articles — the main [README](README.md) only highlights selected ones.


---   

## 📝 Table of Contents
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

## 🪟 Windows   

- 🔥 [Abusing Arbitrary File Deletes to Escalate Privilege and Other Great Tricks](https://www.zerodayinitiative.com/blog/2022/3/16/abusing-arbitrary-file-deletes-to-escalate-privilege-and-other-great-tricks)  
- [Pentester’S Windows NTFS Tricks Collection](https://sec-consult.com/blog/detail/pentesters-windows-ntfs-tricks-collection/)
- [Offensive Windows IPC Internals 1: Named Pipes](https://csandker.io/2021/01/10/Offensive-Windows-IPC-1-NamedPipes.html) by [Carsten Sandker](https://x.com/0xcsandker)  
- [Offensive Windows IPC Internals 2: RPC](https://csandker.io/2021/02/21/Offensive-Windows-IPC-2-RPC.html#the-series) by [Carsten Sandker](https://x.com/0xcsandker)
- [Windows Exploitation](https://web.archive.org/web/20200507040017/https://fullpwnops.com/windows-exploitation-pathway.html) by [Fu11Shade](https://web.archive.org/web/20200713114317/https://github.com/fullshade/)
- 

### Privilege Escalation  
- [From NETWORK SERVICE to SYSTEM](https://decoder.cloud/2020/05/04/from-network-service-to-system/) by [decoder](https://x.com/decoder_it), May 4, 2020
- 🔥🔥 [Faxing Your Way to SYSTEM — Part Two](https://windows-internals.com/faxing-your-way-to-system/) by [Yarden Shafir](https://x.com/yarden_shafir) & [Alex Ionescu](https://x.com/aionescu), Apr 30, 2020  - [Faxhell tool](https://github.com/ionescu007/faxhell)  
- [Windows DLL Hijacking (Hopefully) Clarified](https://itm4n.github.io/windows-dll-hijacking-clarified/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 24, 2020  
- [CVE-2020-0729: Remote Code Execution Through .LNK Files](https://www.zerodayinitiative.com/blog/2020/3/25/cve-2020-0729-remote-code-execution-through-lnk-files) by Trend Micro Research Team, March 26, 2020  
- [From dropbox(updater) to NT AUTHORITY\SYSTEM](https://decoder.cloud/2019/12/18/from-dropboxupdater-to-nt-authoritysystem/) by [decoder](https://x.com/decoder_it), December 18, 2019  
- [Windows Privilege Escalation - DLL Proxying](https://itm4n.github.io/dll-proxying/) by [Clément Labro (itm4n)](https://infosec.exchange/@itm4n), Apr 18, 2019  
- 
### Symbolic Links  
- [Avast Anti-Virus privileged arbitrary file create on virus quarantine (CVE-2023-1585 and CVE-2023-1587)](https://the-deniss.github.io/posts/2023/04/26/avast-privileged-arbitrary-file-create-on-quarantine.html) by Denis Skvortcov, April 26, 2023  
- [Breaking Antivirus: Arbitrary file deletion using Symbolic link](https://nixhacker.com/breaking-antivirus-arbitrary-delete-using-symbolic-link/) Apr 28, 2020  
- [An introduction to privileged file operation abuse on Windows](https://offsec.almond.consulting/intro-to-file-operation-abuse-on-Windows.html) by @clavoillotte 
  
  
---  

## 🐧 Linux  

--- 

## ☁️ Kubernetes & Cloud   
- [What a Cluster: Local Volumes Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-local-volumes-command-injection-vulnerability-rce-system-privileges) by Tomer Peled, March 13, 2024  
- [Can't Be Contained: Finding a Command Injection Vulnerability in Kubernetes](https://www.akamai.com/blog/security-research/kubernetes-critical-vulnerability-command-injection) by Tomer Peled, September 13, 2023  
- [Kubernetes Pod Escape Using Log Mounts](https://www.aquasec.com/blog/kubernetes-security-pod-escape-log-mounts/) by Daniel Sagi (from Aqua)  
- [Dirty DAG: New Vulnerabilities in Azure Data Factory’s Apache Airflow Integration](https://unit42.paloaltonetworks.com/azure-data-factory-apache-airflow-vulnerabilities/) by Ofir Balassiano and David Orlovsky (Palo)
- [Finding Azurescape – Cross-Account Container Takeover in Azure Container Instances](https://unit42.paloaltonetworks.com/azure-container-instances/) by Yuval Avrahami
- [SynLapse – Technical Details for Critical Azure Synapse Vulnerability](https://orca.security/resources/blog/synlapse-critical-azure-synapse-analytics-service-vulnerability/) by Tzah Pahima
- [Kubernetes container runtime CRI-O has make-me-root flaw](https://www.theregister.com/2022/03/15/cr8escape_container_runtime_bug/) by Jessica Lyons, March 15, 2022
  
### by Wiz  
- [Breaking NVIDIA Triton: CVE-2025-23319 - A Vulnerability Chain Leading to AI Server Takeover](https://www.wiz.io/blog/nvidia-triton-cve-2025-23319-vuln-chain-to-ai-server)  
- [NVIDIAScape - Critical NVIDIA AI Vulnerability: A Three-Line Container Escape in NVIDIA Container Toolkit (CVE-2025-23266)](https://www.wiz.io/blog/nvidia-ai-vulnerability-cve-2025-23266-nvidiascape)  
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
- [Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/)  by Yosef Yaakov and Bar Ben-Michael, July 18, 2024  
- [Docker Security – Step-by-Step Hardening (Docker Hardening)](https://reynardsec.com/en/docker-platform-security-step-by-step-hardening/) by ReynardSec, October 16, 2023
- [A new method for container escape using file-based DirtyCred](https://starlabs.sg/blog/2023/07-a-new-method-for-container-escape-using-file-based-dirtycred/) by Choo Yi Kai, July 25, 2023  
- [Container escape using dirtypipe](https://terenceli.github.io/%E6%8A%80%E6%9C%AF/2022/03/19/container-escape-through-dirtypipe), March 19, 2022  
- [Escaping privileged containers for fun](https://pwning.systems/posts/escaping-containers-for-fun/) by Jordy Zomer, March 6, 2022
- [Container escape techniques](https://reaper.gitbook.io/my-penetration-test-guide/privilege-escalation/linux-privilege-escalation/container-escape-techniques)  
- [Container Breakout – Part 2](https://tbhaxor.com/container-breakout-part-2/) by Gurkirat Singh, Sep 10, 2021  
- [Container Breakout – Part 1](https://tbhaxor.com/container-breakout-part-1/) by Gurkirat Singh, Sep 10, 2021
- [Container Breakouts – Part 3: Docker Socket](https://blog.nody.cc/posts/container-breakouts-part3/) by Jan Harrie, July 30, 2020  
- [Container Breakouts – Part 2: Privileged Container](https://blog.nody.cc/posts/container-breakouts-part2/) by Jan Harrie, July 21, 2020  
- [Container Breakouts – Part 1: Access to root directory of the Host](https://blog.nody.cc/posts/container-breakouts-part1/) by Jan Harrie, July 15, 2020  
- Pr[ivileged Container Escapes with Kernel Modules](https://xcellerator.github.io/posts/docker_escape/) by TheXcellerator, Sep 27, 2020   
- [The Route to Root: Container Escape Using Kernel Exploitation](https://www.cyberark.com/resources/threat-research-blog/the-route-to-root-container-escape-using-kernel-exploitation) by Nimrod Stoler
- [How I Hacked Play-with-Docker and Remotely Ran Code on the Host](https://www.cyberark.com/resources/secure-third-party-vendor-and-remote-access/how-i-hacked-play-with-docker-and-remotely-ran-code-on-the-host) by Nimrod Stoler  
- [The Strange Case of How We Escaped the Docker Default Container](https://www.cyberark.com/resources/threat-research-blog/the-strange-case-of-how-we-escaped-the-docker-default-container) by Nimrod Stoler and Gilad Reti, March 4, 2021  
- [Container Basics and Escapes](https://0xn3va.gitbook.io/cheat-sheets/container/overview/basics) by [0xn3va](https://github.com/0xn3va)
- [Container Breakout Vulnerabilities](https://www.container-security.site/attackers/container_breakout_vulnerabilities.html), by Rory McCune
--- 

## 📱 Android & Mobile  

---
## Web  

- [How I Found a Critical Password Reset Bug in the BB program(and Got $4,000)](https://medium.com/@s41n1k/how-i-found-a-critical-password-reset-bug-in-the-bb-program-and-got-4-000-a22fffe285e1)
- [Account Takeover via Password Reset without user interactions](https://gitlab.com/gitlab-org/gitlab/-/issues/436084)
- [Shockwave Identifies Web Cache Deception and Account Takeover Vulnerability affecting OpenAI's ChatGPT](https://www.shockwave.cloud/blog/shockwave-works-with-openai-to-fix-critical-chatgpt-vulnerability) by Gal Nagli, July 15, 2024
- [CVE-2024-25153: Remote Code Execution in Fortra FileCatalyst](https://www.lrqa.com/en/cyber-labs/cve-2024-25153-remote-code-execution-in-fortra-filecatalyst/) by Tom Wedgbury, March 13, 2024  
- 🔥 [ChatGPT Account Takeover - Wildcard Web Cache Deception](https://nokline.github.io/bugbounty/2024/02/04/ChatGPT-ATO.html) by [Harel](https://x.com/h4r3l), Feb 4, 2024
- [Sandwich Attack UUIDv1](https://x.com/0xLupin/status/1745805050562105739) by [0xLupin](https://x.com/0xLupin), Jan 12, 2024
- [Old but GOLD Dot Dot Slash to Get the Flag — Uber Microservice](https://ngailong.wordpress.com/2019/04/07/old-but-gold-dot-dot-slash-to-get-the-flag-uber-microservice/) by Ron Chan, April 7, 2019  
- [Tutorial One: Open Url Redirects](https://web.archive.org/web/20190523023839/https://zseano.com/tutorials/1.html) by Zseano, Sep 14, 2017   
- [Tutorials by zseano](https://web.archive.org/web/20190520052806/https://zseano.com/index.html) by Zseano, Sep 14, 2017
- 🔥 [Web Cache Deception Attack](https://omergil.blogspot.com/2017/02/web-cache-deception-attack.html) by Omer Gil, Feburary 27, 2017
---
## Bug Bounty
- [$10,500 Bounty: A Grammarly Account Takeover Vector](https://infosecwriteups.com/10-500-bounty-a-grammarly-account-takeover-vector-974ef90fb00a) by [Monika sharma](https://medium.com/@commanak46)  
---

## 🌐 Identity 
- [Forging Passkeys: Exploring the FIDO2 / WebAuthn Attack Surface](https://nullpt.rs/forging-passkeys) by [vmfunc](https://x.com/vmfunc), June 20, 2025
- [Abusing FIDO2 passkeys to take over Global Administrators in Entra ID](https://cybersecurity.bureauveritas.com/services/information-technology/pentesting-services/what-can-be-pentested/cloud-pentesting/abusing-fido2-passkeys) by Max Rozendaal




### OAuth  
- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025  
- 🔥 [Account hijacking using “dirty dancing” in sign-in OAuth-flows](https://labs.detectify.com/writeups/account-hijacking-using-dirty-dancing-in-sign-in-oauth-flows/) by Frans Rosén
- [OAuth Non-Happy Path to ATO](https://blog.voorivex.team/oauth-non-happy-path-to-ato) by Omid Rezaei
- [Common OAuth Vulnerabilities](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html) by Jose Catalan and Szymon Drosdzol, Jan 30, 2025
- [The OAuth Oversight: When Configuration Errors Turn into Account Hijacks](https://medium.com/@ProwlSec/the-oauth-oversight-when-configuration-errors-turn-into-account-hijacks-5ed1f9c83d16) by ProwlSec, Nov 4, 2024  
- 🔥🔥 [Writeup: Keycloak open redirect (CVE-2023-6927)](https://securityblog.omegapoint.se/en/writeup-keycloak-cve-2023-6927/) by Pontus Hanssen and Kasper Karlsson, January 11, 2024  
- 🔥[Google OAuth is Broken (Sort Of)](https://trufflesecurity.com/blog/google-oauth-is-broken-sort-of) by Dylan Ayrey, December 15, 2023
- [nOAuth: How Microsoft OAuth Misconfiguration Can Lead to Full Account Takeover](https://www.descope.com/blog/post/noauth) by Omer Cohen, June 20, 2023
- [OAuth 2.0 Hunting Methodology](https://github.com/KathanP19/HowToHunt/blob/master/OAuth/OAuth%202.0%20Hunting%20Methodology.md) by KathanP19, Sep 18, 2022  
- [OAuth 2.0 Vulnerabilities](https://0xn3va.gitbook.io/cheat-sheets/web-application/oauth-2.0-vulnerabilities) by 0xn3va
- [[Google VRP] SSRF in Google Cloud Platform StackDriver](https://ngailong.wordpress.com/2019/12/19/google-vrp-ssrf-in-google-cloud-platform-stackdriver/) by Ron Chan, Dec 19, 2019
- 🔥 [[Uber] redirect_uri is difficult to do it right](https://ngailong.wordpress.com/2017/11/22/uber-redirect_uri-is-difficult-to-do-it-right/) by Ron Chan, Nov 22, 2017
- [[Uber 8k Bug] Login CSRF + Open Redirect = Account Take Over](https://ngailong.wordpress.com/2017/08/07/uber-login-csrf-open-redirect-account-takeover/) by Ron Chan, August 7, 2017

### by Aviad Carmel from Salt  
- 🔥 [Traveling with OAuth — Account Takeover on Booking.com](https://salt.security/blog/traveling-with-oauth-account-takeover-on-booking-com) - 🎥 [Talk](https://www.youtube.com/watch?v=BxiL4Vf_umI)
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

- 🔥 [Trust Me, I’m a Robot: Can We Trust RPA With Our Most Guarded Secrets?](https://www.cyberark.com/resources/threat-research-blog/trust-me-i-m-a-robot-can-we-trust-rpa-with-our-most-guarded-secrets) by Nimrod Stoler
- [CVE-2019-1306: Are you my Index?](https://www.zerodayinitiative.com/blog/2019/10/23/cve-2019-1306-are-you-my-index) by [Mikhail Shcherbakov](https://x.com/yu5k3)
---

⭐ Feel free to [contribute](CONTRIBUTING.md) — add new articles under the correct section, keep entries alphabetized, and provide a short description.
