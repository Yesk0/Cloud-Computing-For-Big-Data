# User Interview Transcript: The "5 Whys" Deep Dive

**Interviewer:** Product Manager (Agent)
**Persona:** Aidar, Senior Procurement Specialist at NC KTZ JSC
**Topic:** Delays in Technical Specification Approvals (Tender Documentation)

---

### Context
Aidar works in the Material Technical Supply department. His KPI is "Timely approval of tender documentation," but his actual day is spent fighting with Excel sheets and PDF technical standards.

### The Interview

**PM:** Thanks for sitting down, Aidar. I noticed in our audit that the "Time to Tender" metric is red. You mentioned it takes 3 weeks just to approve a technical spec for simple spare parts. **(1) Why does it take so long?**

**Aidar:** Honest answer? Because I have to reject 80% of the requests that come from the engineering stations. They send me specifications that are copy-pasted from old contracts, or they reference GOST standards that expired in 2019. If I approve a tender with a bad spec, Audit will fine us later.

**PM:** That sounds frustrating. **(2) Why do the engineers send you outdated or incorrect specifications? Don't they know the current standards?**

**Aidar:** They are track maintenance guys, not lawyers. They are out in the field. When they need a "switch rail type P65," they just open the last contract we signed and copy that text. They don't have access to the legal database where the new ESG compliance rules or the updated "Samruk-Kazyna Local Content" rules are stored. That's *my* drive, not theirs.

**PM:** I see. So there's a disconnect in knowledge access. **(3) Why don't you just give them access to that database or a template that is always up to date?**

**Aidar:** We have "templates" in the ERP, but they are just blank Word docs attached to a SAP record. The rules change every month—new sanctions, new ecological standards (Goal 5), new safety protocols (Goal 6). To make a "perfect template," I would have to manually update 50,000 material codes every week. I can't do that. So I let them send junk, and I spend my weekends manually correcting it with red pen.

**PM:** You are manually correcting thousands of specs. **(4) Why isn't there an automated system to check these specs against the current rules before they reach your desk?**

**Aidar:** Because our "Digitalisation" (Goal 4) is focused on big transit corridors like Tez Customs, not back-office grunt work. The IT department gave us a "document workflow" system, but it's just a digital postman. It moves the PDF from his desk to mine. It doesn't *read* the PDF. It doesn't tell the engineer, "Hey, this GOST is dead." It just delivers the bad file to me faster.

**PM:** So the tool moves data but doesn't validate it. **(5) Why is that specific validation capability missing from your current roadmap?**

**Aidar:** Because nobody realizes that "compliance" is a data problem, not a process problem. They think we just need "more procurement officers." But I don't need more people; I need a smart assistant that sits on the engineer's shoulder and says, "Stop! You can't buy that battery without the lead-free certificate." If I had that, I could focus on strategy, not spellchecking.

---

### Key Insights (The "Aha!" Moments)
1.  **The Symptom:** Procurement is slow.
2.  **The Root Cause:** Engineers lack real-time access to compliance rules at the *moment of creation*.
3.  **The Operational Failure:** The current digital tools (Workflow/ERP) are "dumb pipes"—they transport documents but do not understand their content.
4.  **The Opportunity:** Move validation upstream. Don't check the homework; help them write it correctly.
