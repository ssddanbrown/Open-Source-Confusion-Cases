# APITable

[APITable](https://github.com/apitable/apitable) is a low-code platform that's under an [AGPLv3 license](https://github.com/apitable/apitable/blob/bc14c3118d30014469d7801c6f1a336afce93d16/LICENSE). Within [their licensing guidance](https://github.com/apitable/apitable/blob/bc14c3118d30014469d7801c6f1a336afce93d16/LICENSING.md) they state the following:

> GNU Affero General Public License (AGPL)
> If you remove the “Powered by APITable” logo on embedded APITable page, you’d then need to release your own embedding application under the AGPL. To avoid this, you can instead purchase an Enterprise Edition package.

That line, under the AGPL heading, could give the impression that somehow specifically the removal of a logo required the release of the "embedding application" (not metabase) under AGPL, potentially mis-communicating the copyleft nature of the AGPL license, in order to encourage usage of their enterprise offering.

I queried this [on their GitHub here](https://github.com/apitable/apitable/issues/226). From which they indicated it being based upon Metabase's licensing, which we also queried and they later addressed ([relevant case](../addressed/metabase.md)). Unlike Metabase, APITable appeared to think they could add additional restrictions to the AGPL:

> APITable does not permit rebranding without some restrictions. If you need to rebrand, you have to contact APITable for an enterprise license.
> [ref](https://github.com/apitable/apitable/issues/226#issuecomment-1402774560)

> When you remove the "Powered by APITable" information (or make any other changes), you will need to contact APITable for an enterprise license.
> If you do not want to buy an enterprise license, in this case, you will need to release your own embedding application under the AGPL.
> [ref](https://github.com/apitable/apitable/issues/226#issuecomment-1403215707)

After querying how this fits in with the AGPL, they then said they'd review and add clarification to the license. The issue thread was later closed, and 11 months later at time of writing, no update has been made to the queried licensing wording.