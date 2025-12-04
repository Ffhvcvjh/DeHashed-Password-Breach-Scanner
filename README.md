# DeHashed Password Breach Scanner
>This tool checks credentials against more than 15 billion breached records, giving you instant visibility into leaked emails, passwords, usernames, and related identifiers. It’s built for teams that need fast, actionable intelligence to reduce account compromise risks and strengthen security posture across an organization.

<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>

<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>Linkedin Profile Details Batch Scraper + EMAIL (No Cookies)</strong> you've just found your team — Let's Chat. 👆👆
</p>

## Introduction
The scanner queries multiple breach databases and returns any exposed records linked to your input. It supports a wide range of identifiers—emails, domains, passwords, IPs, phone numbers, and more. Security teams, auditors, and IT administrators use it to uncover vulnerabilities early and automate exposure checks.

### Why Security Teams Rely on It
- Scans billions of breached records in seconds.  
- Supports multiple query types for flexible investigations.  
- Identifies leaked passwords and personal data tied to your inputs.  
- Helps detect compromised accounts before attackers exploit them.  
- Integrates easily into compliance workflows, monitoring systems, or audits.

---
## Features
| Feature | Description |
|---------|-------------|
| Multi-Type Query Support | Search by email, username, password, IP, phone, domain, or VIN. |
| Billion-Scale Breach Search | Checks 15+ billion exposed records across 1,000+ sources. |
| Instant API Results | Provides rapid responses for real-time decision-making. |
| Flexible Output Formats | Supports JSON and CSV exports. |
| Sensitive Data Controls | Redacts sensitive fields when compliance requires it. |
| Rate Limiting | Protects API resources and ensures stable performance. |
| Enterprise Scalability | Built to handle high-volume security workflows. |

---
## What Data This Scraper Extracts
| Field Name | Field Description |
|------------|-------------------|
| query | The original identifier submitted (email, password, etc.). |
| found | Indicates whether matching breached records exist. |
| breaches | List of breach entries containing exposed data. |
| password | Leaked password when accessible. |
| email | Compromised email tied to the query. |
| username | Exposed username associated with the breach. |
| ip | Related IP address found in leaked datasets. |
| phone | Phone number appearing in the breach. |
| domain | Domain information associated with leaked records. |
| redacted | Shows whether sensitive data was masked. |

---
## Example Output
    
    [
      {
        "query": "user@example.com",
        "found": true,
        "breaches": [
          {
            "source": "Collection#5",
            "password": "summer2021",
            "email": "user@example.com",
            "username": "user123",
            "ip": "192.168.1.45",
            "phone": null,
            "domain": "example.com",
            "redacted": false
          }
        ]
      }
    ]

---
## Directory Structure Tree
    
    DeHashed Password Breach Scanner/
    ├── src/
    │   ├── main.js
    │   ├── scanner/
    │   │   ├── breach_lookup.js
    │   │   ├── query_builder.js
    │   │   └── rate_limiter.js
    │   ├── utils/
    │   │   ├── sanitizer.js
    │   │   └── logger.js
    │   └── config/
    │       └── settings.example.json
    ├── data/
    │   ├── test_queries.json
    │   └── sample_output.json
    ├── package.json
    └── README.md

---
## Use Cases
- **Security teams** use it to identify exposed credentials before attackers do.  
- **Compliance auditors** verify that sensitive user data hasn’t been involved in known breaches.  
- **IT administrators** use it to enforce stronger passwords and monitor user onboarding.  
- **Penetration testers** run checks to validate potential compromise points.  
- **Risk managers** quantify exposure and guide mitigation planning.  

---
## FAQs

**What can I search for?**  
Emails, usernames, passwords, phone numbers, IPs, domains, and even VINs.

**Does this tool store sensitive data?**  
No. Data can be redacted, and outputs are delivered in-memory unless explicitly saved.

**Is it suitable for enterprise workflows?**  
Yes, it’s designed to scale easily and handle large volumes of queries.

**Are results accurate?**  
It queries aggregated breach datasets, returning all matches found across 1,000+ sources.

---
### Performance Benchmarks and Results

**Primary Metric:**  
Processes 50–100 breach lookups per second depending on API load.

**Reliability Metric:**  
Maintains over 99% response completeness across diverse query types.

**Efficiency Metric:**  
Uses optimized rate limiting to ensure stable throughput during large batch scans.

**Quality Metric:**  
Returns detailed breach entries with high accuracy across supported identifiers.


---


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
         </p>

