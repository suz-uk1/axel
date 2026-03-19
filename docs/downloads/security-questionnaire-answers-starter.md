# Security Questionnaire Answers — Starter Pack (for lean teams)

> Use this as a starting point when customers send security questionnaires.
> Keep answers truthful and consistent with your actual controls.

## 1) Policies & governance
**Q: Do you have an information security policy?**
A: Yes. We maintain an information security policy that defines baseline security requirements (access control, incident response, change management, supplier reviews). We review it at least annually and upon major changes.

**Q: Who is responsible for security?**
A: A named security owner is responsible for security governance and coordination, and individual control owners are assigned for key operational controls (access reviews, backups, vendor reviews, etc.).

## 2) Access control
**Q: Do you use SSO / MFA?**
A: We require MFA for all production and administrative access. Where supported, we enforce SSO for core systems.

**Q: How do you manage privileged access?**
A: Privileged access is limited to authorized personnel, granted on least privilege, and reviewed on a recurring cadence. Access changes are logged.

**Q: Do you perform access reviews?**
A: Yes. We perform periodic access reviews (at least quarterly for core systems) and record the reviewer, scope, and outcomes.

## 3) Data protection
**Q: Is data encrypted in transit and at rest?**
A: We encrypt data in transit using TLS and use encryption at rest for supported storage systems.

**Q: Do you have data retention and deletion practices?**
A: We define retention periods for customer data where applicable and support deletion requests in accordance with contractual and legal requirements.

## 4) Vulnerability management
**Q: Do you conduct vulnerability scans or penetration tests?**
A: We maintain a vulnerability management process that includes remediation tracking and prioritization. Where applicable, we perform periodic testing and track findings to closure.

**Q: How quickly do you patch critical vulnerabilities?**
A: We prioritize critical issues for rapid remediation. Remediation timelines depend on severity and exploitability; progress is tracked to completion.

## 5) Backups & resilience
**Q: Do you back up production data?**
A: Yes. We perform backups for critical production data.

**Q: Do you test restores?**
A: Yes. We periodically test restores and record outcomes.

## 6) Incident response
**Q: Do you have an incident response plan?**
A: Yes. We maintain an incident response plan, an incident log, and perform post-incident reviews as needed.

**Q: How do you notify customers?**
A: We notify customers in accordance with contractual terms and applicable laws, based on severity and impact.

## 7) Supplier / third-party risk
**Q: Do you review vendors?**
A: Yes. We maintain a vendor list and perform vendor reviews on a recurring basis (e.g., annually) for critical suppliers.

## 8) Audit readiness (evidence)
**Q: How do you provide evidence during audits?**
A: We maintain an evidence tracker (control → owner → frequency → evidence link) so we can provide auditable records (access reviews, restore tests, change approvals, vendor reviews, management review minutes).

---

## Optional: What to attach when asked for proof
- Access review record (redacted)
- Restore test log
- Incident log (redacted)
- Vendor review log
- Risk register excerpt
- Statement of Applicability excerpt
- Internal audit checklist/results
