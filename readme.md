# Open Source Confusers

A list of people/groups that are bringing confusion to Open Source.

[Skip to the list](#the-list)

## History & Purpose

After getting involved in Open Source I've noticed people misrepresenting their licenses or using the term "Open Source" while using a license which does not meet the commonly understood [definition](https://opensource.org/osd). Of course people are free to use words however they want, but most cases I see this occur are those that would bring benefit to the author while propagating confusion of the Open Source term and licencing, and eroding the efforts made by many other to contribute and build the reputation of Open Source.

This page lists such cases in an attempt to highlight & call-out confusion being propagated, while providing a resource to learn from in regards to where confusion may commonly lie. 

Many will see this as pedantic gatekeeping, which it may be from a certain perspective, but I see this as protecting & advocating for the wonderful ideal that is Open Source.

**Note:** Please don't harass or be negative to the people & groups in this list, or their communities. This is meant as a peaceful call-out only, any intent to be harmful is strongly out of order and counter-intuitive to a productive discussion.

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

### Cal.com

The [Cal.com](https://cal.com/) project on GitHub is licensed as AGPLv3. Within [the readme](https://github.com/calcom/cal.com/blob/58c4c894fd48d1b299d89e5fc9e1677f3b690bb8/README.md?plain=1#L100) is, what I believe to be, a misrepresentation of the AGPLv3 in the interest of pointing people to commercial licenses. The first item of the development setup details the following: 

> 1. Clone the repo into a public GitHub repository (or fork https://github.com/calcom/cal.com/fork). If you plan to distribute the code, keep the source code public to comply with [AGPLv3](https://github.com/calcom/cal.com/blob/main/LICENSE). To clone in a private repository, [acquire a commercial license](https://cal.com/sales))

As far as I can tell, nothing within the AGPLv3 requires the source code to be kept public (unless publicly distributing) and nothing prevents code being cloned in a private repository.

I discovered this after a Redditor had shared their project with a similar confused statement, believing the AGPLv3 worked in this way, after using the cal.com repo for reference. I [queried this](files/cal-com-license-slack.png) on the project's slack chat but things got stuck in a loop. After a post of mine, containing this license interpretation example, was [posted on Hacker News](https://news.ycombinator.com/item?id=31897648) the cofounder of cal.com [responded with some further insight](files/cal-com-agpl3-hn-comments.png) and updated the readme wording to the line posted above, which is perhaps more confusing it was before.

### Rock RMS

The [Rock RMS project](https://github.com/SparkDevNetwork/Rock) calls itself Open Source.
The project is licensed under a ["Rock Community License Agreement"](https://www.rockrms.com/license).
The license prevents:

- Any use and distribution by users that are not a "faith based organisation".

The license advises contacting the project owner, Spark Development, Inc, for a commercial license for other uses.

The license was [queried in this issue on GitHub](https://github.com/SparkDevNetwork/Rock/issues/5068)
but the issue was closed advising that, in response to their description containing "Open Source" that:
"We believe that is the best way to describe our project to our community.".