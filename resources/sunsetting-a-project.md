# Sunsetting a project

It might be an eventuality that you never have to face, but for those of us who decide to close down an open source project, doing so in a skilful way requires careful planning, positive communication and a hefty dose of patience.

Here's some collated guidelines to help you along this journey.

## Deciding when the time is right to sunset

It might be the most challenging decision you'll make as an open source maintainer - when to pull down the shutters and sunset your project.

As the saying goes, there's never a good time. There are a lot of technical and practical factors that you can use to determine whether it's worth continuing, including:

- Pull request frequency
- Issue creation frequency
- Frequency of forks
- Actively developed forks
- New projects that supercede this project

Tools like [CHAOSS](https://chaoss.community/) and [OSInsight](https://ossinsight.io) can be really helpful in doing the heavy lifting when it comes to analytics.

There are also other factors that might signal the time is approaching for a project to close, including:

- Maintainer burnout
- Lack of funding
- Change in direction
- Inabilty to decide on a route forward

Sunsetting a project doesn't have to mean that it was a failure. Projects have lifecycles - all things come into being and go out of being based on conditions - and that includes open source projects.

## Making and communicating the decision

Closing down an open source project should always - where possible - be done in a respectful way, giving people sufficient notice to take action, move to using alternatives, or even offer to take over maintaining the project.

While it can sometimes happen in the midst of highly emotional times, the actual process of deciding to take this step and communicating about closing down the project needs to be carried out with care and consideration, rather than burning bridges and rage-quitting. 

Separating out how you feel about the situation from the practicalities can be really challenging, but think of it as your last responsibility to the project, to ensure that it's closed in a good way.

In some ways, perhaps we should start thinking about how the project would close down as soon as we start it, so that at least we'd be ready with a process to follow!

### Communicating the news

The initial communication regarding the decision being made to close down the project should be clear, factual and concise.

If you have a way to communicate with your core contributors who are active within the project, it makes sense to have this conversation with them first if you haven't already 

If you're willing to consider transferring ownership and supporting a continuation of the project, make this explicit. If you're not, and this is the end, make that explicit too.

Once you've had the initial conversations with the core contributors, you should make the communication publicly.

Wherever possible, give people sufficient notice to both receive the message and also to plan for and take action. An absolute minimum time period should be 30 days from notification to the final release.

 Depending on the project and the resources you have, you might want to do this:

- At the top of the README file
- In your project communication channels (e.g. chat rooms, forums, mailing lists)
- On your website
- In your documentation
- In package managers (most support a deprecation notice)
- In internal channels (e.g. if the project is part of an organisation, if your marketing team need to know)
- Directly to the users of the software (e.g. with a banner inside the application or a message in the console)
- Via email to subscribers, if you have a mailing list
- Via social media, if you have official project channels, and via the profiles of the maintainer/s

## Making a final release

Once the news has been shared publicly, you should make a final release, being clear that from this point forward, the project is no longer going to be maintained. Ideally, this release should be at least 30 days after the public communication regarding closing the project.

## Archive, don't delete

Unless there's a good reason, always mark your project as archived, rather than delete it all together. Archiving a project means that people can't contribute or raise issues any more, but it's still available for people to view and potentially to fork and build on anew. It tells people in a prominent way when they are visiting the code repository that it's no longer maintained. It's also a reversible situation - if in the future you want to resurrect it, you can un-archive it.

In larger organisations, you may want to consider having a separate organisation (e.g. orgname-archive) which holds archived projects. This allows you to keep your operating organisation clean and clutter-free but also allows people to find legacy projets with ease.

You can also submit your code to the [Software Heritage](https://www.softwareheritage.org/) archive which preserves an archive of software for longevity - this is a great idea if you're hosting your code on your own infrastructure and you want to decommission that infrastructure, but still ensure the code is accessible in the future.

## Sunsetting an organisation-owned project

When you're closing down a project which has been managed by an organisation - whether that be a company, a foundation or something other, you might also have to decide how and when to withdraw organisation resources and establish new governance models.

There is a super handy [flow chart](https://github.com/rcmcooperative/partner-template/blob/main/assets/RCM-sunsetting.drawio.pdf) created by the [RCM Cooperative](https://www.rcmcooperative.com/) which gives you a great head start in planning this process.

If the community is quite large, it's likely that you'll need to go through some kind of consultative process, particularly if there is an existing governance model that needs changing, or no governance model at all.

Here's how Mautic approached [spinning out from corporate ownership](https://speaking.ruthcheesley.co.uk/QYaM46/how-do-you-change-the-governance-model-of-an-established-open-source-project).

## References

Thanks to these wonderful resources:

- [CHAOSS Community guide to sunsetting a project](https://chaoss.community/practitioner-guide-sunset)

- [GitHub blog on sunsetting projects](https://github.blog/open-source/maintainers/dos-and-donts-when-sunsetting-open-source-projects/)

- [TODO guide on sunsetting projects](https://todogroup.org/resources/guides/shutting-down-an-open-source-project)

- [RCM workflow for sunsetting projects](https://github.com/rcmcooperative/partner-template/blob/main/assets/RCM-sunsetting.drawio.pdf)

- [Mautic's process for changing governance models](https://speaking.ruthcheesley.co.uk/QYaM46/how-do-you-change-the-governance-model-of-an-established-open-source-project)