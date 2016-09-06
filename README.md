# Anomaly-Detection-by-Netflow-and-DNS-Analysis-of-Alexa-1M-websites
The Domain Name System is a fundamental component of the internet since it maps the easy-to-remember domain names to IP addresses. Therefore, it is usually the primary target for most of the malicious attacks such as DNS Poisoning and Rogue DNS servers. With the help of 0x20 bit encoding, the problem of DNS Poisoning is mitigated to quite a large extent. Although, it has a minor requirement that the authoritative nameserver should be able to preserve the case of the DNS query. It is usually difficult to detect the rogue DNS server above the stub resolver. We propose an anomaly detection system which would be able to raise a red flag in case of DNS Poisoning and malicious DNS authority by passive DNS analysis of domain names and then comparing them with the 0th day cluster of the database. We perform the passive DNS analysis for 27 days by querying the whois server of CYMRU, compare the network profiles of the domain names crawled with the 0th day cluster and categorize the domain names as static, benign anomaly and malicious anomaly depending upon the cluster a domain name shifted. In the process, we also create a WHOIS repository for Alexa domain names which is faster to query than the WHOIS server.
