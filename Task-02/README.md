# Task 02 - Nmap Service and Version Detection

## Objective

To identify an active service and obtain basic service information using Nmap.

## Environment

- Kali Linux
- VMware
- Nmap 7.98
- Python HTTP Server

## Target

127.0.0.1

## Test Service

A Python HTTP server was started on TCP port 8000.

Command:

python3 -m http.server 8000 --bind 127.0.0.1

## Nmap Command

nmap -sV -p 8000 127.0.0.1

## Result

Port 8000 was detected as an open HTTP service.

## Learning Outcome

I learned how Nmap can identify an open port and determine the service running on that port.

## Safety

The test was performed against my own Kali Linux localhost in an authorized lab environment.
