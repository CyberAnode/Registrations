---
title: "RST Cloud"
headquarters: "NSW"
product_categories:
- Threat Intelligence

email: info@rstcloud.net
twitter: https://twitter.com/rst_cloud
linkedin: https://www.linkedin.com/company/rst-cloud/
youtube: https://www.youtube.com/@rst-cloud/
github: https://github.com/rstcloud
facebook: https://www.facebook.com/rstcloud.online
website: https://www.rstcloud.com/
address: 60 Martin Place, Sydney NSW 2000
image: "/assets/images/company_logos/rstcloud.png"
---

## Who we are                     
Established in Australia in 2023, RST Cloud is a cutting-edge technology company that specialises in threat intelligence solutions for businesses of all sizes. We offer a range of flexible and scalable solutions that can be customised to meet the unique needs of your business.

Our approach includes the democratisation of threat intelligence, leveraging machine learning, automation, and artificial intelligence to ensure that the knowledge we produce is actionable to the extent that machines can facilitate end-to-end detection, prevention, and response, relying on data sourced from RST Cloud. 


## What we do
We provide threat intelligence products focusing on the needs of SecOps teams of different sizes:
 - Threat intelligence feeds for Threat Detection/Prevention/Hunting
 - SOC tools to minimise False Positives and improve enrichment
 - Threat report collection automation for CTI analysts
 - Blocking lists for firewalls, WAFs, EDR solutions
 - Additional APIs to help cyber teams automate their tasks


## Our products
### [RST Threat Feed](https://www.rstcloud.com/rst-threat-feed/)

A comprehensive threat intel feed of indicators (IP, Domain, URL, Hash) with their relationships to malware, TTPs, tools, threat groups, sectors, CVE, and other objects.

Compiled from over 260 sources, including Twitter, Telegram, online sandboxes (Any.Run, Hybrid Analysis, VMRay, etc.), threat reports, CERTs, malware research sites, GitHub, pastebin, closed sources and our global RST Honeypot network.


### [RST Report Hub](https://www.rstcloud.com/rst-report-hub/)

An electronic library of threat reports from hundreds of security companies, individual researchers and cyber communities. 

These reports undergo transformation from human-readable formats to machine-readable ones, including STIX 2.1. Extensive multilingual translation, archiving as PDFs, and summarization are conducted. Key data, encompassing threat actors, names, software, CVEs, geolocation, industry, etc., is automatically extracted, with due credit to the original report author.


### [RST Noise Control](https://www.rstcloud.com/rst-noise-control/)

A service that can be used with TIP, SOAR, or SIEM solutions to minimise the noise coming from False Positive indicators. Make sure that CDN IPs, known domains, common URLs, or hashes of calc.exe don't trigger alerts.

This API employs over 110 rulesets and incorporates 12 GB of individual exceptions, to check if indicators are “known-good” and to be considered noise.


### [RST IoC Lookup](https://www.rstcloud.com/rst-ioc-lookup/)

An API to check individual values if they are a suspicious or malicious indicator (IP, Domain, URL, Hash). Offering dynamic scoring and automatic decay of outdated indicators, the service ensures fair request rate with low cost.

Ideal for real-time checks in SOAR or be integration into custom applications for online user connection scrunity.


### [RST Whois API](https://www.rstcloud.com/rst-whois-api/)

A service to get actual registration info in JSON format for a given domain without limitations on speed and no ban from WHOIS servers. The results include whenever possible:
 - Data in a unified JSON format
 - Registrar and registrant info
 - Age of the domain
 - Dates (registered, updated, expires)
 - Raw response from WHOIS servers


### [RST Browser Plugin](https://chrome.google.com/webstore/detail/rst-threat-feed-lookup/hkmnjjegighdiojodphipafmkhlgcpba)

An easy-to-use Chrome browser plugin facilitates quick Indicators of Compromise searches. Simply select any text on a webpage, right-click, and choose the "RST IoC Lookup" option from the context menu to perform a lookup that identifies potential threats and provides valuable information including scores, malware, threat actors, descriptions, tags, and references.