# Security policy

This policy covers every repository in [aeron playground](https://github.com/aeron-playground).
Some repositories have their own `SECURITY.md` with more detail. When one does, it applies there.

## Report a vulnerability

Report privately. Don't open a public issue, pull request or discussion.

- **Preferred:** open a private security advisory. Go to the affected repository's **Security**
  tab and click **Report a vulnerability**.
- **Or email:** [agab0323@gmail.com](mailto:agab0323@gmail.com), for example when a repository
  doesn't show that button.

Please include:

- what the problem is and what an attacker could do with it
- steps to reproduce, or a proof of concept
- the repository, and the commit or version you tested
- your name or handle, if you'd like credit

Never include real passwords, private keys, access tokens or other people's data in a report.

## What to expect

- We reply within 3 working days to confirm we got your report.
- We keep you updated while we work on a fix.
- We agree on a disclosure date with you, and we credit you in the advisory unless you prefer not.

There is no bug bounty.

## Scope

In scope: the code in the public repositories of aeron playground.

Out of scope:

- vulnerabilities in outside services we use (report those to the service itself)
- denial of service, spam and rate-limit testing against hosted instances
- social engineering, phishing and physical attacks
- reports from automated scanners without a working impact

## Supported versions

Unless a repository says otherwise, only the latest release and the latest commit on `main` get
security fixes.

## Stay safe

We never ask for your password, private keys, seed phrases or access tokens. Anyone who does is
not us.
