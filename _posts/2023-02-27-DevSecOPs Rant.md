---
title: A Rant about DevSecOps
date: 2022-06-07
tags: [infosec, vulnerabilities, assets]     # TAG names should always be lowercase
image:
  src: /assets/img/imgs/apple.jpg
  width: 1000   # in pixels
  height: 200   # in pixels
  alt: abstract banner
---

## The Rant Begins

Over the last few years, I've seen many people and organisations with the wrong idea about DevOps and Agile, using them as excuses to sidestep process gates and governance. In response, I've often tried to explain the benefits and specific uses of DevOps and Agile practices, and attempted to correct those who abuse DevOps and Agile terms to avoid other good practices, such as ITIL. Sometimes I've been able to help, and sometimes it fell on deaf ears.

## Lovely Intentions

The InfoSec community are mostly a lovely bunch. We know this. But I think we've got a problem with pushing solutions that provide little value to the organisations we work with.

Examples of this include the lengthy and somewhat useless Supplier Assessment Questionnaires that are often required for Third Party Risk Management programmes, or the out-of-date and draconian compliance requirements of certain prescriptive security standards.

I think the InfoSec community have a similar issue with DevSecOps.

When I first heard about DevSecOps, the term thrown about was "Shift Left". This term actually means quite a lot in DevOps, but in the context of the conversations I have having, it was to set up automated Static Analysis Security Testing (SAST) and Dynamic Analysis Security Testing (DAST) in development and delivery pipelines, so vulnerabilities are identified early on.

>For more info on Vulnerability & Security Testing see this other blog I've written on it.
[Vulnerability Mangaement in 4 Stages](https://ross-sec-audio.github.io/posts/Vulnerability-Management-in-4-Stages/ "Vulnerability Mangaement in 4 Stages")

And that was basically it. DevSecOps = Don't rely on Penetration Tests to find exploitable vulnerabilities at the last minute before a release.

![DevSecOps](/assets/img/imgs/devsecops.jpg){: w="400" h="400" }
_Nope_

When I later went on to learn the principles of DevOps through the Pheonix Project, the DevOps Handbook and lots of other material, I was a bit shocked. The three ways and other principles were lost to most implementations and understandings of DevSecOps (At least in my own anecdotal experience).

If you search the term DevSecOps today, you'll be presented with hundreds of sites and blogs, all explaining it at a high level. But only a tiny wee proportion of these discuss anything other than shiting left through automated / early security testing and the adoption of DevSecOps tools.

## Principles, not technology

I believe that many of us have overlooked the original drivers for the creation of Agile and DevOps practices.

Agile ways of working were primarily a response to the difficulty in estimating effort in Software Development work, due to inherent unknowns and complexities.

DevOps practices were a response to Development and Operations teams commonly not being able to or willing to work well together.

The result of the latter was not a list of new technologies, although that did come later to better serve newly adopted principles. Instead, DevOps proposed ways for these two teams to work together.

Reductively put, this boiled down to the 3 Ways:

 - Maintain flow in systems
 - Amplify feedback loops.
 - Promote continuous improvement through learning and experimentation.

When I dove into these tenents, I found lots of other underlying ideas, such as:

 - Limiting work in progress
 - The theory of constraints
 - Determining the four types of work
 - Getting asset management right and
 - Getting change management right

Those last two make me chuckle...Then I find myself rubbing my temples in despair.

Anyway, all the above was put in place to help Dev and Ops teams play nice. They've each helped me as an infosec person work in more helpful ways with other teams.

So many InfoSec teams I see today, across a lot of different industries, cannot play nice with anyone. Lots have implemented automated SAST, SCA, DAST and IAST into pipelines, but as soon as the long list of findings appears, all too often, that team turns into the "Fix our problem first" team. Sigh.

We've missed the point.