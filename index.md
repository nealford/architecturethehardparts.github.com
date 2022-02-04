---
layout: default
---

# Architecture: The Hard Parts

![Architecture: The Hard Parts cover]({{ site.url }}/images/cover.png)


## Architecture: The Hard Parts?

Why do authors write technical books about topics like software architecture? They write them when then have figured something out, a "best practice" that is general enough and has matured enough to tell the rest of the world. In fact, architects rely on the current (but always shifting) notion of "best practices" for guidance in solving tough problems.

_But what happens where there are no best practices?_ What if no one has ever solved this particular problem before? What if there are no good answers, just varying degrees of awfulness?


When you're a software developer, you build outstanding skills in searching online for solutions to your current problem. For example, if you need to figure out how to configure a particular tool in your environment, expert use of Google finds the answer. 

But that's not true for architects.

For architects, many problems present unique challenges because they conflate the exact environment and circumstances of your organization--what are the chances that someone has encountered exactly this scenario _and_ blogged it or posted it on Stack Overflow?

# Welcome to _Architecture: The Hard Parts_

When architects encounter novel problems (by the way, they're all novel when you become an architect), how do they make decisions if no "best practices" exist and no one has ever solved this problem before?

The real job of an architect is, when presented with a novel situation, how well can they delineate and understand the _tradeoffs_ on either side of the decision, so that the organization can make the best informed decision. 

That's what _Software Architecture: The Hard Parts_  does--start teaching architects how to make informed decisions about tough problems in architecture.

One tried and true way to become an experienced architect is...experience. However, we can accelerate that process a bit by providing two critical things: context and scenarios.

## Context
To understand something, you must have enough knowledge and vocabulary to contextualize it--it would be difficult to understand _snow_ if you didn't understand _precipitation_. To that end, the _Architecture: The Hard Parts_ book is organized in two parts: 

### Part 1: Pulling Things Apart…
To make decisions about architecture, you must understand architecture, particuarly how the pieces fit together. This part describes how architects define coupling in architecture, how to analyse architecture, and how to use that knowledge to pull the pieces apart, for architecture restructuring, migration, or disintegration. We talk about the issues in architecture that drive from monolithic architectures towards distributed systems, including data architecture.

#### Chapter 1: What Happens When There are no "Best Practices"?
#### Chapter 2: Discerning Coupling in Software Architecture
#### Chapter 3: Architectural Modularity
#### Chapter 4: Architectural Decomposition
#### Chapter 5: Component-based Decomposition Patterns
#### Chapter 6: Pulling Apart Operational Data
#### Chapter 7: Service Granularity

### Part 2: ...and Putting Them Back Together
Building distributed architectures is hard, yet many applications end up here because of differing degrees of architecture characteristics. The second part of _Architecture: The Hard Parts_ describes common strategies for granularity for microservices, communication, contract management, and a host of other difficult problems in architecture.

#### Chapter 8: Reuse Patterns
#### Chapter 9: Data Ownership and Distributed Transactions
#### Chapter 10: Distributed Data Access
#### Chapter 11: Managing Distributed Workflows
#### Chapter 12: Transactional Sagas
#### Chapter 13: Contracts
#### Chapter 14: Managing Analytical Data
#### Chapter 15: Build Your Own Trade-off Analysis

We don't provide silver bullets--rather, we inform readers on how to make informed decisions within different contexts. To that end...

## Sysops Squad Scenarios

<image src="{{ site.url }}/images/Sysops-Squad.png" align="left" style="padding: 2em;">

Interspersed within the context of <i>Software Architecture: The Hard Parts</i>, we have numerous  <i>scenarios</i>: case studies and exercises that present real-world scenarios, to help simulate similar problems in the wild. We have many different scenarios, highlighting both single tradeoffs and also complex, multi-dimensional tradeoffs. Architecture by its nature is abstract; thus, an entire book of purely abstract concepts would be difficult to read. In Chapter One, we introduce the Sysops Squad, a mythical group within a mythical company that has some serious architecture problems they need to address. As we cover architecture concepts in the abstract, we illustrate how the Sysops Squad architects, developers, database administrators, project managers, and others implement those concepts.

Each chapter starts and ends with a Sysops Squad scenario, and some chapters include intermediate decisions and trade-offs as well. The Sysops Squad allows us to answer specific questions about software architecture without trying to provide overly generic advice, which is useless in software architecture. Want to understand why? Read our book!


