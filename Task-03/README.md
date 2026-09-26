# Task 03 - Nmap Script Scanning

## Objective

To understand how Nmap default scripts can collect additional information about an authorized service.

## Environment

- Kali Linux
- VMware
- Nmap 7.98
- Python HTTP Server

## Target

127.0.0.1

## Test Service

Python SimpleHTTPServer running on TCP port 8000.

## Command Used

nmap -sC -p 8000 127.0.0.1

## Result

The Nmap default scripts were executed against the local HTTP service.

## Learning Outcome

I learned that Nmap NSE scripts can provide additional information beyond basic port scanning.

## Safety

The scan was performed only against my own Kali Linux localhost.
