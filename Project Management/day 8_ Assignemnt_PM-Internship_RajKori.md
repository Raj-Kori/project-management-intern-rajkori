

---

# Presenter: Raj Kori

## Project: Schedula – Salon Booking Application

### Role: Project Management Intern

### Prepared by: Raj Kori

---

# What I’ve Learned About Project Management (As an Intern)

In today’s fast-moving product environment, a Project Manager’s real strength lies in:

- Communicating clearly — both in meetings and in writing
    
- Managing stakeholder pressure calmly
    
- Making practical decisions when no option feels perfect
    
- Bringing structure to unclear or urgent situations
    

Even as an intern, I understand that unclear instructions cost time, energy, and team morale.

---

# Exercise 1 – Handling a Bug the Right Way

### Stakeholder Message:

Please fix this immediately and keep me posted.

### Reported Problem:

Customers are able to schedule appointments beyond the salon’s closing hours.

---

## Example of an Unclear PM Response

Please check and resolve this quickly.

### Why This Is a Problem:

- No clarity on which part of the system is affected
    
- No explanation of expected system behavior
    
- No definition of urgency level
    
- No testing or validation instructions
    
- Developers forced to make assumptions
    

### Possible Outcomes:

- Multiple clarifications required
    
- Incorrect fixes
    
- Delayed release
    
- Rework and frustration
    

As a PM intern, I’ve realized that vague communication creates more work instead of solving problems.

---

## Example of a Structured PM Response

**Issue Summary:**  
Users are currently able to book appointments outside official operating hours.

**Business Risk:**  
Bookings made after closing time cannot be honored, which may lead to negative customer experience and increased support complaints.

**Impacted Area:**  
Online Appointment Booking Module

**Correct System Behavior:**  
The system should prevent bookings after 8:00 PM.

---

### Acceptance Conditions:

- Booking before 8:00 PM → Allowed
    
- Booking at exactly 8:00 PM → Allowed
    
- Booking after 8:00 PM → Not allowed
    

**Display Message:**  
“Bookings are closed for today. Kindly select another available date.”

---

### Validation Requirements:

- Test with multiple user profiles
    
- Ensure no booking record is saved after 8 PM
    
- Confirm correct error message appears
    

---

### Priority & Follow-up:

- Priority Level: High (Customer-facing issue)
    
- Share root cause and expected completion timeline
    
- Notify early if timeline shifts
    

Clear communication ensures faster execution and fewer follow-ups.

---

# Exercise 2 – Making a Practical Launch Decision

### Situation:

The salon booking app is scheduled to launch in 3 weeks.

During QA testing, two issues were identified:

1. WhatsApp appointment reminders are incomplete and unstable
    
2. Online payments work only via cards; UPI option is missing
    

### Development Estimates:

- WhatsApp reminders need 10 additional days
    
- UPI integration requires 12–14 days
    
- Attempting both together increases release risk significantly
    

---

## Step 1: Define the Core Problem

We cannot safely deliver both features before launch due to time and engineering capacity limits. A decision must be made.

As a PM intern, my role is to weigh impact, feasibility, and risk.

---

## Step 2: Evaluate the Options

### Option A: Deliver Both Features Before Launch

**Advantages:**

- Short-term stakeholder satisfaction
    

**Disadvantages:**

- High pressure on development team
    
- Increased probability of bugs
    
- Risk of unstable product launch
    

---

### Option B: Prioritize WhatsApp Reminders

**Advantages:**

- Directly reduces appointment no-shows
    
- Improves business revenue impact
    
- Safer and more controlled release
    

**Disadvantages:**

- UPI delayed
    
- Some stakeholder dissatisfaction
    

---

### Option C: Prioritize UPI Payments

**Advantages:**

- Expands payment flexibility
    
- Adds convenience for users
    

**Disadvantages:**

- Does not address no-show issue
    
- Reminder feature remains unstable
    

---

## My Final Decision – Raj Kori

I would move forward with **prioritizing the WhatsApp reminder feature** for this release.

### Why?

Reducing no-shows directly supports salon revenue and improves service efficiency. Since card payments are already functional, users can still complete transactions.

A stable release with one high-impact feature is better than launching multiple incomplete features.

UPI integration can be scheduled for the next sprint after launch.

---

# Key Learning

Project management is not about choosing everything.  
It’s about choosing wisely.

Even as an intern, I believe clarity, prioritization, and structured decision-making are what differentiate a reactive PM from an effective one.

— Raj Kori