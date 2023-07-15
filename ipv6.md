# IPv6

IPv6 is **128** bits. \
MAC Address **48** bits.

2401:4900:1c65:89b1:cc75:73ff:fe26:2ec2 \
CE:75:73:26:2E:C2

Convert 7th bit 0->1 1->0

64 bits | 4 bits | 4 bits | 16 bits | 16 bits | 24 bits
---|---|---|---|---|---
Internet Service Provider | Same as mac address | reverse 7th bit | Same as mac address | `FFFE` | Last 24 bits of mac address
2401:4900:1c65:89b1 | c | c | 75:73 | ff:fe | 26:2ec2
