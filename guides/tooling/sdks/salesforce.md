---
rank: 4
related_endpoints: []
related_guides:
  - authentication/jwt
  - authentication/oauth2
related_pages:
  - sdks-and-tools
required_guides: []
related_resources: []
alias_paths:
  - /docs/box-for-salesforce-developer-toolkit
cId: tooling
scId: tooling/sdks
id: tooling/sdks/salesforce
isIndex: false
---
# Install Salesforce SDK

The Salesforce SDK can be deployed directly to Sandbox or Developer
Organizations by clicking using the [deploy_salesforce][deploy_salesforce]
functionality.

<Message type="notice">

"Deploy to Salesforce" functionality is not owned or maintained by Box.

</Message>

The SDK is also distributed as an unmanaged package:

* [salesforce_pkg_prod][salesforce_pkg_prod]
* [salesforce_pkg_sandbox][salesforce_pkg_sandbox]

<Message type="warning">

Unmanaged packages can't be upgraded once installed in a Salesforce org so
future upgrades will have to be applied by cloning the repositories locally
and updating classes from your IDE.

</Message>

[deploy_salesforce]: https://githubsfdeploy.herokuapp.com/?owner=box&repo=box-salesforce-sdk

[salesforce_pkg_prod]: https://cloud.box.com/Box-Apex-SDK

[salesforce_pkg_sandbox]: https://cloud.box.com/Box-Apex-SDK-Sandbox
