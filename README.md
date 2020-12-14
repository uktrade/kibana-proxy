# Kibana Proxy

A lightweight proxy, with SSO and IP whitelisting, that runs in GOV.UK PaaS and proxies requests to an AWS Elasticsearch instance's Kibana plugin. Intended use is to allow users to access the Activity Stream ES instance.

Heavily cribbed from https://github.com/uktrade/kibana-paas/

## Deployment

Deploy to CloudFoundry with `cf target -o <org> -s <space>` and `cf push kibana-proxy`. No CI/CD pipeline currently.
