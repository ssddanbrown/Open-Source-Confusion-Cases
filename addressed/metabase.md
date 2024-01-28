# Metabase

[Metabase](https://www.metabase.com/) is a business intelligence platform that is provided under an AGPLv3 license. Their [licensing page had](https://web.archive.org/web/20221207122031/https://www.metabase.com/license/) the following text:

> GNU Affero General Public License (AGPL)
> If you remove the “Powered by Metabase” logo on embedded questions and dashboards, you’d then need to release your own embedding application under the AGPL. To avoid this, you can instead purchase an Enterprise Edition package.

That line, under the AGPL heading, could give the impression that somehow specifically the removal of a logo required the release of the "embedding application" (not metabase) under AGPL, potentially mis-communicating the copyleft nature of the AGPL license, in order to encourage usage of their enterprise offering.

I [raised this with Metabase on GitHub](https://github.com/metabase/metabase/issues/27859), for which they quickly clarified their intent of the licensing setup, and later updated the wording on their website.