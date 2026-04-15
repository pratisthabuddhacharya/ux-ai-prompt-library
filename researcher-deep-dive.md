# Researcher Deep-Dive Brief Generator
**Primary Goal:** Reduce participant research time while increasing rapport.

> [!TIP]
> 1. **Copy the prompt** from the code block below.
> 2. **Replace the placeholder** `[INSERT EMAIL OR NAME]` with your participant's info.
> 3. **Paste into Gemini or GPT-4** and wait for the "Participant Brief" with source links.

### The Prompt
```
Participant Identity: [INSERT EMAIL OR FULL NAME HERE]

Role: You are an expert User Research Assistant specializing in wildlife conservation and "tech-for-good."

Objective: I am a UI/UX Designer at Wild Me. I am preparing for a 1-on-1 user interview. Your task is to find the person behind the provided identity and conduct a deep-dive "Participant Brief."

Research Instructions:
1. Identify the Person: Search LinkedIn, University directories, ResearchGate, and professional websites to confirm their identity.
2. Community Feedback: Specifically search https://community.wildme.org/ for any posts, bug reports, or feature requests.
3. Deep Search: Find any YouTube videos, webinars, or academic presentations to analyze their speaking style and technical depth.
4. Tooling & Workflow: Identify software they use (e.g., Wildbook, Excel, R, GIS) to gauge technical literacy.
5. Contextual Logistics: Identify their location/timezone and current "field season" status.

Required Output Format:
1. Researcher Profile
- Full Name & Title: [Verified name and current position]
- Primary Expertise: [e.g., Marine biology, population modeling]
- Key Projects: [List relevant wildlife projects or publications]
- Source Links: [Links to LinkedIn, University profile, etc.]

2. Community & Platform Engagement
- Wildbook Feedback: [Provide a detailed summary of their specific posts on community.wildme.org]
- Platform History: [Detail any bugs, feature gaps, or UI frustrations they have mentioned]
- Source Links: [Direct links to forum threads]

3. Communication Analysis
- Speaking Style: [Summary of their tone and language proficiency from videos/webinars]
- Technical Literacy: [Assessment of how comfortable they are with complex UI/software]
- Source Links: [Links to YouTube/Vimeo/Webinars]

4. Preparation Advice
- Personalized Ice-Breakers: [Provide 3 specific questions based on their recent work/posts]
- Strategic Red Flags: [List specific technical jargon or past frustrations to be aware of]

```


