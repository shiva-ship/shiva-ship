<h1 align="center">Hi, I'm Shivansh Rastogi 👋</h1>

<h3 align="center">Java backend engineer · API security  · MSc Cybersecurity @ Universität des Saarlandes</h3>

<p align="center">
  <img src="https://img.shields.io/badge/📍-Saarbrücken%2C%20Germany-0969da?style=flat-square" alt="Saarbrücken, Germany" />
  <img src="https://img.shields.io/badge/🏆-ADS--TEC%20Hackathon%201st%20Place-d4a017?style=flat-square" alt="ADS-TEC Hackathon 1st place" />
  <img src="https://img.shields.io/badge/🏅-TIAA%20Titan%20Award-8250df?style=flat-square" alt="TIAA Titan Award" />
</p>

---

## 🧑‍💻 About me

I build and secure backend systems. I spent **2+ years at TIAA** working on production Java and Spring Boot microservices in financial services, and I'm now doing an **MSc in Cybersecurity** at Universität des Saarlandes.

- 🔐 I secure REST and GraphQL APIs with **OAuth 2.0, OIDC and Azure AD**, and test applications against the **OWASP Top 10**
- 🤖 I'm experimenting with **MCP and local LLMs** (Ollama + Mistral) to learn how agents call tools and what access they need
- 📡 Off the clock: **software-defined radio**, ADS-B flight tracking and home-network security. My German amateur radio licence (Class E) is in progress
- 📚 Currently preparing for **CompTIA Security+ (SY0-701)**
- 🌍 I speak English (professional) and German (B1)

## 🛠️ Tech stack

**Backend**

![Java](https://img.shields.io/badge/Java%2017%20%7C%2021-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![REST](https://img.shields.io/badge/REST%20APIs-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Avro](https://img.shields.io/badge/Apache%20Avro-1D4E89?style=for-the-badge&logo=apache&logoColor=white)

**API security and identity**

![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![OpenID Connect](https://img.shields.io/badge/OpenID%20Connect-F78C40?style=for-the-badge&logo=openid&logoColor=white)
![Azure AD](https://img.shields.io/badge/Azure%20AD-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Gravitee](https://img.shields.io/badge/Gravitee%20AM-1E2A3A?style=for-the-badge&logoColor=white)

**Security**

![OWASP](https://img.shields.io/badge/OWASP%20Top%2010-000000?style=for-the-badge&logo=owasp&logoColor=white)
![VAPT](https://img.shields.io/badge/VAPT-B22222?style=for-the-badge&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![CVE Research](https://img.shields.io/badge/CVE%20Research-4B0082?style=for-the-badge&logoColor=white)

**Platform, DevOps and AI**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## 💼 Experience

### Software Engineering Analyst, TIAA (Financial Services)
*May 2022 – October 2024*

- Supported **8 of 43** Java and Spring Boot microservices on a six-person agile release train team. I owned 4 of them and created 2 new ones
- **Revived a shelved project**: moved two services from RabbitMQ to **Kafka + Avro**, upgraded **Java 17 → 21**, added the compliance requirements and deployed cloud-native on **OpenShift**
- Replaced REST calls with **GraphQL** and added **Guava caching**, saving **7 s per request** and **up to 3,000 DB calls per business day**
- Built an automated change workflow that cut approvals from **~13 days of email to 37 minutes**. It won the **Titan Award for Excellence in Innovation**, and I was the youngest recipient
- Ran a hard-switch cutover with MongoDB migration scripts covering ~2,500 objects with **zero downtime**, and brought duplicate processing down to zero
- Secured microservice APIs with **OAuth 2.0 bearer tokens from Azure AD** (scopes and roles), and set up **Gravitee Access Management** as an **OIDC** provider

### Vulnerability Assessment & Penetration Testing Intern, Probosys
*March 2022 – May 2022*

- Tested **2 applications, 200+ libraries and ~70 API calls** against the **OWASP Top 10** and documented the findings

## 🚀 Projects

| Project | What it does |
| --- | --- |
| 🏆 **OT firmware update orchestrator**<br><sub>ADS-TEC hackathon · 1st place</sub> | A Dockerized orchestrator for the ads-tec IRF industrial router firewall. It automates firmware updates across devices from multiple vendors using pluggable drivers, enforces a strict *stop → update → run* sequence, halts and reports on failure, and authenticates to vendor APIs with OAuth 2.0 |
| 📶 **Wireless network security assessment** | Captured and analysed traffic from my own Zyxel access point with Wireshark, verified its WPA2 cryptography, researched related CVEs and wrote a formal assessment report |
| 🤖 **Agentic and local AI tooling** | Experiments with **MCP** and **Ollama** running Mistral locally, to understand how agents call tools and what access they need |
| 🗣️ **Spoken language identification** | Fine-tuned **MMS 300M** on **22 Indian languages** and packaged it with Docker |
| ✈️ **ADS-B flight tracking feeder** | A Raspberry Pi Zero 2 W with an RTL-SDR running dump1090, feeding live aircraft data to Flightradar24 |

## 🎓 Education

| Degree | Institution | Years |
| --- | --- | --- |
| **MSc Cybersecurity** | Universität des Saarlandes, Saarbrücken | 2024 – 2027 |
| **B.Tech Information Technology** (GPA 9.05/10) | Vishwakarma Institute of Technology, Pune | 2019 – 2023 |

## 🏅 Awards

- 🥇 **1st Place, ADS-TEC Industrial IT Hackathon** (organized by NXTGN), November 2026
- 🏆 **Titan Award for Excellence in Innovation**, TIAA (youngest recipient)

---

<p align="center"><i>Always happy to talk about backend engineering, API security, and anything with an antenna attached 📡</i></p>
