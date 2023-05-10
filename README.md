# Introduction

This repo contains an example for setting up a Postman collection that uses Azure Active Directory Access Tokens.
The collection supports simultanious manual operation using the Postman Guid, and automated operation using a GitHub Actions workflow.

Manual operation relies on the OAuth 2.0 Authorization Code flow.
The user logs in through the browser, via a public AAD Application Registration.
Automated operation relies on the OAuth 2.0 Client Credentials flow.
Here, the Actions workflow authenticates against an Application Registration using Federated Credentials.

[This]() blog post describes the setup in more detail.