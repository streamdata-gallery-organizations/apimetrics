---
name: APImetrics
x-slug: apimetrics
description: API performance monitoring, Cloud Service, SLA monitoring and analysis
  that gives you answers, not excuses. Find out how today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
x-kinRank: "10"
x-alexaRank: "2264063"
tags: APImetrics
created: "2018-06-19"
modified: "2018-06-19"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/apis.md
specificationVersion: "0.14"
apis:
- name: APIMetrics List Authentication Settings
  x-api-slug: apimetrics
  description: List Authentication Settings
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///auth/
  tags: Monitoring,Auth
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/auth-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/auth-get-openapi.md
- name: APIMetrics Delete an Authentication Setting
  x-api-slug: apimetrics
  description: Delete an Authentication Setting
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///auth/{id}/
  tags: Monitoring,Auth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/authid-delete-openapi.md
- name: APIMetrics Get an existing Authentication Setting
  x-api-slug: apimetrics
  description: Get an existing Authentication Setting
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///auth/{id}/
  tags: Monitoring,Auth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/authid-get-openapi.md
- name: APIMetrics Update an existing Authentication Setting
  x-api-slug: apimetrics
  description: Update an existing Authentication Setting
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///auth/{id}/
  tags: Monitoring,Auth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/authid-put-openapi.md
- name: APIMetrics List API Calls
  x-api-slug: apimetrics
  description: List API Calls
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/
  tags: Monitoring,Calls
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/calls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/calls-get-openapi.md
- name: APIMetrics Create new API Call
  x-api-slug: apimetrics
  description: Create new API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/
  tags: Monitoring,Calls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/calls-post-openapi.md
- name: APIMetrics List API Calls by Authentication
  x-api-slug: apimetrics
  description: List API Calls by Authentication
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/auth/{auth_id}/
  tags: Monitoring,Calls, Auth, Auth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsauthauth-id-get-openapi.md
- name: APIMetrics Delete an API Call
  x-api-slug: apimetrics
  description: Delete an API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/
  tags: Monitoring,Calls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsid-delete-openapi.md
- name: APIMetrics Get an existing API Call
  x-api-slug: apimetrics
  description: Get an existing API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/
  tags: Monitoring,Calls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsid-get-openapi.md
- name: APIMetrics Update an existing API Call
  x-api-slug: apimetrics
  description: Update an existing API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/
  tags: Monitoring,Calls
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsid-put-openapi.md
- name: APIMetrics Trigger an API Call to run
  x-api-slug: apimetrics
  description: Trigger an API Call to run
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/run
  tags: Monitoring,Calls, , Run
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsidrun-post-openapi.md
- name: APIMetrics List Stats from before a date for an API Call
  x-api-slug: apimetrics
  description: List Stats from before a date for an API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/stats/before
  tags: Monitoring,Calls, , Stats, Before
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsidstatsbefore-get-openapi.md
- name: APIMetrics List Stats since a date for an API Call
  x-api-slug: apimetrics
  description: List Stats since a date for an API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///calls/{id}/stats/since
  tags: Monitoring,Calls, , Stats, Since
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/callsidstatssince-get-openapi.md
- name: APIMetrics List all Deployment
  x-api-slug: apimetrics
  description: List all Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/
  tags: Monitoring,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deployments-get-openapi.md
- name: APIMetrics Create a new Deployment
  x-api-slug: apimetrics
  description: Create a new Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deployments-post-openapi.md
- name: APIMetrics Get all Deployments for an API Call
  x-api-slug: apimetrics
  description: Get all Deployments for an API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/call/{call_id}/
  tags: Monitoring,Deployments, Call, Call
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deploymentscallcall-id-get-openapi.md
- name: APIMetrics Get all Deployments for a Workflow
  x-api-slug: apimetrics
  description: Get all Deployments for a Workflow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/workflow/{workflow_id}
  tags: Monitoring,Deployments, Workflow, Workflow
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deploymentsworkflowworkflow-id-get-openapi.md
- name: APIMetrics Delete a Deployment
  x-api-slug: apimetrics
  description: Delete a Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deploymentsid-delete-openapi.md
- name: APIMetrics Get an existing Deployment
  x-api-slug: apimetrics
  description: Get an existing Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deploymentsid-get-openapi.md
- name: APIMetrics Update an existing Deployment
  x-api-slug: apimetrics
  description: Update an existing Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/deploymentsid-put-openapi.md
- name: APIMetrics List all Reports
  x-api-slug: apimetrics
  description: List all Reports
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///reports/
  tags: Monitoring,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/reports-get-openapi.md
- name: APIMetrics Create a new Report
  x-api-slug: apimetrics
  description: Create a new Report
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///reports/
  tags: Monitoring,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/reports-post-openapi.md
- name: APIMetrics Delete a Report
  x-api-slug: apimetrics
  description: Delete a Report
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///reports/{id}/
  tags: Monitoring,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/reportsid-delete-openapi.md
- name: APIMetrics Get an existing Report
  x-api-slug: apimetrics
  description: Get an existing Report
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///reports/{id}/
  tags: Monitoring,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/reportsid-get-openapi.md
- name: APIMetrics Update an existing Report
  x-api-slug: apimetrics
  description: Update an existing Report
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///reports/{id}/
  tags: Monitoring,Reports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/reportsid-put-openapi.md
- name: APIMetrics List Auth Tokens
  x-api-slug: apimetrics
  description: List Auth Tokens
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/
  tags: Monitoring,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokens-get-openapi.md
- name: APIMetrics Create a new Auth Token
  x-api-slug: apimetrics
  description: Create a new Auth Token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/
  tags: Monitoring,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokens-post-openapi.md
- name: APIMetrics Get all tokens for an Authentication Setting
  x-api-slug: apimetrics
  description: Get all tokens for an Authentication Setting
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/auth/{auth_id}/
  tags: Monitoring,Tokens, Auth, Auth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokensauthauth-id-get-openapi.md
- name: APIMetrics Delete an Auth Token
  x-api-slug: apimetrics
  description: Delete an Auth Token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/{id}/
  tags: Monitoring,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokensid-delete-openapi.md
- name: APIMetrics Get an existing Auth Token
  x-api-slug: apimetrics
  description: Get an existing Auth Token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/{id}/
  tags: Monitoring,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokensid-get-openapi.md
- name: APIMetrics Update an Auth Token
  x-api-slug: apimetrics
  description: Update an Auth Token
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///tokens/{id}/
  tags: Monitoring,Tokens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/tokensid-put-openapi.md
- name: APIMetrics List all Workflows
  x-api-slug: apimetrics
  description: List all Workflows
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflows-get-openapi.md
- name: APIMetrics Create new Authentication Settings
  x-api-slug: apimetrics
  description: Create new Authentication Settings
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflows-post-openapi.md
- name: APIMetrics Delete a Workflow
  x-api-slug: apimetrics
  description: Delete a Workflow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/{id}/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflowsid-delete-openapi.md
- name: APIMetrics Get an existing Workflow
  x-api-slug: apimetrics
  description: Get an existing Workflow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/{id}/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflowsid-get-openapi.md
- name: APIMetrics Trigger a Workflow to run now
  x-api-slug: apimetrics
  description: Trigger a Workflow to run now
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/{id}/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflowsid-post-openapi.md
- name: APIMetrics Create a new Workflow
  x-api-slug: apimetrics
  description: Create a new Workflow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///workflows/{id}/
  tags: Monitoring,Workflows
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/workflowsid-put-openapi.md
- name: APIMetrics
  x-api-slug: apimetrics
  description: API performance monitoring, Cloud Service, SLA monitoring and analysis
    that gives you answers, not excuses. Find out how today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https:///
  tags: APImetrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/apimetrics/master/_listings/apimetrics/openapi.md
x-common:
- type: x-base-url
  url: https://client.apimetrics.io
- type: x-blog
  url: http://apimetrics.io/blog/
- type: x-blog-rss
  url: http://apimetrics.io/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apimetrics
- type: x-developer
  url: https://apimetrics.readme.io/
- type: x-github
  url: https://github.com/APImetrics
- type: x-pricing
  url: http://apimetrics.io/
- type: x-privacy
  url: http://apimetrics.io/privacy
- type: x-terms-of-service
  url: http://apimetrics.io/tos
- type: x-twitter
  url: https://twitter.com/apimetricstats
- type: x-website
  url: http://apimetrics.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---