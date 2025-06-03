# ✅ Technical Challenge – Developer AI Integrations

**Role:** Junior to Mid-Level Developer – AI Integrations  
**Estimated Duration:** 2 to 4 hours  
**Submission:** GitHub repository (or ZIP file if you prefer)

---

## 🎯 Objective

We want to evaluate your ability to:

- 🔌 Integrate external services using APIs  
- 🧠 Model actions that could be triggered by an intelligent agent  
- 🛠 Build simple functionalities using public tools  
- 🤖 Simulate basic interactions between agents in a multi-agent environment  

> This test is designed for curious developers who enjoy building smart, useful tools and exploring APIs.

## 🎯 Nice to Have

- If you know and choice to use FastAPI, it rocks
---

## 🛠 Instructions

1. Clone this repository or create a new one for your solution.
2. Work inside a folder named `/solution`.
3. Include a `README_SOLUCION.md` file with clear instructions on how to run your project.
4. Upload it to GitHub and share the link (or send a ZIP file if needed).

---

## 📦 Tasks

### 1. 🔗 External API Integration

**Goal:** Validate your ability to interact with REST APIs.

- Use a public API such as:
  - [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
  - [MockAPI.io](https://mockapi.io/)
  - Or any other API of your choice

**Implement the following:**

- ✅ Create a resource (e.g., ticket, contact, user, etc.)
- 🔍 Retrieve and filter resources based on a specific condition

**Bonus:**  
If you choose an API not listed above, explain:
- Why you selected it  
- How you found it

---

### 2. 🤖 Simulate Natural Input Processing

**Goal:** Translate an user input into an action and its parameters. You could need an API to use this later

**Implement:**

```python
def process_user_input(text: str) -> dict:
```

**Example input:**

```
"I want to escalate a ticket with high priority"
```

**Expected output:**

```json
{
  "action": "escalate_ticket",
  "priority": "high"
}
```

> You may use your own logic, keyword matching, or regular expressions.

---

### 3. 🔁 Simulate a Basic Multi-Agent Flow

**Goal:** Show how agents might collaborate to solve a task.

**Simulate the following scenario:**

- Agent A receives a task
- Agent A decides whether help is needed
- If help is needed, Agent A "calls" Agent B (simulation only)

**Example output (JSON or log):**

```json
{
  "agent": "Ivanti",
  "task": "create_ticket",
  "help_from": {
    "agent": "Ivanti",
    "reason": "check for duplicates"
  }
}
```

---

### 4. 🌐 Integrate an Extra Capability (Public Service)

**Goal:** Demonstrate your initiative and ability to research and integrate public tools.

**What to do:**

- Choose a free or freemium API or SDK
- Add one simple capability

**Example capabilities:**

- 🗣 Text-to-Speech (e.g., gTTS, ElevenLabs)
- 🌍 Translation (e.g., DeepL API, Google Translate)
- 😊 Sentiment analysis (e.g., Hugging Face, TextBlob)
- 🖼 OCR or basic image detection

**In your `README_SOLUCION.md`, explain:**

- Why you chose this service  
- What limitations it has in its free tier  

> We'll evaluate your research skills, initiative, and clarity in integrating third-party tools.

---

## 📁 Expected Repository Structure

```
/solution
├── api_integration.py
├── process_user_input.py
├── multi_agent_flow.py
├── extra_capability.py
├── requirements.txt
├── README_SOLUCION.md
```

---

## 🧠 Tips

- We're not looking for perfection — we're interested in your **thinking process**.
- Keep it simple, clear, and focused on working code.
- Creativity earns bonus points! 🎁

---

## 🤝 About Us

We're a friendly team that loves to build useful AI-powered tools.  
We work in a relaxed environment, move fast, and enjoy solving real-world problems with code.

If you're into:
- 🔗 APIs
- 🤖 Smart assistants
- 🧩 Building cool integrations

We’d love to see what you come up with! 🚀
