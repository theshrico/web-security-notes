# Local File Inclusion (LFI)

Local File Inclusion vulnerabilities occur when user input is improperly handled and used to access
server-side files.

## Observed Risks
- Reading sensitive system files
- Accessing private SSH keys
- Gaining information useful for lateral movement

## Impact
LFI vulnerabilities can directly lead to:
- Credential compromise
- SSH access
- Full system compromise when combined with other weaknesses

## Mitigation
- Strict input validation
- Use allowlists instead of blocklists
- Avoid dynamic file inclusion based on user input
