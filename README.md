# practical-networking-notebook

1. L2 layer is used for NIC(Network Interface Card) mac address identification and to transport packets from hop to hop(router to router).
2. L3 layer is used for IP address or logical address binding which responsible for data transfer from end to end means sender IP to receiver IP.
3. L4 layer is used to disnguish port between TCP(for browser use) and UDP(for live streaming use). Lyaer 4 is responsible for service to service data delivery.

# MTU (standard of maximum transmission unit)
MTU of a NIC card will decide how much bytes of the packet will transmit at once. If data is huge and mtu is low then the chunk of the packets will be increased and more time will be required. To see current mtu of nic card command ifconfig.
