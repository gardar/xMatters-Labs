<img src="media/_Final_xM_Octo-Logo-01.png" width="200" height="200" align="right">

# xMatters-Labs
Welcome to xMatters Labs, the official/unofficial Research and Development wing of xMatters, inc., and home to the most cutting edge integrations on offer. 

This is a curated list (based on the awesome framework of [awesome-cisco](https://github.com/CiscoDevNet/awesome-ciscospark) and [awesome-go](https://github.com/avelino/awesome-go)) of useful in-progress integrations, interesting code samples, and other experiments, and as such we can provide only limited support. If you run into any problems, open an issue here on Github and we'll see what we can do. 

For a full list of our current integrations, head over to [xmatters.com/integrations](https://www.xmatters.com/integrations). 

To join the discussion on all things related to xMatters integrations, check out our user forums at https://support.xmatters.com/hc/en-us/community/topics/200330486-Integrations-Q-A

# Contributing

## Getting started - Integrating
There are really 3 types of integrations to/from the xMatters platform:
* *Data Source* - Getting groups, user or device data in or out of xMatters
  * *Example*: None yet. Contribute one!
* *Event Triggers* - Initate events. These events do not necessarily need to notify people
  * *Example*: [JIRA - Cloud](#jira---cloud)
  * *One way*: Start here: https://support.xmatters.com/hc/en-us/articles/115001230823
  * *Closed loop*: Start here: https://support.xmatters.com/hc/en-us/articles/211526223
* *Enrichment* - Intended to be tacked on to an existing integration, these provide enrichment or enhancement functionality.
  * *Example*: [StatusPage](#statuspage), ServiceNow [Inform with xMatters](#inform-with-xmatters)
  * *Getting started*: https://support.xmatters.com/hc/en-us/articles/214627943

## Getting started - Post the repo
Once you've completed the integration, it's time to post the artifacts to github. The [xM Labs Template](https://github.com/xmatters/xm-labs-template) has all the details on how to get the repo created, clone the template, update some urls and then push back to github. Once all the documentation bits are complete, drop an email to Travis, or raise an issue [here](https://github.com/xmatters/xMatters-Labs/issues) and we'll fork the repo and get the list below updated.

# Contents
- [Alertus](#alertus)
- [Atlassian](#atlassian)
  - [StatusPage](#statuspage)
  - [JIRA - Cloud](#jira---cloud)
  - [JIRA - Server](#jira---server)
- [Dynatrace](#dynatrace)
- [Jenkins](#jenkins)
- [OverOps](#overops)
- [Stackdriver](#stackdriver)
- [ServiceNow](#servicenow)
  - [Inform with xMatters](#inform-with-xmatters)
  - [CI Support Groups on Engage form](#ci-support-groups-on-engage-form)
- [Slack](#slack)
- [Zabbix](#zabbix)


# Integrations
## Alertus
The [Alertus](https://github.com/xmatters/xm-labs-alertus) integration provides desktop notification capability.

## Atlassian
### StatusPage
[StatusPage](https://github.com/xmatters/xm-labs-statuspage) - Integration for posting to StatusPage.io

### JIRA - Cloud
The standard JIRA cloud integration is geared toward a more generic implementation for JIRA Software and JIRA Service Desk. [https://www.xmatters.com/integration/jira-cloud/](https://www.xmatters.com/integration/jira-cloud/)

### JIRA - Server
With the JIRA Server integration for JIRA Software and JIRA Service Desk, instantly identify and communicate with the correct on-call resources to resolve customer issues as they arise, collaborate via conference bridge, and assign issues to responding users. All activity is automatically logged on the original issue. [https://www.xmatters.com/integration/jira-server/](https://www.xmatters.com/integration/jira-server/)

## Dynatrace
Dynatrace is a leading performance and application monitoring application. This integration extends the alerting capabilities to use xMatters.
[https://github.com/xmatters/xm-labs-dynatrace](https://github.com/xmatters/xm-labs-dynatrace)

## Jenkins
Jenkins is the leading automation server. 
[https://github.com/xmatters/xmatters-labs-Jenkins](https://github.com/xmatters/xmatters-labs-Jenkins)

## OverOps
OverOps is a leading monitoring solution that provides direct insight into code level issues.
[https://github.com/xmatters/xm-labs-overops](https://github.com/xmatters/xm-labs-overops)

## Stackdriver
Google Cloud's monitoring, logging and alerting platform get the xMatters treatment. 
[https://github.com/xmatters/xm-labs-stackdriver](https://github.com/xmatters/xm-labs-stackdriver)

## ServiceNow
### Inform with xMatters
[Inform with xMatters](https://github.com/xmatters/xm-labs-snow-inform) - An "add-on" for ad-hoc FYI type notifications from ServiceNow. 
### CI Support Groups on Engage form
[CI Support Groups](https://github.com/xmatters/xm-labs-snow-ci-groups) - An "add-on" for including the upstream and downstream CI groups to the Engage with xMatters form. 

## Slack
[Slack](https://github.com/xmatters/xm-labs-slack) - Shared Library for working with Slack

## Zabbix
[Zabbix](https://github.com/xmatters/xm-labs-zabbix) - Fully built integration to Zabbix.
