# IP Reputation Investigation Report

## Objective

The objective of this project is to investigate the reputation of an IP address using multiple Open Source Intelligence (OSINT) tools and determine whether the IP is malicious or legitimate.

---

## IP Investigated

**IP Address:** 8.8.8.8

---

## Tools Used

- VirusTotal
- AbuseIPDB
- WHOIS

---

## Investigation Results

### VirusTotal

- Detection Score: **0/91**
- Community Score: **552**
- ASN: **AS15169**
- Organization: **Google LLC**
- Country: **United States**
- Observation: No security vendor flagged the IP as malicious.

### AbuseIPDB

- Abuse Confidence Score: **0%**
- Total Reports: **166**
- ISP: **Google LLC**
- Usage Type: **Content Delivery Network**
- Hostname: **dns.google**
- Country: **United States**

### WHOIS

- Organization: **Google LLC**
- ASN: **AS15169**
- Country: **United States**

---

## Analysis

The IP address **8.8.8.8** belongs to **Google Public DNS**. Although AbuseIPDB contains reports related to this IP, the Abuse Confidence Score is **0%**, and VirusTotal reports **0 detections out of 91 security vendors**. This indicates that the IP is widely used and trusted rather than malicious.

---

## Conclusion

Based on the investigation across VirusTotal, AbuseIPDB, and WHOIS, the IP address **8.8.8.8** is considered **legitimate** and **not malicious**. This investigation demonstrates how multiple threat intelligence sources can be used to validate an IP address before making a security decision.
