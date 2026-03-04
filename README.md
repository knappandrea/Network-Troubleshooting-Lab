
Network Troubleshooting Lab
Network Troubleshooting & TCP/IP Fundamentals Lab
📌 Project Overview

This lab was designed to simulate common help desk and IT support networking issues within a virtualized environment. The goal was to practice diagnosing and resolving connectivity problems using core TCP/IP concepts and command-line troubleshooting tools.

The lab focused on DNS configuration, IP addressing, DHCP behavior, and network diagnostics to mirror real-world support scenarios.

🛠 Technologies Used

VirtualBox (or VMware)

Windows 10

Windows Server (Domain Controller)

TCP/IP Networking

Command Prompt

PowerShell

🏗 Lab Environment

1 Domain Controller (Windows Server)

1 Windows 10 Client

Internal Virtual Network

DNS hosted on Domain Controller

DHCP configuration testing

🎯 Objectives

Configure static and dynamic IP addressing

Diagnose DNS failures

Test network connectivity

Use command-line tools to identify issues

Document structured troubleshooting steps

🔧 Key Tasks Performed
1️⃣ IP Address Configuration

Assigned static IP to server

Configured DHCP on client machine

2️⃣ DNS Testing & Failure Simulation

Configured client DNS to incorrect address (intentional failure)

Attempted domain join and internet connectivity

Used nslookup to verify name resolution failure

Corrected DNS configuration to Domain Controller IP

Confirmed successful resolution

3️⃣ Connectivity Testing

Used ping to test:

Localhost

Default gateway

Domain Controller

Used tracert to identify routing path

Used netstat to review active connections

4️⃣ Simulated “No Internet” Scenario

Issue: Client machine unable to reach external resources
Diagnosis Steps:

Checked IP configuration

Verified DNS settings

Tested gateway reachability

Used ping to isolate break point

Resolution: Corrected DNS server IP address

🧪 Troubleshooting Scenarios
❗ Issue: Cannot Join Domain

Cause: Incorrect DNS configuration
Tool Used: ipconfig, nslookup
Fix: Updated DNS server address
❗ Issue: Intermittent Connectivity

Cause: Incorrect subnet configuration
Fix: Adjusted subnet mask to match network range

❗ Issue: Unable to Resolve Hostname

Cause: DNS service misconfiguration
Fix: Restarted DNS service on Domain Controller
📊 Tools Practiced

ipconfig

ping

tracert

nslookup

netstat

Network adapter configuration

TCP/IP fundamentals

🔐 Security Concepts Reinforced

Importance of proper DNS configuration

Network segmentation basics

Identifying potential misconfigurations

Logging and documenting troubleshooting steps
📚 Key Takeaways

DNS is foundational in domain environments

Structured troubleshooting reduces resolution time

Command-line tools are essential for Tier 1 support

Documentation ensures consistent problem-solving

🚀 Next Steps

Expand lab to include firewall rule testing

Simulate DHCP server outage

Document troubleshooting workflow as reusable guide

Verified IP configuration using ipconfig /all

Compared static vs dynamic addressing behavior
