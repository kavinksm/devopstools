---
title: Apache Log4j vulnerability (CVE-2021-44228)
permalink: /log4jfix/
---

Log4j is an open-source Java logging library widely used in many applications and added in many services as a dependency. This includes enterprise applications, including custom applications developed within an organization.

The below is the aggregated list of DecOps tools and its fixes for log4j vulnerability
## Cloud providers report on log4j

| Tools       | Fix Links |
| ----------- | ----------- |
|	AWS	|	https://aws.amazon.com/security/security-bulletins/AWS-2021-006/	|
|	Azure	|	https://msrc-blog.microsoft.com/2021/12/11/microsofts-response-to-cve-2021-44228-apache-log4j2/	|
|	GCP	|	https://cloud.google.com/blog/products/identity-security/cloud-ids-to-help-detect-cve-2021-44228-apache-log4j-vulnerability	|
|	Oracle	|	https://www.oracle.com/security-alerts/alert-cve-2021-44228.html	|
|	Redhat	|	https://access.redhat.com/security/cve/cve-2021-44228	|

## List of DevOps tools along with its fixes

| Tools       | Fix Links | Updated on |
| ----------- | ----------- |----------- |
|	Appdynamics	|	(https://docs.appdynamics.com/display/PAA/Security+Advisory%3A+Apache+Log4j+Vulnerability)	|	High	|		|
|	Bamboo	|	https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html	|		|		|
|	Chef	|	https://www.chef.io/blog/is-chef-vulnerable-to-cve-2021-44228-(log4j)	|	Not affected	|		|
|	Conflluence	|	https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html	|	Low	|		|
|	Consul	|	https://discuss.hashicorp.com/t/hcsec-2021-32-hashicorp-response-to-apache-log4j-2-security-issue-cve-2021-44228/33138	|		|		|
|	Datadog	|	https://www.datadoghq.com/log4j-vulnerability/	|	Low	|		|
|	Dynatrace	|	https://www.dynatrace.com/news/blog/log4shell-vulnerability/	|		|		|
|	Elastic Stack	|	https://discuss.elastic.co/t/apache-log4j2-remote-code-execution-rce-vulnerability-cve-2021-44228-esa-2021-31/291476	|		|		|
|	Github	|	https://github.blog/2021-12-13-githubs-response-to-log4j-vulnerability-cve-2021-44228/	|		|		|
|	Gitlab	|		|		|		|
|	GoCD	|	https://github.com/gocd/gocd/discussions/9931	|		|		|
|	Grafana	|	https://github.com/grafana/grafana/issues/43000	|	No  Impact	|		|
|	Harness	|	https://harness.io/blog/log4shell-response/	|	Low	|		|
|	Hashicorp vault	|	https://discuss.hashicorp.com/t/hcsec-2021-32-hashicorp-response-to-apache-log4j-2-security-issue-cve-2021-44228/33138	|	Not  affected	|		|
|	Jenkins	|	https://www.jenkins.io/blog/2021/12/10/log4j2-rce-CVE-2021-44228/	|	Low	|	14-Dec-21	|
|	Jfrog	|	https://jfrog.com/knowledge-base/general-jfrog-services-are-not-affected-by-vulnerability-cve-2021-44228/	|	Not  affected	|		|
|	Jira	|	https://confluence.atlassian.com/kb/faq-for-cve-2021-44228-1103069406.html	|	Low	|		|
|	New Relic	|	https://discuss.newrelic.com/t/log4j-zero-day-vulnerability-and-the-new-relic-java-agent/170322	|		|		|
|	Nexus &  Nexus IQ	|	https://blog.sonatype.com/a-new-0-day-log4j-vulnerability-discovered-in-the-wild	|		|		|
|	Packer	|	https://discuss.hashicorp.com/t/hcsec-2021-32-hashicorp-response-to-apache-log4j-2-security-issue-cve-2021-44228/33138	|	Not  affected	|		|
|	Puppet	|	https://puppet.com/blog/puppet-response-to-remote-code-execution-vulnerability-cve-2021-44228/	|	Not affected	|		|
|	Salt	|	https://salt.security/blog/the-log4shell-cve-2021-44228-vulnerability-what-it-is-how-it-works-and-how-to-protect-yourself	|	Not affected	|		|
|	Splunk	|	https://www.splunk.com/en_us/blog/bulletins/splunk-security-advisory-for-apache-log4j-cve-2021-44228.html	|		|		|
|	Subversion	|	-	|		|		|
|	Terraform	|	https://discuss.hashicorp.com/t/hcsec-2021-32-hashicorp-response-to-apache-log4j-2-security-issue-cve-2021-44228/33138	|	Not  affected	|		|
|	Tomcat	|	http://mail-archives.apache.org/mod_mbox/www-announce/202112.mbox/%3C028d1058-2e48-f72c-2037-2070d73b7411@apache.org%3E	|		|		|
|	WebSphere	|	https://www.ibm.com/support/pages/node/6525706	|		|		|
|	Wildfly	|	https://www.wildfly.org/news/2021/12/13/Log4j-CVEs/	|		|		|

### Notes
* Application developed on top of Go-lang are not mostly affected