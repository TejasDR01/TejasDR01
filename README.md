<!-- ============================================================
     GITHUB PROFILE README — TejasDR01
     ============================================================ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,30&height=140&section=header&text=Tejas-Ramachandra&font=Orbitron&fontSize=38&fontColor=ffffff&fontAlignY=55&animation=fadeIn&desc=Software%20Engineer%20%7C%20USC%20MS%20CS%20%7C%20Full-Stack%20%2F%20Security%20%2F%20Systems%20%2F%20AI&descAlignY=78&descSize=15&descColor=8ba4c9" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=From+kernel+space+to+cloud+scale.;I+build+systems+that+survive+production.;Full-Stack+%7C+Distributed+Systems+%7C+AI+Engineering)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0A66C2)](https://linkedin.com/in/devtram)&ensp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=EA4335)](mailto:tdevanap@usc.edu)&ensp;
[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=vercel&logoColor=white)](https://tejasdr01.github.io/Portfolio)&ensp;

</div>

<br/>

<!-------------------------------------------------------------->
<!-- ABOUT                                                      -->
<!-------------------------------------------------------------->

<h2>&nbsp;$ whoami</h2>

<pre>
  name     :  [ YOUR NAME ]
  degree   :  MS Computer Science — University of Southern California  |  GPA: 3.6 / 4.0
  previous :  Software Engineer @ Lookout Security   •   Engineer @ ISRO
  stack    :  Kernel → API → Cloud
  focus    :  Distributed Systems  •  Full-Stack Engineering  •  AI Tooling
  based_in :  Los Angeles, CA
</pre>

I build software end-to-end — not just features, but the systems around them.
At **Lookout Security** I owned production at scale: 100+ instances monitored, 30+ incidents resolved, CI/CD pipelines rebuilt from slow to fast.
At **USC** I'm going deeper — OS internals, cryptography, algorithms — because understanding the machine makes better engineers.
I care about code that is observable, recoverable, and doesn't need a babysitter in production.

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,30&height=2" width="100%"/>

<br/>

<!-------------------------------------------------------------->
<!-- PROJECTS                                                    -->
<!-------------------------------------------------------------->

<h2>&nbsp;$ ls ./projects --pinned</h2>

<br/>

<!-- ── PROJECT 1 ── -->
<details>
<summary><b>&nbsp;&nbsp;OS Kernel — Built from Scratch&nbsp;&nbsp;</b>&nbsp;&nbsp;<code>C</code>&nbsp;<code>x86</code>&nbsp;<code>Systems Programming</code>&nbsp;&nbsp;&nbsp;[ click to expand ]</summary>

<br/>

<blockquote>Most people use an OS. I built one to understand what I was standing on.</blockquote>

Designed and implemented a fully functional OS kernel on an x86 emulator from first principles —
process scheduler, virtual memory manager, and file system, all wired together and tested under load.

<pre>
  Subsystems       →  3 core  (scheduler · virtual memory · file system)
  System Calls     →  30+     (process, memory, I/O domains)
  Concurrent Procs →  20+     (preemptive scheduling)
  Memory Mapping   →  4KB page granularity
  Test Cases       →  100+    (zero memory leaks, Valgrind-equivalent)
</pre>

&nbsp;&nbsp;[![View Repo](https://img.shields.io/badge/View_Repo-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TejasDR01/OS-kernel)

<br/>

</details>

---

<!-- ── PROJECT 2 ── -->
<details>
<summary><b>&nbsp;&nbsp;AI Security Log Analyzer&nbsp;&nbsp;</b>&nbsp;&nbsp;<code>Python</code>&nbsp;<code>LLMs</code>&nbsp;<code>MITRE ATT&CK</code>&nbsp;&nbsp;&nbsp;[ click to expand ]</summary>

<br/>

<blockquote>Log analysis tools show you data. This one tells you what it means.</blockquote>

A threat detection engine that plugs an LLM reasoning layer directly over raw log streams.
Ingests 6 log formats, maps findings to ATT&CK techniques, explains incidents in plain language.
Multi-provider abstraction supports Anthropic, OpenAI, and local Ollama models.

<pre>
  Log Formats      →  6+    (Syslog, CEF, JSON, EVTX, Apache, auth logs)
  True Pos. Rate   →  91%
  ATT&CK Techniques→  30+   across 9 tactics
  Events / Batch   →  500
  False Req. Cut   →  95%   (rate limiting + input sanitization)
</pre>

&nbsp;&nbsp;[![View Repo](https://img.shields.io/badge/View_Repo-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TejasDR01/AI-Log-Analyzer)

<br/>

</details>

---

<!-- ── PROJECT 3 ── -->
<details>
<summary><b>&nbsp;&nbsp;Zero-Trust Network Simulator&nbsp;&nbsp;</b>&nbsp;&nbsp;<code>Python</code>&nbsp;<code>Flask</code>&nbsp;<code>Network Architecture</code>&nbsp;&nbsp;&nbsp;[ click to expand ]</summary>

<br/>

<blockquote>Security architecture debates need data, not opinions. So I built the data.</blockquote>

A working simulation that benchmarks Zero-Trust policy enforcement against traditional perimeter security
across real attack scenarios — lateral movement, breach isolation, access decisions — all measured and reproducible.

<pre>
  Network Segments →  8
  Attack Scenarios →  5     (lateral movement)
  Containment Rate →  95%   vs. perimeter — 3× improvement
  Policy Eval Time →  &lt; 50ms per request
  Dashboard Refresh→  1s    real-time access decisions
</pre>

&nbsp;&nbsp;[![View Repo](https://img.shields.io/badge/View_Repo-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TejasDR01/Zerotrust-Network-Simulator)

<br/>

</details>

---

<!-- ── PROJECT 4 ── -->
<details>
<summary><b>&nbsp;&nbsp;CV-Based Workout Application&nbsp;&nbsp;</b>&nbsp;&nbsp;<code>Python</code>&nbsp;<code>TensorFlow</code>&nbsp;<code>OpenCV</code>&nbsp;&nbsp;&nbsp;[ click to expand ]</summary>

<br/>

<blockquote>Good form feedback shouldn't require a personal trainer in the room.</blockquote>

Real-time pose estimation pipeline that coaches your form mid-rep via a standard webcam.
24fps inference, 92% joint landmark accuracy, live corrective feedback, and longitudinal session tracking.

<pre>
  Landmark Accuracy→  92%   on standard webcam
  Frame Rate       →  24fps
  Exercise Types   →  10+
  Rep Precision    →  ± 1 rep
  Tracking Window  →  30+ day sessions  (6 metrics via SQLite)
</pre>

&nbsp;&nbsp;[![View Repo](https://img.shields.io/badge/View_Repo-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TejasDR01/CV-Based-Workout-App)

<br/>

</details>

---

<!-- ── PROJECT 5 ── -->
<details>
<summary><b>&nbsp;&nbsp;Artsy — Cross-Platform Artist Explorer&nbsp;&nbsp;</b>&nbsp;&nbsp;<code>Angular</code>&nbsp;<code>Kotlin</code>&nbsp;<code>Node.js</code>&nbsp;&nbsp;&nbsp;[ click to expand ]</summary>

<br/>

<blockquote>Two platforms should not mean two codebases.</blockquote>

One shared REST API backend serving both an Angular web app and a Kotlin Android app with full feature parity.
No duplicated business logic. No platform-specific hacks. Validated with a shared 3-level test strategy.

<pre>
  API Endpoints    →  15+
  Platforms        →  Web (Angular)  +  Android (Kotlin)
  Web Load Time    →  &lt; 2s
  Android FPS      →  60fps on mid-range devices
  Test Coverage    →  Unit · Integration · E2E
</pre>

&nbsp;&nbsp;[![View Repo](https://img.shields.io/badge/View_Repo-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/TejasDR01/Artsy-Artist-Explorer)

<br/>

</details>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,30&height=2" width="100%"/>

<br/>

<!-------------------------------------------------------------->
<!-- TECH STACK                                                  -->
<!-------------------------------------------------------------->

<h2>&nbsp;$ cat ./stack.config</h2>

<br/>

<div align="center">

<table>
<tr>
<td align="center" width="200"><b>Programming & Scripting</b></td>
<td>

![Python](https://img.shields.io/badge/Python-1a2035?style=flat-square&logo=python&logoColor=4DBBFF)
![C](https://img.shields.io/badge/C-1a2035?style=flat-square&logo=c&logoColor=4DBBFF)
![C++](https://img.shields.io/badge/C++-1a2035?style=flat-square&logo=cplusplus&logoColor=4DBBFF)
![Java](https://img.shields.io/badge/Java-1a2035?style=flat-square&logo=openjdk&logoColor=ED8B00)
![JavaScript](https://img.shields.io/badge/JavaScript-1a2035?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-1a2035?style=flat-square&logo=typescript&logoColor=3178C6)
![Kotlin](https://img.shields.io/badge/Kotlin-1a2035?style=flat-square&logo=kotlin&logoColor=7F52FF)
![Bash](https://img.shields.io/badge/Bash-1a2035?style=flat-square&logo=gnubash&logoColor=4EAA25)
![PowerShell](https://img.shields.io/badge/PowerShell-1a2035?style=flat-square&logo=powershell&logoColor=5391FE)
![Perl](https://img.shields.io/badge/Perl-1a2035?style=flat-square&logo=perl&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-1a2035?style=flat-square&logo=postgresql&logoColor=4169E1)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-1a2035?style=flat-square&logo=html5&logoColor=E34F26)

</td>
</tr>
<tr>
<td align="center"><b>Web Frameworks</b></td>
<td>

![React](https://img.shields.io/badge/ReactJS-1a2035?style=flat-square&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-1a2035?style=flat-square&logo=angular&logoColor=DD0031)
![Node.js](https://img.shields.io/badge/NodeJS-1a2035?style=flat-square&logo=nodedotjs&logoColor=339933)
![Express](https://img.shields.io/badge/Express-1a2035?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-1a2035?style=flat-square&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-1a2035?style=flat-square&logo=fastapi&logoColor=4DBBFF)
![GraphQL](https://img.shields.io/badge/GraphQL-1a2035?style=flat-square&logo=graphql&logoColor=E10098)
![WebSockets](https://img.shields.io/badge/WebSockets-1a2035?style=flat-square&logo=socketdotio&logoColor=white)

</td>
</tr>
<tr>
<td align="center"><b>DevOps & Cloud</b></td>
<td>

![AWS](https://img.shields.io/badge/AWS-1a2035?style=flat-square&logo=amazonaws&logoColor=FF9900)
![GCP](https://img.shields.io/badge/GCP-1a2035?style=flat-square&logo=googlecloud&logoColor=4285F4)
![Azure](https://img.shields.io/badge/Azure-1a2035?style=flat-square&logo=microsoftazure&logoColor=0078D4)
![Docker](https://img.shields.io/badge/Docker-1a2035?style=flat-square&logo=docker&logoColor=2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1a2035?style=flat-square&logo=kubernetes&logoColor=326CE5)
![Jenkins](https://img.shields.io/badge/Jenkins-1a2035?style=flat-square&logo=jenkins&logoColor=D24939)
![Ansible](https://img.shields.io/badge/Ansible-1a2035?style=flat-square&logo=ansible&logoColor=EE0000)
![Terraform](https://img.shields.io/badge/Terraform-1a2035?style=flat-square&logo=terraform&logoColor=7B42BC)
![Git](https://img.shields.io/badge/Git/GitHub-1a2035?style=flat-square&logo=git&logoColor=F05032)
![Linux](https://img.shields.io/badge/Linux-1a2035?style=flat-square&logo=linux&logoColor=FCC624)
![Jira](https://img.shields.io/badge/Jira-1a2035?style=flat-square&logo=jira&logoColor=0052CC)
![Postman](https://img.shields.io/badge/Postman-1a2035?style=flat-square&logo=postman&logoColor=FF6C37)
![CI/CD](https://img.shields.io/badge/CI%2FCD-1a2035?style=flat-square&logo=githubactions&logoColor=4DBBFF)

</td>
</tr>
<tr>
<td align="center"><b>Databases & Systems</b></td>
<td>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1a2035?style=flat-square&logo=postgresql&logoColor=4169E1)
![MySQL](https://img.shields.io/badge/MySQL-1a2035?style=flat-square&logo=mysql&logoColor=4479A1)
![MongoDB](https://img.shields.io/badge/MongoDB-1a2035?style=flat-square&logo=mongodb&logoColor=47A248)
![Redis](https://img.shields.io/badge/Redis-1a2035?style=flat-square&logo=redis&logoColor=DC382D)
![Kafka](https://img.shields.io/badge/Kafka-1a2035?style=flat-square&logo=apachekafka&logoColor=white)
![Unix/Linux](https://img.shields.io/badge/Unix%2FLinux-1a2035?style=flat-square&logo=linux&logoColor=FCC624)
![Networking](https://img.shields.io/badge/Networking-1a2035?style=flat-square&logo=cisco&logoColor=4DBBFF)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-1a2035?style=flat-square&logo=cloudflare&logoColor=F48120)

</td>
</tr>
<tr>
<td align="center"><b>AI / ML</b></td>
<td>

![TensorFlow](https://img.shields.io/badge/TensorFlow-1a2035?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![PyTorch](https://img.shields.io/badge/PyTorch-1a2035?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1a2035?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![OpenCV](https://img.shields.io/badge/OpenCV-1a2035?style=flat-square&logo=opencv&logoColor=5C3EE8)
![LangChain](https://img.shields.io/badge/LangChain-1a2035?style=flat-square&logo=chainlink&logoColor=4DBBFF)
![LLMs](https://img.shields.io/badge/LLMs-1a2035?style=flat-square&logo=openai&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-1a2035?style=flat-square&logo=numpy&logoColor=013243)
![Pandas](https://img.shields.io/badge/Pandas-1a2035?style=flat-square&logo=pandas&logoColor=150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-1a2035?style=flat-square&logo=plotly&logoColor=4DBBFF)

</td>
</tr>
<tr>
<td align="center"><b>Security Tools</b></td>
<td>

![Metasploit](https://img.shields.io/badge/Metasploit-1a2035?style=flat-square&logo=metasploit&logoColor=2596CD)
![Wireshark](https://img.shields.io/badge/Wireshark-1a2035?style=flat-square&logo=wireshark&logoColor=1679A7)
![Nmap](https://img.shields.io/badge/Nmap-1a2035?style=flat-square&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-1a2035?style=flat-square&logo=burpsuite&logoColor=FF6633)
![OpenSSL](https://img.shields.io/badge/OpenSSL-1a2035?style=flat-square&logo=openssl&logoColor=721412)
![Splunk](https://img.shields.io/badge/Splunk-1a2035?style=flat-square&logo=splunk&logoColor=65A637)
![Suricata](https://img.shields.io/badge/Suricata-1a2035?style=flat-square&logo=suricata&logoColor=orange)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-1a2035?style=flat-square&logo=kalilinux&logoColor=557C94)
![Nikto](https://img.shields.io/badge/Nikto-1a2035?style=flat-square&logo=linux&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-1a2035?style=flat-square&logo=owasp&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-1a2035?style=flat-square&logo=snort&logoColor=white)

</td>
</tr>
</table>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,30&height=2" width="100%"/>

<br/>

<!-------------------------------------------------------------->
<!-- CURRENTLY                                                   -->
<!-------------------------------------------------------------->

<h2>&nbsp;$ tail -f ./now.log</h2>

<pre>
  [ACTIVE]  MS CS @ USC — OS internals, applied cryptography, algorithm design
  [ACTIVE]  Exploring LLM-native tooling for real engineering workflows
  [ACTIVE]  Teaching Python as TA @ USC — explaining things sharpens thinking
  [READING] Distributed systems papers  •  NIST frameworks  •  occasional RFCs
  [SOON]    Something unreleased — still in the dark
</pre>

<br/>

<!-------------------------------------------------------------->
<!-- FUN FACTS                                                   -->
<!-------------------------------------------------------------->

<h2>&nbsp;$ grep --interesting ./debug.log</h2>

<pre>
  > Wrote a preemptive process scheduler before formally studying OS
  > Automated a CI/CD pipeline that caught a 2am prod incident — pipeline got the Slack credit
  > Ranked Top 30 in PicoCTF (CMU) — reverse engineering, cryptography, web exploitation
  > Certs: CompTIA Security+  •  Google Cybersecurity  •  AWS Cloud Practitioner
  > I read RFCs voluntarily. Actual RFCs.
  > Research published on DNS Security — protocol defenses and privacy enhancements
</pre>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=2,3,30&height=2" width="100%"/>

<br/>

<!-------------------------------------------------------------->
<!-- CTA                                                         -->
<!-------------------------------------------------------------->

<div align="center">

<h2>$ open --role "Software Engineer"</h2>

<pre>
  Target Roles  :  SWE  •  AI Engineering  •  Full-Stack  •  Backend  •  Systems
  Available     :  Post graduation  |  Open to relocation  |  Open to remote
  Location      :  Los Angeles, CA
</pre>

<br/>

[![Email](https://img.shields.io/badge/──────&nbsp;Email&nbsp;Me&nbsp;──────-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)&ensp;
[![LinkedIn](https://img.shields.io/badge/──────&nbsp;LinkedIn&nbsp;──────-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_HANDLE)&ensp;
[![Portfolio](https://img.shields.io/badge/──────&nbsp;Portfolio&nbsp;──────-111827?style=for-the-badge&logo=vercel&logoColor=white)](https://tejasdr01.github.io/Portfolio)

<br/>

*Hard problems preferred. Strong engineering culture required.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,30&height=100&section=footer" width="100%"/>

</div>
