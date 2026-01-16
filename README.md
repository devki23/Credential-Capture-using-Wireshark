# Credential Capture using Wireshark

## Objective
The objective of this task is to capture network traffic
and identify login credentials transferred over the network.

## Target Website
http://testphp.vulnweb.com/

## Tool Used
- Wireshark
- Web Browser

## Task Description
Wireshark is a network packet analyzer used to capture
and analyze network traffic. If a website uses insecure
protocols, sensitive data like usernames and passwords
can be seen in plain text.

In this task, login traffic is captured and analyzed
using Wireshark.

## Steps Performed
1. Started Wireshark and selected the network interface.
2. Opened the target website in browser.
3. Logged into the website.
4. Captured HTTP packets in Wireshark.
5. Analyzed packets to find login credentials.
6. Took screenshots of captured packets.

## Output
The captured packets show HTTP requests containing
login credentials in readable format.
Capture file is included.

## Learning Outcome
- Learned how network traffic can be monitored.
- Understood the risk of using HTTP instead of HTTPS.
- Gained hands-on experience with Wireshark.

## Disclaimer
This task was performed for educational purposes only
on a legal and intentionally vulnerable website.
