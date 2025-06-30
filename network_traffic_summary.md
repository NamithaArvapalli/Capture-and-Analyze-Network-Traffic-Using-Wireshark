# Network Traffic Summary

**Duration:** 1 minute  
**Interface:** Wi-Fi (wlan0)  
**Capture Tool:** Wireshark

## ✅ Protocols Observed

1. **DNS**
   - Query: `example.com`
   - Destination: 8.8.8.8 (Google DNS)
   - Response: `93.184.216.34`

2. **ICMP**
   - Ping request/reply from/to `google.com`
   - Round-trip time ~30ms

3. **TCP**
   - 3-way handshake (SYN, SYN-ACK, ACK)
   - Followed by encrypted TLS packets

## 🧾 Notable Packet (DNS)

- **Packet No.:** 12  
- **Source IP:** 192.168.1.10  
- **Destination IP:** 8.8.8.8  
- **Protocol:** DNS  
- **Details:** Query A record for `example.com`
