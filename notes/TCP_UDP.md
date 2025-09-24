# TCP vs UDP Comparison

| **Feature** | **TCP** | **UDP** | **Explanation** | **Use Cases** | **Extra Notes** |
|-------------|---------|---------|-----------------|---------------|-----------------|
| **Speed** | Slow | Fast | TCP has overhead due to reliability features, UDP is lightweight | TCP: Web browsing, UDP: Gaming | - |
| **Reliability** | Lossless | Can lose data | TCP ensures all data arrives, UDP doesn't guarantee delivery | TCP: File transfers, UDP: Live streaming | - |
| **Feedback** | Yes | No | TCP provides acknowledgments, UDP sends data without confirmation | TCP: Emails, UDP: DNS queries | - |
| **Connection** | Connection-oriented | Connectionless | TCP establishes connection first, UDP sends data directly | TCP: HTTP/HTTPS, UDP: DHCP | - |
| **Error Checking** | Full error checking | Basic error checking | TCP retransmits lost data, UDP just detects errors | TCP: Banking apps, UDP: Video calls | - |
| **Header Size** | Larger (20 bytes) | Smaller (8 bytes) | More overhead in TCP for reliability features | - | - |
| **Flow Control** | Yes | No | TCP manages data flow rate between sender/receiver | - | - |
| **Congestion Control** | Yes | No | TCP adjusts to network congestion, UDP doesn't | - | - |
| **Order of Data** | Maintains order | No order guarantee | TCP delivers data in correct sequence | - | - |
| **Examples** | Web pages, Emails, File downloads | Live streaming, Online gaming, DNS | | - | - |
| **NEW FEATURE** | - | - | - | - | - |

## Summary
- **TCP**: Reliable but slower - use when data accuracy is critical
- **UDP**: Fast but unreliable - use when speed matters more than accuracy

---

## 📝 **Areas to Expand (Visible Comments)**

### **Extra Notes Column Ideas:**
- Personal learning tips and tricks
- Exam important points and mnemonics
- Interview questions you encounter
- Real-world experience notes
- Common mistakes to avoid
- Performance benchmarks you find

### **Missing Use Cases to Add:**
- More protocol examples (FTP, SMTP, SNMP, etc.)
- Specific port numbers for each protocol
- Industry-specific applications
- Mobile app examples

### **New Features to Compare:**
- **Security**: Built-in vs Application-level
- **Broadcast Support**: No vs Yes
- **Memory Usage**: Higher vs Lower
- **CPU Overhead**: Higher vs Lower  
- **Latency**: Higher vs Lower
- **Buffer Management**: Complex vs Simple

### **Personal Study Notes Section:**
*Add your own observations, exam prep notes, or project experiences here*

---
**Last Updated:** *Add date when you make changes* 