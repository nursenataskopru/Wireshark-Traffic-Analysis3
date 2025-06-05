# Wireshark Traffic Analysis 3

This repository contains a Wireshark capture file (`capture_assignment3.pcapng`) used for analyzing DNS query and response messages as part of a computer networks assignment by Nursena Taşköprü

##  Assignment Tasks

The tasks performed during the analysis include:

- Identifying DNS query and response messages.
- Determining whether the transport protocol used is **UDP or TCP**.
- Finding source/destination **port numbers** for DNS messages.
- Checking whether a **DNS query** contains an answer section.
- Inspecting the **DNS response** message and listing the answers (e.g., CNAME records).

##  How to View

1. Open the `.pcapng` file using **Wireshark**.
2. Apply the filter
3. Review the `Info` column to identify queries and responses.
4. Expand the **DNS** protocol section to check:
- Query/response type
- Number of answers
- Contents of each answer (CNAME or A records, etc.)
5. Use the **UDP or TCP** header to identify the transport protocol.

## File List

- `capture_assignment3.pcapng` - Network capture file for analysis
- `NursenaTaskopru.pdf` - PDF report with screenshots and written answers

## Student Info

- Name: Nursena Taşköprü  
- Course: Computer Networks  
- Assignment: #3 - DNS Packet Analysis
