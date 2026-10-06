# Unit 8 Lab 2: AI + JUnit + Git

**Student Name:** Johel Hernandez
**GitHub Repository URL:** https://github.com/josaher-prog/cmsc115_unit8_lab2

---

## Iteration 1
* **What the AI code does:** Generated a basic method stub for findResult returning default values.
* **Which tests passed or failed:** Baseline unit tests failed because no search logic was implemented yet.
* **What surprised you:** How quickly the AI set up class structures and method signatures.
* **Commit message used:** Iteration 1: AI-generated implementation

---

## Iteration 2
* **What changed:** Updated prompt to find and return the largest integer in an array.
* **What improved:** Main array iteration logic successfully passed standard positive and negative array tests.
* **What still failed and why:** Edge case tests for empty arrays and null inputs failed.
* **Commit message used:** Iteration 2: largest value implementation

---

## Iteration 3
* **Final behavior of the program:** Returns the maximum value in an integer array, or Integer.MIN_VALUE if the array is null or empty.
* **What was fixed:** Added explicit boundary guard checks for values == null || values.length == 0 prior to array access.
* **What you learned:** AI produces strong baseline code rapidly, but human validation is essential for boundary conditions and edge cases.
* **Commit message used:** Iteration 3: final version passing all tests

---

## Final Reflection

### How did combining AI, JUnit tests, and Git help you develop better software?
JUnit tests immediately highlighted edge cases missed by AI, while Git maintained a clear step-by-step history of code refinement.

### What are the benefits and limitations of using AI for code generation?
AI saves time writing boilerplate code and standard loop logic, but can overlook bounds checking and null handling without precise human prompt engineering.
