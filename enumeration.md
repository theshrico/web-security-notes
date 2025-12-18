# Enumeration

Enumeration is the foundation of any security assessment. The goal is to identify exposed services,
hidden functionality, and misconfigurations before attempting exploitation.

## Web Enumeration
Common findings during enumeration include:
- Hidden directories and endpoints
- Development or testing paths
- Exposed frontend logic files
- Misconfigured virtual hosts or subdomains

Improperly restricted directories and files often reveal sensitive information such as:
- Hardcoded credentials
- Application logic
- Debug or testing resources

## Subdomain & Virtual Host Discovery
Subdomain and vhost enumeration can expose:
- Development environments
- Admin panels
- Internal services not meant for public access

These findings significantly expand the attack surface if not properly secured.

## Network Enumeration
Service discovery allows identification of:
- Running services and versions
- Open management interfaces
- Legacy or vulnerable software

Enumeration should always precede exploitation and guide further testing.
