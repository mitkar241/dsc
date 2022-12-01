# Role Comparison
---

## Summary
---
A team consists of different roles which should work hand-in-hand through great communication and respect for the work, everyone does. That's the only way, a team can succeed.

## DevOps
---
Maybe the best-known philosophy of these three until today. DevOps (short for Development and Operations) is a culture to enable development teams to have more control over shipping code to production. The implementation, both technically and cultural, could vary and differs from organization to organization. Some say you need to focus more on the technical approach, some say it's more about the cultural establishment. But in general we can conclude, that DevOps is an approach to create an efficient way to deploy features and code produced by Development. It may be also concerned with other things improving the Development velocity. This could be e.g. to improve deployment pipelines, define some KPIs around the deployment process and, of course, automation.

## SRE
---
So, from a DevOps perspective, if the code is in production, the cycle is over. Some see monitoring also as an active part for DevOps, some don't. But - in general - we can conclude that someone needs to be responsible for keeping production alive. And this is where SRE - Site Reliability Engineering - takes place. It's all about keeping your services up and running for potential consumers. SRE focuses on monitoring and alerting, defining SLOs (Service Level Objectives) of your services and tracking error budgets, incident respones and postmortems. These all are things to make production reliable. In case you want to dig in deeper, have a look at the recommendations in the first comment.
Let's conclude:
SRE works from Production backward. DevOps works from development forward. Somewhere in the middle, they meet.
DevOps keeps production fresh. SRE keeps production healthy.

## Platform Engineering
---
Platform Engineering is the underlying basis of both previous systems. It focuses on developing an ecosystem that can be efficiently used from Dev, Ops and SRE standpoints. Platform Engineering is about enabling others to do whatever they want to do.
Of course, there might be also some coding in Platform Engineering - for example "Infrastructure as Code" tools like Terraform or Ansible, but also scripting tasks. But it's not focused about the primary business logic - it's about making basic infrastructure more suitable for your needs. IaaS, SaaS and PaaS made operating on much higher layers and more abstract. In some cases you don't have to focus on the underlying infrastructure.
