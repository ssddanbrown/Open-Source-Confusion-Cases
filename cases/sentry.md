# Sentry

Sentry is an error tracking and performance monitoring platform which has advertised as being open source across multiple sites:

- On their "open source" page - [ref](https://open.sentry.io/)
- In blog posts - [ref - first line of post](https://web.archive.org/web/20230804170644/https://blog.sentry.io/we-just-gave-260-028-dollars-to-open-source-maintainers/).
- In Reddit marketing - [ref](https://www.reddit.com/user/getsentry/comments/ylbnv8/error_and_performance_monitoring_for_your_code/j37br70/?context=999).

They were using an [Business Source 1.1 License](https://github.com/getsentry/sentry/blob/3ea2a27cc79279cf0423a0c77af7bc642c7b0e8f/LICENSE), which prevents competitive commercial offerings for a certain amount of time, but they later switched to their [Functional Source License](https://github.com/getsentry/sentry/blob/da74f6c805a5e7f3e94a0eaf5df7830c74f4a1c8/LICENSE.md), which also prevents competitive use for a certain amount of time.

I queried this [in a reddit thread](../files/sentry-reddit-conversation.png) [link](https://www.reddit.com/r/opensource/comments/yieknl/comment/iuiswxi/?context=999), to which I just received defensive responses from David Cramer (Founder/CTO).

While many open source references have been removed, the "open source" link in their site footer remains, [leading to the page](https://open.sentry.io/) stating "We're Open-Source", just above a link to their main repository. This was later [called out on Hacker News](https://news.ycombinator.com/item?id=38336705) which they advised would be addressed via [this GitHub issue](https://github.com/getsentry/team-ospo/issues/211) but no change has been made at the time of writing, months later.

### Wanting to Change Open Source

In addition to the above, there seems to be a common tune of Sentry (or individuals at Sentry) wanting to change what open source is, to cover the licenses they desire to work to their benefit:

> The Future of Open-Source
> We’re literally entering a new decade, and like some of our contemporaries, we believe changes need to be made in the business of open-source software. Previous licensing models – the “open core” model, GPL, and permissive licenses like BSD and Apache-2.0 – are not sufficient for the way OSS is distributed and used today. 
> [ref](https://blog.sentry.io/relicensing-sentry/)

> We love giving away lots of money to Open Source projects, and investing in overarching efforts such as FOSS Funders, and this whole question of advancing the conversation about Open Source that this post is a part of.
> [ref](https://blog.sentry.io/sentrys-open-source-values/)

> We are committed to improving the conversation around this topic, around ensuring open source can be both sustainable and protected.
> [ref](https://blog.sentry.io/lets-talk-about-open-source/)

> The only way for businesses to release their core products under OSI-approved licenses is through a time delay such as the BSL.
> [...]
> I'll concede that this is an evolution or refinement of the definition of open source, but not a change to the essence.
> [ref](https://news.ycombinator.com/item?id=36972936) (HN comment by Sentry Head of Open Source)

> [...], and if in your view that is a change in the essence of open source, then yes, let's change open source. Change or die.
> [ref](https://news.ycombinator.com/item?id=36973188) (HN comment by Sentry Head of Open Source)

> I created the Sentry project, am the CTO, and represent one of the strongest voices in our company for why this opinion of open source must change or open source will continue to be unsustainable.
> [...]
> We need to evolve our irrational views of idealism and find common ground that allows sustainability if we want open source to thrive.
> [ref](https://news.ycombinator.com/item?id=36972824) (HN comment by Sentry CTO & Creator)

> I believe this situation reaffirms my belief that licenses like our FSL [...] are a viable alternative, even though they are not considered Open Source by today's definition.
> [...]
> The world around us is changing, and so must we as the Open Source community. 
> [ref](https://lucumr.pocoo.org/2023/12/25/life-and-death-of-open-source/) (Blog from Sentry Director of Engineering)


That said, Chad Whitacre (Head of Open Source at Sentry) has been very receptive to [feedback and input](https://github.com/getsentry/fsl.software/issues/10) in conversations around how they portray their FSL license relative to open source. The current work may help define better define that zone adjacent to open source.