# Basic Network Security Analysis

## Project Overview

This project is a basic network investigation and security analysis using built-in Windows command-line tools.

The goal was to understand network configuration, test connectivity, analyze DNS, trace network routes, and identify active network connections.

## Objectives

- Analyze basic network configuration
- Test local and Internet connectivity
- Understand DNS resolution
- Analyze network routes
- Identify active network connections and listening ports
- Understand basic network security risks

## Tools Used

- Windows Command Prompt
- ipconfig
- ping
- nslookup
- tracert
- netstat

## 1. Network Configuration

I used the command ipconfig /all to examine my network configuration.

I checked:

- IPv4 Address
- Subnet Mask
- Default Gateway
- DNS Servers

Sensitive network information was not included in this repository.

## 2. Connectivity Testing

I used ping to test network connectivity.

Commands used:

- ping 127.0.0.1
- ping <default-gateway>
- ping google.com

These tests were used to check the local network interface, connection to the default gateway, and Internet connectivity.

## 3. DNS Analysis

I used nslookup to analyze DNS resolution.

Commands used:

- nslookup google.com
- nslookup youtube.com
- nslookup microsoft.com

This helped me understand how DNS resolves domain names into IP addresses.

## 4. Route Analysis

I used tracert google.com to examine the route between my computer and the destination.

This helped me understand the different network hops involved when communicating with a remote server.

## 5. Network Connection Analysis

I used netstat -ano to examine active network connections and services in the LISTENING state.

This helped me understand which network services were listening for connections on the computer.

## 6. Security Analysis

During the investigation, I learned that:

- Network configuration provides important information about a device.
- DNS is used to resolve domain names into IP addresses.
- Listening ports can indicate services running on a system.
- An open port does not automatically mean that a system has been hacked.
- Unnecessary services can increase the attack surface of a device.
- Network command-line tools can help with basic security investigation and troubleshooting.

## 7. What I Learned

Through this project, I gained practical experience with basic network investigation using Windows command-line tools.

I learned how to:

- Check network configuration
- Test network connectivity
- Analyze DNS resolution
- Trace network routes
- Examine active network connections
- Understand listening ports and attack surface

## 8. Conclusion

This project provided a practical introduction to network security analysis.

It helped me build a foundation in networking concepts such as IP addressing, DNS, routing, ports, and network connections.

The project also showed me how basic command-line tools can be useful for security analysis and troubleshooting.
