# Legacy checklist

What happens if you die tomorrow? Or have a serious accident? Or suddenly become incapacitated?

This checklist helps you prepare for the scenario nobody wants to think about: you disappearing without warning. Not a planned handoff, not a graceful transition, but an emergency.

If you're the person holding critical access or knowledge, this is your responsibility to prepare.

## How to use this checklist

Work through each section. For every item, you need:
1. **Who has access** - At least two other people, ideally three
2. **Where to find it** - Documented location, accessible to those who need it
3. **What to do with it** - Clear instructions for the person who takes over

Don't just tick boxes. Actually set these things up and test that others can access them.

## Critical access

### Passwords and credentials

- [ ] Password manager administrative access - at least one other person
- [ ] Password manager account recovery process tested
- [ ] Two-factor authentication backup codes stored securely
- [ ] Hardware security keys - at least one other person knows where they are, ideally have a backup which is solely for use in emergencies, which is stored safely (e.g. in a fireproof container in a safe)
- [ ] Personal email account access plan (recovery email, trusted contacts, legacy contacts)

**GitHub/GitLab/code hosting:**
- [ ] Organisation owner access held by at least three people
- [ ] [Legacy contact](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/repository-access-and-collaboration/maintaining-ownership-continuity-of-your-personal-accounts-repositories) set up on GitHub personal accounts (GitLab does not currently have any support but it's being discussed [here](https://gitlab.com/gitlab-org/gitlab/-/issues/26660))
- [ ] Instructions for next of kin / legacy contact regarding transferring repositories if needed
- [ ] Documentation of what repositories exist and their purpose

**Infrastructure and hosting:**
- [ ] Server access (SSH keys, root passwords) stored securely and accessible to more than one person
- [ ] Cloud provider accounts (AWS, Azure, GCP, DigitalOcean, etc.) have more than one administrative user
- [ ] Domain registrar accounts have more than one administrator
- [ ] DNS management access has more than one administrator
- [ ] SSL certificate management notifications go to a group instead of an individual
- [ ] CDN and hosting services have more than one person with root/admin level access to the servers and to the hosting provider's control panel/support system
- [ ] Monitoring and alerting services have more than one administrator and alert to a group instead of an individual

**Financial accounts:**
- [ ] Bank accounts (for organisational funds) have more than one signatory and a stated 'chain of command' approved by the bank with at least three people listed
- [ ] Payment processors (Stripe, PayPal, etc.) have more than one person as an administrator and notify into a group inbox
- [ ] Expense management tools have at least two administrators
- [ ] Donation platforms (Open Collective, Patreon, GitHub Sponsors, etc.) have at least two administrators
- [ ] Accounting software have at least two administrators, and all credentials for third-party integrations are securely stored including documenting which accounts they are connected with.

**Communication platforms:**
- [ ] Email hosting administration has more than one administrative user and a clear policy on legacy contacts
- [ ] Mailing list management has more than one administrative user and documented information on where it's managed, payment frequencies, and any integrations are clearly documented including which user accounts are connected to any tokens used
- [ ] Slack/Discord/chat platform administration has more than one administrative user
- [ ] Social media account is delegated across more than one person and legacy contacts are set up for personal accounts
- [ ] Website CMS administration has more than one administrative user and documentation on how to access both the application and the hosting provider, plus any associated configurations for tools like Cloudflare.
- [ ] Documentation platform access has more than one administrative user and documentation on how to build, configure and manage.

**Legal and contracts:**
- [ ] Trademark registrations and documentation held in a central, secure location and documented as to who they are assigned to, when they're due for renewal
- [ ] Legal agreements and contracts have clear documentation on who can sign - which allows for more than one person - and are stored in a central location, with documented termination/renewal dates
- [ ] Vendor contracts and renewal dates are documented and in a location accessible to more than one person
- [ ] Insurance policies are stored in a central location, accessible by more than one person, and access to the provider's portal is delegated to more than one person (ideally with a legacy contact where possible)
- [ ] Foundation or legal entity paperwork is stored in a central location and has provision for situations resulting in member's death or unplanned absence

## Communication protocols

### Who announces your absence

- [ ] Primary person identified and they know they're responsible
- [ ] Backup person identified in case primary is unavailable
- [ ] These people have each other's contact details
- [ ] They know how to verify the situation before announcing
- [ ] They have a template message, written beforehand, which is used to notify of the situation

### What they say

Draft template messages for different scenarios:

**Template: Temporary absence**
(Name) is currently unable to participate in (project) due to (vague but honest reason).

During this time, (person) will be handling (responsibility) and (person) will be handling (responsibility).

We expect (name) to return (timeframe if known / "when they're able" if not).
Please direct questions about (topic) to (person).

**Template: Permanent departure**
We're sad to share that (name) has (died / permanently left) and will no longer be leading (project).

(Name) contributed (specific achievements) and we're grateful for their work.

(Optional information about memorial services if relevant)

Going forward, (governance structure) will handle (responsibilities).

Please direct questions about (topic) to (person/email).

We're committed to continuing (project's mission).

- [ ] Templates drafted and stored where successors can find them
- [ ] Clear guidance on what NOT to say (respect privacy, avoid speculation)

### Where they announce

List of all places that need notification, in priority order:

- [ ] Project mailing list or forum
- [ ] Project chat channels
- [ ] Social media accounts
- [ ] Project website/blog
- [ ] Key partners and stakeholders (list them specifically)
- [ ] Funding organisations
- [ ] Parent organisations or foundations

## Technical continuity

### Deployment and releases

- [ ] Deployment process fully documented
- [ ] At least two other people have practised deploying
- [ ] Release signing keys backed up securely
- [ ] CI/CD credentials accessible to successors
- [ ] Emergency rollback procedures documented

### Critical knowledge

- [ ] Architecture decisions documented (ADRs or equivalent)
- [ ] 'Why we built it this way' context captured
- [ ] Known issues and workarounds documented
- [ ] Relationships with key contributors explained
- [ ] Ongoing conversations and decisions-in-progress documented

### Ongoing operations

- [ ] Monitoring and alerting - who receives alerts if you don't respond
- [ ] Regular maintenance tasks documented with schedule
- [ ] Vendor relationships and contact points documented
- [ ] Service renewal dates in shared calendar
- [ ] Budget and financial runway documented

## Governance continuity

### Decision-making authority

- [ ] Clear documentation of who can make what decisions without you
- [ ] Governance structure documented (how are decisions made?)
- [ ] Process for emergency decisions that can't wait
- [ ] Voting procedures if applicable
- [ ] Conflict resolution processes

### Community leadership

- [ ] List of key community members and their roles
- [ ] Relationships with major contributors documented
- [ ] Ongoing community conflicts or concerns documented
- [ ] Community code of conduct enforcement - who handles reports
- [ ] Succession plan for community management roles

### External relationships

- [ ] Key partners and stakeholders with contact details
- [ ] Sponsor relationships and renewal dates
- [ ] Speaking commitments, conference appearances
- [ ] Media contacts and PR relationships
- [ ] Advisory board or steering committee contacts

## Personal preparation

### Legal planning

- [ ] Will or estate plan that addresses digital assets
- [ ] Clear instructions about what happens to your project role
- [ ] Executor or trusted person knows about your project involvement
- [ ] Legal structure (if any) has succession provisions

### Trusted contacts

- [ ] At least two people who know about this checklist
- [ ] They have access to the master document with all the details
- [ ] They know how to verify a real emergency vs. a false alarm
- [ ] You've tested the process (e.g., told them you'll be unreachable for a week)
- [ ] They have each other's contact details

### The master document

This checklist is the framework. You need a private master document with the actual details:

- [ ] Created and stored securely (encrypted, access-controlled)
- [ ] At least two trusted people know how to access it
- [ ] Includes actual passwords, contact details, account numbers
- [ ] Updated at least quarterly
- [ ] Tested - make sure people can actually access and use it

## Testing your preparation

Don't just fill this out and forget it. Test it:

- [ ] Take a week completely off and unreachable - does everything keep running?
- [ ] Have someone else deploy a release using only your documentation
- [ ] Ask your trusted contacts to access your master document - can they actually do it?
- [ ] Review and update this checklist every six months
- [ ] When things change (new services, new people), update immediately

## What this checklist won't do

This checklist won't make your absence easy. It won't eliminate the grief or the disruption. It won't replace the knowledge in your head or the relationships you've built.

What it will do is give your project a fighting chance to survive and your successors a place to start.

That's what you owe to the people who depend on your work.

## Questions to reflect on

- If you died tonight, would anyone know how to access your password manager?
- Could your project make an emergency deployment without you?
- Does anyone else know why you made the technical decisions you made?
- Would your community know who to turn to if you disappeared?

If the answer to any of these is "no," start there.

---

*This checklist is adapted from hard-won experience. Add to it based on your own context. Share improvements via pull request.*