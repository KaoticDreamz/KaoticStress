
KaoticStress v1.0 (c) 2019-2021 by KaoticDreamz - Please do not use this program for illegal uses.

KaoticStress is a tool that involves sending many SYN UDP LDAP TCP packets to a specific target or host.
A Distributed Denial of Service (DDoS) attack is an attempt to make an online
service or target  unavailable by overwhelming or overloading it with traffic from multiple sources.

installation:
1.type make
2.run KaoticStress file by Admin/root user


syntax: ./KaoticStress [[-t IP] [-p PORT] [-r]

options:
	-t the target: IP (default 127.0.0.1)
	-p the target: PORT (default 80)
	-r set RST flag

	Example: sudo ./KaoticStress -t 192.168.0.1 -p 8080"
