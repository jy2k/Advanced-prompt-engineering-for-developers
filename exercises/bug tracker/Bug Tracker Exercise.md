## 🧩 Your Task

Build a command line app to help Triage Bug Reports using the RESPCT framework.
The app should communicate with an LLM to.
Use the beneficial templates and Workflow concepts to build that app.
1. Learn and plan what you intend to use and do with ask.
2. Define rules / instructions.
3. create a todo.md file.
4. create tests.
5. leverage stepwise CoT to own the code.
6. leverage context from the web or internal source code as you progress.
7. Jump ahead but if you get stuck, git discard and start over.
---

### ✅ Step-by-Step Instructions (One for Each RESPCT Letter)

#### **(R) Role**
Craft a prompt that sets the model’s role to give it the right expertise and tone.

> _e.g., “You are a senior software engineer on a platform team…”_

---

#### **(E) Example**
Provide a few example bug reports and show how they should be classified or triaged.

> _e.g., Classify: Critical, Functional, Cosmetic._

---

#### **(S) Structure**
Ask the model to output its results in a specific format.

> _e.g., “Respond using the following format: Severity: ..., Module: ..., Suggested Fix: ...”_

---

#### **(P) Pipeline**
Break the prompt into logical subtasks:
- Extract affected module
- Classify severity
- Suggest possible cause
- Recommend first fix

> _Bonus: Chain them together with inputs/outputs or use LangChain._

---

#### **(C) Constraints**
Add rules:
- Output must be JSON
- Severity must be one of: Critical, Major, Minor
- Don’t suggest deleting production code

---

#### **(T) Task**
Frame the task clearly in a single line.

> _e.g., “Given a user-submitted bug report, triage it by extracting relevant information and recommending a fix.”_
