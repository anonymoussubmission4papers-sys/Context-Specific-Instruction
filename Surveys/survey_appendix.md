# Appendix A. Post-Task and Session-End Survey (Question Text and Display Logic)

This appendix documents the exact survey questions and display logic used in the study. Identifying details (e.g., institution, compensation forms) have been removed to preserve double-blind review.

---

## Block 1: Practice Task (Practice 5)

- **P1. Task identifier** (free text): "Task ID".
- **P2. Bug location** (free text): "File name and line number(s) where you found the bug."
- **P3. Bug description** (free text): "Describe the bug and any potential fix."
- **P4. Process summary** (open-ended): "Briefly describe your overall process for locating the bug (steps/strategies)."
- **P5. Effort** (1–5 Likert): 1 = Extremely easy … 5 = Extremely difficult.
- **P6. Effort—why** (open-ended): "What specific aspects made it challenging or easy?"
- **P7. Satisfaction** (1–5 Likert): 1 = Very unsatisfied … 5 = Very satisfied.
- **P8. Satisfaction—why** (open-ended): "What aspects of your performance influenced your satisfaction?"
- **P9. Perceived stress** (1–5 Likert): 1 = Not at all stressful … 5 = Extremely stressful.
- **P10. Stress—why** (open-ended): "What aspects of the task felt stressful?"

**Branching for instruction groups only (shown if participant was assigned to an instruction group):**

- **I1. Helpfulness of instruction** (1–5 Likert): 1 = Extremely unhelpful … 5 = Extremely helpful.
- **I2. Adherence** (1–5 Likert): 1 = Did not follow … 5 = Followed exactly.
- **I3. Actionability** (1–5 Likert): 1 = Not at all (couldn’t translate steps) … 5 = Completely (performed all steps as intended).
- **I4. Re-reading needed** (1–5 Likert): 1 = Never … 5 = Very often.
- **I5. Unclear parts?** (Yes/No).  
  – If **Yes**: **I5a.** "Which parts felt unclear or ambiguous?" (open-ended).
- **I6. (Abstract-instruction group only)**  
  – **I6a.** "For the ‘Get a quick overview of the codebase’ step, what action(s) did you take?" (open-ended).  
  – **I6b.** "Would more specific guidance have helped? If yes, what kind?" (open-ended).
- **I7. (Context-agnostic concrete group only)**  
  – **I7a.** "Describe the general control flow of this codebase." (open-ended).
- **I8. (Context-specific instruction group only)**  
  – **I8a.** "When tracing the control flow, how much did you use the provided code references (e.g., example line numbers or method names)?" (1–5 Likert: 1 = Never … 5 = Always).  
  – If "Never" or "Rarely": **I8b.** "Why did you choose not to use those references?" (open-ended).  
  – **I8c.** "How helpful were the specific examples (line numbers, method names, file names) for understanding what to do?" (1–5 Likert: 1 = Not helpful at all … 5 = Extremely helpful).

---

## Block 2: Test Task (Test 5)

- **T1–T4**: Same as P1–P4.  
- **T5. Effort** (1–5 Likert; same anchors as P5).  
- **T6. Effort—why** (open-ended).  
- **T7. Satisfaction** (1–5 Likert; same anchors as P7).  
- **T8. Satisfaction—why** (open-ended).  
- **T9. Perceived stress** (1–5 Likert; same anchors as P9).  
- **T10. Stress—why** (open-ended).  
- **T11. Approach shift** (open-ended): "How did your approach here differ from your usual debugging?"

---

## Block 3: End-of-Session Interview (shown only for instruction groups)

- **E1. Instruction reflection** (open-ended): "In the practice task, which parts of the instruction were especially useful or confusing?"
- **E2. Transfer** (Yes/No): "In the test task (without explicit instruction), did you leverage anything from the earlier instruction?"  
  – If **Yes**: **E2a.** "What did you leverage?" (open-ended).
- **E3. Suggestions** (open-ended): "What suggestions would improve the instruction?"
- **E4. Practice effect** (open-ended): "How did the practice session influence your test performance?"
- **E5. Procedure change over sessions** (Yes/No).  
  – If **Yes**: **E5a.** "What aspect(s) of your debugging procedure changed?" (open-ended).

---

## Note on Compensation

Compensation details (e.g., course credit or gift cards) were collected in a **separate, unlinked form** and are not part of this survey instrument.
