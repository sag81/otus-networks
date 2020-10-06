# Lab - Configure Router-on-a-Stick Inter-VLAN Routing

![](https://github.com/sag81/otus-networks/blob/master/labs/02/schema.png)

Device  | Device    | Device        | Subnet Mask   | Default Gateway
------- | --------- | ------------- | ------------- | -------------
R1	    | G0/0/1.3	| 192.168.3.1	  | 255.255.255.0	| N/A
R1	    | G0/0/1.4	| 192.168.4.1	  | 255.255.255.0	| N/A
R1	    | G0/0/1.8	| N/A	          | N/A	          | N/A
S1	    | VLAN 3	  | 192.168.3.11	| 255.255.255.0	| 192.168.3.1
S2	    | VLAN 3	  | 192.168.3.12	| 255.255.255.0	| 192.168.3.1
PC-A	  | NIC	      | 192.168.3.3	  | 255.255.255.0	| 192.168.3.1
PC-B	  | NIC	      | 192.168.4.3	  | 55.255.255.0	| 192.168.4.1

