# Cal.com

The [Cal.com](https://cal.com/) project on GitHub is licensed as AGPLv3. Within [the readme](https://github.com/calcom/cal.com/blob/58c4c894fd48d1b299d89e5fc9e1677f3b690bb8/README.md?plain=1#L100) is, what I believe to be, a misrepresentation of the AGPLv3 in the interest of pointing people to commercial licenses. The first item of the development setup details the following: 

> 1. Clone the repo into a public GitHub repository (or fork https://github.com/calcom/cal.com/fork). If you plan to distribute the code, keep the source code public to comply with [AGPLv3](https://github.com/calcom/cal.com/blob/main/LICENSE). To clone in a private repository, [acquire a commercial license](https://cal.com/sales))

As far as I can tell, nothing within the AGPLv3 requires the source code to be kept public (unless publicly distributing) and nothing prevents code being cloned in a private repository.

I discovered this after a Redditor had shared their project with a similar confused statement, believing the AGPLv3 worked in this way, after using the cal.com repo for reference. I [queried this](../files/cal-com-license-slack.png) on the project's slack chat but things got stuck in a loop. After a post of mine, containing this license interpretation example, was [posted on Hacker News](https://news.ycombinator.com/item?id=31897648) the cofounder of cal.com [responded with some further insight](../files/cal-com-agpl3-hn-comments.png) and updated the readme wording to the line posted above, which is perhaps more confusing than it was before.

In addition to the above, it's unlikely the application can be used via open source code alone, without making significant modifications. I experienced this when attempting to build myself, but this is also confirmed [via this GitHub issue](https://github.com/calcom/cal.com/issues/13575) where a project member states:

> The EE folder is not meant to be removed. The license specifies on not using code from it. This decision was also made to avoid spending resources on having to develop and maintain two separate codebases.
> So as far a you don't actively use enterprise features you would still be honoring the license.

When I posted my concerns earlier [on a Reddit thread](https://www.reddit.com/r/selfhosted/comments/11e3fh9/calcom_selfhostable_opensource_scheduling_high/) the founder [did later comment](https://www.reddit.com/r/selfhosted/comments/11e3fh9/comment/javblop/) but with nothing to dispute what I had said, only really justification.