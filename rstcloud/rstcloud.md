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
We provide threat intel products focusing on the needs of SecOps teams of different sizes:
 - threat intelligence feeds for Threat Detection/ Prevention / Hunting
 - SOC tools to minimise False Positives and improve enrichment
 - threat report collection automation for CTI analysts
 - blocking lists for firewalls, WAFs, EDR solutions
 - addiitonal APIs to help cyber teams to automate their tasks


## Our products
### [RST Threat Feed](https://www.rstcloud.com/rst-threat-feed/)

A comprehensive threat intel feed of indicators (IP, Domain, URL, Hash) with their relationships to malware, TTPs, tools, threat groups, sectors, CVE, and other objects.

It is collected, aggregated, filtered, enriched, cross-correlated, and ranked across more than 260 of sources including: Twitter, Telegram, online sandboxes (Any.Run, Hybrid Analysis, VMRay, etc.), threat reports (malware analysis, DFIR, APT reports, Advisories, Alerts, articles and blogs), CERTs, Malware reseach websites, github, pastebin, close sources and own global RST Honeypot network.


### [RST Report Hub](https://www.rstcloud.com/rst-report-hub/)

An electronic library of threat reports from hundreds of security companies, individual researchers and communities, transformed from human readable formats into machine-readable formats (incl. STIX 2.1).

Each report is translated from non-English languages (Russian, Chinese, Spanish, Korean, etc) to English and saved as a PDF copy for archiving purposes. Then a summary of the report is generated with key facts and the main idea as separate notes and more importantly all the key data is auto-extracted from each report (threat actors, threat names, software, CVE, geo, industry, etc) with a reference to the original author of the report.
.


### [RST Noise Control](https://www.rstcloud.com/rst-noise-control/)

A service that can be used with TIP, SOAR, or SIEM solutions to minimise the noise coming from indicators that causing a lot of FPs. Make sure that CDN IPs, known domains of Microsoft 365, common URLs, or hashes of calc.exe are not raising tickets.

In a nutshell, this API allows to check if an indicator or a batch of indicators are “known-good” and to be considered noise based on more than 110 rulesets and more than 12 Gb of individual exceptions for IP, Domains, URLs, and Hashes.


### [RST IoC Lookup](https://www.rstcloud.com/rst-ioc-lookup/)

An API to check individual values if they are a suspicious or malicious indicator (IP, Domain, URL, Hash). The service provides Dynamic scoring with auto-decaying old indicators and provides fair request rate with low cost.

Useful to be used in SOAR to do a real-time check or to be integrated with a custom application for online checks of user conenctions or their input. This API also can be used together with RST Browser Plugin.


### [RST Whois API](https://www.rstcloud.com/rst-whois-api/)

A service to get actual registration info in JSON format for a given domain without limitations on speed and no ban from WHOIS servers.

You can query from 1 to 1M requests a day, there is no difference. The results include whenever possible:
 - Data in a unified JSON format for all possible WHOIS server responses
 - Registrar and registrant info
 - Age of the domain
 - Dates (registered, updated, expires)
 - Raw response from WHOIS servers

### [RST Browser Plugin](https://chrome.google.com/webstore/detail/rst-threat-feed-lookup/hkmnjjegighdiojodphipafmkhlgcpba)

A simple to use Chrome browser plugin allows you quickly search for Indicators of Compromise (IoCs) using the RST Threat Feed API. Simply select any text on a webpage, right-click, and choose the "RST IoC Lookup" option from the context menu to perform a lookup. It helps you identify potential threats and provides valuable information about IoCs, including scores, malware family, threat actors, descriptions, tags, and references.