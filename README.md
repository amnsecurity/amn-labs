<div align="center">

# ⚡ AMN SECURITY — eJPTv2 Practice Range Platform ⚡
### 🎯 محاكاة عملية مطابقة بنسبة 100% لامتحان شهادة eJPTv2 (INE Security)
### 100% Identical Hands-On Practical Simulation Suite for eJPTv2 Exam

[![Author](https://img.shields.io/badge/Architect-Ayman%20Mahmoud%20Jasim-d4af37?style=for-the-badge&logo=shield)](https://www.linkedin.com/in/aymn-mahmoud)
[![Consultancy](https://img.shields.io/badge/Consultancy-AMN%20Security-0a0908?style=for-the-badge&logo=target&logoColor=d4af37)](https://amn.amnoffsec.workers.dev/)
[![Exam Match](https://img.shields.io/badge/Exam%20Simulation-eJPTv2%20100%25%20Match-gold?style=for-the-badge&logo=securityscorecard&logoColor=black)](https://ine.com/certifications/ejpt)
[![Platform](https://img.shields.io/badge/Engine-Windows%20%7C%20Kali%20Linux%20%7C%20macOS-141210?style=for-the-badge&logo=linux&logoColor=d4af37)](https://github.com/amnsecurity)
[![Docker](https://img.shields.io/badge/Infrastructure-Docker%20%26%20Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Version](https://img.shields.io/badge/Release-v1.0.0-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amnsecurity/amn-labs/releases)

---

### [🌐 Official Website](https://amn.amnoffsec.workers.dev/) &nbsp;•&nbsp; [💼 LinkedIn](https://www.linkedin.com/in/aymn-mahmoud) &nbsp;•&nbsp; [🐙 GitHub](https://github.com/amnsecurity) &nbsp;•&nbsp; [📸 Instagram](https://www.instagram.com/ixctw/)

---

</div>

> ### 🏆 إعلان التطابق والاعتماد العملي | eJPTv2 100% Practical Verification
> **هذه المنصة هي محاكاة عملية واقعية مطابقة بنسبة 100% لبيئة ومسارات وسيناريوهات امتحان eLearnSecurity Junior Penetration Tester v2 (eJPTv2) الصادر من معهد INE Security.**  
> صُممت وهُندست المعامل الـ 16 لتغطي كافة المجالات الأربعة الرئيسية للامتحان الحقيقي:
> 1. **تقييم المنهجيات والاستكشاف (Assessment Methodologies & Reconnaissance):** كشف الأجهزة، مسح المنافذ، تقييم الثغرات.
> 2. **تدقيق واستغلال الأنظمة والشبكات (Host & Network Auditing):** استغلال خدمات Windows و Linux الحقيقية (SMB, WinRM, SSH, RDP).
> 3. **اختراق تطبيقات الويب (Web Application Penetration Testing):** استغلال ثغرات CMS، ووردبريس، رفع الملفات، وحقن الأوامر.
> 4. **ما بعد الاختراق وتصعيد الصلاحيات (Post-Exploitation & PrivEsc):** سحب الأعلام (Flags)، كسر الهاشات، تصعيد الصلاحيات، والتحرك الجانبي داخل الشبكة المزدوجة (Pivoting).

---

## 📌 نبذة عن المنصة | About The Platform

منصة **AMN Security eJPTv2 Practice Range** هي بيئة تدريبية هجومية عملية متكاملة. 

تتميز المنصة بجمع كافة معامل الامتحان العملي (16 بيئة محاكاة واقعية) وأدلة الحلول التفاعلية الفاخرة داخل أداة تنفيذية موحدة `amn-labs.exe`، تتيح لك بضغطة زر واحدة تشغيل أي سيناريو امتحاني عبر حاويات Docker المعزولة تلقائياً، مع فتح دليل تفاعلي مفصل يشرح لك خطوات اجتياز السيناريو وتحصيل الأعلام خطوة بخطوة باللغتين العربية والإنجليزية.

---

## 🏛️ مطابقة اللابات الـ 16 لمحاور امتحان eJPTv2 الحقيقي

| # | المعمل التدريبي | eJPTv2 Domain & Curriculum | محور الامتحان العملي | الصعوبة |
|---|----------------|----------------------------|---------------------|---------|
| **01** | استكشاف الشبكة والأجهزة النشطة | `01_nmap_host_discovery` | Host Discovery, ICMP/ARP Sweep & Bypassing Firewalls | 🟢 Fundamental |
| **02** | ثلاثية فحص الخوادم وكشف الخدمات | `02-04_scan_the_server` (I, II, III) | Deep TCP/UDP Scanning, Service Detection & OS Fingerprint | 🟢 Fundamental |
| **03** | ميدان تدريب AMN (9 ثغرات متكاملة) | `05-13_amn_range` (9 Attack Chains) | Combined DMZ & Internal Network Foothold Exploitation | 🟡 Intermediate |
| **04** | تقييم الثغرات وفحص TLS و FTP | `14-16_vulnerability_assessment` | Vulnerability Assessment, SSL/TLS Ciphers & FTP Auditing | 🟡 Intermediate |
| **05** | استغلال ثغرات الخوادم والأنظمة | `17-19_system_host_based_attacks` | Exploiting System Misconfigurations & Local Services | 🟡 Intermediate |
| **06** | اختراق أنظمة ويندوز المتكامل | `17-21_exploiting_windows` | Windows SMB Relay, WinRM Shells & RDP Foothold | 🟡 Intermediate |
| **07** | تصعيد الصلاحيات في ويندوز | `22-25_windows_privesc_creds` | Windows Token Impersonation, Credential Dumping & SAM | 🔴 Advanced |
| **08** | استغلال خدمات وتطبيقات لينكس | `26-29_exploiting_linux` | Shellshock RCE, PHP Deserialization & SSTI Exploitation | 🟡 Intermediate |
| **09** | هجمات الشبكة واعتراض الحزم | `34-36_network_based_attacks` | ARP Cache Poisoning, Man-in-the-Middle & Rogue Services | 🟡 Intermediate |
| **10** | جمع المعلومات العميق والخدمات | `37-42_information_gathering_enumeration` | DNS Zone Transfers, MySQL Enumeration, SSH & SNMP Probing | 🟢 Fundamental |
| **11** | ما بعد اختراق ويندوز والتحرك الجانبي | `43-51_windows_exploitation_post_exploitation` | Looting, Registry Persistence & Internal Network Lateral Movement | 🔴 Advanced |
| **12** | ما بعد اختراق لينكس وتصعيد الجذر | `52-59_linux_exploitation_post_exploitation` | Linux SUID Binaries, Cron Jobs & Root Shadow Extraction | 🔴 Advanced |
| **13** | أتمتة ميتاسبلويت وواجهة Armitage | `60-61_armitage` | Exploitation Frameworks, MSF Automation & Multi-Target Attacks | 🟢 Fundamental |
| **14** | الميدان الضخم: تصعيد الصلاحيات (24 تحدي) | `62-85_privesc_persistence_megalab` | Complete 24-Task Multi-OS Privilege Escalation Exam Simulator | 🟣 Expert |
| **15** | حملات التصيد والهندسة الاجتماعية | `87_gophish` | Phishing Simulation & Social Engineering Assessment | 🟡 Intermediate |
| **16** | اختراق تطبيقات الويب وووردبريس | `88_wordpress_web_pentest` | WordPress Plugin Vulnerabilities, Web Shells & Web RCE | 🟡 Intermediate |

---

## 🚀 كيفية الاستخدام والتشغيل | Quick Start Guide

### المتطلبات الأساسية | Prerequisites:
* نظام التشغيل: **Windows 10/11** أو **Kali Linux / Ubuntu / macOS**.
* وجود **Docker Desktop** (وتقوم الأداة بفحصه وتشغيله تلقائياً).
* تحميل الملف التنفيذي المباشر **`amn-labs.exe`** من قسم [Releases](https://github.com/amnsecurity/amn-labs/releases).

---

### أوامر المنصة السريعة | CLI Commands:

#### 1. الإعداد الآلي الشامل وتحميل المتطلبات مسبقاً (موصى به عند أول تشغيل):
```bash
# Windows:
.\amn-labs.exe setup

# Linux / Kali:
python3 amn_labs.py setup
```
> **يقوم هذا الأمر تلقائياً بـ:**
> 1. فحص تواجد Docker وتثبيته آلياً عبر `winget` في حال عدم وجوده.
> 2. تشغيل خدمة Docker Desktop تلقائياً في الخلفية في حال كانت متوقفة دون أي تدخل منك.
> 3. تحميل كافة صور Docker الرسمية الأساسية مسبقاً وتخزينها، لتصبح عملية إطلاق أي معمل فورية وتستغرق ثانية واحدة فقط.

#### 2. استعراض قائمة اللابات المتاحة وحالتها:
```bash
.\amn-labs.exe list
```

#### 3. تشغيل معمل محدد وفتح الدليل التفاعلي الفاخر تلقائياً:
```bash
# تشغيل المعمل رقم 1:
.\amn-labs.exe start 1

# تشغيل الميدان التدريبي الشامل (المعمل رقم 3):
.\amn-labs.exe start 3
```
> **ملاحظة:** سيقوم البرنامج بفك تشفير المعمل في بيئة معزولة مؤقتة، تشغيل حاويات Docker في الخلفية (وتشغيل Docker Desktop تلقائياً إذا كان مقفلاً)، وإطلاق الدليل التفاعلي الفاخر تلقائياً في متصفحك الافتراضي على خادم محلي خاص.

#### 4. إيقاف المعمل وتنظيف البيئة بعد الانتهاء:
```bash
.\amn-labs.exe stop 1
```

#### 5. إيقاف كافة اللابات النشطة دفعة واحدة:
```bash
.\amn-labs.exe stop-all
```

#### 6. استعراض الدليل التفاعلي للمعمل دون تشغيل الحاويات:
```bash
.\amn-labs.exe guide 1
```

#### 7. فحص واختبار سلامة الأداة (Self-Verification):
```bash
.\amn-labs.exe verify
```


---

## 👤 معلومات المطور والجهة المطورة | Author & Consultancy

<div align="center">

### **المهندس أيمن محمود جاسم | Eng. Ayman Mahmoud Jasim**
**AMN Security للاستشارات والأمن الهجومي | Offensive Security Consultant**

<br/>

[![Official Website](https://img.shields.io/badge/Official%20Website-AMN%20Security-d4af37?style=for-the-badge&logo=googlechrome&logoColor=black)](https://amn.amnoffsec.workers.dev/)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayman%20Mahmoud-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aymn-mahmoud)
&nbsp;&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-amnsecurity-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amnsecurity)
&nbsp;&nbsp;
[![Instagram](https://img.shields.io/badge/Instagram-@ixctw-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/ixctw/)

<br/><br/>

<b>© 2026 AMN Security. All Rights Reserved. Engineered with Pride for Offensive Security Professionals.</b>

</div>
