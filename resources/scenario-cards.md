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
