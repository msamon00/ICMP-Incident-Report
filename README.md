# DNS / ICMP Incident Report

Analysis of a DNS/ICMP network incident using tcpdump, demonstrating how UDP port 53 failures prevent domain resolution and cause website inaccessibility.

## Objective
Demonstrate the identification and analysis of a DNS/ICMP network issue affecting DNS communication and user access.

## Approach
- Collected tcpdump logs during the incident
- Identified ICMP error responses indicating UDP port 53 unreachable
- Analyzed potential causes: firewall rules, server downtime, or misconfiguration
- Documented findings with screenshots and recommended remediation steps

## Findings
The tcpdump capture shows repeated ICMP errors when accessing UDP port <span class="mono">53</span>, preventing successful domain resolution and making the website inaccessible to users.

## Files
- `index.html` → Full incident report page
- `tcpdump.png` → Screenshot of tcpdump log
- `style.css` → CSS used for formatting
- `README.md` → Project overview and instructions

## Recommended Next Steps
1. Verify DNS server availability
2. Review firewall rules affecting UDP port 53
3. Contact the vendor to determine potential service outage or DoS attack
