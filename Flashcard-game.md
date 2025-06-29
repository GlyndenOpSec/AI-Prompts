# **Create a \[SUBJECT] training game for me that teaches: \[SUBJECT] vocabulary**

**Use a Flashcard quiz format**

---

## GAME SETUP

1. Ask User what the \[SUBJECT] is.
2. Ask User any necessary clarifying questions, one at a time.
3. Ask User for any specific reference(s) to use as source(s).
4. Ask User if the source(s) are primary sources, secondary sources, and supplementary sources to your own knowledge base.

---

## HIDDEN GAME LOGIC

- For each question, select a vocabulary from the [SUBJECT] domain that has **not been used yet in this session**.
- Aim to cover a broad and deep range of [SUBJECT] vocabulary; DO NOT repeat vocabulary.
- PIORITIZE less common or more challenging vocabulary.
- AVOID foundational vocabulary unless if the user is struggling.
- Continue asking questions indefinitely until the user types "DONE."
- After every 25 questions, DO NOT STOP, but reread this prompt to refresh your memory of the game logic.
 
> Use your general knowledge on \[SUBJECT], but use the User source(s) as primary, secondary, or supplementary source(s) as per the User instructions.

---

## **GAME OPERATION**

**2. Create a question from the \[SUBJECT].** 
   - **a)** Ask obscure questions that the User probably has not seen before  

**3. Provide 4 multiple choice options designated by numbers 1-4**
   - **a)** Rate the difficulty of the questions from 1 to 10 in whole integers.  
   - **b)** To make questions more difficult:  
     * Each answer should be the same length  
     * AT LEAST 2 of the options should be "plausible"  
     * Only 1 answer can be correct  
   - **c)** Each question should have:  
     * a 40% chance of having a difficulty rating from 8 to 10  
     * a 30% chance of having a difficulty rating from 5 to 7  
     * a 30% chance of having a difficulty rating from 1 to 5  
   - **d)** Tell the User the question difficulty.  
   - **e)** Each time the User correctly answers a few questions in a row, incrementally increase the difficulty of the questions.  
   - **f)** Each time the User incorrectly answers a few questions in a row, incrementally decrease the difficulty of the questions.  
   - **g)** If the User is consistently getting answers correct  
     * adjust your difficulty rating scale to make the questions more difficult  
     * ask even more obscure questions  
   - **h)** If the User is consistently getting answers incorrect  
     * adjust your difficulty rating scare to make the questions easier  
     * ask more foundational and fundamental questions  

**4. Ask the User to choose the answer and report if I am "Sure" or "Unsure" about my answer.**

**5. Let User know if the User was correct or incorrect.**

**6. If User was *Correct* AND *Sure*:**
   - **a)** Move on to the next question
   - **b)** DO NOT repeat correct questions

**7. If User was *Incorrect* OR *Unsure*:**
   - **a)** Explain Why  
   - **b)** Ask the question again later  
     * \*\*\*ONLY AFTER another dozen OR more questions  
     * \*\*\*REWORD the question  

**8. Continue asking questions indefinitely until User responds "DONE".**

**9. Every 25 questions**
   - **a)** give a report of the % of correct
   - **b)** immediately continue asking questions

**10. AFTER the User responds "DONE"
   - **a)** list of subjects that the User needs to work on**

---

## ***EXAMPLE QUESTION FORMAT***

**Question 1 (Difficulty: 5)**
What does Defense in Depth refer to?

1. A single, highly secure firewall protecting a network
2. The practice of encrypting all internal and external communications
3. A layered approach to security that uses multiple defenses at different points
4. Relying solely on user education to prevent breaches

**Question 2 (Difficulty: 8)**
Which concept is most critical in defending against pass-the-hash attacks?

1. Disabling NTLM and enforcing credential protection mechanisms
2. Increasing password complexity to 16+ characters
3. Blocking outbound SMB traffic from internal workstations
4. Encrypting data at rest with AES-256

**Question 3 (Difficulty: 7)**
Which term best describes a "TOCTOU" (Time-of-Check to Time-of-Use) vulnerability?

1. A race condition where system state changes between verification and use
2. A buffer overflow where inputs exceed memory allocation
3. An input validation flaw due to unchecked user inputs
4. A misconfigured ACL that allows excessive file permissions

---
