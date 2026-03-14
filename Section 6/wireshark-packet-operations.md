# Wireshark: Packet Operations

## Overview
This room focuses on how to work with packets in Wireshark. It explains how analysts capture, filter, and examine packets to investigate network activity.

## Key Concepts
- Packet capturing allows analysts to record network traffic for analysis.
- Each packet contains information such as source IP, destination IP, protocol, and payload data.
- Packet filtering helps analysts focus only on relevant traffic.

## Important Operations
- Capturing live network traffic
- Applying display filters
- Inspecting packet details
- Following packet streams
- Exporting captured packets for investigation

## Common Filters Used
Some useful filters in Wireshark include:
- `ip.addr == x.x.x.x`
- `tcp`
- `dns`
- `http`
- `icmp`

## SOC Analyst Perspective
SOC analysts use packet operations in Wireshark to investigate alerts, identify suspicious communications, and analyze potential attacks such as malware traffic, command-and-control connections, or data exfiltration.

## Key Takeaways
- Packet filtering helps analysts quickly locate important traffic.
- Understanding packet structure is essential for network investigations.
- Wireshark is a powerful tool for analyzing network behavior.
