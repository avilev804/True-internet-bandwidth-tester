# True-internet-bandwidth-tester
get true details about actual download speed using a few high speed servers for downloading files from 100 MB to 1 GB

 NetTruthBench

**NetTruthBench** is a high-performance C#-based network diagnostics suite built to detect ISP throttling, expose false speed test results, and validate hardware performance at LAN and WAN levels—with no external dependencies.

---

## 🔍 What It Does

- Performs real-world **download speed tests** from trusted servers
- Compares **WAN vs LAN** throughput via local loopback
- Measures NIC capabilities, driver-reported speeds, and connection stats
- Verifies **actual delivered bandwidth** versus ISP claims
- Bypasses browser-based speed tests (e.g. Ookla, Fast.com)
- 💯 Everything written in pure C#—no tools, no pings, no nonsense

---

## 🛠️ Components

- `SpeedTest.cs`: Download benchmark using multiple public servers
- `LoopbackServer.cs`: Serves local files over HTTP for LAN max throughput
- `NicInspector.cs`: Reports negotiated speeds, device names, and link types

---

## 📈 Sample Output

✅ Download complete: 1023.98 MB in 124.94 seconds ⚡ Average Speed: 65.56 Mbps

🔌 Ethernet Adapter: Realtek PCIe 5GbE Family Controller Speed: 5000 Mbps (5 Gbps) Local Transfer Speed: 2800+ Mbps (loopback)


---

## 🧪 Why This Matters

Don't trust deceptive ISP numbers or biased browser speed tests. With NetTruthBench, you measure *reality*—not marketing. Use it to:
- Audit your router's WAN bottlenecks
- Detect NIC underperformance or bad cabling
- Generate raw proof for support tickets or public complaints

---


## 🙌 Community

Built with fire and frustration by real users who wanted the truth.
