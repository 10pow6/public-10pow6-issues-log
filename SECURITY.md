# Security Policy

We take the security of 10pow6 and our users seriously. Your 10pow6 account signs you in to every product and holds your TP6 wallet, so thank you for helping keep it safe.

## ⚠️ Do not report security issues publicly

**Please do not open a public GitHub issue, discussion, or pull request for a security vulnerability.** Public reports expose the issue to everyone before we can fix it, putting users, their accounts, and their wallets at risk.

This includes (but is not limited to):

- Authentication, login, or session problems, including signing in to TelePortals, BitGlitch, or Slapget with your 10pow6 account
- Account takeover or impersonation
- Bypassing MFA, recovery codes, passkeys, or step‑up checks
- Exposed secrets, API keys, tokens, or credentials
- Ways to create, receive, or spend TP6 you shouldn't have, or to change another user's balance
- Purchase problems such as receiving TP6 without paying, or being charged without receiving it
- A connected app spending beyond the limits you approved, or charging after you paused or disconnected it
- API keys acting outside their scopes or limits
- Consent or sign‑in redirects that can be sent to a site outside 10pow6
- Data exposure of other users' information (account details, wallet history, connected apps)
- Anything that lets you act as another user or the system

## ✅ How to report privately

Use GitHub's private vulnerability reporting:

### [🔒 Report a vulnerability →](https://github.com/10pow6/public-10pow6-issues-log/security/advisories/new)

You can also open this repository's **Security** tab and click **Report a vulnerability**. Only you and our team can see the report. You need a GitHub account.

**No GitHub account?** Reach us through our community **Discord** (linked from [10pow6.com](https://10pow6.com)) and **send a direct message to a staff/admin member**. Let them know you have a security report, and please **do not post the details in any public channel**. A staff member will follow up with you privately.

Every report should include:

- A clear description of the issue and its impact
- Step‑by‑step instructions to reproduce it
- Any proof‑of‑concept, screenshots, or logs (redact your own credentials, codes, and keys)
- Which site you were on (10pow6.com, Accounts, or a product sign‑in)
- Your handle (so we can credit you, if you'd like)

**We will never ask for your password, recovery codes, authenticator codes, or API keys.** Anyone who does is not us.

**Reports without clear steps to reproduce and a real impact on our users will be closed without a response.**

## 🚫 Out of scope

These aren't vulnerabilities for us. Reports about them will be closed without a response:

- Output from automated scanners or tools without a working proof of concept
- Missing "best practice" HTTP headers or cookie flags (CSP, HSTS, X‑Frame‑Options, etc.) without a demonstrated exploit
- Email configuration findings (SPF, DKIM, DMARC)
- Clickjacking on pages with no sensitive actions
- Self‑XSS, or anything that requires the victim to paste code into their own browser
- CSRF on logout or other actions with no security impact
- Software version numbers, banners, or descriptive error messages
- Missing rate limits on actions with no security impact
- Denial of service, load testing, or flooding
- Social engineering or phishing of our staff or users
- Attacks that require physical access to a device or an already‑compromised account
- Bugs in third‑party services we use, unless you show impact on our users

## What to expect

- We'll acknowledge your report as quickly as we can.
- We'll investigate, keep you updated, and let you know when it's resolved.
- **We don't run a paid bug bounty.** Valid reports are credited in the published advisory, if you'd like.
- Please give us a reasonable window to fix the issue before sharing it publicly.

## Responsible disclosure

Please act in good faith:

- **Don't** access, modify, or delete data or accounts that aren't yours.
- **Don't** degrade or disrupt the service for other users.
- **Don't** use the vulnerability beyond what's needed to demonstrate it.
- **Don't** keep TP6 or anything else gained through a bug.

We're grateful to researchers and users who report responsibly, and we're happy to credit you for valid reports. 🙏
