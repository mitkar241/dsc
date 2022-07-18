# DevOps Concepts
---

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

## Post-Mortem Meetings
---
Many times there is a need to discuss what went wrong during a DevOps process. For this, post mortem meetings are arranged. These meetings yield steps that should be taken to avoid the same failure or set of failures in the future for which the meeting was arranged in the first place.

## What is the purpose of a post-mortem meeting? Do you know how to learn from mistakes?
---

## Tell me about the worst-run/best-run outage you've been a part of. What made it bad/well-run?
---
Take lessons from both failures and successes in dealing with outages.

## How would you prepare for a migration from one platform to another? Fairly self-explanatory, how do you handle transitions?
---

## Draw a comparison between Asset Management and Configuration Management.
---
- The process of monitoring as well as maintaining things of value to an entity or group is called an Asset Management.
- Configuration Management refers to the process of controlling, identifying, planning for, and verifying the configuration items within service in support of Change Management.

## How would you make key aspects of a software system traceable?
---
So that you can figure out what happened quickly if/when something goes wrong.

## How do you handle interruptions?
---
While it’s going to be your job to stop interruptions, how you deal with them now is important for getting an idea of if you know how to fix them quickly and if you know how to make devs and ops work together.

# Describe a dev/test/production workﬂow using GIT
---
