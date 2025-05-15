# Subdomain-Recon-Scanner
A tool written in Python that performs initial intelligence gathering (reconnaissance) on a target domain:
  -Finds existing subdomains using a dictionary
  -Checks the HTTP status of each one (200, 403, 404, etc.)
  -Checks for initial vulnerabilities such as:
    -HTTP header information leakage
    -Open output (log directory)
    -Access to robots.txt or admin panels
    -Attempts to identify sensitive services
