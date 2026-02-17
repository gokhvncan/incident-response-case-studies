# Case 001 - Brute Force Attempt

## Detection Source
ELK Correlation Rule

## Observed Indicators
- 15 failed login attempts
- Same source IP

## MITRE Mapping
T1110 - Brute Force

## Investigation Steps
1. Log pivot
2. IOC enrichment
3. Asset identification

## Response
- Account lock
- Firewall block rule
