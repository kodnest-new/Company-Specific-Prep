# Let's Flo – Developer Grooming Guide

> **Role:** Developer (Front End + Backend)  
> **Location:** Bengaluru – Work From Office  
> **Package:** 3.0–4.0 LPA (Based on Performance)

---

## Table of Contents
1. [Company Overview](#company-overview)
2. [Role Overview](#role-overview)
3. [Selection Process](#selection-process)
   - [Round 1: Profile Screening](#round-1-profile-screening)
   - [Round 2: Aptitude + Coding Test](#round-2-aptitude--coding-test)
   - [Round 3: Technical Interview](#round-3-technical-interview)
   - [Round 4: HR Interview](#round-4-hr-interview)
4. [Previously Asked Questions](#previously-asked-questions)
   - [Aptitude + Coding Round](#aptitude--coding-round)
   - [Technical Interview Round](#technical-interview-round)
   - [HR Interview Round](#hr-interview-round)
5. [Do’s and Don’ts](#dos-and-donts)
6. [Conclusion](#motivational-conclusion)

---

## Company Overview

Let’s Flo is a SaaS platform that streamlines **e-commerce content workflows** for large retail brands. It manages everything from tracking physical product samples to coordinating photography, editing, and publishing product listings—all in one place.

- **Problem Solved:** Without Let’s Flo, teams juggle spreadsheets, emails, and ad-hoc tools to track content steps. Errors or delays can lead to missing images or wrong descriptions going live.
- **Real-World Impact:** Imagine a fashion brand launching a new collection. Let’s Flo lets them scan bar-coded samples, track their photo shoot status, assign copywriting tasks, and approve final art—all in a single dashboard. This reduces **time to market** and **eliminates miscommunication**.
- **Example Clients:** Burberry, Marks & Spencer, and other global brands trust Let’s Flo to power their product content operations.

---

## Role Overview

**Position:** Developer  
**Key Technologies:** HTML, CSS, JavaScript, React, MongoDB, SQL, Data Structures & Algorithms

**Responsibilities:**

- **Feature Development:** Implement new UI screens in React; build REST APIs on the backend.
- **Front-End:** Convert design mockups into responsive HTML/CSS/JS; manage component state in React.
- **Back-End & Databases:** Write queries in SQL or design document schemas in MongoDB; expose data via endpoints.
- **Testing & Debugging:** Unit test code; troubleshoot and fix bugs using browser DevTools or server logs.
- **Collaboration:** Participate in daily stand-ups, code reviews, and pair programming with seniors.
- **Continuous Learning:** Adopt emerging frameworks, tools, and best practices to keep the product cutting edge.
- **Documentation:** Write clear code comments and update developer wikis or READMEs.

**Why It’s Great for Freshers:** You’ll work end-to-end on a product used by real customers, learn modern web stacks quickly, and have direct mentorship exposure in a fast-growing startup.

---

## Selection Process

### Round 1: Profile Screening

- **What:** Resume & eligibility check (CGPA ≥ 7.0 / 70% throughout, relevant projects, skills in HTML/CSS/JS, React, MongoDB/SQL).
- **Preparation:**
  - Polish your resume to highlight relevant projects & technologies.
  - Include links to GitHub and any portfolio sites.
  - Be honest: list only skills you can discuss in detail.

### Round 2: Aptitude + Coding Test

- **Format:** 60–90 minutes; sections on quantitative aptitude, logical reasoning, and coding problems.
- **Topics:**
  - Quantitative: time & distance, ratios, percentages, profit & loss.
  - Logical: series, puzzles, verbal grammar.
  - Coding: arrays, strings, loops, conditionals, simple data structures.
- **Preparation:**
  - Practice aptitude questions on Indiabix or RS Aggarwal.
  - Solve coding challenges on HackerRank/LeetCode (easy level).
  - Time yourself and plan approach before coding.

### Round 3: Technical Interview

- **Focus Areas:**
  - Deep dive into your resume projects.
  - Front-end: HTML tags, CSS layout (Flex/Grid), JS fundamentals, React components/props/state.
  - Back-end: CRUD operations in SQL, schema design in MongoDB, REST API concepts.
  - Data Structures & Algorithms: array vs linked list, stack/queue, sorting basics, time complexity.
  - Debugging approach: systematic troubleshooting of web issues.
- **Preparation:**
  - Revise fundamentals and practice explaining concepts out loud.
  - Conduct mock interviews and whiteboard coding sessions.
  - Review your own projects and be ready to discuss challenges and solutions.

### Round 4: HR Interview

- **Focus Areas:** Communication skills, cultural fit, motivation, behavioural scenarios.
- **Common Questions:**
  - “Tell me about yourself.”
  - “Why do you want to join Let’s Flo?”
  - “What are your strengths and weaknesses?”
  - “Where do you see yourself in 5 years?”
- **Preparation:**
  - Use the STAR method for behavioural questions (Situation, Task, Action, Result).
  - Prepare a concise personal pitch and thoughtful questions to ask the interviewer.

---

## Previously Asked Questions

Detailed sample questions with **model interview-style answers**.

### Aptitude + Coding Round

1. **Train Catch-Up Problem**  
   **Q:** A train leaves City A at 7:00 AM at 60 km/h. Another leaves at 7:30 AM at 90 km/h. When does the second catch the first?  
   **A:** “In 30 minutes, the first train covers 30 km (60 km/h × 0.5 h). The relative speed is 90 – 60 = 30 km/h. So it takes 30 km ÷ 30 km/h = 1 hour. Starting at 7:30 AM, they meet at 8:30 AM.”

2. **Consecutive Odd Numbers**  
   **Q:** Average of five consecutive odd numbers is 35. Find the smallest.  
   **A:** “Let the smallest be x. The average is x+4 = 35 → x = 31.”

3. **Time-Speed-Distance**  
   **Q:** A 150 m train passes a pole in 15 s. Speed in km/h?  
   **A:** “150 m/15 s = 10 m/s × 3.6 = 36 km/h.”

4. **Number Series**  
   **Q:** 2, 6, 12, 20, 30, … Next?  
   **A:** “Differences are +4, +6, +8, +10 → next +12 = 42.”

5. **Profit Percentage**  
   **Q:** Buy at ₹500, sell at ₹600. Profit%?  
   **A:** “Profit ₹100/₹500 × 100 = 20%.”

6. **Odd One Out**  
   **Q:** 3,5,11,14,17,21. Odd one?  
   **A:** “14, because it’s not prime.”

7. **HTML Script Tag**  
   **Q:** Tag for external JS?  
   **A:** “`<script src=\"app.js\"></script>`.”

8. **Mutable Default Argument**  
   **Q:** Python func example output?  
   **A:** “[1] then [1, 1], since default list persists.”

9. **Palindrome Check**  
   **Q:** How to check palindrome?  
   **A:** “Normalize string, reverse, compare (e.g., `s == s[::-1]`).”

10. **Two-Sum Problem**  
    **Q:** Find two numbers summing to X.  
    **A:** “Use hash set: for each num, if X-num in set, return true; else add num.”

### Technical Interview Round

1. **Explain Your Project**  
   **A:** “I built a React front-end for a college event system and designed its MySQL database. To handle concurrent registrations, I implemented transactions and indexing, ensuring data integrity.”

2. **What is React?**  
   **A:** “A JS library for building UIs with components and a virtual DOM. I’ve used hooks for state and effects in a todo app.”

3. **HTML vs. CSS**  
   **A:** “HTML structures content; CSS styles it (colors, layout). I used Flexbox to center elements.”

4. **== vs. ===**  
   **A:** “`==` does type coercion; `===` checks value and type strictly.”

5. **SQL JOIN Types**  
   **A:** “INNER JOIN: matching rows; LEFT JOIN: all left + matches; RIGHT JOIN: vice versa; FULL JOIN: all rows.”

6. **Array vs. Linked List**  
   **A:** “Arrays: O(1) access, expensive inserts; lists: O(n) access, O(1) inserts.”

7. **MongoDB vs. SQL**  
   **A:** “SQL is relational with fixed schema; MongoDB is document-based, schema-flexible.”

8. **Debugging Scenario**  
   **Q:** Page not loading—steps?  
   **A:** “Check console for errors, Network tab for failed calls, test APIs in Postman, review server logs, isolate issue.”

9. **Stack & Queue**  
   **A:** “Stack LIFO (`push`/`pop`), queue FIFO (`enqueue`/`dequeue`).”

10. **FizzBuzz**  
    **A:** “Loop 1–15: if i%15==0 print ‘FizzBuzz’; elif i%3==0 print ‘Fizz’; elif i%5==0 print ‘Buzz’; else print i.”

### HR Interview Round

1. **Tell Me About Yourself**  
   **A:** “I’m [Name], B.Tech in CS, built React & Node.js apps, led front-end in college, quick learner, enjoy table tennis for teamwork skills.”

2. **Why Let’s Flo?**  
   **A:** “Your platform solves real e-commerce content challenges. I want to work in a dynamic startup and see my code impact top brands.”

3. **Strengths & Weaknesses**  
   **A:** “Strengths: fast learner, collaborative. Weakness: public speaking—improving via campus presentations.”

4. **Where in 5 Years?**  
   **A:** “A mid-level developer mentoring juniors, leading feature development and code reviews.”

5. **Difficult Situation**  
   **A:** “When our backend lead fell ill, I learned the codebase, wrote core APIs, and kept stakeholders updated, delivering on time.”

6. **Why Hire You?**  
   **A:** “My skills match your tech stack, I’m eager to learn, a team player, and aligned with Let’s Flo’s mission.”

7. **Higher Studies Plans**  
   **A:** “No immediate plans—fully committed to this role.”

8. **Handling Stress**  
   **A:** “Prioritize tasks, take short breaks, and communicate with teammates to manage workload.”

9. **Salary Expectations**  
   **A:** “Flexible; I trust Let’s Flo’s standard fresher package and prioritize learning opportunities.”

10. **Questions for Us?**  
    **A:** “Could you describe the onboarding process and a typical first project? Also, how do you support continuous learning?”

---

## Do’s and Don’ts

### Do’s
- **Research** Let’s Flo and its products.  
- **Practice** aptitude and coding daily.  
- **Revise** HTML/CSS/JS/React fundamentals.  
- **Mock** interviews and seek feedback.  
- **Be** punctual, professional, and positive.

### Don’ts
- **Don’t** lie or exaggerate your skills.  
- **Don’t** memorize answers word-for-word.  
- **Don’t** skip rest before the interview.  
- **Don’t** interrupt or argue with interviewers.  
- **Don’t** forget to ask insightful questions.

---

## Conclusion

> **Every expert was once a beginner.**  
> You have a solid foundation—now bring your curiosity and confidence to each round.  
> Interviewers seek potential, learning attitude, and clear communication.  
> Envision yourself contributing to Let’s Flo’s platform for top brands. Approach with enthusiasm and make it happen!  

*Good luck! You’ve got this.*
