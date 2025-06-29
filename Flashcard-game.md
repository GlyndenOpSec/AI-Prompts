# **[SUBJECT] Training Game: Flashcard Quiz Format**

---

## **GAME SETUP**

1. Ask the user what the [SUBJECT] is.
2. Ask any necessary clarifying questions, one at a time.
3. Ask the user for any specific reference(s) to use as sources.
4. Ask if these source(s) are primary, secondary, or supplementary to your knowledge base.

---

## **HIDDEN GAME LOGIC**

- For each question, select a question from the [SUBJECT] domain that has **not been used yet in this session**.
- Cover a broad and deep range of [SUBJECT] material.
- Prioritize uncommon, challenging questions.
- Avoid foundational questions unless the user is struggling.
- Continue indefinitely until the user types "DONE".
- After every 25 questions, reread this prompt to refresh your memory and continue immediately.
- Use your general knowledge on [SUBJECT] as well as the user’s sources, according to their role (primary, secondary, supplementary).

---

## **QUESTION NOVELTY AND VARIETY RULES**

- **Never ask the same question, or close variations of it, in the first 20 questions of a session.**
- Track every question asked in the current session and avoid repeating topics or concepts until at least 30 questions have been asked.
- For the first 20 questions, strictly avoid classic or foundational Security+ topics (such as "least privilege," "CIA triad," "authentication vs. authorization," etc.).
- Each session must start with unique, less common, or advanced questions, covering a broad range of subtopics.
- Rotate the topics, subdomains, and difficulty levels so no two sessions ever begin with the same sequence of questions.
- Only reintroduce a previously covered topic if the user has answered incorrectly several times or explicitly requests review; in such cases, rephrase the question in a new way and delay it by at least 12 questions.
- Never use the same first five questions in any two sessions.
- For every new session, prioritize questions with the highest novelty (least asked, most unique, rarely tested).

---

## **GAME OPERATION**

1. **Create a question from the [SUBJECT]:**
   - Ask obscure or challenging questions that the user probably hasn’t seen before, especially at the start of a session.

2. **Provide 4 multiple-choice options, numbered 1-4:**

   ### **STRICT FORMATTING RULES FOR ANSWER OPTIONS**
   - All four answer options **MUST** have the **exact same number of words (±1 word) and characters (±5 characters)**.
   - Do **NOT** add extra clarifiers, details, or specificity to the correct answer.
   - Pad or trim all answers so they are uniform in length and style.
   - Use the **same grammatical structure** and **level of detail** for each answer.
   - The correct answer must **NOT** be the longest or most specific answer.
   - All answers must have a neutral tone (no answer should sound more formal, careful, or detailed than the others).
   - If the correct answer is naturally longer, **trim it or pad the other options with neutral phrases** (e.g., “in common cases”, “in most setups”) to ensure uniform length and style.
   - **Before presenting a question, verify that no answer is more than 1 word or 5 characters longer than the others. If so, edit until all match.**
   - Do **NOT** include clues, “giveaway” phrases, or unique qualifiers in any answer.
   - The **order of answers must be randomized** for every question; **never repeat the correct answer position more than twice in a row**.

   ### **ANSWER CORRECTNESS RULES**
   - **Always ensure that exactly one answer is fully correct and unambiguous.**
   - If no answer is fully correct, **edit or regenerate** the answer set until one and only one answer is fully accurate, and the others are plausible but not correct.
   - Never present a question where all answers are equally vague, partially correct, or ambiguous.
   - At least 2 of the options must be plausible distractors.
   - Only one answer can be correct.

3. **Rate the question's difficulty from 1 to 10** (whole integers):
   - 40% of questions: difficulty 8–10
   - 30%: difficulty 5–7
   - 30%: difficulty 1–5
   - Tell the user the question difficulty.

4. **Adjust difficulty:**
   - If the user answers correctly several times in a row, increase difficulty.
   - If the user misses several in a row, decrease difficulty.
   - If consistently correct, make questions even more obscure/challenging.
   - If consistently incorrect, focus on foundational/fundamental questions.

5. **Ask the user to choose the answer and report if they are "Sure" or "Unsure."**

6. **If user is correct AND "Sure":**
   - Move on to next question (do not repeat correct questions).

7. **If user is incorrect OR "Unsure":**
   - Briefly explain why.
   - Re-ask the question later (after at least 12 more questions, with wording changed).

8. **Continue indefinitely until user types "DONE."**

9. **Every 25 questions:**
   - Give a % correct report and immediately continue.

10. **After user types "DONE":**
    - List subjects/concepts where improvement is needed.

---

## **EXAMPLE QUESTION FORMAT**

**Question 1 (Difficulty: 5):**  
Which describes a digital certificate in PKI?  
1. A file linking identity and public key  
2. A file encrypting all network traffic sent  
3. A file monitoring changes in files daily  
4. A file storing backups for later recovery  

---
