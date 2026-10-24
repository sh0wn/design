# Digital Product Design Playbook

*A framework for honest, evidence-based product design*


## Foundation: Core Design Principles

These principles guide every decision and phase of the design process:

1. **Be an advocate, not an expert** - Continuous learning, active listening, and including diverse voices lead to better solutions
2. **Collaborate early and often** - Great products come from collective wisdom, not lone genius
3. **Make decisions with intention** - Clear purpose enables focused decisions and desired outcomes
4. **Focus on meaningful outcomes over outputs** - Prioritize impact on customers and business over aesthetics and features
5. **Be lean, ship, and iterate** - Stay flexible and responsive to learning and change

**Bonus principle:** Never say no (find the "yes, and...")

---

## The Framework: Four Critical Phases

```
Discovery → Problem Definition → Exploration → Validation
    ↓              ↓                 ↓            ↓
Triangulate    Articulate        Ideate       Test & Learn
Evidence       Problem           Solutions    With Users
```

Each phase has **forcing functions** - checkpoints you must pass before moving forward.

---

## Phase 1: Discovery & Triangulation

### The Goal
Understand the problem space through multiple lenses before jumping to solutions.

### Core Principle: Triangulation
**Never rely on a single source of truth.** Good discovery requires viewing the problem from at least three different vantage points.

---

### EVIDENCE CHECKLIST

Use this checklist to ensure robust triangulation. Aim for **at least 3 different types** of evidence:

**Qualitative Evidence:**
- [ ] User interviews (contextual inquiry, problem interviews)
- [ ] Stakeholder interviews
- [ ] Customer feedback and support tickets
- [ ] Usability testing sessions
- [ ] Field observations
- [ ] User quotes and testimonials

**Quantitative Evidence:**
- [ ] Product analytics and usage metrics
- [ ] Survey data and ratings
- [ ] A/B test results
- [ ] Bug reports and frequency data
- [ ] Performance metrics (speed, error rates)
- [ ] Market research and industry data

**Visual/Artifact Evidence:**
- [ ] Screenshots or videos of the problem
- [ ] Current user flows and journeys
- [ ] Competitor analysis
- [ ] Previous research findings
- [ ] Process maps (start-at-the-end maps)

**System/Technical Evidence:**
- [ ] Technical constraints and dependencies
- [ ] Integration requirements
- [ ] Existing processes and workflows
- [ ] Organizational silos and handoffs

---

### TRIANGULATION QUALITY GUIDE

**Good triangulation combines:**

1. **Different perspectives:**
   - Users experiencing the problem
   - Team members supporting users
   - Data showing the scale/frequency
   
2. **Different timeframes:**
   - Recent feedback (last 30 days)
   - Historical patterns (6+ months)
   - Projected future needs

3. **Different signal types:**
   - What people say (interviews, surveys)
   - What people do (analytics, observations)
   - What systems show (metrics, technical data)

**Example of Strong Triangulation:**
- Customer support tickets show 47 complaints about search in Q3 (quantitative)
- 5 user interviews reveal frustration with outdated results (qualitative)
- Analytics show 62% of logged-in users bypass site search for Google (behavioral)

**Warning Signs of Weak Triangulation:**
- All evidence from the same source type (e.g., only interviews)
- All evidence from the same stakeholder group
- Evidence that contradicts but hasn't been reconciled
- Relying on assumptions instead of evidence

---

### Discovery Activities

**Map the Current State:**
1. **Start-at-the-end mapping**
   - Begin with the desired outcome (5-15 steps)
   - Identify all actors involved
   - Fill in the major steps between the beginning and the end

2. **Ask the experts**
   - Interview team members, support staff, and domain experts
   - Turn observations into "How might we..." questions
   - Everyone takes their own notes

3. **Document constraints**
   - Technology limitations
   - Operating processes
   - Integrations and dependencies
   - Organizational silos
   - User context (expectations, cognitive constraints)

---

### FORCING FUNCTION: Discovery Checkpoint

**Before moving to Problem Definition, you must answer YES to all:**

- [ ] I have gathered evidence from at least 3 different sources
- [ ] My evidence includes both qualitative and quantitative data
- [ ] I can describe the problem from the user's perspective (not just the business perspective)
- [ ] I understand the current state and how users work around existing limitations
- [ ] I have documented key constraints and dependencies
- [ ] I have identified who is affected by this problem and how severely

**If you answered NO to any:** Go back and fill the gaps. The quality of your problem definition depends on this foundation.

---

## Phase 2: Problem Definition

### The Goal
Articulate a clear, user-focused problem statement that guides the team toward meaningful solutions.

### Why This Matters
> "The best problem definition consists of a single specific story that shows why the status quo doesn't work." - Ryan Singer

A good problem statement:
- Centers the user's needs and frustrations
- Makes clear what's not working in the current experience
- Explains why this requires attention now
- Provides focus and alignment for the team

---

### PROBLEM STATEMENT TEMPLATE

Use this three-part structure to write your problem statement:

**Structure:**
1. **WHO** - Identify the target audience or user group affected
2. **CONFLICT** - Describe the core problem or pain point (what's not working)
3. **WHY NOW** - Explain why this matters and why it needs to be addressed

**Format:** Single paragraph, 3-5 sentences, user-focused and action-oriented

---

### PROBLEM STATEMENT WORKSHEET

**Fill this out before writing:**

**WHO is affected?**
- Primary user or audience:
- Secondary stakeholders:

**WHAT is the problem?**
- Current pain point:
- What's failing in the experience:
- How users are working around it:

**WHY does this matter?**
- User impact:
- Business impact:
- Consequences of inaction:
- Expectations being violated:

**Supporting evidence:**
- Evidence source 1:
- Evidence source 2:
- Evidence source 3:

---

### Example Problem Statement

> "Association members are frustrated with the site's search results, because they display out-of-date information and promote irrelevant matches from a narrow slice of the site's content. Since many members are logged in when they use it, they expect the search engine to anticipate their needs, interests, and geographical area. Finally, much of the site's important content is trapped in PDF, making it difficult to index and display in the results."

**Breakdown:**
- **WHO:** Association members
- **CONFLICT:** Search results are outdated and irrelevant, limited to a narrow content slice
- **WHY NOW:** Members expect personalized results when logged in; important content is inaccessible

---

### Design Questions

Rephrase the problem into questions you want to explore. These guide your work and remind you why you're doing this project.

**Prompts for generating design questions:**
- To solve this problem, what needs to be true?
- What questions do we want answered?
- Imagine we travel into the future and our project has failed. What might have caused that?

**Example Design Questions:**
- How might we surface relevant content that matches a member's interests and location?
- What search ranking factors would prioritize current, frequently-accessed content?
- How might we make PDF content searchable and displayable in results?

---

### FORCING FUNCTION: Problem Definition Checkpoint

**Before moving to Exploration, you must answer YES to all:**

- [ ] My problem statement clearly identifies WHO is affected
- [ ] The CONFLICT describes the user's pain point (not just a feature gap)
- [ ] The WHY NOW explains consequences and urgency
- [ ] I can trace each claim in my problem statement back to evidence
- [ ] My problem statement is 3-5 sentences (concise and focused)
- [ ] My team/stakeholders agree this accurately describes the problem
- [ ] I have 2-4 design questions that will guide my exploration

**Quality check:** Read your problem statement to someone unfamiliar with the project. Can they understand:
- Who has the problem?
- What is the problem?
- Why does it matter?

**If NO to any:** Revise your problem statement using the template and worksheet.

---

## Phase 3: Exploration & Ideation

### The Goal
Generate and evaluate multiple solution approaches through rapid, low-fidelity exploration.

### Exploration Philosophy
**Start rough, refine with intention.** The goal is to explore the solution space quickly and collaboratively before committing to high-fidelity work.

---

### Low-Fidelity Exploration Methods

**Fat Marker Sketches**
- Use thick markers (forces you to stay high-level)
- Focus on layout, flow, and key interactions
- Generate multiple variations quickly
- Timebox: 5-10 minutes per sketch

**Breadboarding**
- Text-based notation for interaction design
- Shows places (screens/states), affordances (things users can do), and connections (how they flow)
- Great for discussing logic without visual design debates

**Content Priority Guides**
- List content elements in priority order
- No layout or visual design
- Helps align on what matters most

---

### From Sketches to Prototypes

**The progression:**
1. **Fat marker sketches** - Explore multiple directions (diverge)
2. **Refined sketches** - Narrow to 2-3 concepts (converge)
3. **Breadboarding/wireframes** - Define interaction details
4. **Coded prototypes** - Test realistic interactions and feasibility

**Future exploration area:** Techniques for moving efficiently from fat marker sketches to coded prototypes without over-investing in fidelity.

---

### Collaborative Exploration

**The process (from your notes):**
1. PM, designer, and engineer interview customers together
2. Collaborate on potential solutions
3. Designer develops solution candidates
4. Test solutions with customers/users
5. Team discusses learnings and decides how to proceed

**Remember:** "Successful products and innovative solutions are always the result of collaborative teamwork, diverse perspectives, and collective wisdom."

---

### Shaping the Solution

A shaped concept includes:
- **Interaction design** viewed from the user's perspective
- **What** the feature does
- **How** it works
- **Where** it fits into existing flows

The shaped concept should address:
- The problem (from your problem statement)
- Constraints (from discovery)
- Solution approach
- Potential rabbit holes to avoid
- Known limitations

---

### FORCING FUNCTION: Exploration Checkpoint

**Before moving to Validation, you must answer YES to all:**

- [ ] I have explored at least 3 different solution approaches
- [ ] My solution(s) directly address the problem statement
- [ ] I have collaborated with PM and engineering on feasibility
- [ ] I can explain how my solution works from the user's perspective
- [ ] I have identified potential rabbit holes and how to avoid them
- [ ] My solution respects the constraints documented in discovery
- [ ] I have documented decisions and trade-offs made during exploration

**If NO to any:** Continue exploration or revisit earlier phases if the solution feels disconnected from the problem.

---

## Phase 4: Validation & Iteration

### The Goal
Test solution candidates with real users, learn from their feedback, and iterate based on evidence.

### Validation Principle
**Test with users, decide as a team.** Validation isn't about proving you're right—it's about learning what works and what doesn't.

---

### Testing Approaches

**Early validation (concept testing):**
- Sketches or low-fi prototypes
- Focus on: Does this solve the problem? Is the approach understandable?
- Fast, cheap, directional feedback

**Later validation (usability testing):**
- Higher fidelity prototypes or beta features
- Focus on: Can users complete tasks? Where do they struggle?
- More investment, more detailed insights

---

### Learning & Iteration

**After testing:**
1. Team discusses learnings together
2. Revisit design questions: What did we learn?
3. Decide how to proceed:
   - Ship it
   - Iterate on specific issues
   - Pivot to a different approach
   - Go back to discovery (rare, but sometimes necessary)

**Remember:** "Be lean, ship, and iterate" - Embrace flexibility and continuous improvement.

---

### FORCING FUNCTION: Validation Checkpoint

**Before considering the work "done," you must answer YES to all:**

- [ ] I have tested my solution with real users (or have a plan to test after launch)
- [ ] I can describe what worked and what didn't, with evidence
- [ ] The team has discussed learnings and agreed on next steps
- [ ] We have metrics or success criteria defined for post-launch
- [ ] Known issues or limitations are documented
- [ ] We have a plan for iteration based on learning

**Remember:** Shipping is not the end—it's the beginning of learning at scale.

---

## Quick Reference

### The "What We Know" Exercise

Before making significant decisions, create three lists:

1. **What we know is true** (high confidence, based on evidence)
2. **What we hope is true** (hypotheses worth exploring)
3. **What is definitely not true** (constraints, ruled-out options)

This exercise helps align the team and identify gaps in understanding.

---

### Red Flags: When You're Off Track

**Warning signs you've drifted from good process:**

- Starting with solutions instead of problems
- Relying on opinions instead of evidence
- Skipping user input or testing
- Working in isolation instead of collaborating
- Falling in love with your first idea
- Ignoring constraints or dependencies
- Making decisions without clear intention
- Focusing on features/outputs instead of outcomes
- Moving forward despite "NO" answers at forcing functions

**When you notice these:** Pause. Go back to the relevant phase and do the work properly.

---

### Project Documentation Template

Every project should have a living document (concept doc, PRD, vision doc) that includes:

**Phase 1 Elements:**
- Problem statement
- Evidence (with sources)
- Current state mapping
- Constraints and dependencies

**Phase 2 Elements:**
- Design questions
- Success criteria
- Guiding principles for this project

**Phase 3 Elements:**
- Solution approach (with sketches/prototypes)
- Decisions and tradeoffs made
- What will be delivered

**Phase 4 Elements:**
- Testing approach and timeline
- Learning and iteration plan
- Team and stakeholder alignment

**Remember:** These are living documents. They should evolve as you learn, but changes should be conversational and discussed with the team.

---

### Quick Checklist: Am I Being Honest?

Use this meta-checklist when you feel uncertain:

- [ ] Have I gathered evidence from multiple sources?
- [ ] Can I trace my decisions back to user needs?
- [ ] Have I collaborated with PM and engineering?
- [ ] Have I tested my assumptions with users?
- [ ] Am I focusing on outcomes, not just outputs?
- [ ] Have I documented my reasoning?
- [ ] Am I moving too fast? Too slow?

**If you answered NO to multiple items:** Slow down. Revisit the relevant phase.

---

## Closing Thoughts

This playbook exists to keep you honest and grounded in fundamentals:

1. **Triangulate your evidence** - Multiple perspectives reveal truth
2. **Define problems clearly** - User-focused problem statements guide good work
3. **Explore before committing** - Sketching and prototyping reduce risk
4. **Test and learn** - Users teach us what works
5. **Collaborate always** - Great products are never solo efforts

The process isn't always linear. You'll loop back, revisit phases, and discover new information. That's expected. What matters is that each decision is made with **intention** and **evidence**.

Use the forcing functions not as bureaucracy, but as moments of honesty: "Am I really ready to move forward?"

---

*Version 1.0 - Created October 2025*
