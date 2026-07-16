# My recap of EuroPython 2026

* [Monday](#monday-2026-07-13-tutorials)
* [Tuesday](#tuesday-2026-07-14-tutorials)
* [Wednesday](#wednesday-2026-07-15-talks)
* [Thursday](#thursday-2026-07-16-talks)
* [Friday](#friday-2026-07-17-talks)
* [Saturday](#saturday-2026-07-18-sprints)
* [Sunday](#sunday-2026-06-19-sprints)

My favorites:

* Imogen Wright - How Complex Systems Taught Me To Fail
* Nikita Karamov - Should you trust Trusted Publishing?

Talks to watch in replay:

* Laura Summers - The Human-in-the-Loop is Tired
* Marco Grossi - From one to 1 million packet/second: scaling global Internet 
* Jonathan Striebel - uvx which-profiler – Which Profiler, When
* Katie Bickford - Why doing difficult things is good for you and good for your team

## Monday 2026-07-13: Tutorials

### 09h30-12h45: Getting out of the Testing Hell

Animating a workshop with **Jonathan Gaffiot**

https://ep2026.europython.eu/session/getting-out-of-the-testing-hell

* https://github.com/Lenormju/getting-out-testing-hell
* https://gitlab.com/jgaffiot1/getting-out-testing-hell

Around 55 people attended, and we got great feedback.

### 09h30-12h45: Cooking with asyncio: an introduction to asynchronous programming

Rodrigo Girão Serrão

https://ep2026.europython.eu/session/cooking-with-asyncio-an-introduction-to-asynchronous-programming

I would have liked to attend this workshop, but couldn't.

* repo: https://github.com/mathspp/asyncio
* slides: https://asyncio.mathspp.com/intro.html

### 09h30-17h00: Packaging Summit

https://ep2026.europython.eu/session/packaging-summit

Would have loved to attend, but sadly couldn't.

Notes: https://hackmd.io/@jezdez/europython2026-packaging-summit

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

[slides (direct download link)](https://programme.europython.eu/media/europython-2026/submissions/M8Q77Z/resources/Should_you_jbXzWD1.pdf)

[slides on SpeakerDeck](https://speakerdeck.com/kytta/should-you-trust-trusted-publishing)

https://blog.yossarian.net/2026/07/07/You-shouldnt-trust-trusted-publishing

GhostAction + ShaiHulud + LiteLLM supply-chain attacks

OIDC = OpenID Connect, based on OAuth 2.0

humans don't need to manage secrets, they configure their accounts and let servers handle the rest

PyPI trusted publishers: GitHub, GitLab, Google Cloud, ActiveState

https://pypi.org/project/gcp-attest/

### 11h40-12h10 Talk: The Human-in-the-Loop is Tired

Laura Summers

https://ep2026.europython.eu/session/the-human-in-the-loop-is-tired

Could not attend, the room was too crowded.

https://summerscope.github.io/slides/the-human-in-the-loop-is-tired-pl/

### 11h40-12h10 Talk: Property based testing with Hypothesis

Freya Bruhin

https://ep2026.europython.eu/session/property-based-testing-with-hypothesis

Good intro to Hypothesis, and which specific problems it tries to solve.

https://github.com/the-compiler/hypothesis-talk

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

https://ep2026.europython.eu/session/security-and-ethics-in-the-age-of-generative-ai

### 13h50-14h20 Talk: Why doing difficult things is good for you and good for your team

Katie Bickford

https://ep2026.europython.eu/session/why-doing-difficult-things-is-good-for-you-and-good-for-your-team

Could not attend, may be worth a replay.

### 14h30-15h00 Talk: Beyond `Optional` in Real-World Projects: Missing, `None`, and Unset

Koudai Aono

https://ep2026.europython.eu/session/beyond-optional-in-real-world-projects-missing-none-and-unset

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

https://github.com/jstriebel/which-profiler

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

### 16h45-17h30 Keynote podcast: Core.py recording with Guido van Rossum

Pablo Galindo Salgado, Guido van Rossum, Łukasz Langa

`perchance` keyword

### 17h30-17h40 Announcement: EuroPython 25th anniversary

### 17h40-17h55: Python Quiz

In Python2, what does the following cursed code output?

```
print`3<3`[~3]
```

1. `'a'`
2. `25`
3. `True`
4. `SyntaxError`

<details>
    <summary>Answer</summary>
    a
</details>

### 17h55-18h40: Lightning talks

* rafting and hackathon: HALT (Hungry, Angry, Lonely, Tired), so bring chocolate
* Marimo is a better jupyter notebook
* rant about how long it would take (5 years) for Python to deprecate the IPv6 reserved address, from a RFC published 21 years ago, which make the would-be contributor give up, like so many others
* ariadne is a library to implemnt GraphQL server, the lightning talk was about how to optimize (reduce queries number) when using SQLAlchemy as a backend
* App to catalog the elogical data from the UK national history museum gardens
* The "boy scout rules" applied to codebase, and how to write better plugins using https://betterpy.dev/

## Thursday 2026-07-16: Talks

### 09h20-10h05 Keynote: The Pursuit Of Purity (The Right Way To Do AI)

Marlene Mhangami

https://ep2026.europython.eu/session/the-pursuit-of-purity-the-right-way-to-do-ai

https://github.com/marlenezw/europython26

> I keep struggling to find ways to try them the right way, the way that people I know and otherwise respect claim to be using them.  — Glyph Lefkowitz, “I think I’m done thinking about genAI for now” (2025)

Nothing new to me, just a light overview of the AI tooling ecosystem, without any details. And all their demos failed.

### 10h05-10h30 Announcement: Python Steering Council Update

### 10h50-11h35 Talk: The Hidden Cost of Complexity: Reducing Cognitive Load in Python

Jarosław Śmietanka

https://ep2026.europython.eu/session/the-hidden-cost-of-complexity-reducing-cognitive-load-in-python

https://github.com/exploy/cognitive-load-europython-2026

### 10h50-11h35 Talk: Navigating waters of background jobs and queues in Python as of 2026

Sebastian Buczyński

https://ep2026.europython.eu/session/navigating-waters-of-background-jobs-and-queues-in-python-as-of-2026

Look into Dramatiq. Also, Temporal is a good fit for complex workflows.
Shared to Ludo.

TODO slides

Pick your battles when making architecture decisions:
* simplicity
* developer experience
* async support
* observability
* AI skills

### 10h50-11h35 Talk: From one to 1 million packet/second: scaling global Internet monitoring

Marco Grossi

https://ep2026.europython.eu/session/from-one-to-1-million-packet-second-scaling-global-internet-monitoring

Well worth a replay !

### 11h45-12h15 Talk: Deploying Python Web Apps in 2026

Will Vincent

https://ep2026.europython.eu/session/deploying-python-web-apps-in-2026

### How we write unit test in my team in Openchip

Jan Koprowski

https://ep2026.europython.eu/session/how-we-write-unit-test-in-my-team-in-openchip

https://github.com/jankoprowski/ep2026

Did not attend. Slides are in pptx.

## 12h25-12h55 Talk: Django’s Magic, FastAPI’s Reality: Test Isolation at Scale

Maciej Sobczak

https://ep2026.europython.eu/session/djangos-magic-fastapis-reality-test-isolation-at-scale

Won't attend, but worth a replay.

## 12h25-12h55 Talk: Stop firefighting: practical observability for Python APIs, workers & jobs

Daria Korsakova

https://ep2026.europython.eu/session/stop-firefighting-practical-observability-for-python-apis-workers-jobs

https://medium.com/manychat-engineering/practical-observability-checklist-for-apis-workers-jobs-part-1-c9c18ffc23d5

https://medium.com/manychat-engineering/practical-observability-checklist-for-apis-workers-jobs-part-2-d07553ee80f1

[slides](https://dariakors.github.io/talks/europython-2026-stop-firefighting-practical-observability/)

what does observable mean?
* is it up?
* is it **ready**?
* is it doing useful work?
* is it failing?
* is it slow?
* what changed recently?
* Which dependency, workload, customer, job, event, ... is processed?

## 12h25-12h55 Talk: Immutability: Fast and Safe sharing of Data across Subinterpreters

Fridtjof Stoldt, Tobias Wrigstad

https://ep2026.europython.eu/session/immutability-fast-and-safe-sharing-of-data-across-subinterpreters

Seems interestinng but very situational.

## 13h05-13h35 Talk: Python Dicts: Past, Present, and Free-Threaded Future

Lysandros Nikolaou

https://ep2026.europython.eu/session/python-dicts-past-present-and-free-threaded-future

Very technical, about how to make them thread-safe without the GIL enforcing linearity, and still performant.

### 13h15-14h15 Poster: Python Syntax Diagram

Petr Viktorin

https://ep2026.europython.eu/session/python-syntax-diagram

Very well done!

### 14h30-15h00 Talk: Anatomy of a Phishing Campaign

Mike Fiedler

https://ep2026.europython.eu/session/anatomy-of-a-phishing-campaign

Already seen [the PyCon US version (that is very similar)](https://www.youtube.com/watch?v=uXW1qeUS6Yw), but worth a replay.

### 14h30-15h00 Talk: Leverage pytest's Fixture to write focused and highly decoupled tests

Antonio Spadaro

https://ep2026.europython.eu/session/leverage-pytest-s-fixture-to-write-focused-and-highly-decoupled-tests

May be worth a replay.

https://ilovelinux.dev/ep26

### 14h30-15h00 Talk: What is this footgun called unittest.mock, and how to avoid misusing it

Claudiu Belu

https://ep2026.europython.eu/session/what-is-this-footgun-called-unittest-mock-and-how-to-avoid-misusing-it

May be worth a replay, specially for the OpenStack part.

### 14h30-16h30 Workshop: Leading Under Pressure

Tereza Iofciu

https://ep2026.europython.eu/session/leading-under-pressure

Mostly for Pyladies, not the general public, but was not announced as such.

### 16h00-16h30 Talk: Learning from the not-so-secret Python security "cabal"

Seth Michael Larson

https://ep2026.europython.eu/session/learning-from-the-not-so-secret-python-security-cabal

Worth a replay.

### 16h00-16h30 Talk: Binary Dependencies: Identifying the Hidden Packages We All Depend On

Vlad-Stefan Harbuz

https://ep2026.europython.eu/session/binary-dependencies-identifying-the-hidden-packages-we-all-depend-on

Very interesting!

talk adn replay: https://vlad.website/binary-dependencies-identifying-the-hidden-packages-we-all-depend-on/

article: https://vlad.website/how-binary-dependencies-work/

### 16h00-16h30 Talk: AI Slop to AI Gold: Building Codebases That Last

Dan Jones

https://ep2026.europython.eu/session/ai-slop-to-ai-gold-building-codebases-that-last

May be interesting to replay.

### 16h40-17h25: Keynote: How to Run 160 KM: Building Resilience When Things Feel Hard

Leah Wasser

https://ep2026.europython.eu/session/how-to-run-160-km-building-resilience-when-things-feel-hard

### 17h25-18h10: Lightning Talks

* TODO

### 19h00: Social event

## Friday 2026-07-17: Talks

### TODO

## Saturday 2026-07-18: Sprints

Skipped it to visit the city instead.

## Sunday 2026-06-19: Sprints

Already left, sorry.
