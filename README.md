# Agentic-Ai

Linkedin-post-writer-through-ai-agent
1️⃣ System Requirements

Windows laptop ✅

WSL installed (already done in 1st class)

Linux distro (Ubuntu) inside WSL

2️⃣ Software / Tools

CCR (Cloud Code Router) → already installed

Gemini API Key → already working

Python 3 (usually pre-installed in WSL)

Check Python:

python3 --version

3️⃣ Basic Knowledge Needed

You only need:

What is a skill → a small AI feature with defined input & output

Basic folder & file creation

Very basic Python (functions, strings)

👉 No advanced AI knowledge required.

✅ PART 2: What is a “Skill” (Important Concept)

A skill is:

A structured way to tell AI what it can do, what input it takes, and what output it should generate

In PIAIC:

Skills are usually defined using:

📄 Markdown file (.md) → describes the skill

🐍 Python file (optional) → runs logic if needed

For your assignment: 👉 Markdown-based skill is enough

✅ PART 3: Create Project Folder (Step-by-Step) Step 1: Open WSL

From CMD:

wsl

Step 2: Create a project folder mkdir linkedin_post_writer cd linkedin_post_writer

✅ PART 4: Create the Skill File (CORE STEP) Step 3: Create skill file nano linkedin_post_writer.md

Step 4: Paste this skill definition 👇

LinkedIn Post Writer Skill
Description
This skill generates engaging LinkedIn posts based on a given topic.

Input
topic: The topic of the LinkedIn post (string)
Output
A LinkedIn post that includes:

Attention-grabbing opening
Relevant content related to the topic
3–5 hashtags
Call-to-action
Rules
Tone should be professional by default
Content should be suitable for LinkedIn audience
Hashtags must be relevant to the topic
Example
Input
Importance of continuous learning in tech

Output
🚀 In today’s fast-changing tech world, continuous learning is no longer optional—it’s essential.

Technology evolves rapidly, and professionals who invest in learning new skills stay ahead of the curve. Whether it’s AI, cloud computing, or cybersecurity, upgrading your knowledge keeps you relevant and confident in your career.

Start learning today, because your future self will thank you.

#ContinuousLearning #TechGrowth #LifelongLearning #CareerDevelopment

👉 What skill are you learning next?

Step 5: Save & exit

Press CTRL + O → Enter

Press CTRL + X

✅ PART 5: Start CCR (Very Important) Step 6: Start Cloud Code Router

Run (example command — use your actual one): ccr code ✅ PART 6: Give topic in ccr code prompt: Run linkedin_post_writer with topic:
