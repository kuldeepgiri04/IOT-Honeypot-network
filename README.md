# IoT Honeypot Network using Cowrie

## Project Overview
This project demonstrates the deployment of a Cowrie SSH/Telnet honeypot to monitor and capture malicious activities targeting IoT systems.

The honeypot simulates a vulnerable device to attract attackers and record their behavior for cybersecurity analysis.

## Tools Used
- Kali Linux
- Cowrie Honeypot
- GitHub

## Features
- Detects SSH brute force attacks
- Logs attacker login attempts
- Records commands executed by attackers
- Helps analyze attacker behavior

## Project Structure
bin/ – Cowrie executable scripts  
etc/ – Configuration files  
src/ – Source code  
var/ – Attack logs and captured data  

## How to Run the Honeypot

### Activate environment
source cowrie-env/bin/activate

### Start honeypot
bin/cowrie start

### Stop honeypot
bin/cowrie stop

### Check attacker logs

tail -f var/log/cowrie/cowrie.log


## Example Attack Detection
The honeypot records attacker login attempts and commands used during attacks.

## Author
Kuldeep Giri
Catherine
Rinku Shamrao Dhole
Ben joseph
