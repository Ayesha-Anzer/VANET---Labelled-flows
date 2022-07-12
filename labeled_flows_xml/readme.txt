ISCX 2012 Intrusion Detection Evaluation Dataset
==================================================
The file ISCXDataset.md5 contains all the relevant MD5 hashes.

Files are archived using 7Zip.

Linux:
	7z e testbed-X.7z

Windows:
	7Zip application or Winrar


Each trace is exactly 24 hours. Please be aware that tcpreplay will extend the replay times to beyond 24 hours(26h or more). For more accurate replays we suggest using Colasoft Packet Player on Windows.

The file "labeled_flows_xml" contains detailed flow information in XML format for each day. The flows have been generated using IBM QRadar appliance. The "Tag" column indicates whether the flow is normal or part of an attack scenario. Please note that all flows from day 1 (11 June) are normal, thus no flow XML file is included.

The XML files contain the following:
"appName","totalSourceBytes","totalDestinationBytes","totalDestinationPackets","totalSourcePackets","sourcePayloadAsBase64","destinationPayloadAsBase64","destinationPayloadAsUTF","direction","sourceTCPFlagsDescription","destinationTCPFlagsDescription","source","protocolName","sourcePort","destination","destinationPort","startDateTime","stopDateTime","Tag"

Friday  	11/6/2010	Normal Activity. No malicious activity	 16.1 GB
Saturday  	12/6/2010	Normal Activity. Contains a small number of bruteforce attacks as labeled, remove if required 	 4.22
Sunday  	13/6/2010	Infiltrating the network from inside + Normal Activity	 3.95
Monday  	14/6/2010	HTTP Denial of Service + Normal Activity	 6.85
Tuesday  	15/6/2010	Distributed Denial of Service using an IRC Botnet + Normal Activity	 23.4
Wednesday  	16/6/2010	Normal Activity. Contains a small number of bruteforce attacks as labeled, remove if required 	 17.6
Thursday  	17/6/2010	Brute Force SSH + Normal Activity	 12.3

By using this Dataset you have already agreed to the license agreement attached.
