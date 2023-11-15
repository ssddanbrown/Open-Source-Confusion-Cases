# Bitwarden - Passwordless

[Passwordless](https://bitwarden.com/products/passwordless/) by Bitwarden is an "API framework that minimizes complexities associated with passkey development" which advertises itself as Open Source while significant parts are under a custom [Bitwarden License Agreement](https://github.com/passwordless/passwordless-server/blob/main/LICENSE.txt).

It's not totally clear how this license applies to the projects it's assigned to, but it appears to:

- Prevent production use.
- Prevent competitive use.
- Prevent redistribution of the code.
- Not grant modification.

Examples of advertising as open source include:

> "All Passwordless.dev code is open source." - [In the project docs](https://docs.passwordless.dev/guide/).

> "The open source offering saves engineering resources and [...]" - [Marketing Blogpost](https://bitwarden.com/blog/bitwarden-passwordless-dev-hits-general-availability/)

> "Thorough, third party assessments of the Bitwarden Passwordless.dev open source code [...]" - [Product Homepage](https://bitwarden.com/products/passwordless/) *(although could be indicating their only the open source work is assessed, a little unclear)*

I queried this with them [on GitHub here](https://github.com/passwordless/passwordless-server/issues/37), which prompted an open source license to be applied to the JS client library but other code remains proprietary.