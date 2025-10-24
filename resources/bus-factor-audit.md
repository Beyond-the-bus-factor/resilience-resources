# Bus factor audit

Your bus factor is the number of people who would need to disappear before your project collapses. For most projects, that number is uncomfortably small.

This audit helps you identify single points of failure across three dimensions: technical systems, governance structures, and community relationships.

## How to use this audit

Work through each section honestly. For every area that is relevant to your situation, ask:

1. **How many people** can handle this independently?
2. **How long** would it take someone else to figure it out?
3. **What would break** if those people disappeared tomorrow?

Don't just count who *could* theoretically do something. Count who *actually knows how* and has the access to do it right now.

## Technical systems

### Code and architecture

| Area | Who knows it? | Bus factor | Risk level |
|------|---------------|------------|------------|
| Core codebase architecture | | | |
| Critical algorithms or complex logic | | | |
| Database schema and migrations | | | |
| API design and integration points | | | |
| Performance optimisation | | | |
| Security implementations | | | |

**Questions to ask:**
- Could someone else explain why we built it this way?
- Is the 'why' documented, or just the 'what'?
- Are there parts of the code only one person has touched in the last year?

### Infrastructure and deployment

| Area | Who can do it? | Bus factor | Risk level |
|------|----------------|------------|------------|
| Deploy to production | | | |
| Roll back a broken deployment | | | |
| Provision new infrastructure | | | |
| Access production databases | | | |
| Manage DNS and domains | | | |
| Renew SSL certificates | | | |
| Configure monitoring and alerting | | | |
| Respond to security incidents | | | |

**Questions to ask:**
- Could we deploy in an emergency with our lead person unavailable?
- Is the deployment process documented well enough for someone to follow it?
- Do we have the credentials we'd need if our infrastructure person disappeared?
- Do we know what all the domains and sub-domains we own are used for?

### Development operations

| Area | Who manages it? | Bus factor | Risk level |
|------|-----------------|------------|------------|
| CI/CD pipeline configuration | | | |
| Release process and versioning | | | |
| Package management and dependencies | | | |
| Code signing and release artefacts | | | |
| Repository administration | | | |
| Branch protection and policies | | | |
| Third-party integrations | | | |

**Questions to ask:**
- Is our release process documented enough for someone new to follow?
- Do we have backup access to all the services we depend on?
- What would happen if our CI/CD suddenly stopped working?
- Are we using tokens tied to an individual in our workflows, rather than a bot account?
- Are there repositories or resources where only a single person has access?

## Governance and decision-making

### Authority and process

| Area | Who decides? | Bus factor | Risk level |
|------|--------------|------------|------------|
| Project roadmap and priorities | | | |
| Technical architecture decisions | | | |
| Community policy and guidelines | | | |
| Financial decisions and budget | | | |
| Legal matters and contracts | | | |
| Partnership and sponsorship agreements | | | |
| Hiring or inviting new contributors | | | |

**Questions to ask:**
- Are our decision-making processes written down?
- Could we make an urgent decision if our lead is unavailable?
- Do people know what decisions they can make without asking permission?

### Documentation and knowledge

| Area | Where is it? | How current? | Risk level |
|------|--------------|--------------|------------|
| Project vision and strategy | | | |
| Governance structure and roles | | | |
| Decision-making processes | | | |
| Historical context for major decisions | | | |
| Ongoing discussions and open questions | | | |
| Financial records and contracts | | | |
| Legal entity structure (if applicable) | | | |

**Questions to ask:**
- If our founder left tomorrow, could someone else articulate the project vision?
- Do we document *why* we made decisions, or just *what* we decided?
- Where do we keep the context that lives in people's heads?

### External relationships

| Relationship | Who manages it? | Bus factor | Risk level |
|--------------|-----------------|------------|------------|
| Major sponsors and funders | | | |
| Corporate partners | | | |
| Foundation relationships | | | |
| Legal and financial advisors | | | |
| Media and PR contacts | | | |
| Conference and event organisers | | | |
| Other project collaborations | | | |

**Questions to ask:**
- Would our partners know who to contact if our lead disappeared?
- Are these relationships documented, or just in one person's email?
- Could someone else pick up these relationships without awkwardness?

## Community and people

### Community leadership

| Role | Who does it? | Bus factor | Risk level |
|------|--------------|------------|------------|
| Community management and moderation | | | |
| Onboarding new contributors | | | |
| Code review and mentoring | | | |
| Code of conduct enforcement | | | |
| Conflict resolution | | | |
| Communication and announcements | | | |
| Social media and public presence | | | |

**Questions to ask:**
- Could our community function if our main moderator left?
- Who would handle a code of conduct report if the usual person is unavailable?
- Is there a list of who our active, trusted contributors are?

### Contributor relationships

| Area | Who knows them? | Bus factor | Risk level |
|------|-----------------|------------|------------|
| Top 5 regular contributors | | | |
| Subject matter experts | | | |
| People interested in leadership roles | | | |
| Contributors who've stepped back | | | |
| Difficult personalities and conflicts | | | |
| Up-and-coming contributors to nurture | | | |

**Questions to ask:**
- If our community lead left, who would know the context of ongoing relationships?
- Are contributor relationships documented anywhere?
- Do we know who to reach out to if we need help urgently?

### Communication channels

| Channel | Who administers? | Bus factor | Risk level |
|---------|------------------|------------|------------|
| Mailing lists | | | |
| Chat platforms (Slack/Discord/etc) | | | |
| Forums or discussion boards | | | |
| Social media accounts | | | |
| Project website and blog | | | |
| Documentation sites | | | |
| Issue tracker and project boards | | | |

**Questions to ask:**
- Could we post an urgent announcement if our usual person is unavailable?
- Do we have admin access distributed across multiple people?
- What would happen if we lost access to our primary communication channel?

## Scoring your risk

For each area, assign a risk level:

**🔴 Critical (Bus factor 1):** Only one person can handle this. If they leave, we're in crisis.

**🟡 Vulnerable (Bus factor 2):** Two people can handle this, but it's risky. Losing one creates a crisis.

**🟢 Resilient (Bus factor 3+):** Three or more people can handle this independently. We can survive losing someone.

## What your audit tells you

### Count your critical risks

How many areas are marked critical (red)? These are your immediate emergencies. If you have more than five critical areas, your project is dangerously fragile.

### Look for patterns

- **Knowledge concentration:** Is everything technical held by one person? Everything governance by another?
- **Access concentration:** Does one person hold all the credentials and admin rights?
- **Relationship concentration:** Are all external relationships owned by one person?

### Identify your "key person risk"

Is there one person whose departure would create multiple crises? That person is your bus factor problem. They may not realise how dependent the project is on them.

## What to do with this information

Don't panic. Every project has vulnerabilities. The goal isn't perfection - it's knowing where you're fragile so you can plan accordingly.

### Immediate actions (next 30 days)

1. **Address one critical risk** - Pick your scariest red item and get one more person trained up
2. **Document one area** - Take something that lives in one person's head and write it down
3. **Share one set of credentials** - Use a password manager to give access to at least one more trusted person

### Short-term actions (next 90 days)

1. **Create a succession plan** - For your highest-risk person, draft what would happen if they left
2. **Cross-train deliberately** - Pair people up to share knowledge in your most vulnerable areas
3. **Document your governance** - Write down how decisions actually get made

### Long-term systemic changes

1. **Build rotation practices** - Make sure no one stays the sole expert in critical areas
2. **Create forcing functions** - Require two reviewers, multiple deployers, shared ownership
3. **Audit regularly** - Revisit this every six months as your project evolves

## Questions for reflection

- What surprised you about your vulnerabilities?
- Which risks scare you the most?
- If you could only fix three things, which would they be?
- Who needs to see this audit besides you?

## Using this audit with your team

This works better as a collaborative exercise:

1. **Do it individually first** - Everyone fills out their own view of the bus factor
2. **Compare notes** - You'll discover gaps nobody realised existed
3. **Prioritise together** - Decide as a team which risks to address first
4. **Review quarterly** - Bus factors change as people's involvement shifts

---

*This audit is a snapshot, not a solution. Use it to start difficult conversations about sustainability.*
