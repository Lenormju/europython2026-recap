# My recap of EuroPython 2026

## Monday 2026-07-13: Tutorials

### 09h30-12h45: Getting out of the Testing Hell

Animating a workshop with **Jonathan Gaffiot**

https://ep2026.europython.eu/session/getting-out-of-the-testing-hell

* https://github.com/Lenormju/getting-out-testing-hell
* https://gitlab.com/jgaffiot1/getting-out-testing-hell

Around 55 people attended, and we got great feedback.

### Afternoon

Did not attend any workshop, instead I took a nap and went visiting the city.

## Tuesday 2026-07-14: Tutorials

### 09h30-12h45: Learn Quantum Computing with QiliSDK: From Circuits to Pulse-Level Control

Vyron Vasileiadis

https://ep2026.europython.eu/session/learn-quantum-computing-with-qilisdk-from-circuits-to-pulse-level-control

* https://github.com/qilimanjaro-tech/europython2026-qilisdk-tutorial
* https://htmlpreview.github.io/?https://github.com/qilimanjaro-tech/europython2026-qilisdk-tutorial/blob/main/slides/qilisdk_tutorial.html
* https://github.com/qilimanjaro-tech/qilisdk
* https://qilimanjaro-tech.github.io/qilisdk

Very high quality, but not much hands-on (around 20 minutes, for a 180-minutes workshop, which is ~12%). A full-day "course" would be better suited I think. But the teaching material is very good !

### 13h45-17h00: Introduction to security research. Find a CVE with CodeQL.

Sylwia Budzynska

https://ep2026.europython.eu/session/introduction-to-security-research-find-a-cve-with-codeql

* https://github.com/sylwia-budzynska/codeql-workshop/

Github-only, non-free to use for business, so limited usefulness if you are not already a GitHub enterprise customer.
Requires to use VSCode, which to me is a torture.
At least the Codespace was working sort of fine. But on a "free" 4-core CPU it was very sluggish to query for a few results on an already-computed database.
I tried to set it up locally, and even with Claude's help, I could not execute my query. So very not impressed.

### 19h30: Speaker Dinner

## Wednesday 2026-07-15: Talks

### ❤️ 09h30-10h15 Keynote: How Complex Systems Taught Me To Fail

Imogen Wright

https://ep2026.europython.eu/session/how-complex-systems-taught-me-to-fail

[Richard I. Cook : How Complex Systems Fail](https://how.complexsystems.fail/)

Covid-19 Omicron

Nancy Leveson - STAMP/STPA, loss, there is no single root cause

Perrow - Normal accidents, they happen, due to interactive complexity and tight coupling

### ❤️ 10h45-11h30 Talk: Should you trust Trusted Publishing?

Nikita Karamov

https://ep2026.europython.eu/session/should-you-trust-trusted-publishing

[slides](https://programme.europython.eu/media/europython-2026/submissions/M8Q77Z/resources/Should_you_jbXzWD1.pdf)

https://blog.yossarian.net/2026/07/07/You-shouldnt-trust-trusted-publishing

GhostAction + ShaiHulud + LiteLLM supply-chain attacks

OIDC = OpenID Connect, based on OAuth 2.0

humans don't need to manage secrets, they configure their accounts and let servers handle the rest

PyPI trusted publishers: GitHub, GitLab, Google Cloud, ActiveState

### 11h40-12h10 Talk: The Human-in-the-Loop is Tired

Laura Summers

https://ep2026.europython.eu/session/the-human-in-the-loop-is-tired

Could not attend, the room was crowded

### 11h40-12h10 Talk: Property based testing with Hypothesis

Freya Bruhin

https://ep2026.europython.eu/session/property-based-testing-with-hypothesis

Good intro to Hypothesis, and which specific problems it tries to solve.

### 12h20-12h50 Talk: From Code Hero to Team Leader: Learning to Let Go

Manivannan Selvaraj

https://ep2026.europython.eu/session/from-code-hero-to-team-leader-learning-to-let-go

Goals:
* trust your team
* ask better questions
* create clarity
* remove blockers
* celebrate them, not you

Issues:
* decision machine: dont ask for micro-changes, share understandings
* jira vs leadership: a task is for an outcome (why)
* pr review vs leadership: reviewing becomes a bottleneck, create copies of myself versus create autonomous people
* loving being a hero: firefighter versus building for tomorrow

Do:
* let people own their decisions
* don't rescue every problem
* stand up for the team
* give credit
* create independance
* grow trust

Remember:
* engineers solve problems
* tech leads create problem solvers

### 12h50-13h50 Poster: A tour of the module `itertools`

Rodrigo Girão Serrão

### 12h50-13h50 Poster: Django TDD Patterns: A Visual Field Guide

Kuldeep Pisda

### 13h50-14h50 Panel: Security and Ethics in the Age of Generative AI

Julien Lenormand, Maria Lowas-Rzechonek, Mike Fiedler, Seth Michael Larson, Sylwia Budzynska

### 15h25-15h55 Talk: How many spoons does your environment cost: Broken demos & human element

Dawn Wages

https://ep2026.europython.eu/session/how-many-spoons-does-your-environment-cost-broken-demos-human-element

https://dawnwages.info/ep-26/

Spoon theory

why environments fail ?
* messy abstraction layers
* wrong mental model
* messy process

why do we fail ?
* memory model
* switching tasks
* masking tax

### 15h25-15h55 Talk: uvx which-profiler – Which Profiler, When

Jonathan Striebel

https://ep2026.europython.eu/session/uvx-which-profiler-which-profiler-when

Could not attend, waiting for the replay

### 16h05-16h35 Talk: Demystifying CRA for the community

Anwesha Das

https://ep2026.europython.eu/session/demystifying-cra-for-the-community

Cyber Resilience Act

nice memes

how to reduce the vulnerability window duraion ? how to fix issues faster ?

building trust: secure by default (not just compliance)
* take proper mesures during conception, have secured development environemnts, keep secrets secure
* address security issues
* providing updates
* mandatory transparency

FOSS maintainers under no obligation, but can follow guidelines

PSF is only a steward (helps make viable, nut are not the original creator), not responsible either

https://access.redhat.com/security/eu-cyber-resilience-act-stewardship-guidelines

https://devguide.python.org/security/policy/

https://orcwg.org/cra/

https://cra.orcwg.org/faq/all/

### 16h45-17h30 Podcast: Core.py recording with Guido van Rossum

Pablo Galindo Salgado, Guido van Rossum, Łukasz Langa

`perchance` keyword

### 17h30-17h40 Announcement: EuroPython 25th anniversary

### 17h40-17h55: Python Quiz

### 17h55-18h40: Lightning talks

## Thursday 2026-07-16: Talks

### 09h20-10h05 Keynote: The Pursuit Of Purity (The Right Way To Do AI)

Marlene Mhangami

https://ep2026.europython.eu/session/the-pursuit-of-purity-the-right-way-to-do-ai

### 10h05-10h30 Announcement: Python Steering Council Update

### 10h50-11h35 Talk: The Hidden Cost of Complexity: Reducing Cognitive Load in Python

Jarosław Śmietanka

https://ep2026.europython.eu/session/the-hidden-cost-of-complexity-reducing-cognitive-load-in-python

### 10h50-11h35 Talk: Navigating waters of background jobs and queues in Python as of 2026

Sebastian Buczyński

https://ep2026.europython.eu/session/navigating-waters-of-background-jobs-and-queues-in-python-as-of-2026

### 10h50-11h35 Talk: From one to 1 million packet/second: scaling global Internet monitoring

Marco Grossi

https://ep2026.europython.eu/session/from-one-to-1-million-packet-second-scaling-global-internet-monitoring

### 11h45-12h15 Talk: Deploying Python Web Apps in 2026

Will Vincent

https://ep2026.europython.eu/session/deploying-python-web-apps-in-2026

### TODO

### 19h00: Social event

## Friday 2026-07-17: Talks

### TODO

## Saturday 2026-07-18: Sprint

Skipped it to visit the city instead.

## Sunday 2026-06-19: Sprint

Already left, sorry.
