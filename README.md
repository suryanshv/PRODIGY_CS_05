# PRODIGY_CS_05
Network Packet Analyzer
This packet sniffer tool is a Python-based program designed to capture, analyze, and log network traffic in real-time. The tool leverages the powerful scapy library to intercept network packets and extract critical information such as source and destination IP addresses, protocols, port numbers, and payload data. The captured data is then systematically logged to a text file for further analysis.

The tool continuous monitors hte traffic and captures the packets travelling on the network. 
It captures the traffic and identify the protocol used by the captured packet.
It identify the source and destination IP address as well as source and destination port number.
The tool captures the raw payload data of packet for deep inspection

The tool requires Npcap or WinPcap to be installed for low-level packet capture.
The captured data is automatically saved to packet_log.txt in the same directory as the script.

DISCLAIMER
It is a valuable tool for students and professionals learning about networking and cybersecurity, providing hands-on experience with packet-level data.
Unauthorized use of packet sniffers can violate privacy and legal regulations.
