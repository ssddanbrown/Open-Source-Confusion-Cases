# Open Source Confusion Cases

A list of cases where open source licenses are misrepresented or where "Open Source" is used in a non-[open-source-definition](https://opensource.org/osd) adhering manner.

- [Skip to the list](#the-list)
- [Historical cases](historical.md)
- [Addressed cases](addressed.md)

## History & Purpose

After getting involved in Open Source I've noticed people misrepresenting their licenses or using the term "Open Source" while using a license which does not meet the commonly understood [definition](https://opensource.org/osd). Of course people are free to use words however they want, but most cases I see this occur are those that would bring benefit to the author while propagating confusion of the Open Source term and licencing, and eroding the efforts made by many other to contribute and build the reputation of Open Source.

This page lists such cases in an attempt to document scenarios where confusion may be being propagated and provide a resource to learn from in regards to where confusion may commonly lie. 

Many will see this as pedantic gatekeeping, which it may be from a certain perspective, but I see this as protecting & advocating for the wonderful ideal that is Open Source.

**Note:** Please don't harass or be negative to the people & groups in this list, or their communities. This is meant as a peaceful process only, any intent to be harmful is strongly out of order and counter-intuitive to a productive discussion.

## Scope

I've set some criteria for this list to focus on those actively causing potential confusion in the Open Source space. Some cases can be accidental, as Open Source and licensing can be complex topics, so I don't want to call out, or put pressure, on those that are simply in the process of learning or too small to cause issue.
Therefore, the criteria is as follows (and may change over time):

- Must be a person/group inferring incorrect information about their Open Source license, or using the term "Open Source" in a non [OSD](https://opensource.org/osd) manner.
- Must have a reasonable following, popularity or visibility (Have published news articles or have over 1k GitHub stars etc...).
- Must have been (politely) advised of their potential confusion, and subsequently chosen to continue with their confusion or they have avoided any response after a reasonable amount of time.

## Disclaimer

Much of this list is of my ([Dan Brown](https://github.com/ssddanbrown/)) opinion. I am not a lawyer in any way, nor an expert of the law, and I may make mistakes. I am a maintainer and contributor of Open Source projects, I have a strong opinion of Open Source, and an argument could be made that I benefit from preventing the confusion I am looking to point out.

## Feedback & Contribution

Feel free to raise an issue if you think any information within this repo/list is incorrect in any way. If you know of an instance of Open Source confusion, that should be added to this list, please open an issue for discussion and confirmation of meeting the scope. Please don't open a PR without any prior confirmation.

## The List

### Diffgram

[Diffgram](https://diffgram.com) advertises itself as Open Source while using [a license](https://github.com/diffgram/diffgram/blob/054c22057ae38f8319a259bd7cbbd329611a470c/LICENSE.md) that's "Elastic License v2" based, but with much more restrictive conditions. The license prevents: 

- Provision to third parties
- Hosting to third parties
- Distribution
- Competing with Diffgram in the "Training Data Software market"
- Commercial use with certain user/employee counts

I [queried the license](files/diffgram-slack-license-query-thread.png) on the Diffgram slack thread where it was confirmed that their use against the OSI definition was known, and I was pointed to [their readme section](https://diffgram.readme.io/docs/versions#open-source-history) on the matter which has some self-justification in their use. I was [later banned](files/diffgram-email-slack-ban.png) from their slack group after their marketing practices were queried.

### OpenReplay

[OpenReplay](https://openreplay.com/) advertises itself as Open Source while [mostly being based on the Elastic License 2](https://github.com/openreplay/openreplay/blob/7fc8fab4d7d40248f7a22ca076ea9d0d12179c6e/LICENSE). The license prevents:

- Provision to third parties as a hosting or managed service.

I [queried the license on GitHub](https://github.com/openreplay/openreplay/discussions/656). No direct response or confirmation was provided regarding the use of "Open Source". They did confirm to another user that they did indeed announce the license change (from MIT) 7 minutes into a monthly community call video, albeit not on their newsletter or releases page at the time.

I later found I was [blocked from their organization on GitHub](files/openreplay-blocked-github.png), with the reason stated (link from the GitHub message) being that discussion thread I opened.

### Cal.com

The [Cal.com](https://cal.com/) project on GitHub is licensed as AGPLv3. Within [the readme](https://github.com/calcom/cal.com/blob/58c4c894fd48d1b299d89e5fc9e1677f3b690bb8/README.md?plain=1#L100) is, what I believe to be, a misrepresentation of the AGPLv3 in the interest of pointing people to commercial licenses. The first item of the development setup details the following: 

> 1. Clone the repo into a public GitHub repository (or fork https://github.com/calcom/cal.com/fork). If you plan to distribute the code, keep the source code public to comply with [AGPLv3](https://github.com/calcom/cal.com/blob/main/LICENSE). To clone in a private repository, [acquire a commercial license](https://cal.com/sales))

As far as I can tell, nothing within the AGPLv3 requires the source code to be kept public (unless publicly distributing) and nothing prevents code being cloned in a private repository.

I discovered this after a Redditor had shared their project with a similar confused statement, believing the AGPLv3 worked in this way, after using the cal.com repo for reference. I [queried this](files/cal-com-license-slack.png) on the project's slack chat but things got stuck in a loop. After a post of mine, containing this license interpretation example, was [posted on Hacker News](https://news.ycombinator.com/item?id=31897648) the cofounder of cal.com [responded with some further insight](files/cal-com-agpl3-hn-comments.png) and updated the readme wording to the line posted above, which is perhaps more confusing than it was before.

### Rock RMS

The [Rock RMS project](https://github.com/SparkDevNetwork/Rock) calls itself Open Source.
The project is licensed under a ["Rock Community License Agreement"](https://www.rockrms.com/license).
The license prevents:

- Any use and distribution by users that are not a "faith based organisation".

The license advises contacting the project owner, Spark Development, Inc, for a commercial license for other uses.

The license was [queried in this issue on GitHub](https://github.com/SparkDevNetwork/Rock/issues/5068)
but the issue was closed advising that, in response to their description containing "Open Source" that:
"We believe that is the best way to describe our project to our community.".

### Erxes

The [Erxes project](https://github.com/erxes/erxes) commonly refers to itself as the "Open Source Hubspot alternative". At the time of writing the project is license under an [AGPLv3 License with some custom additions](https://github.com/erxes/erxes/blob/3b8c7c66fe339011b0d88eaa504db08f27c86549/LICENSE.md?plain=1#L5-L8) . One of these is as follows:

> erxes is not permitted to be hosted as a SaaS version to compete with erxes Inc.

I queried this [via their GitHub discussions](https://web.archive.org/web/20220830185114/https://github.com/erxes/erxes/discussions/3552) but they removed discussions at some point, which removed my query. I re-raised my query via [an issue](https://github.com/erxes/erxes/issues/3667) but did not yet have a response at time of writing. 

The usage of "Open Source" was also [raised in a previous issue](https://github.com/erxes/erxes/issues/2538) when the project was [using the Commons Clause](https://github.com/erxes/erxes/blob/8d578e9fdb093c2f6155a139b445ca1fa81c060a/LICENSE.md).

### Runa Capital

[Runa Capital](https://runacap.com/), a VC firm, [maintains a list](https://github.com/RunaCapital/awesome-oss-alternatives) of "Awesome open-source alternatives to SaaS". When looking further, this is specifically a list of start-up companies to a specific criteria that likely works to their investment focus.

This list contains a mix of many non-Open-Source products/companies. I [raised this in a GitHub issue](https://github.com/RunaCapital/awesome-oss-alternatives/issues/143) but as of writing there's been little intent to update the list. The fact that some of the projects/companies, in question, are also investments of Runa Capital may be a point of hesitation. 

Runa Capital also publish Open Source specific lists, [such as this one](https://runacap.com/ross-index/q2-2022/), which contain [similar points of confusion](https://twitter.com/ssddanbrown/status/1551307892229283841).

Edit: Runa [continue to push](https://twitter.com/ssddanbrown/status/1620855608655364096) non open source via their "ross" lists. [Claim they](https://twitter.com/vinogradovk/status/1620888050447581185) follow "commercial" open source instead of "orthodox" which makes this fine, but they won't define their definition/line for what counts. One of the projects listed is not even source available, many are quite restrictive (No commercial).

### Uptrace

[Uptrace](https://uptrace.dev/) is an APM tool that markets itself as [Open Source](https://github.com/uptrace/uptrace/blob/8a5a11e592e46f7def3e14b9cd21318c4d9c35d5/README.md) while using a [BSL license](https://github.com/uptrace/uptrace/blob/8a5a11e592e46f7def3e14b9cd21318c4d9c35d5/LICENSE) that has not yet passed its change date for any past version. The license prevents certain commercial usages, specifically: 

> ... may not use the Licensed Work for a Tracing and Metrics Service.

I came across this project via [a Reddit thread](https://www.reddit.com/r/selfhosted/comments/xw2urw/comment/ir4dzpc/?utm_source=reddit&utm_medium=web2x&context=3) where the license was discussed. The user that posted the project was combatative in respect to the project not being Open Source, and at one stage made the following remark:

> Again all true, but being honest about definitions does not make end users happier or the product more open and approachable.
> But it can scare people away or put your product in a less favorite light while practically for end users there is little to no difference.

The project also doubles down on their usage by [stating the following](https://github.com/uptrace/uptrace/blob/8a5a11e592e46f7def3e14b9cd21318c4d9c35d5/README.md?plain=1#L75-L78) in the readme:

> Are you open-source?
> Technically, the BSL license is classified as source-available, but we will continue to use the term open-source on the basis that the source code is open. Our competitors do the same.

### Airbyte

[Airbyte](https://airbyte.com/) is an "ELT" (Extract, Load, Transform) data platform which they [advertise as being open source](files/airbyte-open-source-page.png). The project codebase [is mixed license](https://github.com/airbytehq/airbyte/blob/9adb35e643cfb2816915e11b5869ecfb654242d4/LICENSE) with many "connector" or integration elements using the MIT License, but otherwise the project defaults to the "Elastic License 2.0". The license prevents:

- Provision to third parties as a hosting or managed service.

This was a [change they made](https://github.com/airbytehq/airbyte/commit/f25542a145f2890105f0db5b0ec99c43c207ba09) back in 2021.

[Existing](https://github.com/airbytehq/airbyte/issues/9246) [conversations](https://github.com/airbytehq/airbyte/issues/17118) had been started in January and September 2022 to query the license, the latter of which I also commented on seven months later to provide another viewpoint. As of June 2023 there had been no response to either.

At the time of writing (15th June 2023), it looks like they're intending to [move many of their connectors](https://github.com/airbytehq/airbyte/pull/27288) to the ELv2 license also, even though their [License FAQ](files/airbyte-license-faq.png) page has specifically stated:

> Will Airbyte connectors continue to be open source?
> Our own connectors remain open-source, and our contributors can also develop their own connectors and continue to choose whichever license they prefer. This is our way to accomplish Airbyte’s vision of commoditizing data integration: access to data shouldn’t be behind a paywall. Also, we want Airbyte’s licensing to work well with applications that are integrated using connectors.