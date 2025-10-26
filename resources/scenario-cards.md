# Scenario cards

These scenario cards are designed for workshop exercises where teams practice responding to bus factor crises. Use them to stress-test your project's resilience and identify vulnerabilities before they become emergencies.

## How to use these cards

### For workshops

1. **Print and cut** these scenarios into individual cards
2. **Divide into small groups** of 3-4 people
3. **Each group picks a card** (or you assign them)
4. **Give groups 10 minutes** to work through the scenario
5. **Share back** key insights with the full group

### For solo reflection

Pick a scenario that makes you uncomfortable. Work through the questions honestly. What would actually happen in your project?

### For team planning

Use these as the basis for creating your actual emergency response plans. Turn your workshop answers into documented procedures.

## The scenarios

---

### Scenario 1: The sudden disappearance

**The situation:**

Your lead maintainer hasn't responded to messages in 72 hours. This is completely unlike them - they're usually very responsive. Their phone goes straight to voicemail. You've tried their personal email, work email, chat platforms - nothing. You have no way to reach their family or emergency contacts.

Your project has a critical security vulnerability that needs to be patched and deployed immediately. Only the missing maintainer has ever done a production deployment.

**Questions to work through:**

- What do you do in the first 24 hours?
- Who has the authority to decide what happens next?
- How do you access the systems you need to deploy the fix?
- What do you tell the community?
- How do you handle this if they never return?

**Think about:**
- Emergency access procedures
- Deployment documentation and access
- Communication protocols
- Who can make emergency decisions

---

### Scenario 2: The burnout announcement

**The situation:**

Your second-most active contributor posts in your private team chat: "I need to be honest. I'm completely burnt out. I can't do this anymore. I'm stepping away immediately. I know I'm leaving you in the lurch with the release next week, but I genuinely can't continue. Sorry."

This person has been maintaining about 40% of your codebase, mentoring new contributors, and handling most of the community moderation. The release they mentioned is already delayed and has commitments to three major organisations waiting for it.

**Questions to work through:**

- How do you respond to this person in the next hour?
- Who picks up their responsibilities in the short term?
- What do you do about the release deadline?
- How do you prevent this happening to someone else?
- What does your project need to change?

**Think about:**
- Emotional support for burned-out contributors
- Distribution of responsibilities
- Realistic capacity planning
- Organisational culture and sustainability

---

### Scenario 3: The hostile fork

**The situation:**

Your project's co-founder, who has significant technical influence and a personal following in the community, announces they're forking the project. They claim the current leadership has 'lost sight of the original vision' and they're creating a 'true community-led' alternative.

They've convinced three of your most active contributors to join them. They're hosting their fork under a similar name, causing confusion in the community. Half your Discord server is now debating which version is 'legitimate.'

**Questions to work through:**

- How do you respond publicly?
- What do you do about the contributors who are leaving?
- How do you handle the community division?
- What governance or communication failures led to this?
- How do you move forward as a project?

**Think about:**
- Conflict resolution processes
- Governance legitimacy and transparency
- Community communication
- Handling competing visions

---

### Scenario 4: The corporate acquisition

**The situation:**

Your biggest corporate sponsor just acquired the company that employs your lead maintainer and two core team members. The acquisition includes an intellectual property clause that potentially affects their ability to contribute to your project.

Your lead maintainer sends you a private message: 'I think I can still contribute, but my new employment contract is complicated. Legal is reviewing it. I might need to step back from leadership roles. Can we talk?'

Meanwhile, community members are panicking on social media about the project being 'taken over by BigCorp.'

**Questions to work through:**

- What do you need to know about the legal situation?
- How do you protect the project's independence?
- Who takes over leadership if they need to step back?
- How do you reassure the community?
- What governance changes do you need?

**Think about:**
- Legal independence and project ownership
- Leadership succession in complex situations
- Community trust and communication
- Reducing corporate key person dependencies

---

### Scenario 5: The technical debt crisis

**The situation:**

Your lead developer died suddenly in an accident. The entire community is grieving. 

A week later, you discover that a critical piece of infrastructure they maintained is built on a hacky workaround that they were 'planning to fix properly.' It's starting to fail under increased load. The documentation says 'see Jane for details' - Jane was the developer who died.

Nobody else understands how it works. It's written in a framework version that's no longer supported. If it fails completely, your entire project goes down.

**Questions to work through:**

- How do you handle the immediate technical crisis whilst grieving?
- Who tries to figure out the undocumented system?
- Do you rebuild it or try to maintain it?
- What do you tell users about potential downtime?
- How do you honour the person you lost whilst moving forward?

**Think about:**
- Emergency technical knowledge recovery
- Balancing emotional processing with practical needs
- Technical debt and bus factor
- Memorial and moving forward

---

### Scenario 6: The governance deadlock

**The situation:**

Your project has a three-person steering committee that makes decisions by consensus. One member has announced they're stepping down due to a new job that won't allow them time for the project.

The remaining two steering committee members have fundamentally different visions for the project's future. They've been disagreeing publicly on major decisions. The community is confused about direction and some contributors are leaving because of the uncertainty.

Your governance documents don't cover what happens when steering committee members leave or when consensus can't be reached.

**Questions to work through:**

- How do you fill the steering committee vacancy?
- What do you do about the deadlock between remaining members?
- How do you revise governance to prevent this situation?
- What do you communicate to the community?
- How do you rebuild trust and clarity?

**Think about:**
- Governance succession planning
- Conflict resolution mechanisms
- Decision-making when consensus fails
- Communication during leadership transitions

---

### Scenario 7: The cascade failure

**The situation:**

Your project lead is taking a planned three-month sabbatical. You prepared for this - you have succession plans, documentation, distributed access.

Two weeks into their sabbatical, your infrastructure person's partner has a medical emergency and they need to step back indefinitely. One week after that, your community manager accepts a dream job and gives two weeks' notice.

You've suddenly lost your three most experienced people in three weeks. Your backup plans assumed losing one person, not three. The remaining team is overwhelmed and panicking.

**Questions to work through:**

- How do you triage responsibilities across remaining people?
- What work do you stop doing entirely?
- How do you recruit new help urgently?
- What do you tell the community?
- How do you keep remaining people from burning out?

**Think about:**
- Dealing with multiple simultaneous losses
- Prioritisation under crisis
- Rapid onboarding and trust building
- Team sustainability under pressure

---

### Scenario 8: The financial crisis

**The situation:**

Your project has one major sponsor who funds your only paid maintainer position. That sponsor announces they're ending funding in 30 days due to their own financial problems.

Your paid maintainer has been doing the work of three people - release management, security patches, community management, and infrastructure maintenance. They can't afford to continue without pay. You have no other funding sources lined up.

**Questions to work through:**

- What work can volunteers realistically take on?
- How do you find funding in 30 days?
- What happens if you can't find funding?
- How do you transition the paid maintainer's work?
- What do you tell the community about the project's future?

**Think about:**
- Sustainability beyond single funding sources
- Volunteer capacity and paid work
- Financial transparency
- Project scope and sustainability

---

### Scenario 9: The security incident

**The situation:**

A critical security vulnerability in your project is being actively exploited. You need to patch it, do a security release, and coordinate disclosure - all in the next 12 hours.

Your security response person is on a two-week holiday in a remote area with no internet. They're the only one who knows your security release process, has the GPG keys for signing releases, and maintains relationships with the security research community.

**Questions to work through:**

- How do you handle the security release without your security person?
- Who has access to release signing keys?
- How do you coordinate disclosure without the usual relationships?
- What do you tell affected users?
- What changes do you make to prevent this situation?

**Think about:**
- Security process documentation and bus factor
- Emergency access to critical credentials
- Distributed security knowledge
- Crisis communication

---

### Scenario 10: The founder returns

**The situation:**

Your project's original founder stepped away two years ago due to burnout. You and others stepped up, changed some technical directions, evolved the governance, and built the project into something bigger.

Now the founder announces they're coming back and want to 'help guide the project back to its roots.' They're charismatic, well-known in the community, and people are excited about their return.

But their vision conflicts with decisions you've made. They're undermining your authority by going directly to contributors. The community doesn't know who to listen to.

**Questions to work through:**

- How do you welcome them back without losing current progress?
- What role is appropriate for a returning founder?
- How do you handle public disagreements?
- What governance clarifications do you need?
- How do you maintain your own authority and legitimacy?

**Think about:**
- Emeritus roles and boundaries
- Governance authority and legitimacy
- Handling influential community figures
- Balancing history with current leadership

---
### Scenario 11: The successor conversation

**The situation:**

You've been the solo maintainer of a moderately popular open source project for four years. You're starting to burn out and need to step back, but there's no one else with maintainer access.

There's one contributor, Sarah, who's been consistently active for the past year. She's competent, trustworthy, and the community likes her. She has a full-time job and contributes in her spare time.

You know you need to ask her to become a co-maintainer, but you keep putting it off. You're worried she'll feel obligated to say yes even if she doesn't want to. You don't know how to frame it - is this a favour you're asking? A responsibility you're giving her? How do you explain the time commitment when you barely manage it yourself? And what if she says no and it makes things awkward?

Meanwhile, you're getting more exhausted and the project is suffering.

**Questions to work through:**

- How do you approach Sarah about becoming a co-maintainer?
- What do you actually say? How do you frame the conversation?
- How do you address the burden/time commitment honestly?
- What if she says no - then what?
- How do you build in ways for her to say no comfortably?

**Think about:**
- The power dynamics of the ask
- Being honest about burden vs making it appealing
- Creating an easy 'no' option
- Trust and vetting
- What if there literally is no Sarah - what then?

---

### Scenario 12: The hovering founder

**The situation:**

You successfully transitioned leadership of your project to a new maintainer six months ago. You announced your step-back publicly, handed over all access, and explained the governance change to the community.

But you're still here. You read every issue. You comment on pull requests with 'suggestions.' When the new maintainer makes decisions you disagree with, you post in the community chat about 'concerns.' Community members still @ you directly with questions, bypassing the new maintainer. You tell yourself you're 'just helping' and 'providing institutional knowledge.'

The new maintainer hasn't said anything, but you've noticed they're less active lately. Some community members are confused about who's actually in charge.

**Questions to work through:**

- Have you actually let go, or just said you have?
- What behaviours show you're still holding on?
- How do you redirect community members to the new maintainer?
- How do you give advice without undermining their authority?
- What does truly stepping back actually look like?

**Think about:**
- The difference between advisory and interfering
- Community expectations and retraining them
- Your own identity wrapped up in the project
- When your input is helpful vs harmful
- How to support without controlling

---

### Scenario 13: The succession planning that never happens

**The situation:**

You've been meaning to work on succession planning for two years. You know it's important. You've bookmarked articles, you attended a conference talk about it, you have it on your someday/maybe list.

But your project has 47 open issues, three pull requests waiting for review, a security vulnerability that needs patching, and two major features in progress. Your day job is demanding. Your family needs you. The community is waiting for the next release.

Every time you think 'I should really work on succession planning this week,' something urgent comes up. The weeks turn into months turn into years. You're now the single point of failure for a project with 50,000 users, and you're exhausted. You can't keep going, but you also can't stop.

**Questions to work through:**

- What would it take for you to actually prioritise succession planning?
- How do you create space for it when everything feels urgent?
- What's the forcing function that would make you do it?
- Could you build it into regular project rhythms instead of a one-time task?
- What's the smallest first step you could take this week?

**Think about:**
- Important vs urgent
- What it would take to make you stop
- Building succession into ongoing work
- The cost of not planning
- Creating forcing functions deliberately

---

### Scenario 14: Building the bench

**The situation:**

Your project has been running for five years with rotating leadership using an 'up and out' model. Every team lead role has a two-year term limit. After two years, people step down and someone else steps up.

This was working well until last month, when the current project lead's term is ending in three months, and there's no clear successor. The previous leads have all moved on to other projects or life commitments. Current active contributors are either too new or have said they're not interested in leadership.

You have regular contributors, but no one who feels ready or willing to take on the lead role. The system that worked for years is suddenly showing its limits. Do you extend the current lead's term (undermining the up and out principle)? Do you leave the role empty? Do you shut down the project?

**Questions to work through:**

- How do you develop potential leaders before you need them?
- What does 'building the bench' actually look like in practice?
- How do you make leadership roles appealing, not just burdens?
- What support and structures help new leaders succeed?
- How do you balance term limits with continuity?

**Think about:**
- Intentional leadership development
- Making leadership sustainable and appealing
- Onboarding and mentoring practices
- Shared leadership models
- When systems need adjustment

---

### Scenario 15: The formalised handoff

**The situation:**

You've decided to step down as project lead in six months. You have a documented succession process (inspired by leadership transitions other open source projects have successfully completed) with clear milestones, handoff checklists, and a transition timeline.

You've identified your successor and they've agreed. The community knows it's happening. Everything should be straightforward.

But as you work through the handoff checklist, you realise how much critical knowledge isn't actually documented. The 'why' behind technical decisions. The history of community conflicts. The relationships with sponsors. The unwritten rules about how decisions really get made. Your documented process covers the what, but not the how or why.

Your successor is getting overwhelmed. They're discovering that being project lead isn't only about the formal responsibilities - it's about all the invisible work and institutional knowledge you carry.

**Questions to work through:**

- What needs to be in a succession handoff beyond access and responsibilities?
- How do you transfer institutional knowledge and context?
- What's the difference between a checklist and actual readiness?
- How do you make the invisible work visible?
- What does good documentation look like for succession?

**Think about:**
- Formal vs informal knowledge
- The invisible labour of leadership
- Realistic timelines for handoffs
- Supporting successors through the learning curve
- What can't be documented

---

### Scenario 16: The community resistance

**The situation:**

You've successfully handed over project leadership to a new maintainer after a six-month transition. They're competent, committed, and the handoff went smoothly. You've publicly stepped back and are only responding when specifically asked.

But the community is pushing back. Long-time contributors are complaining in side channels that 'things have changed' and 'it's not the same anymore.' Users are tagging you in issues instead of the new maintainer. Some vocal community members are questioning decisions, saying 'the old leadership would never have done it this way.' A few people have forked the project, claiming the 'original vision' is lost.

Your successor messages you: 'I don't think they respect me. Should I just step down?'

The succession was technically successful, but socially it's failing.

**Questions to work through:**

- How do you support the new maintainer without undermining them by stepping back in?
- What do you say to community members who keep coming to you?
- How do you help the community accept that change is normal and healthy?
- Is this a you problem, a them problem, or a successor problem?
- When is community resistance legitimate feedback vs resistance to any change?

**Think about:**
- Your role in legitimising the new leader
- Community expectations and change management
- The difference between supporting and rescuing
- When to defend the successor's decisions vs let them handle it
- How succession requires the community to change too

---

### Scenario 17: The successor's doubt

**The situation:**

You've been asked to step up as co-maintainer of a popular open source project. You're honoured, excited, and absolutely terrified.

You've been a contributor for 18 months. You know the codebase reasonably well. The current maintainer trusts you and has been mentoring you. The community seems supportive. On paper, you're ready.

But you don't feel ready. The current maintainer makes decisions confidently. They know the history. They have relationships with sponsors and key contributors. They handle conflicts gracefully. When you look at what they do, you think 'I could never do that.'

You keep finding reasons to delay accepting the role. Maybe you should contribute for another year first? Maybe there's someone better? What if you make a mistake that breaks things for thousands of users? What if people don't respect your authority? What if you're not actually as good as the current maintainer thinks?

**Questions to work through:**

- How do you know if you're actually not ready vs imposter syndrome?
- What support do you need to feel legitimate as a maintainer?
- How do you step into authority you don't yet feel you deserve?
- What would help you feel 'ready enough'?
- Is anyone ever truly ready?

**Think about:**
- Imposter syndrome in leadership transitions
- The gap between competence and confidence
- What makes someone legitimate as a maintainer
- Support structures for new leaders
- Learning while leading vs being perfect first

---

### Scenario 18: Sunsetting a small project

**The situation:**

You created a small open source library five years ago that solves a specific problem. It has about 200 stars, maybe 50 active users based on download stats, and gets an issue or PR every few months.

You haven't touched it in two years. Your interests have moved on. You have a demanding job, young kids, and no energy for maintenance. Every time you see an email notification, you feel guilty.

The project works fine for what it does. But dependencies are outdated, there are a few open security issues, and the documentation references tools that no longer exist. It's not dead, but it's not really alive either.

You could try to find a maintainer, but honestly, you don't think it deserves one. Better alternatives exist now. But people are using it. Do you just abandon it? Archive it? Sunset it properly? What's your responsibility here?

**Questions to work through:**

- When is sunsetting the right choice vs finding a successor?
- What do you owe to your users when you want to end a project?
- How do you sunset responsibly vs just walking away?
- What's the difference between archiving and abandoning?
- How do you let go without guilt?

**Think about:**
- Not every project needs to live forever
- Responsible deprecation practices
- Migration paths and documentation
- The guilt of letting go
- When to sunset vs when to find successors

---

### Scenario 19: Sunsetting a company-owned project

**The situation:**

Your company open sourced a tool three years ago as part of a strategic initiative. It got decent adoption - about 2,000 stars, an active community, some enterprise users. You've been maintaining it as part of your job.

Now company priorities have shifted. The product this tool supported is being discontinued. Your team is being reorganised. Your manager has made it clear: no more work time for this project.

You still believe in the project. The community is active. Some users depend on it for critical infrastructure. But without company support, you can't maintain it properly. You don't have time to do it unpaid, and finding outside maintainers for a company-owned project is complicated.

The code is already open source, but the company owns the trademark, the domain, and has copyright. You can't just hand it to someone else. Do you sunset it? Try to spin it out? Let it slowly die? What about the users who depend on it?

**Questions to work through:**

- What's your responsibility to the community vs your employer?
- How do you sunset a project with active users?
- Can you spin it out to a foundation or independent maintainers?
- What happens to trademarks, domains, and IP?
- How do you communicate this to enterprise users?

**Think about:**
- Corporate vs community interests
- Legal and IP complications
- Your personal obligations vs company decisions
- Responsible deprecation with dependencies
- The politics of sunsetting company projects

---

## After the workshop

### Capture what you learned

- What scenarios felt most realistic for your project?
- What vulnerabilities did this exercise expose?
- What worked well in how you approached the scenarios?
- What would you have no idea how to handle?

### Turn insights into action

- Create or update your emergency response protocols
- Document the procedures you realised aren't documented
- Distribute the access that's too concentrated
- Have the difficult conversations this exercise revealed you need

### Create your own scenarios

These scenarios are starting points. Create cards based on your actual near-misses and fears:

- What almost went wrong in your project?
- What keeps you awake at night?
- What happened to other projects you've seen?

Make them specific to your context and use them with your team.

---

**The point of these scenarios isn't to have perfect answers. It's to realise what you don't know, what isn't prepared, and what needs to change before a real crisis hits.**
