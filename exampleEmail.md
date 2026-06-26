
Conversation with Gemini
generate me a fake email that I can use as an example to use the iterative refinement prompt.

Here is a classic example of a "mediocre-at-best" corporate email. It’s perfect for an iterative refinement prompt because it has all the hallmarks of a rough draft: it’s too long, a bit disorganized, slightly passive-aggressive, and the actual call to action is buried at the bottom.

The Example Email
Subject: RE: Project Orion updates and also the timeline issue / resource constraints

Hey team,

So, as you all probably know, we’ve been working really hard on Project Orion, but we’ve run into a couple of roadblocks with the development side of things, and honestly, the timeline we talked about last week is looking pretty unrealistic at this point.

Sarah’s team is super bogged down with the Q2 data migration, which we didn't really account for in the initial kickoff meeting, so we are short-handed. I know everyone is busy, but we really need to figure something out because leadership is asking for a status report by Friday.

Also, I think the design assets are still missing? If anyone has those, can you drop them in the shared drive?

Anyway, I was thinking maybe we could push the launch back by two weeks, or maybe we can borrow a developer from the marketing team, but I don't know if they have the bandwidth either. Let me know what you think we should do, or if you want to hop on a quick call tomorrow afternoon to brainstorm. I’m free between 2 PM and 4 PM, I think.

Thanks,

Alex

Project Lead

Why this is a great test case for iterative refinement:
You can use this prompt sequence to test your AI's refinement capabilities:

Round 1 (Clarity & Tone): "Clean up this email to make it professional, concise, and action-oriented. Use bullet points for readability."

Round 2 (Audience Shifting): "Now, rewrite this version but adapt it specifically for executive leadership. Focus on the impact and the solution, less on the internal drama."

Round 3 (Style Adjustment): "Make it sound a bit more firm but collaborative. Ensure the deadline for the team's response is prominent."

create a markdown page so i can share this on my github

Your Markdown file is ready
MD icon
iterative_refinement_example
 MD 
Open

I have compiled the example into a clean, well-formatted Markdown file (iterative_refinement_example.md). It uses clear headers, bullet points, and markdown blockquotes so it will render beautifully on GitHub.

How to use this on GitHub:
Create a new file in your GitHub repository (e.g., name it README.md or iterative-prompt-example.md).

Download the file generated above and paste its contents directly into your repository.

Commit the changes to share it with your audience!




Your Howest chats aren't used to improve our models. Gemini is AI. It can make mistakes, so double-check it. Your privacy and GeminiOpens in a new window

# Iterative Refinement Prompting Example

This repository contains a classic example of a poorly structured corporate email, designed specifically to test and demonstrate the power of **Iterative Refinement Prompting** with Large Language Models (LLMs).

## The Raw Email (The Test Case)

**Subject:** RE: Project Orion updates and also the timeline issue / resource constraints

> Hey team,
> 
> So, as you all probably know, we’ve been working really hard on Project Orion, but we’ve run into a couple of roadblocks with the development side of things, and honestly, the timeline we talked about last week is looking pretty unrealistic at this point. 
> 
> Sarah’s team is super bogged down with the Q2 data migration, which we didn't really account for in the initial kickoff meeting, so we are short-handed. I know everyone is busy, but we really need to figure something out because leadership is asking for a status report by Friday. 
> 
> Also, I think the design assets are still missing? If anyone has those, can you drop them in the shared drive? 
> 
> Anyway, I was thinking maybe we could push the launch back by two weeks, or maybe we can borrow a developer from the marketing team, but I don't know if they have the bandwidth either. Let me know what you think we should do, or if you want to hop on a quick call tomorrow afternoon to brainstorm. I’m free between 2 PM and 4 PM, I think. 
> 
> Thanks,
> 
> Alex  
> Project Lead

---

## Why This Email is Perfect for Iterative Refinement

This draft captures the exact real-world flaws that an AI can systematically fix:
* **Buried Call to Action:** The actual requests (missing assets, schedule a call) are hidden in the middle and bottom.
* **Passive-Aggressive / Defensive Tone:** Pre-blaming scheduling issues on Sarah's team instead of focusing on solutions.
* **Lack of Visual Hierarchy:** Large blocks of unstructured text that are difficult to scan.
* **Indecisiveness:** Multiple "maybes" and "I think" statements that weaken leadership authority.

---

## Suggested Iterative Prompting Sequence

To practice or demonstrate iterative refinement, feed the raw email to your LLM and use the following multi-turn prompt workflow:

### 🔄 Round 1: Clarity, Structure, and Actionability
* **Prompt:** > "Clean up this email to make it professional, concise, and action-oriented. Eliminate conversational filler, fix the tone to be collaborative yet firm, and use bullet points to separate key issues and clear action items."

### 🔄 Round 2: Audience Optimization (Upward Management)
* **Prompt:**
  > "Now, rewrite this version but adapt it specifically for executive leadership (e.g., the VP of Product). Remove internal team coordination details, focus strictly on the project timeline impact, present the clear mitigation strategies, and clearly ask for their approval on the proposed path forward."

### 🔄 Round 3: Setting Rigid Constraints & Deadlines
* **Prompt:**
  > "Go back to the team-facing version from Round 1. Make it more decisive. Remove tentative phrasing like 'maybe' or 'I think'. Explicitly add a hard deadline of Thursday at 4 PM for the team to drop in the design assets and reply with their availability."
iterative_refinement_example.md
Displaying iterative_refinement_example.md.