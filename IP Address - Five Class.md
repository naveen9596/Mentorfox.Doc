In IPv4 networking, IP addresses are divided into five classes: A, B, C, D, and E, each designed to accommodate networks of different sizes. Class A, B, and C are the most commonly used for general network addressing, while Class D is for multicast addressing, and Class E is reserved for experimental purposes. 
# Class A:
Designed for very large networks with many hosts. 
The first octet (8 bits) represents the network ID, and the remaining three octets (24 bits) represent the host ID. 
The first bit of the first octet is always 0, and the valid range for the first octet is 1-126. 
Examples: 10.0.0.1, 10.255.255.254. 
# Class B:
Designed for medium-sized networks. 
The first two octets (16 bits) represent the network ID, and the remaining two octets (16 bits) represent the host ID. 
The first two bits of the first octet are 10, and the valid range for the first octet is 128-191. 
Examples: 172.16.0.1, 172.31.255.254. 
# Class C:
Designed for smaller networks. 
The first three octets (24 bits) represent the network ID, and the last octet (8 bits) represents the host ID. 
The first three bits of the first octet are 110, and the valid range for the first octet is 192-223. 
Examples: 192.168.1.1, 192.168.255.254. 
# Class D:
Reserved for multicast addressing, allowing a single packet to be sent to multiple devices simultaneously. 
The first four bits of the first octet are 1110, and the valid range for the first octet is 224-239. 
# Class E:
Reserved for experimental purposes and future use. 
The first four bits of the first octet are 1111, and the valid range for the first octet is 240-255

<img width="715" height="375" alt="image" src="https://github.com/user-attachments/assets/cad4415a-6165-422c-b74b-0d618a26beaa" />


## Dotted Decimal Notation
Some points to be noted about dotted decimal notation: 

The value of any segment (byte) is between 0 and 255 (both included).
No zeroes preceding the value in any segment (054 is wrong, 54 is correct).
Dotted Decimal Notation

<img width="634" height="214" alt="image" src="https://github.com/user-attachments/assets/a4a98678-9247-4c85-baf8-91debd7ceb28" />

## Hexadecimal Notation

<img width="602" height="152" alt="image" src="https://github.com/user-attachments/assets/96767cd1-e7a7-4068-83a6-d2e6018eddd6" />

# Note: 

IP addresses are globally managed by Internet Assigned Numbers Authority (IANA) and Regional Internet Registries (RIR).
While finding the total number of host IP addresses, 2 IP addresses are not counted and are therefore, decreased from the total count because the first IP address of any network is the network number and whereas the last IP address is reserved for broadcast IP.

<img width="932" height="435" alt="image" src="https://github.com/user-attachments/assets/11fa9ca6-5260-4aab-9d91-3b108e1ece26" />

<img width="1027" height="569" alt="image" src="https://github.com/user-attachments/assets/90a3550c-a0c3-498f-a802-273c70a27d72" />

