# CSE534-Project
Codes involved in CSE534 Project, Fall 2019

This part includes: 
1. network topology

• SDN   foundation:   
  1)   POXis  a  networking  softwareplatform  written  in  Python,  and  works  as  an  OpenFlowcontroller; The POX used in this study is POX 0.5.0.
   2)OpenFlow: it is a protocol that installed on OVS to giveaccess to the forwarding plane. The Open vSwitch usedin this study is Open vSwitch 2.3.1 with OpenFlow 1.1.
   
2. the captured .pcap data in the simulated network

• DoS attack generation:  
  1) iperf: used to set up a serverlistening to a certain TCP port that receives an attack;
  2)hping3:  Flooding  the  victim  server  with  a  high  numberof ping packets;
  3) tcpdump: Listening to and capturingall the packets that goes through the flooded link.
  
• Traffic  Analysis:    
  1)  WinSCP:  Downloading  the  datacaptured  in  GENI  to  local  computer.
  2)  Wireshark:Generating  the  I/O  graphs  with  regard  to  every  attackconducted
