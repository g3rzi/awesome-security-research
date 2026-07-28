
# awesome-security-research [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  
😎 A curated list of awesome resources for **security research**:  
vulnerability discovery, exploit development, reversing, containers, Kubernetes, and more.  

---

## 📚 Table of Contents
- [Articles](#articles)
- [Talks & Videos](#talks--videos)
- [Tools](#tools)
- [CTFs](#ctfs)
- [Learning Resources](#learn)

---
## Legend

- 🔥 – Highly recommended / must-watch  
- 💵 – Paid or has a paid tier  
---

## 🌱 How to Use This List

If you're new to security research:

1. Start with a few talks from **Talks & Videos** (marked 🔥).
2. Pick a domain (Web, Windows, Kubernetes, etc.) and read through the matching section in **Articles.md**.
3. Choose 1–2 tools from **Tools** in that domain and actually use them on a test target or lab.
4. Repeat in cycles: Watch → Read → Experiment → Take notes.

---
## Articles 
A curated collection of vulnerability research articles and blog posts.  
➡️ See the full list here: [**articles.md**](articles.md)

---  

## Talks & Videos  
- [DEF CON 33 - HTTP 1 1 Must Die! The Desync Endgame - James 'albinowax' Kettle](https://www.youtube.com/watch?v=PUCyExOr3sE) (🔥) by James Kettle, Oct 11 2025  
- [Splitting the Email Atom: Exploiting Parsers to Bypass Access Controls](https://www.youtube.com/watch?v=Uky45wwqsO4) (🔥🔥)  by Gareth Heyes, March 3, 2025
- [BingBang: Hacking Bing.com (and much more) with Azure Active Directory ](https://www.youtube.com/watch?v=l4hA2eZuMF8) (🔥🔥) by Hillai Ben-Sasson (Wiz), Feb 20, 2024
- [mTLS: When Certificate Authentication is Done Wrong](https://www.youtube.com/watch?v=3zEZ6d9PVZ8) by Michael Stepankin, Feb 20, 2024   
- [Weaponizing Plain Text: ANSI Escape Sequences as a Forensic Nightmare](https://www.youtube.com/watch?v=opW_Q7jvSbc) by STOK, Jan 3, 2024  
- [Smashing the State Machine: The True Potential of Web Race Conditions](https://www.youtube.com/watch?v=VzqG_-a8_Jo) (🔥🔥) by James Kettle, Jan 2, 2024
- [BlueHat 2023: Houdini of the Terminal with David Leadbeater](https://www.youtube.com/watch?v=iIHw0KWgzAs) (🔥) by David Leadbeater, March 2, 2023
- [Defender-Pretender: When Windows Defender Updates Become a Security Risk](https://www.youtube.com/watch?v=3hYjdWNhhvk) by Omer Attias and Tomer Bar, Feb 2, 2024
- [Backdooring and Hijacking Azure AD Accounts by Abusing External Identities](https://www.youtube.com/watch?v=uKDS2t9_KsA) by Dirk-jan Mollema, Nov 17, 2022
- [Pwning Cloud Vendors with Untraditional PostgreSQL Vulnerabilities](https://www.youtube.com/watch?v=X6CiUD3EcfQ) by Shir Tamari  & Nir Ohfeld, Nov 17, 2022
- [The Journey of Hunting In-the-Wild Windows LPE 0day](https://www.youtube.com/watch?v=voDpk7nQAyw) by Quan Jin, Nov 17, 2022  
- [Trace Me if You Can: Bypassing Linux Syscall Tracing](https://www.youtube.com/watch?v=cVf7Ww67j68) by Rex Guo & Junyuan Zeng, Nov 17, 2022  
- [DEF CON 30 - James Kettle - Browser-Powered Desync Attacks: A New Frontier in HTTP Request Smuggling](https://www.youtube.com/watch?v=B8KW8KPVcUo) (🔥🔥) by James Kettle, October 20, 2022  
- [CG - Trust Me, I'm a Robot: Can we trust RPA with our most guarded secrets?](https://www.youtube.com/watch?v=EbsdV38P0wI) (🔥🔥) by Nimrod Stoler and Nethanel Coppenhagen, Sept 4 2022
- [DEF CON 29 - Ian Coldwater, Chad Rikansrud - Real Life Story of the 1st Mainframe Container Breakout](https://www.youtube.com/watch?v=7DXF7YDBf-g) by Ian Coldwater and Chad, Aug 5, 2021
- [#HITBLockdown D1 - 60 CVEs In 60 Days - Eran Shimony](https://www.youtube.com/watch?v=HFO8GCGQcUc) (🔥) by Eran Shimony, May 21, 2020  
- [GOD MODE UNLOCKED - Hardware Backdoors in x86 CPUs](https://www.youtube.com/watch?v=_eSAF_qT_FY) by [Christopher Domas (xoreaxeaxeax)](https://github.com/xoreaxeaxeax) (🔥), August 28 2018
- [A New Era of SSRF - Exploiting URL Parser in Trending Programming Languages!](https://www.youtube.com/watch?v=voTHFdL9S2k&t=66s) by Orange Tsai, Jan 8, 2020  
- [DEF CON 23 - Chris Domas - Repsych: Psychological Warfare in Reverse Engineering](https://www.youtube.com/watch?v=HlUe0TUHOIc) by [Christopher Domas (xoreaxeaxeax)](https://github.com/xoreaxeaxeax) (🔥), April 20, 2016   
- [REcon 2015 - The movfuscator (Christopher Domas)](https://www.youtube.com/watch?v=2VF_wPkiBJY) by [Christopher Domas (xoreaxeaxeax)](https://github.com/xoreaxeaxeax), Feb 17, 2016  

### AI  
- [Source to Sink: Improving LLM Vuln Discovery | [un]prompted 2026](https://www.youtube.com/watch?v=bxwEZMhqeR0&t=85s) by Scott Behrens & Justice Cassel, Mar 25, 2026  
- [Black-hat LLMs | [un]prompted 2026](https://www.youtube.com/watch?v=1sd26pWhfmg) by Nicholas Carlini, Mar 25, 2026
- [Scaling LLM-Based Vulnerability Research via Static Analysis and Document Ranking](https://www.youtube.com/watch?v=gKQeTfbXjZY) by Caleb Gross (@noperator), Nov 4, 2025  


### Kubernetes    
- [Kubernetes Privilege Escalation: Container Escape == Cluster Admin?](https://www.youtube.com/watch?v=oc1tq_r6VNM) by Yuval Avrahami and Shaul Ben Hai, November 28, 2022
- [DEF CON 30 - Billy Jheng, Muhammad Ramdhan - All Roads Lead to GKEs Host - 4+ Ways to Escape](https://www.youtube.com/watch?v=DcyjTlTIcMA) by Billy Jheng and Muhammad Ramdhan, Oct 20, 2022  

### Containers  
- [HEXACON 2025 - CUDA de Grâce by Valentina Palmiotti & Samuel Lovejoy](https://www.youtube.com/watch?v=Lvz2_ZHj3lo&t=1s) by Valentina Palmiotti & Samuel Lovejoy, Nov 24, 2025
- [PancakesCon 5 - A Gentle Intro to Container Escapes and No-Clump Gravy](https://www.youtube.com/watch?v=Mj29HnlrraY) by Natalie Somersall, Jul 2, 2024  
- [How to Use "Leaky Vessels" for Container Escape in #kubernetes w/ Jay Beale](https://www.youtube.com/watch?v=HCYv0q6Yu1w) by Jay Beale, Feb 21, 2024  
- [Container Escape: All You Need Is Cap (Capabilities)](https://www.youtube.com/watch?v=iALZWtWwRyc) by Eran Ayalon and Ilan Sokol, June 7 2023  
- [The COW (Container On Windows) Who Escaped the Silo](https://www.youtube.com/watch?v=e6oegr3cl4U) by Eran Segal, Nov 17, 2022
- [#HITB2021SIN D2T2 - Container Escape In 2021 - Li Qiang](https://www.youtube.com/watch?v=WBC7hhgMvQQ) by Li Qiang, Sep 2, 2021
- [Escaping Virtualized Containers](https://www.youtube.com/watch?v=0hrv0qyOEd0) (🔥🔥) by Yuval Avrahami, May 14, 2021  
- [A Compendium of Container Escapes](https://www.youtube.com/watch?v=BQlqita2D2s) by Capsule8, Jan 15, 2020
- [#HITBLockdown D2 - Prisoner Number 6 - Nimrod Stoler](https://www.youtube.com/watch?v=aMBq0LZo_2I) (🔥) by Nimrod Stoler, Jun 3, 2020  
- [CG - Prisoner Number Six - Nimrod Stoler & Lavi Lazarovitz](https://www.youtube.com/watch?v=sPN5bRGoZlI) (🔥) by Nimrod Stoler, August 7, 2019
- [#HITB2016AMS D1T1 - Escape From The Docker KVM QEMU Machine - Shengping Wang and Xu Liu](https://www.youtube.com/watch?v=XcvRfg3_ACY) by Xu Liu and Shengping Wang, Jun 21, 2016
- [Vulnerability Exploitation In Docker Container Environments](https://www.youtube.com/watch?v=77-jaeUKH7c) by Anthony Bettini, Mar 5, 2016

### Identity  
- [Turning WebAuthn Against Itself](https://www.youtube.com/watch?v=LCGm5-ZjKK0) by Shourya Pratap Singh, Jonny Lin and Daniel Seetoh, Aug 28, 2025  

---  
## Tools  

### Framework
- [Dark-Moon](https://github.com/ASCIT31/Dark-Moon) - Open source autonomous AI penetration testing framework and MCP host for web, API, Active Directory and Kubernetes
- [raptor](https://github.com/gadievron/raptor) - turns Claude Code into a general-purpose AI

### Web  
- [CyberChef](https://gchq.github.io/CyberChef/)  
- [Burp Suite](https://portswigger.net/burp) (free, the pro version is 💵)  
- [Caido](https://caido.io/compare/burpsuite) - Modern alternative to Burp Suite  
- [OWASP ZAP](https://www.zaproxy.org/) - Webapp scanner  
- [URL validation bypass cheat sheet](https://portswigger.net/web-security/ssrf/url-validation-bypass-cheat-sheet) 
- [JSAnalyzer](https://github.com/jenish-sojitra/JSAnalyzer) - Burp extension for JavaScript static analysis  
- [Firecrawl](https://www.firecrawl.dev/playground?endpoint=scrape) - Scraping

#### API  
- APIStorm One (Not published yet)  
- [Arjun](https://github.com/s0md3v/Arjun) - HTTP parameter discovery suite  
- [Fuzzapi (Depcrecated)](https://github.com/Fuzzapi/fuzzapi) - REST API pentesting
- [Shannon](https://github.com/KeygraphHQ/shannon) - AI Pentester for Web Apps and APIs
- [awesome-apisec](https://github.com/arainho/awesome-api-security) - A collection of awesome API Security tools and resources. 

### AI  
- [AntiGravity](https://antigravity.google/download)
- [NotebookLM](https://notebooklm.google/)  
- [DeepWiki](https://deepwiki.com/)  
- [ChatGPT](https://chatgpt.com/)  
- [Claude](https://claude.ai/)  
- [Cursor](https://cursor.com/)
- [CAI - Cyber Secyruty AI Framework](https://github.com/aliasrobotics/CAI)
- [claw-code](https://github.com/instructkr/claw-code) - Claucde code open source ported to Python
- [Heretic](https://github.com/p-e-w/heretic) - Censorship removal for language models
- [Security Reports RAG](https://github.com/n0n4m3x41/rag-enhancing-vuln-research)
- [WooYun Legacy](https://github.com/tanweai/wooyun-legacy/blob/main/README.en.md) - A Claude Code plugin built on 22,132 business logic vulnerability cases.
- [Firecrawl](https://www.firecrawl.dev/) - Web Crawler with AI (💵)
- [crawl4ai](https://github.com/unclecode/crawl4ai) - Web Crawler with Playright   

#### Skills
- [skills.sh](https://skills.sh/) - Skills marketplace  
- [railguard-skill](https://github.com/Netflix-Skunkworks/railguard-skill/tree/main) by [Andrea B](https://www.linkedin.com/in/andrx/?lipi=urn%3Ali%3Apage%3Ad_flagship3_pulse_read%3B%2B1eJIy5OQBen6HF0HqrcXA%3D%3D)  


### Network  
- [Wireshark](https://www.wireshark.org/)   
- [Fiddler](https://www.telerik.com/download/fiddler)   
- [nmap](https://nmap.org/) - Network mapper  
- [bettercap](https://github.com/bettercap/bettercap) by [Simone Margaritelli (evilsocket)](https://github.com/evilsocket)  

### Mobile  
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) (🔥)

### Fuzzing  
- [jazzer.js](https://github.com/CodeIntelligenceTesting/jazzer.js) - Coverage-guided, in-process fuzzing for Node.js

### .NET  
- [DeReviewer](https://github.com/yuske/DeReviewer) by Mikhail Shcherbakov - (From the blog [CVE-2019-1306: Are you my Index?](https://www.zerodayinitiative.com/blog/2019/10/23/cve-2019-1306-are-you-my-index))  


### Windows  

- [Faxhell - A Proof-of-Concept bind shell using the Fax service and a DLL hijack based on Ualapi.dll](https://github.com/ionescu007/faxhell)
- [pestudio](https://www.winitor.com/download) by Marc Ochsenmeier   
- [CFF Explorer](https://ntcore.com/explorer-suite/)  
- [PEiD](https://www.aldeid.com/wiki/PEiD)  
- [HxD](https://mh-nexus.de/en/hxd/)
- [Procmon](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon)  
- [Process Explorer](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer)  
- [System Informer (Process Hacker)](https://systeminformer.sourceforge.io/)  
- [TCPView](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview)  
- [mimikatz](https://github.com/gentilkiwi/mimikatz) - by [Benjamin DELPY](https://github.com/gentilkiwi)
- [ItWasAllADream](https://github.com/byt3bl33d3r/ItWasAllADream) - A PrintNightmare (CVE-2021-34527) Python Scanner by [byt3bl33d3r](https://github.com/byt3bl33d3r)  

#### PE  
- [PE-sieve](https://github.com/hasherezade/pe-sieve) - Recognizes and dumps a variety of potentially malicious implants (replaced/injected PEs, shellcodes, hooks, in-memory patches) by hasherezade.  
- [PE-bear](https://github.com/hasherezade/pe-bear) - Portable Executable reversing tool with a friendly GUI by hasherezade.  
- [Detect It Easy (DiE)](https://github.com/horsicq/Detect-It-Easy) - Program for determining types of files for Windows, Linux and MacOS.  

#### Namedpipes  
- [Pipetap](https://github.com/sensepost/pipetap) by [Leon Jacobs](https://github.com/leonjza)  
- [PipeViewer - Shows detailed information about named pipes in Windows](https://github.com/cyberark/PipeViewer) by Eviatar Gerzi  
- [NamedPipeMaster](https://github.com/zeze-zeze/NamedPipeMaster) - Analyze and monitor in named pipes, by zeze-zeze  
- [IO Ninja](https://ioninja.com/) 💵  

#### RPC  
- [RPCMon - RPC Monitor tool based on Event Tracing for Windows](https://github.com/cyberark/RPCMon) by Eviatar Gerzi   
- [RpcInvestigator](https://github.com/trailofbits/RpcInvestigator) - Exploring RPC interfaces on Windows by trailofbits ([blog](https://blog.trailofbits.com/2023/01/17/rpc-investigator-microsoft-windows-remote-procedure-call/))  
- [rpcfirewall](https://github.com/zeronetworks/rpcfirewall) - Hooking RCP calls by zeronetworks ([Sagi Dulce](https://github.com/sagiesec))  


#### Reversing    
- [API monitor](http://www.rohitab.com/apimonitor) by rohitab
- [x64dbg](https://x64dbg.com/)  
- [dnSpyEx - .NET debugger and assembly editor.](https://github.com/dnSpyEx/dnSpy)  
- [dnSpy](https://github.com/dnSpy/dnSpy) (original - DEPRECATED) - .NET debugger and assembly editor.
- [IDA](https://hex-rays.com/ida-free)  
- [radare](https://radare.org/n/) by pancake  
- [WinDBG](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/)
- [Ghidra](https://github.com/NationalSecurityAgency/ghidra)
- [webcrack](https://github.com/j4k0xb/webcrack) - Deobfuscate obfuscator.io, unminify and unpack bundled javascript

### Linux
- [PEASS-ng - Privilege Escalation Awesome Scripts SUITE new generation](https://github.com/peass-ng/PEASS-ng) (🔥)

  
### Containers    
- [Edgeshark](https://github.com/siemens/edgeshark/) - Discover and capture container network traffic.
- [deepce](https://github.com/stealthcopter/deepce) (🔥) - Docker Enumeration, Escalation of Privileges and Container Escapes (DEEPCE).
  
### Kubernetes  
- [KubiScan](https://github.com/cyberark/KubiScan) - Scan Kubernetes cluster for risky permissions by Eviatar Gerzi    
- [kubeletctl](https://github.com/cyberark/kubeletctl) - A client for kubelet by Eviatar Gerzi    
- [kubesploit](https://github.com/cyberark/kubesploit) - Offensive tool by Eviatar Gerzi  
- [kubestriker](https://github.com/vchinnipilli/kubestriker) - Security Auditing tool by vasant chinnipilli
- [aad-pod-identity](https://github.com/Azure/aad-pod-identity/) - Assign Azure AD identities to pods in Kubernetes, in order to access Azure resources  
- [audit2rbac](https://github.com/liggitt/audit2rbac) - Autogenerate RBAC policies based on Kubernetes audit logs  
- [CDK](https://github.com/cdk-team/CDK) - Zero Dependency Container Penetration Toolkit  
- [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper) - Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless  
- [cnspec](https://cnspec.io) - Scan Kubernetes clusters, containers, and manifest files for vulnerabilities and misconfigurations  
- [falco](https://github.com/falcosecurity/falco) - Container Native Runtime Security   
- [KBOM](https://github.com/ksoclabs/kbom) - Kubernetes Bill of Materials Toolkit 
- [kdigger](https://github.com/quarkslab/kdigger) - Kubernetes focused container assessment and context discovery tool for penetration testing  
- [kiam](https://github.com/uswitch/kiam) - Integrate AWS IAM with Kubernetes
- [kube-bench](https://github.com/aquasecurity/kube-bench) - Check whether Kubernetes is deployed according to security best practices  
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) - Hunt for security weaknesses in Kubernetes clusters  
- [kube-psp-advisor](https://github.com/sysdiglabs/kube-psp-advisor) - Help building an adaptive and fine-grained pod security policy  
- [kube-scan](https://github.com/octarinesec/kube-scan) - k8s cluster risk assessment tool  
- [kubescape](https://github.com/kubescape/kubescape) - k8s risk analysis, security compliance, and misconfiguration scanning.  
- [kubelight - WIP but promising](https://github.com/OWASP/KubeLight) - OWASP project to scan your Kubernetes Cluster for Security & Compliance.  
- [Kubei](https://github.com/Portshift/kubei) - Vulnerabilities scanner for Kubernetes clusters  
- [kube2iam](https://github.com/jtblin/kube2iam) - Provide different AWS IAM roles for pods running on Kubernetes  
- [kubeaudit](https://github.com/Shopify/kubeaudit) - Audit your Kubernetes clusters against common security controls  
- [kubectl-bindrole](https://github.com/Ladicle/kubectl-bindrole) - Find Kubernetes roles bound to a specified ServiceAccount, Group or User  
- [kubectl-dig](https://github.com/sysdiglabs/kubectl-dig) - Deep Kubernetes visibility from the kubectl  
- [kubectl-kubesec](https://github.com/stefanprodan/kubectl-kubesec) - Scan Kubernetes pods, deployments, daemonsets and statefulsets with kubesec.io  
- [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can) - Show who has permissions to \<verb\> \<resource\> in Kubernetes  
- [OWASP Top Ten for Kubernetes](https://owasp.org/www-project-kubernetes-top-ten/) -  The Top Ten is a prioritized list of these risks backed by data collected from organizations varying in maturity and complexity  
- [terrascan](https://github.com/accurics/terrascan) - Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure  
- [kyverno](https://github.com/nirmata/kyverno) - Kubernetes Native Policy Management  
- [netchecks](https://github.com/hardbyte/netchecks/) - Tool to validate assumptions about the network  
- [rakkess](https://github.com/corneliusweig/rakkess) - Review access matrix for Kubernetes server resources  
- [rback](https://github.com/team-soteria/rback) - RBAC in Kubernetes visualizer  
- [red-kube](https://github.com/lightspin-tech/red-kube) - K8S Adversary Emulation Based on kubectl  
- [steampipe](https://github.com/turbot/steampipe) - Use SQL to query your cloud services (AWS, Azure, GCP and more) running Kubernetes  
- [steampipe-kubernetes](https://github.com/turbot/steampipe-plugin-kubernetes) - Use SQL to query your Kubernetes resources  
- [steampipe-kubernetes-compliance](https://github.com/turbot/steampipe-mod-kubernetes-compliance) - Kubernetes compliance scanning tool for CIS, NSA & CISA Cybersecurity technical report for Kubernetes hardening.  
- [trivy](https://github.com/aquasecurity/trivy) - A Simple and Comprehensive Vulnerability Scanner for Containers, Suitable for CI  
- [trivy-operator](https://github.com/aquasecurity/trivy-operator) - Kubernetes-native security (Vulnerabilities, IaC Misconfig, exposed secrets, RBAC assessment, compliance, and more) toolkit for kubernetes  
- [kubernetes-rbac-audit](https://github.com/cyberark/kubernetes-rbac-audit) - Tool for auditing RBACs in Kubernetes  
- [kubernetes-external-secrets](https://github.com/external-secrets/kubernetes-external-secrets) - Tool to get External Secrets from Hashicorp Vault and AWS SSM  
- [vault-secrets-operator](https://github.com/ricoberger/vault-secrets-operator) - An operator to create Kubernetes secrets from Vault for a secure GitOps based workflow   

*Most of the tools are taken from [awesome-kubernetes-security](https://github.com/ksoclabs/awesome-kubernetes-security)  
### Miscellaneous   
- [CVE PoC](https://github.com/trickest/cve)

---


## CTFs  
A (very small) selection of CTFs and platforms that are especially good
for learning real-world vulnerability research:

- [pwnable.kr](https://pwnable.kr/) – Binary exploitation challenges
- [pwn.college](https://pwn.college/) – Structured teaching for pwn & exploitation
- [Hack The Box](https://www.hackthebox.com/) – Labs & boxes (mixed difficulty)
- [Root Me](https://www.root-me.org/) – Web, crypto, pwn, reversing, misc
- [exploit.education](https://exploit.education/) - Labs for Linux PWNs and Binary exploitation
- [Crackmes.one](https://crackmes.one/) - Crackmes to improve reverse engineering skills.  
---
## Learn  
- [Appsec.FYI](https://appsec.fyi/) - a free curated library of application security resources
- [flare-learning-hub](https://github.com/mandiant/flare-learning-hub) - Free educational content on reverse engineering and malware analysis from the FLARE team
- [exploitation-course](https://github.com/ashemery/exploitation-course) - Offensive Software Exploitation Course
- [Vulnerabilities 1001: C-Family Software Implementation Vulnerabilities](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Vulns1001_C-family+2023_v1/about)
- [bug-bounty-reference](https://github.com/ngalongc/bug-bounty-reference) -  a list of bug bounty write-up that is categorized by the bug nature
- [Awesome Bug Bounty](https://github.com/djadmin/awesome-bug-bounty)
- [vulnerability-Checklist](https://github.com/Az0x7/vulnerability-Checklist)  


---
## Contributing

Contributions are welcome! 🎉

Before opening a PR:

- Make sure the resource is **high quality** and focused on **security research**  
  (vuln discovery, root cause analysis, exploitation, etc. – not generic “how to hack”).
- Place it in the right section and keep the list **alphabetically sorted**.
- Prefer **original research** and deep-dive content over shallow summaries.

If you're unsure, open an issue and we can discuss it.  

--- 
## License

This list is licensed under **CC0 1.0 Universal**.  

To the extent possible under law, I waive all copyright and related rights to  
the content of this repository. See the [LICENSE](LICENSE) file for details.  

---

## Disclaimer

All tools and resources are listed for **educational and defensive purposes only**.  
Use them responsibly and follow the laws in your jurisdiction.  

---

⭐ If you find this project useful, consider giving it a star!
