# Authentication & Credential Exposure

Authentication weaknesses often originate from poor secrets management and frontend exposure.

## Credential Exposure
In several labs, credentials were found:
- Hardcoded in frontend resources
- Visible in development or testing interfaces
- Reused across multiple services

Exposing credentials in the frontend represents a critical failure of access control and secrets handling.

## Impact
- Unauthorized access
- Lateral movement
- Privilege escalation

## Mitigation
- Remove credentials from frontend code
- Use secure secrets management solutions
- Enforce credential rotation and strong password policies
