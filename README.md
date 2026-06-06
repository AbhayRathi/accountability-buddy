# Receipts

**Your habits have receipts.**

Receipts is a brutally honest, local-first personal accountability system that helps people stop drifting through life by turning vague goals into measurable commitments, checking whether they followed through, and giving direct feedback based on their actual behavior.

The core loop:

> **Commitment → Check-In → Receipt → Truth Report → Next Commitment**

Receipts is not a generic AI life coach.
Receipts is not an AI friend.
Receipts is not therapy.
Receipts is not another productivity dashboard.

Receipts is the system that asks:

> “You said you were going to do the thing. Did you?”

And if the answer is no, it helps the user confront why.

---

## 1. Product Thesis

People do not need more motivation.

They do not need another productivity app, another Notion template, another self-help video, or another AI assistant giving generic advice.

They need a system that remembers what they said they wanted, checks what they actually did, and helps them close the gap.

Most people have vague aspirations:

* “I want to get in shape.”
* “I want to make more money.”
* “I want to build my company.”
* “I want to lock in.”
* “I want to be more disciplined.”
* “I want to stop wasting my life.”

Receipts forces those vague desires into measurable action:

* “Do 100 pushups by 7 PM.”
* “Send 10 sales DMs by 5 PM.”
* “Publish the landing page hero section today.”
* “Study for 90 minutes before opening social media.”
* “Go to the gym at 6 PM.”
* “Call the person I said I would call.”

The product exists to make users realize:

> “My habits are either building the life I want or proving that I am avoiding it.”

---

## 2. One-Sentence Description

Receipts is an active accountability AI that remembers your commitments, checks whether you followed through, uses receipts when available, and gives brutally honest feedback so you stop letting life pass by on autopilot.

---

## 3. Core Positioning

### Main Positioning

**A life coach with receipts.**

### Tagline

**Your habits have receipts.**

### CTA

**Get cooked.**

### Public Hook

**Send your Screen Time. Get cooked.**

### Retention Hook

**Did you do the thing?**

### Long-Term Vision

A local-first personal intelligence that learns your habits, vices, routines, goals, excuses, and behavior patterns, then tells you the truth every day.

---

## 4. What We Are Building

We are building an active accountability system.

The first version should help users:

1. Define one meaningful goal.
2. Convert that goal into one measurable daily commitment.
3. Set a check-in time.
4. Receive an active check-in.
5. Confirm whether they completed the task.
6. Provide a receipt if needed.
7. Receive a direct Truth Report.
8. Set the next commitment.
9. Build a memory of patterns over time.

The product should feel like the analog accountability call between two people:

> “Bro, what did you say you were going to do today? Did you actually do it? If not, why? What are you doing tomorrow?”

That is the product.

---

## 5. What We Are Not Building Yet

Do not build these in the MVP:

* Full mobile app
* Hardware
* Avatar-first experience
* Full local Jarvis agent
* 20 integrations
* Complex dashboard
* Enterprise product
* Therapy product
* AI companion/friend replacement
* Foundation model
* Full model training pipeline
* Crypto token
* Ad marketplace
* Social network
* Full browser/computer surveillance layer
* Complicated analytics
* Over-polished brand launch

The MVP should prove one thing:

> Will people set a measurable task, accept an active check-in, feel the feedback, and come back tomorrow?

---

## 6. First Target Users

Do not start with everyone.

First target users:

> **Ambitious but distracted young people who know they are wasting potential.**

This includes:

* College students who need to lock in
* Young builders
* Early founders
* Creators
* Self-improvement people
* Gym/productivity people
* People addicted to screen time
* People who use ChatGPT but do not know how to turn it into a real personal system
* People who feel life passing by and want direct accountability

Avoid leading with:

* Lonely people
* Dating/single people
* Spirituality/religion
* Mental health
* Therapy
* Clinical improvement

Those may become later use cases, but they are not the first positioning.

First public framing:

> **For ambitious people whose habits are not matching their goals.**

---

## 7. Core User Loop

### Step 1: Morning Commitment

User sets one measurable task.

Bad examples:

* “Get in better shape.”
* “Make more money.”
* “Be more productive.”
* “Work on my startup.”
* “Study more.”

Good examples:

* “Do 100 pushups by 7 PM.”
* “Send 10 outreach messages by 5 PM.”
* “Study calculus for 90 minutes before opening Instagram.”
* “Publish the landing page by midnight.”
* “Apply to 5 internships today.”
* “Go to the gym at 6 PM.”

The system should reject vague goals and force specificity.

---

### Step 2: Active Check-In

The system checks in at the chosen time.

Examples:

> “It’s 6:30 PM. You said you were going to send 10 outreach messages. Did you do it?”

> “You committed to 90 minutes of studying before social media. Did that happen, or did your thumb stage another coup?”

This can start as:

* In-app check-in
* Email
* Text
* Push notification later
* Voice call later
* Local agent later

---

### Step 3: Receipt / Acknowledgment

User provides proof or acknowledgment.

MVP input types:

* Yes/no
* Short text response
* Screenshot
* Screen Time screenshot
* Calendar screenshot
* Manual explanation
* Link/photo/file optional later

The product does not need perfect proof at first.

The first proof can simply be:

> “Did you do it? Yes or no?”

Over time, receipts make the system stronger.

---

### Step 4: Truth Report

The system responds based on completion, user history, tone preference, and receipts.

If the user completed the commitment:

> “Good. You actually did the thing. No fake motivational speech needed. Stack another win tomorrow.”

If the user failed:

> “You didn’t fail because the task was impossible. You failed because it got uncomfortable and you started negotiating with yourself like a defense attorney.”

Truth Report sections:

1. What you said you wanted
2. What you said you would do
3. What actually happened
4. The contradiction
5. The roast/callout
6. The deeper truth
7. One next action
8. Tomorrow’s commitment

---

### Step 5: Next Commitment

Every loop ends with another measurable commitment.

The system should not let the user escape into vague reflection.

End with:

> “What is the one measurable thing you will do tomorrow?”

---

## 8. MVP Feature List

### Must-Have

* User profile
* Main goal
* Habit/vices input
* Daily measurable commitment
* Check-in time
* Completion status
* Optional receipt upload
* Truth Report generation
* Memory of past commitments
* Next commitment creation
* Basic tone selection
* Basic off-limits topics
* Simple landing page

### Should-Have

* Shareable roast card
* Screen Time upload
* Email reminders
* Basic streaks
* Basic accountability score
* Simple report history
* Simple local-first privacy explanation

### Later

* SMS check-ins
* Voice check-ins
* Chrome extension
* Desktop app
* Calendar integration
* Email integration
* Browser activity
* Screen Time integration
* Mobile app
* Local vector store
* Local model support
* Avatar/persona
* MCP servers
* Advanced agent workflows
* Paid plans
* Credit system
* Team/founder mode

---

## 9. Core Data Objects

Suggested core schema:

### User

* id
* name
* email/phone
* tone preference
* privacy preferences
* off-limits topics
* created_at

### Goal

* id
* user_id
* title
* description
* category
* priority
* active/inactive

### Vice / Habit

* id
* user_id
* name
* category
* description
* severity
* pattern notes

### Daily Commitment

* id
* user_id
* goal_id
* task
* measurable_success_condition
* due_time
* created_at
* status: pending/completed/failed/skipped

### Check-In

* id
* commitment_id
* scheduled_time
* sent_at
* response
* completed: boolean
* explanation
* created_at

### Receipt

* id
* user_id
* commitment_id
* type: screenshot/text/calendar/screen_time/manual
* file_url/local_path
* extracted_summary
* created_at

### Truth Report

* id
* user_id
* commitment_id
* report_text
* roast
* deeper_truth
* next_action
* score
* created_at

### Pattern Memory

* id
* user_id
* pattern_type
* description
* supporting_events
* confidence
* created_at
* updated_at

---

## 10. Technical Architecture

The business is not the model.

The business is:

* accountability loop
* structured memory
* behavior graph
* active check-ins
* tone/personality layer
* privacy/trust
* habit formation

### Architecture Principle

Do not use expensive LLM calls for things databases and rules can do.

### Layer 1: Database Memory

Use normal storage for:

* goals
* commitments
* check-ins
* streaks
* user preferences
* patterns
* reports
* receipts

Do not ask an LLM to remember basic facts that should live in the database.

### Layer 2: Rules Engine

No LLM needed for:

* check-in scheduling
* due dates
* completion status
* streaks
* reminders
* score calculation
* basic progress tracking

### Layer 3: Small/Fast Models

Use small/lightweight models for:

* extracting tasks from user text
* classifying excuses
* summarizing receipts
* detecting habit categories
* compressing memory
* identifying patterns

### Layer 4: Strong Models

Use stronger models only for:

* Truth Reports
* weekly deep reviews
* emotionally nuanced feedback
* high-quality roast/personality
* complex reflection
* long-term pattern analysis

### Token Optimization

From day one, optimize:

* short prompts
* structured inputs
* compact user memory
* summarized history
* model routing
* caching repeated context
* cheap models for simple tasks
* large models only where quality matters

### Local-First Direction

Long-term, the product should be local-first.

Possible future architecture:

* local database
* local vector store
* local lightweight model
* optional cloud LLM calls
* user-controlled data export
* desktop app
* browser extension
* local agent
* encrypted user memory

MVP can use cloud models if needed, but the product should be designed so that user memory and sensitive data can eventually live locally.

---

## 11. Model Strategy

Do not train a model first.

Start with:

* strong system prompts
* structured memory
* curated principles
* user history
* rules engine
* model routing
* RAG later

Training can come later if needed.

Initial model stack can include:

* lightweight local/open-source models for extraction/classification
* frontier models for Truth Reports
* fallback model routing to manage cost
* optional bring-your-own-key later

Do not scrape influencers, coaches, or copyrighted content as a dependency for the MVP.

Build the voice internally first.

---

## 12. Product Voice

Brand character:

> **Savage mentor with receipts.**

The product should feel:

* direct
* funny
* emotionally intelligent
* serious when needed
* playful but classy
* anti-fluff
* non-corporate
* non-therapy
* not cruel
* not fake-positive

### Voice Rules

1. Roast behavior, not identity.
2. Use receipts, not random insults.
3. Praise when earned.
4. Be direct, not abusive.
5. Be funny, not useless.
6. Never diagnose.
7. Never pretend to be therapy.
8. Never attack race, sexuality, religion, disability, body type, or identity.
9. Avoid misogynistic, narcissistic, hateful, or degrading tone.
10. Profanity is allowed, but it should be intentional and not trashy.

### Good Tone

> “You said you wanted discipline. Your phone says you wanted dopamine with a charging cable. I’m not judging. I’m reading the receipts.”

### Bad Tone

> “You’re worthless.”

### Good Roast

> “Your habits are voting against your goals.”

### Bad Roast

> “You’re pathetic.”

---

## 13. Trust Strategy

This product cannot work without trust.

Users will eventually be asked to share:

* goals
* failures
* vices
* shame
* screen time
* routines
* avoidance patterns
* private commitments
* personal weaknesses
* maybe money

They will not give that to us because we ask nicely.

We have to earn it.

### Core Trust Principle

> Do not ask for deep secrets before proving usefulness on low-stakes behavior.

Start with low-friction receipts:

* one task
* one goal
* one Screen Time screenshot
* one daily check-in

Earn the right to go deeper.

---

## 14. Trust Ladder

Trust should be built in stages.

### Stage 1: Curiosity

User sees a funny roast or post.

They think:

> “That’s funny. That’s kind of true.”

Goal: make them feel something without asking for much.

### Stage 2: Low-Stakes Use

User submits one goal or one Screen Time screenshot.

They are not yet giving their whole life.

Goal: show accuracy and usefulness.

### Stage 3: Recognition

User gets a Truth Report and feels:

> “This thing actually sees the pattern.”

Goal: emotional accuracy.

### Stage 4: Repeat Use

User comes back tomorrow.

Goal: build consistency.

### Stage 5: Memory

User realizes the product remembers commitments and patterns.

Goal: trust through continuity.

### Stage 6: Deeper Disclosure

User voluntarily shares more:

* vices
* fears
* excuses
* routines
* ambitions
* failures

Goal: never force depth; earn it.

### Stage 7: Payment

User pays because the product has become part of their self-improvement loop.

Goal: money follows trust and usefulness.

---

## 15. Emotional Trust

Users need to feel:

1. **Seen**
   “This understands what I am actually doing.”

2. **Safe**
   “It will not use my secrets against me.”

3. **Respected**
   “It roasts my behavior, not my worth.”

4. **Challenged**
   “It does not let me escape into excuses.”

5. **In Control**
   “I can set boundaries and delete/export my data.”

6. **Improving**
   “This is helping me become more honest with myself.”

### Important

The product should make users feel uncomfortable sometimes, but not unsafe.

There is a difference between:

> “This hurt because it was true.”

and:

> “This made me feel attacked.”

We want the first.
Never the second.

---

## 16. Trust Through Product Design

Trust features to build early:

* off-limits topics
* tone intensity selector
* local-first explanation
* delete data option
* export data option
* clear privacy policy
* no dark patterns
* no hidden data selling
* no surprise sharing
* no public reports without explicit consent
* anonymous share cards by default
* explain why feedback was given
* allow users to correct the AI
* allow users to mark feedback as too harsh/not useful

### Off-Limits Topics

Users should be able to say:

* do not joke about family
* do not joke about weight
* do not joke about appearance
* do not joke about religion
* do not joke about money
* do not joke about relationships
* do not use profanity
* do not be savage

This makes the product feel more personal and safer.

---

## 17. Trust Through Consistency

Marketing should not constantly change.

The brand should stay consistent:

* same tone
* same promise
* same visual identity
* same slogan
* same product loop
* same character

People trust recognizable patterns.

Do not keep repositioning every week.

For the first 2–4 weeks, stick with:

> **Your habits have receipts.**

> **Send your Screen Time. Get cooked.**

> **Did you do the thing?**

---

## 18. Trust Through Restraint

The product should not overreach.

Do not say:

* “We will fix your life.”
* “We cure loneliness.”
* “We treat ADHD.”
* “We replace therapy.”
* “We know you better than anyone.”
* “We are the most advanced personal intelligence.”

Say:

* “We help you turn goals into measurable commitments.”
* “We help you confront the gap between your goals and behavior.”
* “We help you build accountability.”
* “We give direct feedback with receipts.”

Trust comes from not overclaiming.

---

## 19. Privacy Promise

Long-term promise:

> **Local-first. Your life data belongs to you.**

MVP-safe version if cloud models are used:

> **Private by design. We only use the data needed to generate your report. We do not sell your personal data. You control what you share.**

Do not claim full local execution unless it is actually true.

Suggested privacy principles:

1. User owns their data.
2. User can delete their data.
3. User can export their data.
4. Reports are private by default.
5. Sharing is opt-in.
6. Sensitive data is minimized.
7. Local-first is the long-term architecture.
8. Cloud calls should be transparent.
9. No targeted ads based on personal weaknesses in MVP.
10. No selling intimate behavior data.

---

## 20. Monetization

The product should be accessible but still profitable.

### Free Tier

Purpose: access, growth, and trust.

Includes:

* one daily commitment
* basic check-in
* limited Truth Reports
* limited memory
* limited receipt uploads

### Paid Tier: $9/month

Purpose: core subscription.

Includes:

* daily accountability
* memory
* weekly Truth Report
* more uploads
* more tone modes
* more check-ins
* stronger personalization

### Super User Tier: $20/month

Purpose: serious users.

Includes:

* deeper memory
* advanced pattern reports
* priority model usage
* voice later
* integrations later
* local-first advanced features
* more frequent check-ins

### Future Credit System

Use credits, not crypto tokens.

Possible credits:

* referral credits
* streak credits
* free student credits
* compute credits
* deep report credits

Avoid in MVP:

* tradable tokens
* user coins
* ad-to-earn mechanics
* crypto speculation
* targeted ads based on private personal data

Reason:

Trust matters more than monetization complexity at this stage.

---

## 21. Why Not Ads First

Ads may conflict with the trust promise.

If the product knows someone’s:

* vices
* loneliness
* weight goals
* money goals
* discipline failures
* screen time habits

then targeted advertising can feel exploitative.

Do not start there.

Maybe later:

* opt-in marketplace
* sponsor-supported free tier
* non-creepy recommendations
* transparent user-controlled offers

But not first.

First prove people will use and pay for accountability.

---

## 22. Competitive Context

The world is moving toward personal AI:

* memory
* voice
* vision
* proactive agents
* local/on-device systems
* personalized assistants
* hardware experiments

Companies like Hark are trying to build broad personal intelligence platforms.

We should not compete with that framing.

Do not say:

> “We are building the most advanced personal intelligence.”

That sounds like a smaller version of a bigger company.

Instead say:

> **We are building the brutally honest accountability layer for your life.**

Big companies will build broad assistants.

Receipts should own the sharper category:

> **Personal AI for self-confrontation and daily accountability.**

---

## 23. Marketing Strategy

Marketing should demonstrate the product, not explain it.

### Main Campaign

> **Send your Screen Time. Get cooked.**

### Secondary Campaign

> **Did you do the thing?**

### Core Message

> “You said you wanted X. Your behavior shows Y. Here are the receipts.”

### Platforms

* TikTok
* Instagram Reels
* YouTube Shorts
* LinkedIn
* X
* Reddit carefully
* Discord communities carefully
* in-person conversations
* student groups
* founder groups
* self-improvement communities

---

## 24. Content Pillars

### 1. Roast Examples

Example:

> Goal: build a startup
> Reality: 5h 12m social apps
> Verdict: founder cosplay
> Roast: your cofounder is apparently the For You Page

### 2. Daily Brutal Truths

Example:

> You do not need another productivity app. You need to stop negotiating with the task.

### 3. Goal vs Reality

Examples:

* college edition
* founder edition
* gym edition
* creator edition
* screen time edition

### 4. Build in Public

Example:

> We are building an AI that checks whether you actually did the thing you said you were going to do. If not, it calls you out.

### 5. User Reports

Anonymized Truth Reports from real users.

### 6. Founder Videos

Direct videos explaining:

* why fake motivation is useless
* why accountability needs receipts
* why most AI coaches are too soft
* why this is not therapy
* why local-first matters

---

## 25. First 10 Video/Post Ideas

1. “I gave our AI my Screen Time and it cooked me.”
2. “This is what your phone says about your discipline.”
3. “Your habits are voting against your goals.”
4. “The AI that says what your friends won’t.”
5. “Goal vs reality: college edition.”
6. “Goal vs reality: founder edition.”
7. “You don’t need motivation. You need receipts.”
8. “We’re building an anti-BS accountability AI.”
9. “Yesterday you said X. Did you do it?”
10. “Send your Screen Time. Get cooked.”

---

## 26. Direct Outreach Script

Use this when talking to people:

> “We’re building a brutally honest accountability AI. You give it one measurable task, it checks in later, and it tells you whether your behavior matches your goals. Want to test it tomorrow?”

Then ask:

1. What is one thing you need to do tomorrow?
2. What time should it check in?
3. What counts as proof?
4. Do you want the tone direct, savage, or drill-sergeant style?
5. Anything off-limits?

After the report, ask:

1. Was it accurate?
2. Was it useful?
3. Was it too harsh?
4. Did it make you realize anything?
5. Would you come back tomorrow?
6. Would you pay for daily accountability?

---

## 27. In-Person Validation

Do not overexplain the grand vision.

Say:

> “Want to test something? Give me one thing you need to do tomorrow. I’ll have the system check in and call you out if you don’t do it.”

If they say yes, they are a real tester.

If they only say “cool idea,” that does not count.

The test is whether they give:

* one measurable task
* check-in time
* permission to be held accountable

---

## 28. Success Metrics

Week one success:

* 25 people submit a goal or receipt
* 15 say the report feels accurate
* 10 say it made them realize something
* 5 come back the next day
* 3 share it or send it to someone
* 1–3 say they would pay

Most important metric:

> **Did they come back tomorrow?**

Secondary metrics:

* number of commitments created
* completion rate
* check-in response rate
* reports generated
* shares
* referrals
* willingness to pay
* emotional reaction

The key emotional success metric:

> “This made me realize I was letting life pass by.”

---

## 29. MVP Build Plan

### Day 1

* repo setup
* README
* basic landing page
* basic brand direction
* database schema
* commitment creation flow

### Day 2

* check-in scheduling
* completion response
* basic Truth Report generation
* user memory
* tone selection

### Day 3

* receipt upload
* Screen Time upload
* report history
* next commitment flow

### Day 4

* share cards
* email/text check-in if possible
* first user testing

### Day 5

* iterate on tone
* tighten prompts
* fix onboarding
* collect feedback

### Day 6

* post first public content
* recruit more testers
* run 10–25 users through flow

### Day 7

* review metrics
* decide whether to expand, simplify, or pivot

---

## 30. MVP Screens

### Landing Page

Headline:

> **Your habits have receipts.**

Subheadline:

> Set one measurable task. Get checked on. If you dodge it, Receipts calls you out.

CTA:

> **Get cooked**

### Onboarding

Fields:

* name
* main goal
* current vice/habit
* tone preference
* off-limits topics
* check-in preference

### Commitment Screen

Fields:

* what will you do?
* by when?
* what counts as done?
* when should we check in?

### Check-In Screen

Prompt:

> “You said you would do X by Y. Did you?”

Options:

* Yes
* No
* Partially
* Upload proof
* Explain

### Truth Report Screen

Sections:

* commitment
* result
* truth
* roast
* next action
* tomorrow’s commitment

### History Screen

Shows:

* past commitments
* completed/failed
* patterns
* streaks
* reports

---

## 31. Prompting Guidelines

System should always know:

* user goal
* current commitment
* completion status
* past pattern summary
* tone preference
* off-limits topics
* whether receipt exists
* what next action is needed

Prompt style:

* structured input
* compact memory
* short context
* no unnecessary chat history
* output in fixed sections

Truth Report output format:

```md
## Commitment
...

## Result
...

## The Truth
...

## The Roast
...

## Pattern
...

## Tomorrow's Move
...
```

---

## 32. Safety Boundaries

Receipts should not:

* diagnose users
* act as therapy
* encourage shame spirals
* encourage self-harm
* attack protected traits
* give medical/legal/financial guarantees
* manipulate users emotionally
* pressure users into oversharing
* sell sensitive personal data
* make public posts without consent

Receipts should:

* encourage agency
* focus on behavior
* respect boundaries
* allow tone control
* allow data deletion
* praise progress
* challenge excuses
* redirect serious mental health issues to appropriate human support

---

## 33. Brand Identity

### Placeholder Name

**Receipts**

### Tagline

**Your habits have receipts.**

### CTA

**Get cooked.**

### Character

**Savage mentor with receipts.**

### Visual Direction

* retro receipt printer
* old terminal
* CRT/VHS influence
* bold typography
* vibrant but not generic
* not sterile SaaS
* not blue-white AI startup
* not therapy pastel
* recognizable color system
* share cards that look like receipts

### Design Metaphor

> A receipt printer for your life.

Example report style:

```txt
RECEIPT #0041

GOAL:
Build startup

TODAY'S COMMITMENT:
Send 10 outreach messages

RESULT:
3 sent

CONTRADICTION:
You said growth. Your behavior said avoidance.

ROAST:
Your ambition showed up for the branding meeting and skipped the sales call.

TOMORROW:
Send 10 before noon. No negotiation.
```

---

## 34. Final Strategic Direction

Do not build a generic personal intelligence.

Build the sharp wedge:

> **Brutally honest accountability with receipts.**

Do not chase Hark/OpenAI/Google/Anthropic.

Let them build broad assistants.

Receipts should own:

> **The accountability layer that tells users the truth about their behavior.**

The first build should prove:

> Users will set measurable commitments, accept active check-ins, feel the feedback, and return the next day.

If that works, then expand into:

* local agent
* Chrome extension
* desktop app
* deeper memory
* Screen Time integrations
* calendar/email integrations
* voice
* avatar
* local models
* personalized intelligence layer

But first:

> **Did you do the thing?**

---

## 35. Immediate Next Steps

1. Use this README as the product reference.
2. Build the commitment/check-in loop.
3. Create the landing page.
4. Recruit 10 testers.
5. Have each tester set one measurable task.
6. Check in the next day.
7. Generate Truth Reports.
8. Track emotional reaction and retention.
9. Post daily around the campaign.
10. Review after one week.

---

## 36. Final Product Definition

Receipts is a local-first, brutally honest accountability system for ambitious people whose habits are not matching their goals.

It helps users define measurable commitments, checks whether they followed through, uses receipts when available, and gives direct feedback with memory so they stop drifting and start becoming who they said they wanted to be.

Core loop:

> **Commitment → Check-In → Receipt → Truth Report → Next Commitment**

Core promise:

> **Your habits have receipts.**
