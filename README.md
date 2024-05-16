# Network Diagnostic Toolkit

## Overview
The Network Diagnostic Toolkit is a comprehensive set of command-line tools designed to troubleshoot and resolve network connectivity issues efficiently. This toolkit showcases proficiency in network troubleshooting methodologies and offers solutions for various network-related challenges.

## Tools Included
1. **PING**: Used to test the reachability of a host on an IP network. It sends ICMP echo request packets to the target host and waits for ICMP echo reply packets. 
2. **TRACERT**: Traces the route taken by packets across an IP network. It shows the IP addresses and the time taken for each hop along the path.
3. **IPCONFIG**: Retrieves network configuration information for the local system, including IP address, subnet mask, default gateway, and DNS servers.
4. **NSLOOKUP**: Queries DNS servers to retrieve domain name or IP address information. It can be used to troubleshoot DNS-related issues such as incorrect DNS records or server unavailability.

## Usage
Each tool serves a specific purpose in diagnosing and resolving network issues:

- **PING**: Use to check if a remote host is reachable and measure the round-trip time.
  
  Example: `ping google.com`

- **TRACERT**: Trace the path packets take to reach a destination and identify where connectivity issues may occur.
  
  Example: `tracert google.com`

- **IPCONFIG**: Obtain details about the local network configuration to ensure correct IP addressing and gateway settings.
  
  Example: `ipconfig /all`

- **NSLOOKUP**: Perform DNS queries to troubleshoot domain name resolution problems.
  
  Example: `nslookup google.com`

