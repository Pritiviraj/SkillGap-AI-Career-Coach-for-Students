# SkillGap 🎯
### AI Career Coach for Students

> Built for the 5-Day AI Agents: Intensive Vibe Coding Course with Google × Kaggle (June 2026)
> Track: Agents for Good

## The Problem

Students in India graduate without knowing exactly what skills they need for their target career. Career counselors are expensive. Online advice is generic. SkillGap fixes this.

## The Solution

A multi-agent AI career coach built on Google ADK that analyzes your skill gap and recommends free learning resources.

## Architecture

User Input (role + skills)
         │
         ▼
SkillGap (Google ADK LlmAgent)
         │
         ├── Tool 1: analyze_skill_gap()
         ├── Tool 2: recommend_resources()
         └── Tool 3: safety_checker()
         │
         ▼
Structured Career Report

## Course Concepts Demonstrated

| Concept | Where |
|---|---|
| Agent (ADK LlmAgent) | Kaggle notebook Cell 4 |
| Tool use | analyze_skill_gap, recommend_resources |
| Security features | safety_checker agent |
| Session memory | InMemorySessionService |
| Antigravity IDE | Video demonstration |

## Setup Instructions

1. Open the Kaggle notebook
2. Add your Gemini API key to Kaggle Secrets as GOOGLE_API_KEY
3. Enable internet in notebook settings
4. Run cells 1 through 5 in order
5. Type your target role and current skills when prompted

## Supported Roles

- Data Scientist
- Web Developer
- AI Engineer
- Software Engineer
- Data Analyst
- Marketing Analyst

## Example Output

Target Role: Data Analyst
Match Score: 12/100
Missing Skills: Excel, Python, Visualization, Statistics
Next Step: Start learning Excel this week
All resources recommended are FREE

## Security

No personal data stored permanently. Session memory only. All outputs include professional disclaimers.

## Author

Pritiviraj Murthy
5-Day AI Agents Intensive Vibe Coding Course
Google x Kaggle — June 2026
