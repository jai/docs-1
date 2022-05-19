# Release 4.3.0

Name: <span style="color: turquoise"><span class="glyphicon glyphicon-lamp"></span> "Manticore turquoise lamp"</span>
Release Date: June 1st, 2022

- [Download Rundeck](https://download.rundeck.com/)
- [Sign up for Release Notes](https://www.rundeck.com/release-notes-signup)
- [Upgrade instructions](/upgrading/)

## Overview

Check out the new features and enhancements for Rundeck Enterprise and Rundeck Community included in this release.

## Enterprise Updates

* Allow more than ~30 actions on a single webhook
* PagerDuty /Incident/Add Responders job step fails if there is no value in the &quot;User&quot; field
* Property to customize maximum resources to retrieve from Thycotic
* AWS - Execute Lambda Steps / Validate AWS Credentials Step
* Add configuration to disable &quot;Public Key&quot; GUI download option


## Core Product Updates

* [Storybook Knobs Deprecated](https://github.com/rundeck/rundeck/pull/7721)
* [Fix:Webhook minimum actions error message showing incorrectly](https://github.com/rundeck/rundeck/pull/7718)
* [Update Multiline Regex Data Capture Filter to capture multiple key-value pairs.](https://github.com/rundeck/rundeck/pull/7711)
* [Fix: Bug where Ansible plugins don&#39;t show properly](https://github.com/rundeck/rundeck/pull/7704)
* [Fix local file copier config error](https://github.com/rundeck/rundeck/pull/7703)
* [Fix: XXSSP header is deprecated](https://github.com/rundeck/rundeck/pull/7696)
* [Avoid logging warnings by removing dot notation config value access](https://github.com/rundeck/rundeck/pull/7695)
* [Messages for WebHooks import errors and new messages for webhook toke…](https://github.com/rundeck/rundeck/pull/7694)
* [Remove unused CSS file](https://github.com/rundeck/rundeck/pull/7692)
* [Add configuration to disable &quot;Public Key&quot; GUI download option](https://github.com/rundeck/rundeck/pull/7691)
* [Update node-forge versions to address CVEs](https://github.com/rundeck/rundeck/pull/7690)
* [Fix: Cluster manager hostname disappears](https://github.com/rundeck/rundeck/pull/7685)
* [Remove options when importing Job Definitions](https://github.com/rundeck/rundeck/pull/7674)
* [Support for OpenAPI documentation Generation](https://github.com/rundeck/rundeck/pull/7672)
* [Fix: 404 page when clicking on referenced execution from a different parent](https://github.com/rundeck/rundeck/pull/7649)
* [Can&#39;t open referenced job in GUI, when has thousands of log executions](https://github.com/rundeck/rundeck/pull/7648)

[Here is a link to the full list of public PRs](https://github.com/rundeck/rundeck/pulls?q=is%3Apr+milestone%3A4.3.0+is%3Aclosed)


## Staff Contributors

* Greg Schueler (gschueler)
* Stephen Joyner (sjrd218)
* Imad Jafir (imad6639)
* Luis Toledo (ltamaster)
* Rodrigo Navarro (ronaveva)
* Carlos Eduardo (carlosrfranco)
* Miguel Ramos (mishingo)
* Christopher McCarroll-Gilbert (chrismcg14)
* Jason Qualman (qualman)
* Alexander Abarca (alexander-variacode)
* Alberto Hormazabal Cespedes (ahormazabal)
* Leonel Juarez (L2JE)
* Eric He (ehe-pd)
* Forrest Evans (fdevans)
* Darwis (DarwisNarvaezDev)
* Antony Velasquez Ruiz (avelasquezr)