+++
title = 'Security Update: Incident Involving Unauthorized Admin Access'
date = 2023-08-30
+++
**TL;DR:** Sourcegraph experienced a security incident that allowed a single attacker to access some data on Sourcegraph.com. This was limited to:

**Paid customers:**
- The license key recipient’s name and email address.
- A small subset of customers’ Sourcegraph license keys may have been accessed (note that license keys do not enable access to Sourcegraph instances). We are reaching out directly to those who may have been impacted to rotate license keys.

**Community users:**
- Sourcegraph account email addresses. No action is required.

No other customer info, including private code, emails, passwords, usernames, or other PII, was accessible.

**Background:**
On August 30, 2023, a malicious actor used a leaked admin access token in our public Sourcegraph instance at Sourcegraph.com. The attacker used their privileges to increase API rate limits for a small number of users. Our security team quickly identified the breach, revoked the malicious user's access, and initiated an internal investigation.

**Impact:**
The attack was limited to viewing the license key recipient’s name and email address for paid customers, and Sourcegraph account email addresses for community users. No private customer data or code was accessed.

**Mitigation Steps:**
- Identified and revoked the malicious account access.
- Rotated a subset of Sourcegraph customer license keys.
- Temporarily reduced rate limits for all free community users.
- Expanded secret scanning and monitoring for malicious activity.

**Next Steps:**
Sourcegraph is actively working on a long-term solution to prevent future incidents and will provide updates to the community.

[More details here](https://sourcegraph.com/security-update-incident-unauthorized-admin-access)
