# Task 03 - Nmap NSE Script Scanning

## Objective

To understand how Nmap default NSE scripts can collect additional information about an authorized service.

## Environment

- Operating System: Kali Linux
- Virtualization: VMware
- Nmap Version: 7.98
- Target: 127.0.0.1

## Test Service

A Python HTTP server was running on TCP port 8000.

## Command

nmap -sC -p 8000 127.0.0.1

## Result

The scan identified port 8000 as open.

The HTTP title script reported:

Directory listing for /

## Learning Outcome

I learned that Nmap NSE scripts can collect additional information about services beyond basic port scanning.

## Safety

The scan was performed only against my own Kali Linux localhost in an authorized lab environment.# Task 03 - Nmap Script Scanning

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
