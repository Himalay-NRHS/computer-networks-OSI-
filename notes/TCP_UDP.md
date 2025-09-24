# TCP vs UDP Comparison

| **Feature** | **TCP** | **UDP** | **Explanation** | **Use Cases** | **Extra Notes** |
|-------------|---------|---------|-----------------|---------------|-----------------|
| **Speed** | Slow | Fast | TCP has overhead due to reliability features, UDP is lightweight | TCP: Web browsing, UDP: Gaming | 🔥 **ADD HERE** |
| **Reliability** | Lossless | Can lose data | TCP ensures all data arrives, UDP doesn't guarantee delivery | TCP: File transfers, UDP: Live streaming | 🔥 **ADD HERE** |
| **Feedback** | Yes | No | TCP provides acknowledgments, UDP sends data without confirmation | TCP: Emails, UDP: DNS queries | 🔥 **ADD HERE** |
| **Connection** | Connection-oriented | Connectionless | TCP establishes connection first, UDP sends data directly | TCP: HTTP/HTTPS, UDP: DHCP | 🔥 **ADD HERE** |
| **Error Checking** | Full error checking | Basic error checking | TCP retransmits lost data, UDP just detects errors | TCP: Banking apps, UDP: Video calls | 🔥 **ADD HERE** |
| **Header Size** | Larger (20 bytes) | Smaller (8 bytes) | More overhead in TCP for reliability features | 🔥 **ADD MORE EXAMPLES** | 🔥 **ADD HERE** |
| **Flow Control** | Yes | No | TCP manages data flow rate between sender/receiver | 🔥 **ADD EXAMPLES** | 🔥 **ADD HERE** |
| **Congestion Control** | Yes | No | TCP adjusts to network congestion, UDP doesn't | 🔥 **ADD EXAMPLES** | 🔥 **ADD HERE** |
| **Order of Data** | Maintains order | No order guarantee | TCP delivers data in correct sequence | 🔥 **ADD EXAMPLES** | 🔥 **ADD HERE** |
| **Examples** | Web pages, Emails, File downloads | Live streaming, Online gaming, DNS | | 🔥 **ADD MORE** | 🔥 **ADD HERE** |
| 🔥 **NEW ROW** | 🔥 **ADD NEW** | 🔥 **ADD NEW** | 🔥 **ADD NEW** | 🔥 **ADD NEW** | 🔥 **ADD NEW** |

## Summary
- **TCP**: Reliable but slower - use when data accuracy is critical
- **UDP**: Fast but unreliable - use when speed matters more than accuracy 