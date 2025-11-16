NetWatch – Privacy Policy

Last Updated: February 2025

NetWatch is a Chromium-based browser extension designed to detect phishing pages, insecure SSL certificates, malicious advertisements, and other web security risks. The extension prioritizes user privacy and does not collect, sell, or share any personal data.

1. Information We Collect
1.1 URLs Sent for Security Scanning

NetWatch sends the active webpage URL to the NetWatch API server only for the purpose of security scanning, including:

VirusTotal (via server)
Google Safe Browsing (GSB)
URLScan threat intelligence
CheckSSL certificate validation
Internal SSL checker
DNR-based ad filtering (local only)

This URL is not stored, not logged, and not linked to any user identity.

1.2 Local Browser Data (Not transmitted)
NetWatch uses browser APIs, but no local data ever leaves the device. This includes:

Browser tab URL
Protocol (HTTP/HTTPS)
SSL certificate security state
Whether ads were blocked

This data is used exclusively to generate on-page warnings.

2. What We DO NOT Collect

NetWatch never collects, stores, or transmits:

Personal information
Cookies
Login details / passwords
Browser history
IP addresses
User identifiers
Analytics or telemetry
Advertising identifiers
Payment information

NetWatch does not sell or share data with third parties.

3. How the Extension Uses Permissions

The Chrome Web Store requires justification for each permission:

activeTab
Used to read the current tab’s URL so the extension can:

Scan it for phishing or malware
Show an in-page security alert
Display security findings in the popup

No other data from the tab is accessed.


declarativeNetRequest
Used only for rule-based ad blocking of malicious advertisements.
No network requests or user data leave the browser.


host_permissions ("<all_urls>")
Required because NetWatch must:

Detect HTTP vs HTTPS
Validate SSL certificate info
Show security overlays on any visited page

No page content is read; only page metadata is analyzed.


notifications
Used to optionally notify the user if a high-risk threat is detected.


scripting
Allows the extension to inject the security overlay script to warn users when a malicious site is loaded.


storage
Used only to store:

Cached scanning results to improve speed
Flags to avoid repeating alerts on the same site

No personal or browsing data is saved.


tabs
Allows the extension to know when the user switches tabs so the security scan can be rerun.
NetWatch does not log or store tab information.


webNavigation
Used to detect when a page navigation finishes so the background scanner can run automatically.

remote code use
NetWatch uses remote API calls exclusively to:

VirusTotal (through the NetWatch backend)
Google Safe Browsing
URLScan
CheckSSL

No user identity or personal data is ever sent. Only the URL being scanned is transmitted.


4. Third-Party Services
NetWatch communicates with:

VirusTotal
Google Safe Browsing (GSB)
URLScan.io
CheckSSL API
NetWatch API (your server)

Data shared: only the active URL.
No personal data, cookies, or identifiers are transmitted.

5. Data Retention

NetWatch does:

Not store user data
Not store browsing history
Not create profiles
Not log or retain URLs after scanning

Short-term cache (non-personal) is stored in memory for performance and expires automatically.

6. Security
NetWatch sends all API requests through HTTPS.
The extension does not execute or load any remote scripts into the browser.

7. Single Purpose Description
NetWatch performs one purpose:
To protect users from phishing pages, insecure SSL certificates, malicious URLs, and harmful advertisements by scanning the active page using security APIs and displaying warnings inside the browser.

It does not provide any other functionality.

8. Contact

For privacy inquiries, you may contact the developer at:
netwatch.ust@gmail.com
