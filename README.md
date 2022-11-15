<div align="center">
<h1>Awesome Camunda Platform 8 Connectors</h1>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contribute](https://img.shields.io/badge/contribute-project-blue.svg)](https://github.com/camunda-community-hub/camunda-8-connectors/pulls) [![](https://img.shields.io/badge/Compatible%20with-Camunda%20Platform%208-0072Ce)](https://docs.camunda.io/)
  
<hr />
<a href="https://docs.camunda.io/docs/components/integration-framework/introduction-to-connectors/">Camunda Platform 8 Connectors</a>&nbsp;&nbsp;&nbsp;
<a href="https://camunda.com/events/code-conduct/">Code of Conduct</a>&nbsp;&nbsp;&nbsp;
<a href="https://github.com/camunda-community-hub/community/blob/main/CONTRIBUTING.MD">Contributing</a>
<hr />
</div>

A curated list of awesome [Camunda Platform 8 Connectors](https://docs.camunda.io/docs/components/integration-framework/introduction-to-connectors/) projects, driven by the Community, Partners, and Camunda.
We are excited to empower our ecosystem to build connectivity, accelerating process orchestration with any system!

## Contents

* [Out-of-the-box Connectors](#out-of-the-box-connectors)
* [Partner Connectors](#partner-connectors)
* [Community Connectors](#community-connectors)
* [Related projects](#related-projects)
* [Resources](#resources)

# Out-of-the-box Connectors

Connector runtimes provided by [Camunda out-of-the-box](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/available-connectors-overview/) in C8 SaaS and Self-Managed:

| Connector    | JAR with dependencies                                                                          | Code repository                                             | Documentation                                                                                                                              | License                                      | Lifecycle |
| ------------ | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------- | ---------- |
| Amazon SQS   | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-sqs)          | [GitHub](https://github.com/camunda/connector-sqs)          | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/aws-sqs/)     | [Camunda Platform Self-Managed Free Edition] | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |
| AWS Lambda   | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-aws-lambda)   | [GitHub](https://github.com/camunda/connector-aws-lambda)   | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/aws-lambda/)  | [Camunda Platform Self-Managed Free Edition] | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |
| Google Drive | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-google-drive) | [GitHub](https://github.com/camunda/connector-google-drive) | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/googledrive/) | [Camunda Platform Self-Managed Free Edition] | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |
| REST         | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-http-json)    | [GitHub](https://github.com/camunda/connector-http-json)    | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/rest/)        | [Apache 2.0]                                 | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |
| SendGrid     | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-sendgrid)     | [GitHub](https://github.com/camunda/connector-sendgrid)     | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/sendgrid/)    | [Camunda Platform Self-Managed Free Edition] | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |
| Slack        | [Maven Central](https://search.maven.org/artifact/io.camunda.connector/connector-slack)        | [GitHub](https://github.com/camunda/connector-slack)        | [Camunda Docs](https://docs.camunda.io/docs/components/integration-framework/connectors/out-of-the-box-connectors/slack/)       | [Camunda Platform Self-Managed Free Edition] | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-) |

# Partner Connectors

Connector runtimes provided by Camunda partners:
Coming Soon!

| Connector              | Partner | JAR with dependencies | Code repository | Documentation | License | Lifecycle |
| ---------------------- | ------- | --------------------- | --------------- | ------------- | ------- | --------- |
| Git (*coming soon!*)   |         |                       |                 |               |         |           |
| JIRA (*coming soon!*)  |         |                       |                 |               |         |           |
| MySQL (*coming soon!*) |         |                       |                 |               |         |           |
| Email (*coming soon!*) |         |                       |                 |               |         |           |

# Community Connectors

Connector runtimes provided by the Community:

| Connector        | JAR with dependencies | Code repository                                                                          | Documentation                                                                                              | License    | Lifecycle                                                                                                                                                                            |
|------------------|-----------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Openweather API  | -                     | [GitHub](https://github.com/camunda-community-hub/camunda-8-connector-openweather-api/)  | [README](https://github.com/camunda-community-hub/camunda-8-connector-openweather-api/blob/main/README.md) | Apache 2.0 | [![](https://img.shields.io/badge/Lifecycle-Proof%20of%20Concept-blueviolet)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#proof-of-concept-) |
| SendBPMNMessage  | -                     | [GitHub](https://github.com/camunda-community-hub/camunda-8-connector-sendBPMNmessage)   | [README](https://github.com/camunda-community-hub/camunda-8-connector-sendBPMNmessage/blob/main/README.md) | Apache 2.0 | [![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-)                        |


# Related projects

Projects related to Camunda 8 Connectors that are not Connectors themselves.

* [OpenAPI Connector Template Generator for REST Connector Runtime](https://github.com/camunda-community-hub/openapi-connector-template-generator)
* [Node.js Connector SDK](https://github.com/camunda-community-hub/connector-sdk-nodejs) - write Connectors in JavaScript / TypeScript for execution in Node.js.


# Resources

Additional resources related to Camunda 8 Connectors:

* [Official Connector Documentation](https://docs.camunda.io/docs/components/integration-framework/introduction-to-connectors/)
* [Connector SDK](https://github.com/camunda/connector-sdk) and [its documentation](https://docs.camunda.io/docs/components/integration-framework/connectors/custom-built-connectors/connector-sdk/)
* [Connector Template](https://github.com/camunda/connector-template)

[apache 2.0]: https://www.apache.org/licenses/LICENSE-2.0
[camunda platform self-managed free edition]: https://camunda.com/legal/terms/cloud-terms-and-conditions/camunda-cloud-self-managed-free-edition-terms/
