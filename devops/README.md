# DevOps
---

- [ ] [Dev-ops-Interview - Tikam02](https://github.com/Tikam02/DevOps-Guide/blob/master/Interview/Dev-ops-Interview.md)

## Fundamental differences between DevOps & Agile
---
Although DevOps shares some similarities with the Agile methodology, which is one of the most popular SDLC methodologies, both are fundamentally different approaches to software development. Following are the various fundamental differences between the two:

- Agile Approach – The agile approach is only meant for development in Agile while the DevOps approach is meant for both development and operations in DevOps.
- Practices and Processes – While agile involves practices such as Agile Scrum and Agile Kanban, DevOps involves processes such as CD (Continuous Delivery), CI (Continuous Integration), and CT (Continuous Testing).
- Priority – Agile prioritizes timeliness whereas, DevOps gives equal priority to timeliness and quality.
- Release Cycles – DevOps offers smaller release cycles with immediate feedback while Agile offers only smaller release cycles without immediate feedback.
- Feedback Source – Agile relies on feedback from customers while feedback from self (monitoring tools) is involved in DevOps.
- Scope of Work – For Agile, the scope of work is agility only but for DevOps, it is agility and the need for automation.

## Why do we need DevOps
---
Organizations these days are trying to transport small features to customers via a series of release trains instead of releasing big feature sets. There are several benefits of doing so, including better software quality and quick customer feedback.

- All such benefits lead to a higher level of customer satisfaction, which is the most important goal for any product development project. To do so, companies need to:
  - Increase deployment frequency
  - Lessen lead time between fixes
  - Lower failure rate of new releases
  - In case of new release crashing, have a faster mean time to recovery
- DevOps helps in fulfilling all these requirements and thus, achieving seamless software delivery. Full-fledged organizations like Amazon, Etsy, and Google have adopted DevOps methodology resulting in achieving performance levels that were previously uncharted.
- With the adoption of DevOps methodology, organizations are able to accomplish tens to thousands of deployments in a single day. Moreover, doing so while offering first-rate reliability, security, and stability.

## Important business and technical benefits of using DevOps
---
DevOps brings a lot of business and technical benefits to the table. Some of the most important ones are listed down as follows:

- Business benefits:
  - Enhanced operating environment stability
  - Faster delivery of features
  - More time for adding value to the product
- Technical benefits:
  - Continuous software delivery
  - Faster problem resolution
  - Lesser complex problems

## Popular DevOps tools
---
Following is a list of some of the most widely used DevOps tools:

- Ansible – A configuration management and application deployment tool
- Chef – A configuration management and application deployment tool
- Docker – A containerization tool
- Git – A version control system (VCS) tool
- Jenkins – A continuous integration (CI) tool
- Jira – An agile team collaboration tool
- Nagios – A continuous monitoring tool
- Puppet – A configuration management and application deployment tool
- Selenium – A continuous testing (CT) tool

## Anti-Patterns of DevOps
---
When a DevOps pattern commonly adopted by other organizations doesn’t work in a specific context and still the organization continues using it, it leads to the adoption of an anti-pattern. In other words, anti-patterns are myths about DevOps. Some of the notable anti-patterns are:

- An organization needs to have a separate DevOps group
- Agile equals DevOps
- DevOps is a process
- DevOps is development-driven release management
- DevOps is not possible because the organization is unique
- DevOps is not possible because the people available are unsuitable
- DevOps means Developers Managing Production
- DevOps will solve all problems
- Failing to include all aspects of the organization in an ongoing DevOps transition
- Not defining KPIs at the start of a DevOps transition
- Reduce the silo-based isolation of development and operations with a new DevOps team that silos itself from other parts of the organization

## Continuous Integration
---
CI in DevOps stands for Continuous Integration. CI is a development practice in which developers integrate code into a shared repository multiple times in a single day.

- Continuous Integration of development and testing enhances the quality of the software as well as reducing the total time required for delivery.
- The developer has broken the build if a team member checking in code runs into a compilation failure. As such, other developers are not able to sync with the shared source code repository without introducing compilation errors into their own workspaces.
- This disrupts the collaborative and shared development process. Hence, as soon as a CI build breaks, it’s important to identify and correct the problem immediately.
- Typically, a CI process includes a suite of unit, integration, and regression tests that run each time the compilation succeeds. In case any of the aforesaid tests fail, the CI build is considered unstable (which is common during an Agile sprint when development is ongoing) and not broken.

## Shift Left in DevOps
---
The traditional software development lifecycle when graphed on a paper has two sides, left and right. While the left side of the graph includes design and development, the right side includes production staging, stress testing, and user acceptance.

- To shift left in DevOps simply means the necessity of taking as many tasks on the right i.e. that typically happens toward the end of the application development process and incorporate them into earlier stages of a DevOps methodology.
- There are several ways of accomplishing a shit left in DevOps, most notably:
- Create production-ready artifacts at the end of every Agile sprint 
- Incorporating static code analysis routines in every build

- The level of doing the DevOps the right way is directly dependent on the degree of shifting left as much as possible.

## CAMS in DevOps
---
The acronym CAMS is usually used for describing the core creeds of DevOps methodology. It stands for:

- Culture
- Automation
- Measurement
- Sharing

## KPIs used to gauge DevOps success
---
KPIs is a contracted form of Key Performance Indicators. In order to measure the success of a DevOps process, several KPIs can be used. Some of the most popular ones are:

- Application performance
- Application usage and traffic
- The automated test pass percentage
- Availability
- Change volume
- Customer tickets
- Defect escape rate
- Deployment frequency
- Deployment time
- Error rates
- Failed deployments
- Lead time
- Meantime to detection (MTTD)
- Mean time to recovery (MTTR)

## Major benefits of implementing DevOps automation
---
Following are the major benefits of implementing DevOps automation:

- Removal of the possibility of human error from the CD equation (Core benefit)
- As tasks become more predictable and repeatable, it is easy to identify and correct when something goes wrong. Hence, it results in producing more reliable and robust systems
- Removes bottlenecks from the CI pipeline. It results in increased deployment frequency and decreased number of failed deployments. Both of them are important DevOps KPIs
