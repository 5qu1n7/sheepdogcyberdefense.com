# Blog Post Publishing Schedule

This document tracks all scheduled blog posts. Posts are stored in `src/pages/blog/_drafts/` with date prefixes and automatically published on their scheduled date via GitHub Actions.

## Schedule Format

Files should be named: `YYYY-MM-DD-post-slug.astro`

Example: `2026-03-15-penetration-test-quality-checklist.astro`

GitHub Actions will automatically move the file from `_drafts/` to `blog/` at 8 AM UTC on the specified date.

---

## Publishing Schedule

### March 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-03-15 | Penetration Testing Report Quality Checklist | penetration test quality, report review, findings validation | 📝 Ready |
| 2026-03-22 | 30-60-90 Day Remediation Plan After PT | remediation timeline, vulnerability fixes, security roadmap | 📝 Ready |
| 2026-03-29 | Supply Chain Security: Vendor Assessment | vendor security, third-party risk, supply chain | 📝 Ready |

### April 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-04-05 | Ransomware Trends & Defenses for Texas Businesses | ransomware, ransomware defense, Texas cybersecurity | 📝 Ready |
| 2026-04-12 | HIPAA Compliance & Penetration Testing | HIPAA penetration testing, healthcare security, compliance | 📝 Ready |
| 2026-04-19 | What Happens If You Fail a Penetration Test | penetration test failure, remediation, security gap | 📝 Ready |
| 2026-04-26 | Cyber Insurance Requirements: Security Testing | cyber insurance, insurance requirements, penetration testing | 📝 Ready |

### May 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-05-03 | Physical vs Cyber: Why Both Matter | physical security, cybersecurity, integrated security | 📝 Ready |
| 2026-05-10 | Employee Security Training: Beyond Awareness | security training, phishing awareness, employee security | 📝 Ready |
| 2026-05-17 | Compliance Calendar 2026: When to Test | compliance requirements, testing schedule, regulatory | 📝 Ready |
| 2026-05-24 | Government Contractors: CMMC Requirements | CMMC, government contractor, defense contractor security | 📝 Ready |
| 2026-05-31 | PCI-DSS 2026 Updates & Implications | PCI-DSS compliance, payment security, e-commerce | 📝 Ready |

### June 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-06-07 | Security Incident Response: Building Your Team | incident response, breach response, security team | 📝 Ready |
| 2026-06-14 | Zero Trust Architecture for Texas Businesses | zero trust, network security, access control | 📝 Ready |
| 2026-06-21 | API Security Testing: Protecting Your Data | API security, application security, testing | 📝 Ready |
| 2026-06-28 | Vulnerability Scanning vs Penetration Testing | vulnerability assessment, security testing, gap analysis | 📝 Ready |

### July 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-07-05 | Secure Development Lifecycle: Building Security In | SDLC, secure coding, development security | 📝 Ready |
| 2026-07-12 | Third-Party Risk Management & Vendor Testing | vendor assessment, third-party risk, supply chain | 📝 Ready |
| 2026-07-19 | Cloud Security: AWS, Azure, Google Cloud | cloud security, cloud penetration testing, IaaS | 📝 Ready |
| 2026-07-26 | Data Classification & Protection Strategies | data security, DLP, classification | 📝 Ready |

### August 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-08-02 | Insider Threat Detection & Prevention | insider threats, user behavior, monitoring | 📝 Ready |
| 2026-08-09 | Social Engineering Attacks: Awareness & Defense | social engineering, phishing, human security | 📝 Ready |
| 2026-08-16 | Secure Remote Work: VPN, MFA, Monitoring | remote work security, home office, VPN | 📝 Ready |
| 2026-08-23 | Disaster Recovery & Business Continuity Testing | disaster recovery, business continuity, incident response | 📝 Ready |
| 2026-08-30 | Security Certifications Worth Pursuing | OSCP, CEH, security training, careers | 📝 Ready |

### September 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-09-06 | NIST Framework: Building a Comprehensive Program | NIST, cybersecurity framework, governance | 📝 Ready |
| 2026-09-13 | Container Security: Docker & Kubernetes | container security, DevOps security, orchestration | 📝 Ready |
| 2026-09-20 | Threat Intelligence: Using It To Improve Security | threat intelligence, threat modeling, risk | 📝 Ready |
| 2026-09-27 | State Privacy Laws: CCPA, TDPSA & Compliance | privacy law, compliance, data protection | 📝 Ready |

### October 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-10-04 | Mobile App Security: iOS & Android Testing | mobile security, app testing, vulnerability | 📝 Ready |
| 2026-10-11 | Secure Password Management & MFA Best Practices | password security, MFA, authentication | 📝 Ready |
| 2026-10-18 | Compliance Audit Preparation: Getting Ready | audit, compliance, assessment preparation | 📝 Ready |
| 2026-10-25 | Red Team Engagement: What to Expect | red teaming, advanced testing, simulations | 📝 Ready |

### November 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-11-01 | Ransomware Recovery: Getting Back to Normal | ransomware recovery, incident response, restoration | 📝 Ready |
| 2026-11-08 | Security Metrics: Measuring Your Program | metrics, KPI, security measurement | 📝 Ready |
| 2026-11-15 | Critical Infrastructure Security & CIS Controls | CIS controls, infrastructure, hardening | 📝 Ready |
| 2026-11-22 | Year-End Security Review: Planning for 2027 | review, planning, strategy | 📝 Ready |

### December 2026

| Date | Post Title | Keywords | Status |
|------|-----------|----------|--------|
| 2026-12-06 | 2026 Security Breaches: Lessons Learned | breach analysis, lessons, trends | 📝 Ready |
| 2026-12-13 | Security Culture: Making It Part of Your DNA | culture, awareness, behavior change | 📝 Ready |
| 2026-12-20 | 2027 Security Predictions & Trends | predictions, future, trends | 📝 Ready |
| 2026-12-27 | Penetration Testing ROI: Proving the Value | ROI, business case, value | 📝 Ready |

---

## How It Works

1. **Draft:** Posts are created in `src/pages/blog/_drafts/` with date prefix
2. **Schedule:** File name indicates publish date (e.g., `2026-03-15-post-slug.astro`)
3. **Publish:** GitHub Actions checks daily at 8 AM UTC
4. **Automatic:** When the date matches, the post is moved to `src/pages/blog/` and committed
5. **Live:** Cloudflare Pages automatically deploys the new commit

## Status Legend

- 📋 Planned: Topic identified, waiting to be drafted
- ✍️ Drafting: Currently being written
- 📝 Ready: Drafted and in _drafts folder, waiting for publish date
- ✅ Published: Live on site

## Post Word Count Target

Each post should be **1,500-2,500 words** for SEO optimization.

## Next Steps

1. Create drafts for March posts
2. Commit with date-prefixed filenames
3. GitHub Actions will automatically publish on schedule
