# Cyber Security Internship – Task 10

## Task Title
Firewall Configuration & Testing

## Objective
To configure and test firewall rules using Windows Defender Firewall and understand the impact of allowing and blocking network traffic.

## Tool Used
- Windows Defender Firewall

## Firewall Status
Windows Defender Firewall was enabled for all network profiles:
- Domain
- Private
- Public

## Firewall Rules Configured

### Allow Rule
- Rule Name: Allow HTTP Port 80
- Port: 80
- Protocol: TCP
- Action: Allow the connection
- Profile: All

This rule allows legitimate web traffic to access the system.

### Block Rule
- Rule Name: Block Telnet Port 23
- Port: 23
- Protocol: TCP
- Action: Block the connection
- Profile: All

Telnet is an insecure protocol, and blocking it improves system security.

## Testing and Observation
- Allowed ports permitted network traffic
- Blocked ports denied unauthorized connections

This confirmed that firewall rules were working as intended.

## Firewall Logs (Concept)
Firewall logs can be used to monitor allowed and blocked traffic and detect suspicious activities.

## Impact of Firewall Configuration
- Reduced attack surface
- Prevented unauthorized access
- Blocked insecure services
- Improved overall system security

## Deliverables
- Firewall Configuration & Testing Report (PDF)
