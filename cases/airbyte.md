### Airbyte

[Airbyte](https://airbyte.com/) is an "ELT" (Extract, Load, Transform) data platform which they [advertise as being open source](../files/airbyte-open-source-page.png). The project codebase [is mixed license](https://github.com/airbytehq/airbyte/blob/9adb35e643cfb2816915e11b5869ecfb654242d4/LICENSE) with many "connector" or integration elements using the MIT License, but otherwise the project defaults to the "Elastic License 2.0". The license prevents:

- Provision to third parties as a hosting or managed service.

This was a [change they made](https://github.com/airbytehq/airbyte/commit/f25542a145f2890105f0db5b0ec99c43c207ba09) back in 2021.

[Existing](https://github.com/airbytehq/airbyte/issues/9246) [conversations](https://github.com/airbytehq/airbyte/issues/17118) had been started in January and September 2022 to query the license, the latter of which I also commented on seven months later to provide another viewpoint. As of June 2023 there had been no response to either.

At the time of writing (15th June 2023), it looks like they're intending to [move many of their connectors](https://github.com/airbytehq/airbyte/pull/27288) to the ELv2 license also, even though their [License FAQ](../files/airbyte-license-faq.png) page has specifically stated:

> Will Airbyte connectors continue to be open source?
> Our own connectors remain open-source, and our contributors can also develop their own connectors and continue to choose whichever license they prefer. This is our way to accomplish Airbyte’s vision of commoditizing data integration: access to data shouldn’t be behind a paywall. Also, we want Airbyte’s licensing to work well with applications that are integrated using connectors.