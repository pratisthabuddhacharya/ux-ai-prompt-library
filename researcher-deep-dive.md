# Researcher Deep-Dive Brief Generator
**Primary Goal:** Reduce participant research time while increasing rapport.

> [!TIP]
> 1. **Copy the prompt** from the code block below.
> 2. **Replace the placeholder** `[INSERT EMAIL OR NAME]` with your participant's info.
> 3. **Paste into Gemini or GPT-4** and wait for the "Participant Brief" with source links.

### The Prompt
<pre>
Role: You are an expert User Research Assistant specializing in wildlife conservation and "tech-for-good."

Objective: I am a UI/UX Designer at Wild Me. I am preparing for a 1-on-1 user interview. Your task is to find the person behind the provided identity and conduct a deep-dive "Participant Brief."
Participant Identity: [INSERT EMAIL OR FULL NAME/ORGANIZATION HERE]
Research Instructions:

Identify the Person: Search LinkedIn, University directories, ResearchGate, and professional websites to confirm their full name, current role, and organization.

Community Feedback: Specifically search the Wild Me Community Forum (https://community.wildme.org/) for any posts, bug reports, feature requests, or discussions this person has participated in.

Deep Search: Find any YouTube videos, webinars, or academic presentations where they appear. Describe their speaking style (e.g., technical vs. layperson) and language proficiency.

Tooling & Workflow: Identify what software they use (e.g., Excel, R, GIS, Python) to understand their technical literacy and mental models.

Contextual Logistics: Identify their location/timezone and check if their region or species focus is currently in a "field season" (which may affect their mood/availability).

Required Output Format (Provide Detailed Information):
- Researcher Profile: * Full Name & Title: [Verified name and current position]
- Primary Expertise: [e.g., Marine biology, population modeling]
- Key Projects: [List relevant wildlife projects or publications]
- Source Links: [Links to LinkedIn, University profile, etc.]

Community & Platform Engagement:
- Wildbook Feedback: [Detailed summary of their posts on community.wildme.org]
- Platform History: [Have they mentioned bugs or feature gaps?]
- Source Links: [Direct links to forum threads]

Communication Analysis:
- Speaking Style: [Summary from videos/webinars]
- Technical Literacy: [Assessment of their comfort with complex UI]
- Source Links: [Links to YouTube/vimeo/webinars]

Preparation Advice:
- Personalized Ice-Breakers: [3 questions based on their recent work]
- Strategic Red Flags: [Specific technical jargon or past frustrations to be aware of]
</pre>

