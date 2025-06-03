# ✅ Technical Challenge – Developer AI Integrations

**Role:** Junior to Mid-Level Developer – AI Integrations  
**Estimated Time:** 2 to 4 hours  
**Submission:** GitHub repository (preferred) or ZIP file  

---

## 🎯 Objective

We want to evaluate your ability to:

- 🔌 Integrate external services using APIs  
- 🧠 Model actions triggered by intelligent agents  
- 🛠 Build simple features using public tools  
- 🤖 Simulate interactions between agents in a multi-agent environment  

> This challenge is for curious developers who enjoy building smart, useful tools and exploring APIs creatively.

---

## 🛠 Instructions

1. Clone this repository **or create your own** from scratch.
2. Work inside a folder called `/solution`.
3. Include a `README_SOLUCION.md` with:
   - Setup instructions
   - How to run your code
4. Submit your solution via:
   - GitHub repository (share the link), or
   - ZIP file (if you prefer)

---

## 📦 Tasks

### 1. 🔗 External API Integration

**Goal:** Validate your ability to interact with REST APIs.

- Use a public API (e.g., [JSONPlaceholder](https://jsonplaceholder.typicode.com/), [MockAPI.io](https://mockapi.io/), or one you choose).
- Implement two basic operations:
  - ✅ Create a resource (e.g., ticket, contact, user)
  - 🔍 Retrieve and filter resources based on a condition

**Bonus:**  
If you use a different API, briefly explain why you picked it and how you found it.

---

### 2. 🤖 Natural Language Input Processing

**Goal:** Convert user text into a structured action and parameters.

- Implement a function:

```python
def process_user_input(text: str) -> dict:
