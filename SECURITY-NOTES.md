# Log4Shell (CVE-2021-44228) — Security Notes

**CVE identifier:** CVE-2021-44228

**What Log4Shell is:** A remote code execution (RCE) vulnerability in Apache Log4j 2 framework. It affected versions 2.0-beta9 through 2.14.1 (all versions below 2.15.0), enabling an attacker to send a malformed log message that triggers a JNDI lookup leading to remote code execution.

**Affected versions:** Apache Log4j 2 versions < 2.15.0 (e.g., 2.0-beta9 through 2.14.1)

**Fixed version:** 2.15.0 (and later); 2.12.2, 2.13.0, 2.11.2 also patched in certain advisory cycles.

**Severity:** Critical — CVSS 3.1 score 10.0 (AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H) per Mitre.

**Sources:**
- CVE-2021-44228 page (CVE.org): https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-44228
- Apache Log4j 2 Security Page: https://logging.apache.org/log4j/2.x/security.html
- Oracle Java security lookup: https://www.oracle.com/java/technologies/security-lookup.html