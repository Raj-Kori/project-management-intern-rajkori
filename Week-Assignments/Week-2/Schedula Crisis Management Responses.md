
---

# 📘 Assignment – Day 10

**Name:** Raj Kori
**Date:** 18 Feb 2026

---

## Crisis 1: Scope Creep Emergency

**Problem Statement:**  
Six days before launch, the client requested four major new features (WhatsApp booking, Google Calendar sync, Birthday coupons, Instagram integration). The sprint is already at full capacity, creating risk of delay and instability.

**Root Cause (3 Whys):**

1. Competitors offered these features.
2. Customers demanded WhatsApp booking.
3. Scope was not formally frozen or prioritized.

**Options:**

- **Option A – Add All Features:** Launch delayed 2–3 weeks, high bug risk, client happy short-term.
- **Option B – Add WhatsApp Only:** On-time launch, partial satisfaction, controlled workload.
- **Option C – Defer All Features:** Stable launch, client disappointment, requires clear roadmap.

**Recommendation:**  
Choose **Option B**: Deliver WhatsApp booking now, commit others to Phase 2 roadmap.  
This balances timeline, stability, and client trust.

**Prevention Strategy:**

- Formal scope freeze before final sprint.
- Signed-off roadmap.
- Change request documentation.
- Regular client alignment meetings.

---

## Crisis 2: Team Conflict

**Root Cause (3 Whys):**

1. Developer redoing work due to late design changes.
2. Designer updated UI after development began.
3. No design freeze or approval checkpoint.

**Immediate Fix (Today):**

- **Rajesh (Developer):** Implement only approved designs, freeze version by EOD.
- **Priya (Designer):** Finalize UX improvements before sprint start, lock design today.
- **Amit (QA):** Test frozen design, UI freeze confirmed by 4 PM.

**Process Change (Next Sprint):**

- Introduce **Design Freeze Rule** before sprint start.
- Mandatory design approval meeting.
- No mid-sprint changes without formal request.
- Clear version tagging for QA.

---

## Crisis 3: Data Quality

**Root Cause (5 Whys):**

1. Invalid slots accepted.
2. Validation logic incomplete.
3. Partial implementation to meet deadline.
4. Rules not fully defined.
5. Acceptance criteria missing.

**Demo Strategy:**

- Use valid test data only.
- Avoid edge cases.
- Communicate: _“Advanced validation enhancements are being finalized.”_

**Client Communication:**  
“We identified edge-case validation improvements during QA. Core booking flow is functional, and rules will be strengthened within 3 days to ensure stable release.”

**3-Day Action Plan:**

- **Day 1:** Implement full validation (business hours, min duration, overlap prevention, holiday blocks).
- **Day 2:** QA regression + edge-case testing, fix defects.
- **Day 3:** Final stability testing, client UAT, emergency buffer.

**Prevention Strategy:**

- Detailed acceptance criteria.
- Validation checklist before coding.
- QA involvement during requirements.

---

## Key PM Takeaways

- Scope creep is normal — unmanaged scope creep is dangerous.
- Team conflict signals process gaps, not personal issues.
- Transparency with clients builds trust.
- Root cause analysis prevents repeat mistakes.

---
