✅ Technical Challenge - Developer AI Integrations
Role: Junior to Mid-Level Developer – AI Integrations
Estimated Duration: 2 to 4 hours
Submission: GitHub repository (or ZIP file if you prefer)

🎯 Objective
We want to evaluate your ability to:

Integrate external services using APIs.

Model actions that could be triggered by an intelligent agent.

Build simple functionalities using public tools.

Think about basic interactions between agents in a simulated multi-agent environment.

This test is designed for curious developers who enjoy building smart, useful tools and exploring APIs.

🛠 Instructions
Clone this repository or create a new one for your solution.

Work inside a folder named /solution.

Include clear instructions in a README_SOLUCION.md file on how to run your project.

When you’re done, upload it to GitHub and share the link (or send a ZIP file if needed).

📦 Tasks
1. 🔗 External API Integration
Goal: Validate your ability to interact with REST APIs.

Use a public API such as JSONPlaceholder, MockAPI.io, or another of your choice.

Implement two actions:

Create a resource (e.g., a ticket, contact, user, etc.)

Retrieve and filter resources based on a specific condition.

Bonus: If you choose an API not listed above, explain why you selected it and how you found it.

2. 🤖 Simulate Natural Input Processing
Goal: Translate a user input into an action and its parameters.

Implement a function called process_user_input(text: str) that takes a string like:

css
Copy
Edit
"I want to escalate a ticket with high priority"
Return a JSON object like this:

json
Copy
Edit
{
  "action": "escalate_ticket",
  "priority": "high"
}
You can use your own rules or regular expressions to detect the intent and extract parameters.

3. 🔁 Simulate a Basic Multi-Agent Flow
Goal: Show how agents might work together to solve a task.

Create a function that simulates Agent A:

It receives a task.

It decides whether it needs help.

If it does, it "calls" Agent B for assistance (simulation only).

Output the flow in JSON or log format. Example:

json
Copy
Edit
{
  "agent": "Ivanti",
  "task": "create_ticket",
  "help_from": {
    "agent": "ServiceNow",
    "reason": "check for duplicates"
  }
}
4. 🌐 Integrate an Extra Capability (Public Service)
Goal: Demonstrate your initiative and ability to research and integrate tools.

Pick a free or freemium service (API or SDK).

Integrate a simple capability. Examples:

Text-to-Speech (gTTS, ElevenLabs, etc.)

Translation (DeepL API, Google Translate)

Sentiment analysis (Hugging Face, TextBlob)

OCR or simple image detection

In your README_SOLUCION.md, explain:

Why you chose this service.

What are the limitations of its free tier.

We’re evaluating your technical decisions, initiative, and clarity of implementation.

📁 Expected Repository Structure
bash
Copy
Edit
/solution
├── api_integration.py
├── process_user_input.py
├── multi_agent_flow.py
├── extra_capability.py
├── requirements.txt
├── README_SOLUCION.md
🧠 Tips
We’re not looking for a perfect solution — we’re more interested in how you think and how you solve problems.

Keep it simple, clear, and focused on working code.

Show creativity if you want bonus points.

🤝 About Us
We're a small and growing team that loves to build useful AI-powered tools. We work in a relaxed environment, move fast, and enjoy solving real-world problems with code. If you're into APIs, smart assistants, or building cool integrations, we’d love to see what you come up with!
