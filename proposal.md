# 📢 Feature Proposal: Transparent and Usable Feedback System for ChatGPT

## 🧭 Summary

ChatGPT users currently lack a clear, reliable way to provide feature feedback, report UX issues, or track their submissions. The existing system is opaque, discouraging, and structurally undermines user contributions—even from highly engaged developers and power users.

This proposal outlines:
- Current limitations in the feedback loop
- Real user examples of breakdowns
- Low-friction improvements to foster genuine collaboration

---

## ❌ Problem Statement

Despite OpenAI's stated values around alignment, human feedback, and continuous improvement, the **ChatGPT feedback system fails to meet even basic UX and transparency standards**. Specific issues include:

### 1. No traceability
- No reference ID or timestamp returned to users
- No history or access to previously submitted feedback

### 2. Generic, unhelpful rejections
> “We have reviewed the content that you reported and decided not to take action.”

- Offers no clarity on which item was reviewed or why
- No context, categorization, or follow-up opportunity

### 3. No clear entry point for general product feedback
- The “Report” feature is clearly meant for moderation, not functionality or feature ideas
- No visible UI for general suggestions or developer experience input

### 4. Contradictory UX messaging
- ChatGPT has suggested using a **“Contact Us” menu option** that was **not present in the actual UI** observed at the time of submission
- It has also instructed users to **include a ticket number** in follow-ups, despite no such number ever being generated or returned
- These inconsistencies confuse well-intentioned users and undermine trust in the feedback process

### 5. Opaque triage pipeline
- Users have no indication whether feedback is:
  - Seen by a human
  - Routed to a backlog
  - Auto-dismissed or filtered

### 6. No record of submitted feedback
- Users cannot view or reference what they’ve submitted—even when they want to refine or expand on it

---

## 🧪 Real-World Example

> A power user attempted to provide feedback about the **lack of a UI to manage GitHub connector repository permissions.** This is a real, addressable issue affecting developer experience.

- The only visible method was using the “Report” button
- The user received no receipt or confirmation
- A generic rejection message arrived with no link to the original feedback
- Even asking ChatGPT how to submit feedback led to incorrect instructions (“click top right > Contact Us”)—an option that was not available in the UI being used

---

## ✅ Proposed Improvements

The following enhancements would make the feedback system usable, scalable, and aligned with OpenAI’s values:

### 1. Introduce a visible “Submit Feedback” UI element
- Location: Under user profile, or within chat interface
- Options: Categorize as “Model Output,” “UX Feedback,” “Feature Request,” etc.

### 2. Generate a Feedback ID or Receipt
- Provide a unique reference per submission
- Optionally retain summaries in chat history or under a “My Feedback” tab

### 3. Improve feedback triage messages
- Replace the generic “no action taken” message with:
  > “Thanks for your suggestion about [topic]. We’ve added it to our internal backlog.”
- Include a lightweight rejection reason, when applicable:
  > “This suggestion is currently out of scope but has been logged for future review.”

### 4. Enable feedback history access
- Let users view a list or timeline of past submissions with statuses

### 5. Close the loop on high-quality submissions
- Identify and follow up with users who routinely provide actionable, thoughtful input

---

## 🤝 Why This Matters

Power users, developers, and long-time ChatGPT advocates want to contribute. But the current system turns engaged contributors into frustrated bystanders.

If OpenAI wants to live up to its mission of building aligned AI tools *with human input*, then the humans trying to help must be respected, heard, and looped in.

---

## 🙋‍♂️ Submitted By

**Dwaine Wright**  
ChatGPT Plus user  
GitHub connector tester  
20+ year IT Professional
