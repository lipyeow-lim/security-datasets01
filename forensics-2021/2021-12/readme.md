# Parsed PCAP Data from the December 2021 Forensics Contest

Challenge:
https://www.malware-traffic-analysis.net/2021/12/08/index.html

Solution:
https://isc.sans.edu/diary/December+2021+Forensic+Contest+Answers+and+Analysis/28160

Zeek Command for extracting the metadata from the provided PCAP:

    zeek -Cr 2021-10-22-ISC-forensic-challenge-traffic.pcap LogAscii::use_json=T
