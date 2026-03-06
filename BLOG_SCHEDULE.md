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
