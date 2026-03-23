---
description: >-
  Tool Description : An internet scanning and reconnaissance platform that
  continuously indexes exposed devices, services, and infrastructure across the
  global internet.
---

# Censys

| **Censys**       | **Quick Overview**                                                                                                                      |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://censys.com/](https://censys.com/)                                                                                              |
| What it does     | Searches and maps internet-facing assets (servers, IPs, domains, certificates) using continuous scanning and indexing.                  |
| How to use it    | Search by IP, domain, certificate, or service, filter results , then analyse exposed infrastructure and metadata.                       |
| Cost             | Partially free.                                                                                                                         |
| Account required | No for basic use. Yes for full functionality.                                                                                           |
| Cookies          | The cookies used collectively enable user identification, session tracking, behavioural analytics, ad targeting, and referral tracking. |
| Ownership        | Censys Inc, founded by Zakir Durumeric, Brian Kelly and David Adrian.                                                                   |
| Use in Reporting | Used in cybersecurity investigations, infrastructure mapping, attribution, and identifying exposed or vulnerable systems.               |

### **What does Censys do?**

Censys continuously scans the internet to discover and index publicly accessible devices and services, including servers, websites, databases, and IoT systems. It collects metadata such as open ports, SSL/TLS certificates, protocols, and software configurations, allowing users to search and analyse global internet infrastructure.

**The lowdown:** It’s essentially a search engine for the internet’s exposed infrastructure, showing what devices are online, how they’re configured, and who might be behind them.

### How to Use:

1. **Enter an IP address, domain name, certificate fingerprint, or organisation into the search bar. You can also enter a query as in the below:**

<figure><img src="../.gitbook/assets/unknown (46).png" alt=""><figcaption></figcaption></figure>

**For example, you can find hosts by country, city or state:**

<figure><img src="../.gitbook/assets/unknown (47).png" alt=""><figcaption></figcaption></figure>

<br>

2. **Filter and refine results using attributes like ports, services, location, or software.**<br>
3. **Analyse the returned data to identify infrastructure, detect vulnerabilities, or map networks.**<br>

_NB: For full search capabilities, unlimited queries, historical datasets, API access, and advanced filtering options, you’ll need a paid account._

### Cost:

* [ ] Paid
* [x] Partially Free
* [ ] Free

Basic use is free but advanced use requires payment.&#x20;

## Data Processing

### Account required:

* [x] Yes
* [x] No

The free tier allows limited searches and basic functionality.

To perform advanced queries, access full datasets, historical data, or API features, you must create a registered account.

### Cookies:

Cookies show that Censys and its third-party services (Twitter/X, Bing, t.co) track user behaviour, identify devices, monitor site usage, and support analytics, personalisation, and advertising.

### Use in Reporting

Censys can support:

* Cybersecurity investigations
* Identifying exposed servers or databases
* Attribution of infrastructure to organisations
* Tracking malicious infrastructure (e.g., phishing, malware servers)
* Supporting vulnerability and risk assessments

As a real-world example, Censys was used by cybersecurity researchers and journalists to investigate exposed servers and infrastructure linked to the [2020 SolarWinds hack.](https://www.forbes.com/sites/thomasbrewster/2021/01/06/1500-solarwinds-customers-are-exposing-themselves-to-hackers-as-russian-espionage-continues/)

| **Capabilities**                              | **Limitations**                                                            |
| --------------------------------------------- | -------------------------------------------------------------------------- |
| Global internet-wide scanning.                | Only shows publicly exposed systems rather than internal/private networks. |
| Search by IP, domain, certificate or service. | Data may not always be in real-time.                                       |
| SSL/TLS certificate tracking and analysis.    | Requires technical knowledge to interpret results.                         |
| Identification of open ports and services.    | The free tier has query limits.                                            |
| Infrastructure mapping and fingerprinting.    | Attribution to individuals can be difficult or uncertain.                  |

### Summary

Censys is a powerful OSINT tool for discovering and analysing internet-facing infrastructure, essential for cybersecurity and digital investigations. It's most useful in the collection and exploitation stages of the OSINT workflow, enabling investigators to identify exposed systems, map networks, and uncover technical details about online assets.

### Ownership

Censys is a series C company based in Ann Arbor (United States), founded in 2015 by Zakir Durumeric, Brian Kelly and David Adrian.

### Ethical Considerations:

* Data should be used responsibly and legally.
* Do not attempt unauthorised access to discovered systems.
* Be mindful of the risk of misinterpretation of technical data.
* Should be used for defensive, research, or investigative purposes only.



### Related Tools:

* [Shodan](shodan.md)
* ZoomEye
* BinaryEdge



#### Sources:

[https://censys.com/](https://censys.com/)&#x20;

[https://tracxn.com/d/companies/censys/\_\_3GBTZqJCaQp-ZndBecQ520W1m3sHRu0I1EvfHliOlkA](https://tracxn.com/d/companies/censys/__3GBTZqJCaQp-ZndBecQ520W1m3sHRu0I1EvfHliOlkA)&#x20;

[https://www.forbes.com/sites/thomasbrewster/2021/01/06/1500-solarwinds-customers-are-exposing-themselves-to-hackers-as-russian-espionage-continues/](https://www.forbes.com/sites/thomasbrewster/2021/01/06/1500-solarwinds-customers-are-exposing-themselves-to-hackers-as-russian-espionage-continues/)

[https://dev.to/stark\_zhuang\_df5076f35c68/top-5-technical-asset-discovery-tools-in-osint-5a64](https://dev.to/stark_zhuang_df5076f35c68/top-5-technical-asset-discovery-tools-in-osint-5a64)&#x20;

[https://x.com/censysio](https://x.com/censysio)

