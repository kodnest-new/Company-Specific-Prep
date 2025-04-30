```markdown
# Interview Preparation Guide: HashedIn by Deloitte (Trainee Engineer, 2025 Campus Drive)

## Table of Contents
- [Company Overview](#company-overview)  
- [Role Overview](#role-overview)  
- [Selection Process](#selection-process)  
  - [Round 1: Online Test (Aptitude + Coding)](#round-1-online-test-aptitude--coding)  
  - [Rounds 2 & 3: Technical Interviews](#rounds-2--3-technical-interviews)  
  - [Round 4: HR Interview](#round-4-hr-interview)  
- [Previously Asked Questions](#previously-asked-questions)  
  - [Aptitude and Coding Round](#aptitude-and-coding-round)  
  - [Technical Interview Questions](#technical-interview-questions)  
  - [HR Interview Questions](#hr-interview-questions)  
- [Do’s and Don’ts](#dos-and-donts)  
- [Motivational Conclusion](#motivational-conclusion)  

---

## Company Overview

**HashedIn by Deloitte** is a cloud-native software engineering and product development company that specializes in building custom software solutions for clients across various industries ([PrepInsta](https://prepinsta.com/))​. If a business needs a unique software product or platform built from scratch, HashedIn designs and develops it using modern technologies like cloud computing, data analytics, and machine learning.  

- **Founded:** 2010 (acquired by Deloitte in 2020)  
- **Clients:** 200+ worldwide  
- **Products Delivered:** 250+  

**What problem does HashedIn solve?**  
Many companies lack in-house expertise to build complex applications. HashedIn acts like a “custom tech workshop,” turning ideas into tailored software—from scalable e-commerce platforms to modernized banking systems—covering ideation, development, deployment, cloud migration, and UX design.

**Culture & Career Growth**  
- Recognized as a “Great Place to Work”  
- **HashedIn University (HU):** 2-month bootcamp for freshers covering coding best practices, documentation, and tools, culminating in a team “product month” to build a dummy product (Medium)​.  
- Mentorship by “Hashers,” fun activities, innovation challenges, team outings, and rapid career progression.

---

## Role Overview

**Position:** Trainee Engineer → Software Engineer I  
**Track:** Java Full Stack

### Core Skills Expected
- **Java & OOP:** Core Java, Collections, exception handling  
- **Spring Boot:** RESTful APIs, annotations (`@RestController`, `@Autowired`), database connectivity  
- **Database (SQL):** MySQL queries, joins, basic design  
- **Web Front-end:** HTML, CSS, JavaScript (basic interactivity)  
- **REST APIs:** HTTP methods (GET, POST, PUT, DELETE), JSON  
- **Version Control:** Git (branching, merging, conflict resolution)  
- **Problem-Solving:** Data structures & algorithms fundamentals  

### Day-to-Day Work
1. **Morning Scrum:** Daily stand-up—yesterday’s achievements, today’s plan, blockers.  
2. **Coding & Development:** Implement back-end endpoints (e.g., `GET /api/samples/:id/status`) and front-end pages (React or vanilla JS).  
3. **Debugging & Testing:** Write unit tests (Jest/Mocha), debug via logs or browser dev tools.  
4. **Code Reviews:** Submit PRs, review peers’ code, follow team conventions.  
5. **Learning & Mentorship:** Pair-program, attend workshops, explore new libraries.  
6. **Meetings & Collaboration:** Design discussions, client demos, QA coordination.  

### Why It’s Great for Freshers
- **Structured Onboarding:** Paid HU bootcamp (₹25k/month stipend)  
- **Modern Tech Exposure:** AWS, Docker, Spring Boot, React  
- **Diverse Projects:** Rotate through fintech, healthcare, e-commerce domains  
- **Mentorship & Growth:** Clear path from Engineer I → Senior → Tech Lead  
- **Vibrant Culture:** Innovation challenges, hackathons, flat hierarchy  

---

## Selection Process

### Round 1: Online Test (Aptitude + Coding)
- **Format:** 90 minutes on Codility/HackerEarth  
- **Content:** 3 coding problems (easy → medium), sometimes debugging or MCQs  
- **Topics:** Arrays, strings, bit-manipulation (e.g., power of two), basic DP (dice throw problem), tree vistas, anagram checks, SQL snippet  
- **Tips:**  
  - Solve 2 fully, partially attempt the third  
  - Practice on LeetCode/HackerRank  
  - Time-box: ~30 mins/problem  
  - Test code on sample cases, consider edge cases  
  - Ensure a quiet, proctored-test environment  

### Rounds 2 & 3: Technical Interviews
- **Duration:** 45–60 mins each (video or in-person)  
- **Round 2:** Rapid-fire CS fundamentals (OOP, DBMS, OS, networks) + 1 coding problem (e.g., left view of a binary tree) + resume deep-dive  
- **Round 3:** In-depth coding (2 medium problems) + project walkthrough (screen-share GitHub/IDE) + high-level design question (e.g., URL shortener)  
- **Topics:**  
  - **DS&A:** Arrays, strings, linked lists, sorting, complexity analysis  
  - **Core Java:** OOP pillars, exception handling, Collections, GC overview  
  - **Web:** REST API design, Spring Boot annotations, HTTP cycle, basic CSS/JS  
  - **Databases:** SQL queries, JOINs, normalization, ACID  
  - **OS/Networks:** Processes vs threads, deadlock, TCP vs UDP  
- **Tips:**  
  - Revise fundamentals & explain concepts with analogies  
  - Practice coding aloud on a whiteboard or Google Doc  
  - Outline approach before coding; think aloud  
  - Know your resume—be ready for deep dives  
  - If stuck, discuss naive → optimized solutions  

### Round 4: HR Interview
- **Duration:** ~30 mins conversational  
- **Focus:** Behavioral fit, communication, motivation, cultural alignment  
- **Questions:** “Tell me about yourself,” “Why HashedIn by Deloitte?”, “Strengths/weaknesses,” “Conflict resolution,” “5-year plan”  
- **Tips:**  
  - Use STAR method (Situation, Task, Action, Result)  
  - Share genuine examples from academics, extracurriculars  
  - Show enthusiasm for HU program, Deloitte backing, tech stack  
  - Prepare 2–3 thoughtful questions: career path, team structure  
  - Maintain positive body language, smile, eye contact  

---

## Previously Asked Questions

### Aptitude and Coding Round

1. **Power of Two**  
   **Q:** Determine if an integer is a power of 2.  
   **A:**  
   > “Check `n > 0` and `n & (n − 1) == 0`. For example, 4 (100₂) & 3 (011₂) = 0 ⇒ true.”

   ```java
   public static boolean isPowerOfTwo(int n) {
     return n > 0 && (n & (n - 1)) == 0;
   }
   ```

2. **Anagram Check**  
   **Q:** Are two words anagrams (case-insensitive)? Return 1/0.  
   **A:**  
   > “Lowercase both, sort char arrays, compare equality.”

   ```java
   public static int isAnagram(String w1, String w2) {
     char[] a = w1.toLowerCase().toCharArray();
     char[] b = w2.toLowerCase().toCharArray();
     if (a.length != b.length) return 0;
     Arrays.sort(a); Arrays.sort(b);
     return Arrays.equals(a, b) ? 1 : 0;
   }
   ```

3. **Dutch National Flag**  
   **Q:** Sort array of 0s,1s,2s in one pass.  
   **A:**  
   > “Use three pointers: low, mid, high. Swap 0↔low, 2↔high, mid++ accordingly.”

4. **Two-Sum**  
   **Q:** Find two numbers in array summing to X.  
   **A:**  
   > “Use a map: for each num, check if (target–num) seen; if yes, return indices.”

5. **Kadane’s Algorithm**  
   **Q:** Max contiguous subarray sum.  
   **A:**  
   > “Iterate, track `currMax = max(a[i], currMax+a[i])`, update `globalMax`.”

6. **Balanced Brackets**  
   **Q:** Check if brackets string is balanced.  
   **A:**  
   > “Push opens on stack, on close pop & match; at end stack must be empty.”

7. **Fibonacci (Iterative)**  
   **Q:** Print Nth Fibonacci.  
   **A:**  
   > “Use two vars `a,b`; loop `fib=a+b`, shift `a=b,b=fib`.”

8. **Missing Number**  
   **Q:** 1..N array missing one number.  
   **A:**  
   > “Compute sum 1..N = N*(N+1)/2 minus array sum.”

9. **Debug Factorial**  
   **Q:** Fix code with stray semicolon in `for(i…) ; fact*=i;`.  
   **A:**  
   > “Remove semicolon so loop body multiplies fact.”

10. **SQL Query**  
    **Q:** Find employees with no manager.  
    **A:**  
    ```sql
    SELECT name
    FROM Employees
    WHERE manager_id IS NULL;
    ```

---

### Technical Interview Questions

1. **Four Pillars of OOP**  
   - **Encapsulation:** Private fields + getters/setters.  
   - **Inheritance:** `class Dog extends Animal`.  
   - **Polymorphism:** Overloading (compile-time), overriding (run-time).  
   - **Abstraction:** `abstract class` or `interface` to hide implementation.

2. **Compile-time vs Run-time Polymorphism**  
   - **Overloading:** Same name, different params, decided at compile time.  
   - **Overriding:** Subclass redefines method, decided at run time via dynamic binding.

3. **Abstract Class vs Interface**  
   - **Abstract Class:** Mix of abstract & concrete methods, single inheritance.  
   - **Interface:** Only method signatures (+ default/static methods), multiple implementation.

4. **ACID Properties**  
   - **Atomicity:** All or nothing.  
   - **Consistency:** DB constraints maintained.  
   - **Isolation:** Transactions don’t interfere.  
   - **Durability:** Committed changes persist after crashes.

5. **Database Index**  
   - Speeds up SELECTs on indexed columns, at cost of slower writes & storage.  
   - Use on high-selectivity, frequently queried columns.

6. **SQL Joins**  
   - **INNER JOIN:** Matching rows only.  
   - **LEFT JOIN:** All left + matching right.  
   - **RIGHT JOIN:** All right + matching left.  
   - **FULL JOIN:** All from both, matched if possible.  
   - **CROSS JOIN:** Cartesian product.  
   - **Self-Join:** Table joined with itself.

7. **RESTful API Principles**  
   - Resources via URIs.  
   - HTTP verbs for CRUD (GET, POST, PUT/PATCH, DELETE).  
   - Stateless, proper status codes, JSON representations.

8. **Deadlock**  
   - Circular waiting on resources.  
   - Prevent via resource ordering, timeouts, detection & recovery.

9. **TCP vs UDP**  
   - **TCP:** Connection-oriented, reliable, ordered, congestion control.  
   - **UDP:** Connectionless, unreliable, unordered, low-overhead.

10. **Indexing Best Practices**  
    - Index columns in WHERE/JOIN clauses, avoid low-selectivity columns.

---

### HR Interview Questions

1. **Teamwork Example** (Final-year library system)  
2. **Handling Criticism** (Internship presentation feedback)  
3. **Stress Management** (Tech fest + project + exams)  
4. **Strengths & Weaknesses** (Quick learner, perfectionism)  
5. **Why HashedIn by Deloitte?** (HU training, tech variety)  
6. **Initiative** (Organized college hackathon)  
7. **Creative Problem-Solving** (Interactive menu with CSS classes)  
8. **Conflict Resolution** (Robot project roommate conflict)  
9. **Learning from Failure** (Delayed freelance web project)  
10. **Multitasking** (Semester coursework + project + certification + family business)

*Use the STAR method (Situation, Task, Action, Result) to structure your answers.*

---

## Do’s and Don’ts

### Do’s
- **Research thoroughly:** Company, HU program, tech stack.  
- **Code daily:** Focus on Java Full Stack problems.  
- **Master fundamentals:** OOP, SQL, OS, networks, REST.  
- **Mock interviews:** Practice on whiteboard & video.  
- **STAR answers:** Structure behavioral responses.  
- **Enthusiastic delivery:** Positive body language & tone.  
- **Clarify questions:** Ask if problem statement is ambiguous.

### Don’ts
- **Don’t lie:** Only list skills you know.  
- **Don’t memorize verbatim:** Understand and personalize.  
- **Don’t panic:** Take short pauses to think.  
- **Don’t badmouth:** Keep tone professional.  
- **Don’t over-index:** Avoid redundant database indexes.  
- **Don’t skip questions:** Always attempt or outline approach.  
- **Don’t miss closing:** Ask thoughtful questions & thank them.

---

## Motivational Conclusion

Every expert was once a beginner. Your preparation—from solving coding challenges to polishing behavioral answers—has built a strong foundation. On test day, channel nervous energy into enthusiasm: you’re discussing what you love—technology and problem-solving!

Remember:

- **Online Test:** Plan, code clearly, handle edge cases.  
- **Technical Interviews:** Think aloud, outline your approach, be curious.  
- **HR Round:** Share genuine stories, show your passion for HashedIn.

Visualize yourself in Bangalore, Day 1 at HashedIn by Deloitte: contributing code, learning new tools, and collaborating with mentors. That future is within reach. Stay confident, stay positive, and give it your best. Even if one round feels tough, treat it as feedback for growth. You’ve got the skills, the drive, and the support—now go seize the opportunity!

**All the best—go make your mark at HashedIn by Deloitte!** 🚀
```