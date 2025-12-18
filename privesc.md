# Privilege Escalation Concepts

Privilege escalation often occurs due to overly permissive system configurations.

## Sudo Misconfiguration
Allowing users to run interpreters (e.g., Python) with elevated privileges can result in immediate
root-level access.

## Impact
- Complete system compromise
- Loss of integrity and confidentiality

## Mitigation
- Audit sudoers configuration
- Restrict interpreter execution
- Apply principle of least privilege
