
---

# 🚨 Crisis Management Report – Schedula (Salon Booking App)

**Date:** February 18, 2026

---

## CRISIS 1: Scope Creep Emergency

### Problem Statement

Six days before launch, the client requested four major new features while the sprint is already at full capacity. This risks delaying launch and reducing product stability.

### Root Cause (3 Whys)

- **Why 1:** Client compared Schedula with competitor apps and requested parity features.
- **Why 2:** Feature expectations were not clearly aligned or prioritized before the final sprint.
- **Why 3:** Launch scope was not formally documented, signed off, and locked with a change control process.

**Root Cause:** Lack of formal scope freeze and change control before final sprint.

### Response Options

|Option|Outcome|Trade-offs|
|---|---|---|
|**A – Add All Features Before Launch**|Client happy short-term|Launch delayed 2–3 weeks, high dev pressure, bug risk|
|**B – Prioritize WhatsApp Booking Only**|Balanced satisfaction|On-time launch, one high-value feature added, others moved to Phase 2|
|**C – Launch As Planned, Move All to Phase 2**|Stable release|On-time launch, temporary client disappointment, requires clear roadmap|

### Recommendation

**Option B – Prioritize WhatsApp Booking.**  
This delivers the highest business value while keeping launch on track. Remaining features will be scheduled for Phase 2.

👉 _Human touch:_ Communicate empathetically with the client:  
_"We understand your excitement about new features. To ensure a smooth launch, we’ll prioritize WhatsApp booking now and roll out the other enhancements in Phase 2. This way, you get a stable product on time and a clear roadmap for growth."_

---

## CRISIS 2: Team Conflict Scenario

### Root Cause (3 Whys)

- **Why 1:** Developer redoing work due to late design changes.
- **Why 2:** Design changes occurred after development started.
- **Why 3:** No design freeze or approval checkpoint before sprint execution.

**Root Cause:** Lack of structured design-to-development handoff process.

### Immediate Fix (Today’s Action)

- **Rajesh (Developer):** _“Designs will be frozen by EOD today. You’ll only implement approved versions. No rework without PM approval.”_
- **Priya (Designer):** _“All UX improvements must be finalized before sprint start. For this sprint, we’ll lock designs after today.”_
- **Amit (QA):** _“You’ll test the latest approved version. Final UI freeze confirmed by 4 PM.”_

### Process Change for Next Sprint

- Introduce **Design Freeze Rule** before sprint start.
- Mandatory design approval meeting.
- No UI changes mid-sprint without formal change request.
- Clear version tagging for QA.

👉 _Human touch:_ Frame this as teamwork, not blame:  
_"We’re locking designs today to protect everyone’s effort. Going forward, we’ll set clear checkpoints so no one has to redo work unnecessarily."_

---

## CRISIS 3: Data Quality Issue

### Root Cause (5 Whys)

- **Why 1:** Invalid time slots accepted.
- **Why 2:** Validation logic incomplete.
- **Why 3:** Partial implementation to meet sprint deadline.
- **Why 4:** Time slot rules not fully defined during planning.
- **Why 5:** Business validation scenarios not documented in acceptance criteria.

**Root Cause:** Incomplete validation requirements and rushed implementation.

### Demo Strategy

- Use valid test data only.
- Avoid edge-case scenarios.
- Communicate clearly: _“Advanced validation enhancements are being finalized for launch.”_

### Client Communication (2–3 Sentences)

_"During final QA, we identified edge-case improvements in time-slot validation. The booking flow is fully functional, and we’re strengthening rules over the next three days to ensure a stable release."_

### 3-Day Action Plan

- **Day 1:** Implement full validation logic (business hours, min duration, overlap prevention, holiday blocks).
- **Day 2:** QA regression + edge-case testing, fix defects immediately.
- **Day 3:** Final stability testing, client UAT, emergency buffer.

---

## Prevention Strategy

- **Scope Creep:** Formal scope freeze, signed roadmap, change request documentation.
- **Team Conflict:** Design freeze, approval checkpoints, version control discipline.
- **Data Quality:** Detailed acceptance criteria, validation checklist, QA involvement during requirements.

---

## Key PM Takeaways

- Scope creep is normal — unmanaged scope creep is dangerous.
- Team conflict usually signals process failure, not personality issues.
- Transparency with clients builds long-term trust.
- Root cause analysis prevents repeat mistakes.

👉 _Human touch closing note:_  
_"Projects rarely go exactly as planned. What matters is how we respond—with clarity, empathy, and discipline. By balancing stability with client needs, we protect both the product and the team."_

---

Would you like me to also **draft a client-facing email** summarizing these crises and resolutions in a concise, reassuring way? That could help you communicate the plan smoothly.