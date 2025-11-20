<h1>Microsoft sentinel SOC+SIEM home lab</h1>

 ### [YouTube Demonstration]https://youtu.be/xNMslkjPxvQ?si=ra6NLbw6qD9jI-VT


<h2>Description</h2>
Built a cloud-based security monitoring environment using Azure Sentinel to collect, analyze, and visualize threat activity from a custom honeypot network. Deployed a segmented virtual network with intentionally exposed services to attract malicious traffic, then integrated log sources into Sentinel for real-time detection and incident investigation. Created custom workbooks, alerts, and analytic rules to track attacker behavior, map global IP activity, and perform correlation across multiple log types. Documented attack patterns, enrichment steps using GeoIP and OSINT sources, and developed repeatable processes for threat hunting and incident response. This project demonstrates hands-on experience with SIEM operations, log analysis, network security, and cloud security architecture.

<h2>Tools and Utilities Used</h2>

### Azure Platform
- **Azure Virtual Machine** used as the primary honeypot system  
- **Azure Virtual Network** for network segmentation and traffic control  
- **Network Security Groups** configured to expose selected ports for attack telemetry  
- **Azure Portal** for deployment and management  
- **Azure Log Analytics Workspace** for centralized log collection  
- **Microsoft Sentinel (SIEM)** for alerting, dashboards, and threat investigation  

### Security and Logging Tools
- **Sysmon** for detailed Windows event logging  
- **Windows Event Viewer** for local validation and log inspection  
- **Log Analytics Agent / AMA Agent** to forward honeypot logs into Sentinel  
- **Intentional service exposure** such as RDP or open ports to attract attacker traffic  

### Threat Analysis
- **KQL Workbooks in Microsoft Sentinel** to query, visualize, and analyze attack activity  
- **GeoIP data sources** (including the public CSV dataset used in the lab) for IP enrichment and geographic profiling 


