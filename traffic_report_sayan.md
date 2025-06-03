# Network Traffic Analysis Report

**Name:** Sayan Mandal  
**Tool:** Wireshark  
**Date:** June 2025  

## 1. Objective

To capture live network packets and identify basic internet protocols using Wireshark.

## 2. Protocols Identified

- **DNS:** Domain resolution for `google.com`
- **HTTP:** GET requests for `example.com`
- **ICMP:** Ping to `google.com`

## 3. Sample Packet Details

### DNS Query
- **Source:** 192.168.1.X  
- **Destination:** 8.8.8.8  
- **Query:** A record for `google.com`

### HTTP Request
- **Method:** GET  
- **Host:** example.com  
- **User-Agent:** Chrome

### ICMP Echo Request
- **Type:** 8 (Echo Request)  
- **Identifier:** 0x0010

## 4. Summary

This hands-on activity helped understand basic internet protocol behavior and how to analyze packet headers using Wireshark.
