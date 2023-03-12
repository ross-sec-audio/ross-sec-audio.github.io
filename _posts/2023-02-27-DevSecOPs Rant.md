---
title: A Rant about DevSecOps
date: 2023-02-27
tags: [infosec, vulnerabilities, assets, devops, devsecops]     # TAG names should always be lowercase
image:
  src: /assets/img/imgs/geo.png
  width: 1000   # in pixels
  height: 200   # in pixels
  alt: abstract banner
---

## Scene setting

Over the last few years, I’ve witnessed many organisations express pretty negative views and misplaced ideas about DevOps and Agile, while sometimes using them as excuses to sidestep process gates and governance.

In response, I've often tried to explain the benefits and specific uses of DevOps and Agile practices and attempted to correct those who abuse DevOps and Agile terms to avoid other good practices. Sometimes I've been able to help, and sometimes it fell on deaf ears.

This short blog is me continuing to try to help. It's about how the InfoSec community often misunderstands the underlying principles and premises of DevOps, Agile and subsequently DevSecOps.

## Lovely intentions

The InfoSec community are mostly a lovely bunch. Good craic like. But I think we've got a problem with pushing solutions that provide little value to the organisations we work with.

Some good examples of this include the lengthy and somewhat useless third-party/supplier assessment questionnaires that are often required for Third Party Risk Management programmes, or the out-of-date and draconian compliance requirements of certain prescriptive security standards (…PCI-DSS *cough* 👀).

I think the InfoSec community have a similar issue with DevSecOps.

When I first heard about DevSecOps, the term thrown about was "Shift Left". This term actually means quite a lot in DevOps, but in the context of the conversations I was having, it was about setting up automated Static Analysis Security Testing (SAST) and Dynamic Analysis Security Testing (DAST) in development and delivery pipelines, so vulnerability identification happens early on in that lifecycle.

>For more info on Vulnerability & Security Testing see this other blog I've written.
[Vulnerability Management in 4 Stages](https://ross-sec-audio.github.io/posts/Vulnerability-Management-in-4-Stages/ "Vulnerability Management in 4 Stages")

And that was basically it. DevSecOps = Don't rely on Penetration Tests to find exploitable vulnerabilities at the last minute before a release.

![DevSecOps](/assets/img/imgs/devsecops.jpg){: w="400" h="400" }
_Nope_

When I later went on to learn the principles of DevOps through the Phoenix Project, the DevOps Handbook, I was a bit shocked. The three ways and other principles were lost to most implementations and understandings of DevSecOps (At least in my own anecdotal experience).

If you search the term DevSecOps today, you'll be presented with hundreds of sites and blogs, all explaining it at a high level. But only a tiny wee proportion of these discuss anything other than shifting left through automated / early security testing and the adoption of DevSecOps tools.

We as an industry I think we've been pushing this kind of tool based DevSecOps, while missing some important parts of the story.

## Principles, AND technology

I believe that this is because many of us have overlooked the original drivers for the creation of Agile and DevOps practices.

Agile ways of working were primarily a response to the challenges of infrequent and complex code deployments, along with the difficulty of estimating effort in Software Development work in general, due to inherent unknowns and complexities.

DevOps practices were a response to Development and Operations teams commonly not being able to or willing to work well together.

The result of the latter was not a list of new technologies, although that did come later to better serve newly adopted principles. Instead, DevOps proposed ways for these two teams to work together effectively.

Reductively put, this boiled down to the "3 Ways":

 - Maintain flow in systems.
 - Amplify feedback loops.
 - Promote continuous improvement through learning and experimentation.

When I dove into these tenants, I found lots of other fun ideas, such as:
 - Limiting work in progress (this should be thought to babies)
 - The theory of constraints
 - Identifying the four types of work and handling each accordingly
 - Getting incident management right
 - Getting asset management right
 - Getting change management right

Those last two make me chuckle...Then I find myself rubbing my temples in despair.

All these principles and practices were developed to help Dev and Ops teams play nice. They've each assisted me as an InfoSec defender to work in more helpful ways with other teams. This is key to successfully protecting an organisation. For example, if you find a scary vulnerability in a product or component, at the end of the day you’ve got to convince the maintainer of that asset to prioritise fixing the vulnerability. Tools for mutual and amicable collaboration don’t just help get the job done, but they also promote a friendly working environment.

So many InfoSec teams I see today, across a lot of different industries, cannot play nice with other teams. Lots have implemented automated SAST, SCA, DAST and IAST into pipelines, but as soon as the long list of findings appears, all too often, that team turns into the “You must fix this vulnerability by this deadline" team. Sigh.

We've missed the point.

