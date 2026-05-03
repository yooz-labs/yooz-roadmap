# Security Policy

This is the **public roadmap** repository for Yooz. It contains prose, milestones, and discussion content. The security expectations here are different from product repos.

## Reporting a vulnerability

**Please do not open a public GitHub issue for security vulnerabilities found in Yooz products.**

Even though this repo is the public roadmap, vulnerabilities you find in any Yooz product, deployed site, or service should still be reported privately so we can coordinate disclosure.

Email **dev@yooz.info** with:

- A clear description of the issue.
- A minimal reproduction (steps, code, screenshots) if you have one.
- Affected product / version / URL.
- Your name and contact for follow-up. We're happy to credit you in the fix announcement if you'd like.

We aim to acknowledge within **2 business days** and provide a triage decision (accepted / needs more info / not a security issue) within **5 business days**.

## Scope of this repo

This repo is documentation only. Concrete in-scope issues are limited:

- **Information disclosure**: confidential business strategy, internal-only content, or unredacted private discussions accidentally published here.
- **Phishing surface**: misleading links pointing to non-Yooz domains, or links impersonating Yooz contact channels.
- **Repo configuration issues**: missing branch protection, public secrets in repo history, etc.

For vulnerabilities in actual Yooz products (engine, whisper, notes, voice, etc.), report them via the SECURITY.md of the corresponding product repo, or to **dev@yooz.info** if you're not sure where it belongs.

## Disclosure timeline

We follow **coordinated disclosure**:

1. You report → we acknowledge within 2 business days.
2. We triage and confirm within 5 business days.
3. We develop + ship a fix. Standard fix window: **30 days** for critical / high, **60 days** for medium, **90 days** for low.
4. We coordinate the disclosure date with you.

## Hall of Fame

We'll list reporters with their permission once we've shipped fixes.

---

For non-security questions or general issues, please use **GitHub Discussions** or **Issues**.
