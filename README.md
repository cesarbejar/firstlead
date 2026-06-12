# firstlead-new-manager-onboarding-agent
Project for the 2026 Microsoft Skillfest Hackaton
FirstLead by The Skillful Manager Academy
A New Manager Onboarding Agent — powered by Microsoft Copilot
Microsoft AI Skillfest — Agents League Hackathon | Enterprise Agents Track

FirstLead is a Microsoft Copilot agent developed by The Skillful Manager Academy that guides newly promoted managers through their first 90 days — delivering structured onboarding, proactive leadership coaching, and milestone check-ins directly inside Microsoft Teams.

Built on the Academy's proven leadership development methodology, FirstLead makes expert-level manager coaching accessible to every organization at enterprise scale — with no custom code required.

## The Problem
Organizations invest significantly in identifying and promoting talented people into management — and then leave them to figure out leadership on their own. Most new manager onboarding consists of a welcome email, an org chart, and a hope that things go well.

Cesar Bejar, founder of The Skillful Manager Academy, has observed this pattern across more than 30 years working in Organizational Development and HR. Since launching the Academy in March 2023, that experience has been formalized into a curriculum built specifically to close this gap:

New managers lack clarity on what is now expected of them as leaders
They struggle to find relevant resources at the moment they need them
Coaching and feedback rarely arrive when it matters most — in the first 90 days
The cost of failed or struggling managers is absorbed silently through team disengagement, conflict, and attrition

FirstLead was built to solve this — not as a training event, but as a persistent, intelligent coaching presence available every day.

## The Solution
FirstLead embeds The Skillful Manager Academy's leadership development framework directly into Microsoft Teams as a Copilot agent. Every new manager receives the same high-quality, structured onboarding experience — regardless of location, department, or whether their organization has a dedicated HR business partner.

The Three-Phase Journey
Phase 1: Orientation & Role Clarity
Timeline: Week 1–2
Focus: Day 1 welcome, role expectations, team resources, key contacts
Phase 2: Leadership Coaching
Timelien: Week 3–6
Focus: Weekly micro-coaching nudges on feedback, 1:1s, conflict, and team trust
Phase 3: Milestone Reflection
Timeline: Day 60 & 90
Focus: Structured self-assessment, progress capture, and development summary

Each phase is grounded in the Academy's core curriculum — the same frameworks delivered through workshops, coaching engagements, and leadership programs trusted by organizations nationwide.

Architecture & Tools
Component 1: Agent builder
Technology 1: Microsoft Copilot Studio (no-code)
Component 2: Deployment channel
Technology 2: Microsoft Teams
Component 3: Knowledge source
Technology 3: SharePoint — Academy content library and different public websites
Component 4: Proactive messaging
Technology 4: Teams bot framework via Copilot Studio
Component 5: Identity & access
Technology 5: Microsoft Entra ID (organizational SSO)
Component 6: Content framework
Technology 6: The Skillful Manager Academy methodology
Component 7: Intelligence layer
Technolog 7: Work IQ (Microsoft IQ) — M365 organizational context

No custom code was written. FirstLead is built entirely on Copilot Studio's visual canvas with native M365 connectors — making it deployable and maintainable by HR teams without developer support.

What Makes FirstLead Different
Most onboarding tools are repositories — document libraries the new manager is expected to explore on their own. FirstLead is the opposite: it comes to the manager, at the right moment, with the right content.

The coaching content is not generic AI output. It is drawn from The Skillful Manager Academy's proprietary curriculum — decades of real-world leadership development experience translated into conversational guidance that new managers can apply immediately.

## Demo
📹 Watch the demo video (link to recording)

The demo covers:

1. A new manager receiving their Day 1 welcome from FirstLead in Teams
2. The agent answering a question about team expectations using SharePoint knowledge
3. A Week 4 coaching nudge on running an effective 1:1 — drawn from Academy methodology
4. The 90-day check-in conversation and reflection summary

Business Impact
Outcome 1: Faster time-to-productivity
What it means in practice 1: Managers get structured guidance from Day 1, not month 3
Outcome 2: Consistent coaching quality
What it means in practice 2: Every manager receives Academy-level support, everywhere
Outcome 3: Reduced HR overhead
What it means in practice 3: Routine onboarding Q&A handled by the agent
Outcome 4: Scalable at no marginal cost
What it means in practice 4: One configuration supports the entire organization
Outcome 5: Measurable development data
What it means in practice 5: 60- and 90-day reflections create a coaching record over time

## About The Skillful Manager Academy
The Skillful Manager Academy was founded in March 2023 by Cesar Bejar, a leadership development practitioner with over 30 years of experience in Organizational Development, HR, change management, and generational diversity. The Academy was built to formalize that experience into a structured curriculum — equipping managers at every level with the practical skills, frameworks, and confidence needed to lead effectively in today's workplace.

Cesar has studied Artificial Intelligence at Johns Hopkins University and created FirstLead as a direct expression of the Academy's mission: making skilled management accessible to every organization, at scale.
🌐 theskillfulmanager.com

## Setup & Deployment
To replicate FirstLead in your Microsoft 365 tenant using Copilot Studio:

1. Sign in to copilotstudio.microsoft.com
2. Create a new agent — name it FirstLead
3. Set the persona as a professional leadership onboarding coach aligned to your organization's values
4. Build the three topic flows (Orientation, Coaching, Check-in) using the visual canvas
5. Upload Academy-aligned onboarding content to SharePoint and connect it as a knowledge source
6. Publish to Microsoft Teams via the Channels section
7. Trigger agent assignment when a manager promotion is recorded in your HR system

Configuration screenshots and topic flow diagrams are included in the /docs folder.

## License
MIT License — organizations are encouraged to adapt and deploy FirstLead within their Microsoft 365 environment.

FirstLead is a project by Cesar Bejar - The Skillful Manager Academy, submitted to the Microsoft AI Skillfest — Agents League Hackathon, Enterprise Agents Track, June 2026.

## AI Tools Used
This project was built with assistance from:
- Microsoft Copilot Studio (agent builder)
- Claude by Anthropic (project planning, 
  content writing, and documentation)
