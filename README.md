# Task-4--firewall-task

# Firewall Configuration Task

## Steps Performed

1. Listed current firewall rules:
sudo ufw status numbered


text
2. Blocked inbound traffic on port 23 (Telnet):
sudo ufw deny 23


text
3. Tested the rule using `telnet localhost 23`.
4. Allowed SSH (port 22):
sudo ufw allow 22


text
5. Removed the block rule for port 23:
sudo ufw delete deny 23


## Screenshots

*(Add your screenshots here by uploading them to the repo and linking them)*

## Summary: How a Firewall Filters Traffic

A firewall inspects network traffic and allows or blocks it based on rules you set, protecting your system from unauthorized access.

