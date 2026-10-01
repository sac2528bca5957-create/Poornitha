# EduGenie — Comprehensive Demo & Testing Video Voice-Over Script

This document provides scene-by-scene narration scripts for recording voiceovers for `media/Demo_Video.mp4` and `media/Testing_Video.mp4`.

---

## Part 1: Demo Video Script (`media/Demo_Video.mp4`)
**Target Duration:** 3:30 (210 seconds)  
**Tone:** Professional, engaging, and educational.

---

### Scene 1: Introduction & Architecture Overview (0:00 - 0:30)
**Visual:** Web browser landing on `http://127.0.0.1:8000`. The hero banner and five educational feature cards are displayed. The navbar shows the active status badge (`Demo Mode (Offline)` or `Live Gemini API`).

**Voiceover Narration:**
> "Hello and welcome to the demonstration of **EduGenie**, an intelligent learning assistant powered by Google Gemini and Generative AI. 
> EduGenie is engineered to make learning accessible, intuitive, and interactive for students of all academic levels. 
> Built on a high-performance FastAPI backend with a responsive, modern interface, EduGenie offers five core capabilities: Smart Question & Answer, Concept Simplification, Educational Text Summarization, Interactive Quiz Generation with automated grading, and Personalized Learning Roadmaps. 
> Furthermore, EduGenie features deterministic offline generators and fallback mechanisms, ensuring zero downtime even in offline environments or during API rate-limiting events. Let's explore each capability in action."

---

### Scene 2: Scenario 1 — Smart Q&A (`Which is the largest ocean?`) (0:30 - 1:05)
**Visual:** User enters `"Which is the largest ocean?"` into the Q&A card, clicks **Ask Question**, and watches the spinner resolve into a structured, concise answer.

**Voiceover Narration:**
> "In our first scenario, a student seeks quick, factual knowledge about Earth's geography. 
> We type: *'Which is the largest ocean?'* and submit the query. 
> Instantly, EduGenie analyzes the intent and returns a concise, accurate response: The Pacific Ocean is the largest and deepest ocean on Earth, spanning over 63 million square miles and covering more than 30% of the planet's surface. 
> Notice how the answer provides both the direct answer and essential context without overwhelming the learner."

---

### Scene 3: Scenario 2 — Concept Explainer (`Quantum Computing` & `Binary Search`) (1:05 - 1:45)
**Visual:** 
1. User enters `"quantum computing"`, selects Gemini backend, and clicks **Explain Simply**.
2. Markdown formatted explanation appears with headings, Qubit analogies, and real-world significance.
3. User enters `"binary search algorithm"`, switches backend to `LaMini-Flan-T5-783M (Local)`, and clicks **Explain Simply**.
4. Explanation with the phonebook analogy and $O(\log n)$ efficiency renders smoothly.

**Voiceover Narration:**
> "Next, let's explore the Concept Explainer. Complex scientific concepts often intimidate young learners. EduGenie simplifies them through intuitive analogies.
> First, we enter *'quantum computing'* with our cloud-based Gemini backend. The model generates a school-level breakdown explaining Qubits as spinning coins in superposition, contrasting classical binary switches with simultaneous state exploration.
> Now, we switch to our local inference backend and enter *'binary search algorithm'*. EduGenie illustrates the divide-and-conquer strategy using a 1,000-page telephone directory analogy, explaining why search complexity drops from linear time to logarithmic $O(\log n)$."

---

### Scene 4: Scenario 3 — Educational Passage Summarizer (1:45 - 2:20)
**Visual:** User clicks **Load Industrial Revolution Passage**. A dense paragraph of historical text is loaded into the multiline textarea. User clicks **Generate Summary**. Structured key bullet points and a concluding takeaway appear.

**Voiceover Narration:**
> "In Scenario 3, students dealing with dense textbook passages can generate high-yield study summaries. 
> We load a comprehensive passage on the Industrial Revolution spanning steam engines, textile mechanization, and urbanization.
> Clicking *'Generate Summary'*, EduGenie extracts four foundational takeaways: the transformation from agrarian to industrial economy, key technological breakthroughs, societal urbanization, and long-term global impacts. 
> This enables rapid revision and retention before examinations."

---

### Scene 5: Scenario 4 — Interactive Quiz Generator & Real-Time Grader (2:20 - 2:55)
**Visual:** User inputs `"Pythagoras theorem"` and clicks **Generate 3 MCQs**. Three formatted questions appear with radio buttons. User chooses correct answers for Q1 and Q3, and intentionally chooses a wrong answer for Q2. Clicks **Check All Answers**. Q1 & Q3 turn green with checkmarks, Q2 highlights the incorrect choice in red with the correct formula revealed, and the score banner shows `Score: 2/3 (66.7%)`.

**Voiceover Narration:**
> "In Scenario 4, we evaluate student comprehension using the Interactive Quiz Generator. 
> We enter *'Pythagoras theorem'* and generate an assessment. EduGenie generates exactly three multiple-choice questions with four plausible distractors each.
> Let's test our understanding: we select the correct formula for Question 1, intentionally select an incorrect option for Question 2, and pick the correct hypotenuse calculation for Question 3.
> Upon clicking *'Check All Answers'*, EduGenie provides instantaneous visual feedback: correct options are highlighted in emerald green, incorrect selections in red with the right answer clearly revealed, and our final score banner displays 2 out of 3, or 66.7%."

---

### Scene 6: Scenario 5 — Personalized Learning Roadmap (`SQL`) (2:55 - 3:15)
**Visual:** User enters `"SQL"`, clicks **Generate Roadmap**. A three-stage milestone path appears: Beginner Fundamentals, Intermediate Data Manipulation, and Advanced Optimization with timeframes and curated resources.

**Voiceover Narration:**
> "Finally, in Scenario 5, EduGenie assists career transitioners and self-learners by generating structured learning roadmaps. 
> For the topic *'SQL'*, EduGenie outputs a milestone-based curriculum across three stages: Stage 1 covers foundational DDL/DML in weeks one to two; Stage 2 covers joins, aggregations, and subqueries in weeks three to four; and Stage 3 dives into window functions, indexing, and execution query plans in weeks five to six, complete with curated interactive exercises."

---

### Scene 7: Mobile Responsiveness & OpenAPI Docs (3:15 - 3:30)
**Visual:** Mobile viewport demo (390x844) showing responsive layout, followed by the `/docs` Swagger UI.

**Voiceover Narration:**
> "EduGenie is fully responsive across all device form factors, from ultra-wide desktops to mobile devices, and exposes fully documented RESTful OpenAPI endpoints. 
> Thank you for watching the EduGenie demonstration."

---

## Part 2: Testing Video Script (`media/Testing_Video.mp4`)
**Target Duration:** 2:15 (135 seconds)  
**Tone:** Technical, methodical, and QA-focused.

---

### Scene 1: Automated Test Suite Execution via Pytest (0:00 - 0:45)
**Visual:** Terminal split or screen recording showing `pytest -v --cov=. tests/`. 37 test cases executing and passing with green checkmarks, followed by the coverage table showing 80% total code coverage.

**Voiceover Narration:**
> "Welcome to the QA and Verification walkthrough for EduGenie. 
> Quality assurance is built into every layer of our application. We execute our automated test suite comprising 37 comprehensive unit, integration, route, and edge-case tests using pytest and pytest-cov.
> As seen in the terminal, all 37 test cases pass with zero failures across API validation, schema integrity, JSON stripping, and fallback handlers, achieving an 80% test coverage across the entire codebase."

---

### Scene 2: Edge Case & Input Validation Testing (0:45 - 1:30)
**Visual:** Browser UI testing edge cases:
1. Submitting empty question in Q&A -> error message appears.
2. Submitting empty topic in Explainer -> client-side validation triggers.
3. Submitting 2-character text in Summarizer -> minimum character length warning.
4. Testing special characters, unicode, and large inputs.

**Voiceover Narration:**
> "Now let's verify defensive programming and edge-case handling in the user interface. 
> When a user attempts to submit an empty input in the Q&A or Explainer modules, the application intercepts the request and presents a helpful, non-blocking error banner.
> In the Summarizer module, entering fewer than five characters triggers input length validation to prevent uninformative summarizations. 
> The backend gracefully handles unicode, mathematical notations, and large passages without crashing or buffer overflows."

---

### Scene 3: AI Failure Fallback & Health Route Verification (1:30 - 2:15)
**Visual:** 
1. Simulating an API rate limit (429) or offline network state.
2. UI seamlessly switching to deterministic offline generator with badge notification.
3. Navigating to `GET /health` to verify JSON health payload.

**Voiceover Narration:**
> "A core strength of EduGenie is its resilience against external API failures. 
> When simulated rate limits or network dropouts occur, the application triggers its fallback pipeline, routing queries to verified deterministic generators.
> The `/health` endpoint confirms system liveness, active runtime mode, and model parameters. 
> This robust fault tolerance guarantees an uninterrupted learning experience under any operational condition. Thank you."
