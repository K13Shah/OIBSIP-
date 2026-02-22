# Basic Firewall Configuration Using UFW

## Objective
To configure a basic firewall using UFW on Ubuntu Linux.

## Steps Performed

1. Installed UFW using apt.
2. Set default policies:
   - Deny all incoming traffic
   - Allow all outgoing traffic
3. Allowed SSH (Port 22).
4. Denied HTTP (Port 80).
5. Enabled the firewall.
6. Verified configuration using `ufw status verbose`.

## Rules Configured

- SSH (22) → ALLOW
- HTTP (80) → DENY

## Output

Firewall status shows active rules with correct configuration.

## Author
Krisha Shah
