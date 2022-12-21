# Parsed PCAP Data from the October 2021 Forensics Contest

Website for the 2021 challenge:

https://isc.sans.edu/diary/October+2021+Contest+Forensic+Challenge/27960

The data is available here: 

https://www.malware-traffic-analysis.net/2021/10/22/index.html

The password for the zip files: infected

The solution to the challenge is described here:

https://isc.sans.edu/diary/October+2021+Forensic+Contest+Answers+and+Analysis/27998

The zeek commands used to extract the metadata from the PCAP:

    zeek -Cr 2021-10-22-ISC-forensic-challenge-traffic.pcap
    zeek -Cr 2021-10-22-ISC-forensic-challenge-traffic.pcap LogAscii::use_json=T


