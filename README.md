# Flowable

Flowable is an open-source BPM and workflow engine with rich REST APIs for deploying process definitions, starting process instances, managing tasks, querying workflow state, and orchestrating AI agents, people, and processes together. It provides BPMN, CMMN, and DMN automation engines via Java and REST APIs, with enterprise offerings targeting regulated industries such as banking, insurance, and healthcare.

## APIs

Flowable exposes 19 REST APIs in its enterprise platform, with the following core APIs also available in the open-source Community Edition:

| API | Base Path | Description |
|-----|-----------|-------------|
| BPMN API | `/process-api` | Process definitions, instances, executions, tasks |
| CMMN API | `/cmmn-api` | Case definitions, instances, plan items |
| DMN API | `/dmn-api` | Decision tables and rule execution |
| Form API | `/form-api` | Form definitions and submissions |
| Content API | `/content-api` | Binary content and attachments |
| IDM API | `/idm-api` | Users, groups, privileges, tokens |
| External Worker API | `/external-job-api` | External service task acquisition and completion |

Full Swagger documentation for all APIs: https://documentation.flowable.com/latest/develop/core-swagger

## Authentication

REST API endpoints use HTTP Basic Authentication by default, configured via the `flowable.rest.app.authentication-mode` property. Flowable recommends pairing Basic Authentication with HTTPS/TLS. Enterprise deployments integrate with SSO, LDAP, or SAML through the IDM module.

## SDKs and External Clients

Flowable provides official external worker client libraries for:

- **Java**: https://github.com/flowable/flowable-external-client-java
- **Python**: https://github.com/flowable/flowable-external-client-python
- **JavaScript / TypeScript**: https://github.com/flowable/flowable-external-client-js
- **Go**: https://github.com/flowable/flowable-external-client-golang
- **.NET / C#**: https://github.com/flowable/flowable-external-client.net

## Pricing

| Tier | Cost |
|------|------|
| Community Edition | Free (Apache-2.0) |
| Flowable Platform | Contact Sales (Users + RCPI packages) |
| Agentic Case Platform | Contact Sales (Users + RCPI + Agent packages) |

Details: https://www.flowable.com/pricing

## Links

- **Website**: https://www.flowable.com
- **Open Source Docs**: https://www.flowable.com/open-source/docs/
- **Enterprise Docs**: https://documentation.flowable.com/latest/developer
- **GitHub Org**: https://github.com/flowable
- **Main Repository**: https://github.com/flowable/flowable-engine
- **Forum**: https://forum.flowable.org
- **Blog**: https://www.flowable.com/blog
- **Pricing**: https://www.flowable.com/pricing
- **Status Page**: https://status.flowable.com
- **LinkedIn**: https://www.linkedin.com/company/1416054
- **X / Twitter**: https://twitter.com/flowablebpm
