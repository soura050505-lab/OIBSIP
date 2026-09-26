# Task 01 - Nmap Localhost Scanning

## Objective

To perform a basic network scan using Nmap in an authorized local Kali Linux environment.

## Environment

- Operating System: Kali Linux
- Virtualization: VMware
- Tool: Nmap 7.98
- Target: 127.0.0.1 (localhost)

## Command Used

nmap 127.0.0.1 -oN Task-01/nmap-localhost.txt

## Result

The host 127.0.0.1 was detected as up.

Nmap scanned its default 1000 TCP ports.

Result:

- Host: Up
- Ports scanned: 1000
- Open ports: 0
- Closed ports: 1000

## Learning Outcome

I learned how to perform a basic Nmap scan and understand the status of TCP ports on a local system.

## Safety

The scan was performed only against my own Kali Linux system in an authorized local lab environment.# Task 01 - Nmap Network Scanning

## Objective

To understand basic network scanning using Nmap in an authorized local lab environment.

## Tool Used

- Nmap 7.98
- Kali Linux
- VMware

## Target

127.0.0.1 (Localhost)

## Command Used

nmap 127.0.0.1

## Output

The scan results are saved in:

nmap-localhost.txt

## Learning

I learned how Nmap can be used to identify open ports and services on an authorized system.

## Safety

The scan was performed only against my own local system/lab environment.
