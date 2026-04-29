<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1f2e,100:FF0000&height=180&section=header&text=Granger%20Security&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Cybersecurity%20Education%20%7C%20SOC%20Analyst%20%7C%20Threat%20Intelligence&descSize=16&descAlignY=58&descColor=FF0000" />

[![YouTube](https://img.shields.io/badge/YouTube-Granger_Security-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![Subscribers](https://img.shields.io/badge/Subscribers-199+-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)
[![Videos](https://img.shields.io/badge/Videos_Published-89-FF4500?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Granger-Security)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-bhargav--baranda-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/bhargav-baranda)
[![Portfolio](https://img.shields.io/badge/Security_Portfolio-Bhargav--Baranda-181717?style=flat-square&logo=github)](https://github.com/Granger0007/Bhargav-Baranda-Portfolio)
[![ISC² CC](https://img.shields.io/badge/ISC²-Certified_in_Cybersecurity-00599C?style=flat-square)](https://www.isc2.org/certifications/cc)
[![Royal Holloway](https://img.shields.io/badge/Royal_Holloway-ACE--CSR_(NCSC%2FGCHQ)-003087?style=flat-square)](https://www.royalholloway.ac.uk)

</div>

---

## 📺 About This Channel

**Granger Security** is a cybersecurity education channel built by a security analyst — documenting the real process of building SOC capabilities from scratch, in public.

No polished course content. No scripted perfection. Real lab work, real mistakes, real detections.

**Who this is for:**
- Aspiring SOC analysts breaking into the field
- Security+ candidates who want concepts tied to real SOC scenarios
- Career changers who need proof that the transition is possible
- Anyone building a home lab and hitting the same ARM64 walls I hit

**89 videos published. Still going.**

---

## 📁 Repository Structure

```
granger-security-youtube/
├── 📁 cve-analysis/               ← Per-CVE research, writeups, MITRE mapping
│   └── [CVE-YYYY-XXXXX]/
│       ├── research-notes.md     ← Raw intelligence gathered
│       ├── mitre-mapping.md      ← ATT&CK tactic/technique/sub-technique
│       ├── video-script.md       ← Full narration script
│       └── description.md        ← YouTube SEO description + timestamps
├── 📁 threat-intel-briefs/        ← Weekly threat landscape summaries
│   └── [YYYY-MM-DD]/
│       ├── brief.md              ← Full written brief
│       └── sources.md            ← Verified sources with dates
├── 📁 soc-lab-walkthroughs/       ← Lab investigation companion writeups
│   └── [topic]/
│       ├── walkthrough.md        ← Step-by-step with screenshots
│       └── detection-rules/      ← Sigma/SPL/KQL produced in the session
├── 📁 security-plus/              ← Exam concept breakdowns tied to SOC reality
│   └── [domain]/
│       ├── concepts.md           ← Explained with SOC scenario anchors
│       └── practice-questions.md ← With full answer breakdowns
├── 📁 templates/
│   ├── video-script-template.md  ← Standard script structure
│   ├── cve-research-template.md  ← CVE analysis framework
│   └── youtube-description.md    ← SEO description template
└── 📁 assets/
    └── thumbnails/               ← Thumbnail concepts and text
```

---

## 🎬 Content Pillars

<table>
<tr>
<td width="50%" valign="top">

### 🔴 CVE Analysis
Breaking vulnerabilities — explained for analysts, not just researchers.

Every CVE video includes:
- Affected versions and patch status
- MITRE ATT&CK technique mapping
- Detection opportunity (what does exploitation look like in logs?)
- Splunk/Sigma detection rule where applicable
- Companion writeup linked in description

</td>
<td width="50%" valign="top">

### 🟡 Threat Intel Briefs
Weekly cybersecurity news — framed for the SOC, not the headlines.

Format: What happened → Who's behind it → What TTPs were used → What should a SOC analyst watch for → Detection opportunity.

Verified sources only. Every item dated and cited.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔵 SOC Lab Walkthroughs
Live investigations from the ARM64 home lab.

Real tool output. Real Splunk queries built from scratch. Real Suricata alerts. Real Wazuh detections. If something breaks on camera, it stays in — that's how learning actually works.

Every walkthrough links to a GitHub writeup with the detection rules produced.

</td>
<td width="50%" valign="top">

### ⚪ Security+ Explained
SY0-701 concepts tied to SOC reality — not just definitions.

Format: "Here's what the exam says → here's what it looks like in a real alert → here's how you'd handle it in a SOC."

Designed for candidates who want to understand it, not just pass it.

</td>
</tr>
</table>

---

## 📋 Video Production Workflow

```
1. RESEARCH       → Verify CVE/threat intel from primary sources (NCSC, CISA, NVD, vendor)
2. MITRE MAPPING  → Tactic → Technique → Sub-technique → Observed Procedure
3. SCRIPT         → Hook → Problem → Investigation → Detection → Lesson
4. RECORD         → Screen capture of actual lab work where possible
5. EDIT           → iMovie — clean cuts, chapters, timestamps
6. DESCRIPTION    → SEO-optimised title + keyword-rich description + timestamps
7. PUBLISH        → YouTube + community post + LinkedIn writeup
8. PORTFOLIO      → GitHub companion writeup committed same day
```

---

## 🔗 Content × Portfolio Integration

Every significant video maps to a GitHub writeup in the [Security Operations Portfolio](https://github.com/Granger0007/Bhargav-Baranda-Portfolio).

| Video Type | GitHub Output |
|---|---|
| CVE Analysis | `/threat-intel/campaign-analysis/[CVE]/` |
| Lab Walkthrough | `/incidents/[case-XXX]/` + detection rules |
| Detection Rule Build | `/detection-rules/sigma/` + `/splunk-spl/` + `/sentinel-kql/` |
| Threat Intel Brief | `/threat-intel/apt-profiles/` or `/campaign-analysis/` |

**The principle:** YouTube builds the audience. GitHub builds the proof. LinkedIn builds the network. Every piece of content feeds all three.

---

## 📌 Featured CVE Analysis

| CVE | Title | CVSS | Video |
|---|---|:---:|---|
| CVE-2024-20353 | Cisco Catalyst SD-WAN Auth Bypass | 8.6 | [▶ Watch](https://youtube.com/@Granger-Security) |
| *More added weekly* | — | — | — |

---

## 🎓 About the Creator

**Bhargav Baranda** — MSc Information Security graduate and security analyst building toward UK SOC analyst roles.

- 📚 MSc Information Security — Royal Holloway, University of London (2025)
  *Formally recognised as an Academic Centre of Excellence in Cyber Security Research by NCSC and GCHQ*
- 🏅 ISC² Certified in Cybersecurity (CC)
- 🔄 CompTIA Security+ SY0-701 — in progress, expected Q2 2026
- 🔬 Home lab: Apple Silicon ARM64 · UTM · Kali Linux · Splunk · ELK · Suricata · Wazuh
- 📋 9 SOC labs documented across network analysis, threat detection, and packet forensics
- 🎯 Actively seeking SOC Analyst roles across the UK market

The channel exists because I couldn't find content that showed the *actual process* of building these skills — not the polished end result, but the real work. The labs I publish here are the same labs I'm using to build my portfolio and land a job.

---

## 📬 Get In Touch

| Channel | Link |
|---|---|
| 📺 YouTube | [@Granger-Security](https://youtube.com/@Granger-Security) |
| 💼 LinkedIn | [linkedin.com/in/bhargav-baranda](https://www.linkedin.com/in/bhargav-baranda) |
| 💻 GitHub | [github.com/Granger0007](https://github.com/Granger0007) |
| 📧 Email | bbaranda055@gmail.com |

---

<div align="center">

*All scripts, research notes, and detection rules in this repository are freely available under the MIT License.*
*Subscribe. Learn. Build.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF0000,50:1a1f2e,100:0d1117&height=100&section=footer"/>

</div>
