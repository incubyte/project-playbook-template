| **Call**                                                              | **Participants**                                                                     | **Duration**  | **Frequency**                                                                                            |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------- | -------------------------------------------------------------------------------------------------------- |
| [3 Amigos](#three-amigos)                                             | BA, QA, Developer pair                                                               | 15-30 minutes | At least once for each PBI                                                                               |
| [Mob review / programming](#mob-review-or-programming)                | All project developers, Technical Advisor                                            | 30-60 minutes | Bi-weekly                                                                                                |
| [Architecture feed forward](#architecture-feed-forward)               | All project developers, Technical Advisor, Sapan                                     | 30-60 minutes | Bi-weekly                                                                                                |
| [RCA and CAPA](#rca-and-capa)                                         | Cross functional team, Technical Advisor                                             | 30-60 minutes | Bi-weekly (can change based on amount of production issues)                                              |

## Three Amigos

[3 amigos](https://www.agilealliance.org/glossary/three-amigos) a.k.a Story Kick Off huddles refers to the primary perspectives to examine an increment of work before, during, and after development. Those perspectives are:

-   Business – What problem are we trying to solve?
-   Development – How might we build a solution to solve that problem?
-   Testing – What about this, what could possibly happen?

People holding these different perspectives should collaborate to define what to do, and agree on how they know when it is done correctly.

**After the call everyone must have clear understanding of what the definition of done looks like.**

## Mob review or programming

[Mob programming](http://www.mobprogrammingguidebook.com/images/mobprogrammingguidebook.pdf) (sometimes informally called mobbing or ensemble programming) is a software development approach where the whole team works on the same thing, at the same time, in the same space, and at the same computer.

[Mob review](https://speakerdeck.com/jjanvier/mob-review-at-akeneo) is similar to mob programming but for reviews. Ideally, if mob programming is done then the mob reviews are not needed. Mob reviews are good for reviewing code that affects multiple cross-functional teams to get rapid feedback and share information.

## Architecture feed forward

**_This call is useful if the team is a bit larger_**

Discuss the big picture of the planned architecture, discuss design approach for any upcoming stories that affects architecture, includes any new component in the architecture, find solutions to current architectural concerns, discuss trade-offs, take concrete action items to implement and ultimately create [ADR](https://adr.github.io/)s of the decisions for future reference.

## RCA and CAPA🔬

The goal of Root Cause Analysis (RCA) is to find root of the issue by asking "Whys" and RCA feeds in to the Corrective Action and Preventive Action (CAPA) process.

CAPA represents what will be done to address it and prevent it from happening again.

-   The Corrective Action is designed to correct an immediate problem.
-   The Preventive Action is designed to prevent the problem’s reoccurrence.
    -   Prevent by design
    -   Prevent by static code analysis, tests, or some other form of automation

### Recommended CAPA template should have

-   Issue No
-   Issue description
-   Status
    -   Corrective pending
    -   RCA pending
    -   Preventive pending
    -   Done
-   2-3 Whys. Understand using [5-whys](https://kanbanize.com/lean-management/improvement/5-whys-analysis-tool)
-   Why was it not caught in QA
-   Corrective action
-   Preventive action