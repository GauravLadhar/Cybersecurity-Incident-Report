# Cybersecurity Incident Report: Network Traffic Analysis

This project investigates a DNS connectivity issue affecting access to a client website, "www.yummyrecipesforme.com." Users reported receiving a “destination port unreachable” error when trying to load the site. Using network analysis tool data from a given tcpdump log, I examined the DNS and ICMP traffic logs to identify and troubleshoot the problem.

The investigation revealed that UDP requests to the DNS server’s port 53 were met with ICMP error messages, indicating that the port was unreachable. Findings suggest the DNS server was either down or improperly configured, preventing the DNS resolution process. This project provides a detailed breakdown of the issue, methodology, and insights gained from analyzing network protocols to diagnose and resolve connectivity issues.
