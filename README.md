# Auth0 Ruby API Samples
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors) <img src="https://img.shields.io/badge/community-driven-brightgreen.svg"/> <br>

### Deprecation notice

This repository has been deprecated.

### Contributors

Thanks goes to these wonderful people who contribute(d) or maintain(ed) this repo ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://twitter.com/beardaway"><img src="https://avatars3.githubusercontent.com/u/11062800?v=4" width="100px;" alt="Conrad Sopala"/><br /><sub><b>Conrad Sopala</b></sub></a><br /><a href="#maintenance-beardaway" title="Maintenance">🚧</a> <a href="#review-beardaway" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://rafael-noguera.com.ve"><img src="https://avatars2.githubusercontent.com/u/15782359?v=4" width="100px;" alt="Rafael Noguera"/><br /><sub><b>Rafael Noguera</b></sub></a><br /><a href="https://github.com/auth0-community/auth0-ruby-api-samples/commits?author=rafanog" title="Code">💻</a></td>
    <td align="center"><a href="http://ryanchenkie.com"><img src="https://avatars1.githubusercontent.com/u/1847678?v=4" width="100px;" alt="Ryan Chenkie"/><br /><sub><b>Ryan Chenkie</b></sub></a><br /><a href="https://github.com/auth0-community/auth0-ruby-api-samples/commits?author=chenkie" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/alexisluque"><img src="https://avatars2.githubusercontent.com/u/30907012?v=4" width="100px;" alt="Alexis Luque"/><br /><sub><b>Alexis Luque</b></sub></a><br /><a href="https://github.com/auth0-community/auth0-ruby-api-samples/commits?author=alexisluque" title="Code">💻</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

## Intro 
These samples demonstrate how to create an API with Ruby which only permits access to resources if a valid **access token** is included. This verification is done by validating the signature and claims in a JSON Web Token (JWT) signed by Auth0.

These samples do not demonstrate how to sign a JWT but rather assume that a user has already been authenticated by Auth0 and holds an access token for API access. For information on how to use Auth0 to authenticate users, see [the docs](https://auth0.com/docs).

To go to the sample you are interested in, navigate to the root folder.

This repo is supported and maintained by Community Developers, not Auth0. For more information about different support levels check https://auth0.com/docs/support/matrix .

## Contribute

Feel like contributing to this repo? We're glad to hear that! Before you start contributing please visit our [Contributing Guideline](https://github.com/auth0-community/getting-started/blob/master/CONTRIBUTION.md).

Here you can also find the [PR template](https://github.com/auth0-community/auth0-ruby-api-samples/blob/master/PULL_REQUEST_TEMPLATE.md) to fill once creating a PR. It will automatically appear once you open a pull request.

## Issues Reporting

Spotted a bug or any other kind of issue? We're just humans and we're always waiting for constructive feedback! Check our section on how to [report issues](https://github.com/auth0-community/getting-started/blob/master/CONTRIBUTION.md#issues)!

Here you can also find the [Issue template](https://github.com/auth0-community/auth0-ruby-api-samples/blob/master/ISSUE_TEMPLATE.md) to fill once opening a new issue. It will automatically appear once you create an issue.

## Repo Community

Feel like PRs and issues are not enough? Want to dive into further discussion about the tool? We created topics for each Auth0 Community repo so that you can join discussion on stack available on our repos. Here it is for this one: [auth0-ruby-api-samples](https://community.auth0.com/t/auth0-community-oss-auth0-ruby-api-samples/15972)

<a href="https://community.auth0.com/">
<img src="/Assets/join_auth0_community_badge.png"/>
</a>

## License

This project is licensed under the MIT license. See the [LICENSE](https://github.com/auth0-community/auth0-ruby-api-samples/blob/master/LICENSE) file for more info.

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like
  * Google
  * Facebook
  * Microsoft
  * Linkedin
  * GitHub
  * Twitter
  * Box
  * Salesforce
  * etc.

  **or** enterprise identity systems like:
  * Windows Azure AD
  * Google Apps
  * Active Directory
  * ADFS
  * Any SAML Identity Provider

* Add authentication through more traditional [username/password databases](https://docs.auth0.com/mysql-connection-tutorial)
* Add support for [linking different user accounts](https://docs.auth0.com/link-accounts) with the same user
* Support for generating signed [JSON Web Tokens](https://docs.auth0.com/jwt) to call your APIs and create user identity flow securely
* Analytics of how, when and where users are logging in
* Pull data from other sources and add it to user profile, through [JavaScript rules](https://docs.auth0.com/rules)

## Create a free Auth0 account

* Go to [Auth0 website](https://auth0.com/signup)
* Hit the **SIGN UP** button in the upper-right corner
