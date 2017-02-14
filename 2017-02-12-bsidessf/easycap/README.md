#easycap / FORENSICS 40 points
```
Can you get the flag from the packet capture?

* easycap.pcap

```
Open file with wireshark
There is only one TCP stream with 82 packets.
Each packet from `ip.src == 172.31.98.199` in the end contains 1 byte of flag.
`Wireshark>Analyze>Follow>TCP Stream`
>FLAG:385b87afc8671dee07550290d16a8071s