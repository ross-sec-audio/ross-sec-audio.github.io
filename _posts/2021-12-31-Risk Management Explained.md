---
title: InfoSec Risk Management Explained
date: 2021-12-31
tags: [infosec, risk management]     # TAG names should always be lowercase
---

## Introduction
The purpose of this article is to clearly describe how Information Security Risk Management can practically and significantly improve the security posture of your organisation. 

### TL;DR
Risk Management provides methodologies to consistently measure an organisation's exposure to threats and vulnerabilities, which allows that org to prioritise required improvements to information security based on pressing needs (i.e. the likelihood and proximity of a risk) and the benefits of those improvements (i.e. the impact). 

However, the benefits of this approach will only be realised if the organisation in question explicitly embeds the outputs of Risk Management into its strategic planning and is willing to iterate based on changes to variables therein. 

### Risk Management vs Gap Analyses vs Maturity Models
In future posts I might expand on the benefits and limitations of information security maturity models and gap analyses, but for this post's purpose's I'll give a brief overview

#### Maturity Models
InfoSec Maturity Models are useful tools to understand the current state of an organisation's security posture, across a number of security domains, by assigning a maturity measurement to given controls. 

Below is an example of a maturity rating range:

| **Maturity** | **Description** |
|--|--|
| Level 1 - **Initial** | The control and its processes are unorganized, and unstructured as there is a dependency on individual efforts. Processes are not documented, repeatable or scalable. |
| Level 2 - **Developing** | The control and its processes are mostly repeatable due to them being established, defined, and documented. |
|Level 3 - **Defined** | The control and its processes completely documented, standardised and have maintenance support.
|Level 4 - **Managed** | At this level, the organisation monitors this control through data collection and analysis.
|Level 5 - **Optimizing** | This control has continuous improvement embedded in its processes, through monitoring and feedback. |  
 
Maturity models are particularly useful in demonstrating the security domains where an organisation is lacking and through giving that organisation a basic roadmap to improve (i.e. document your processes and introduce continuous improvement).

Through some proprietary models, organisations can gain insights on how their org fairs against their peers in the same country, industry, etc. An example of this is Gartner's ITScore for Information Security.

Unfortunately Maturity Models have their limitations:
 - Users may interpret the models as a linear progression with a clear end goal (i.e. Level 5). The mistake here is to miss the mention of continuous improvement which requires on-going review.
 - The improvement paths described in most maturity models lack real advice on how to improve given controls outside process improvement.

#### Gap Analyses
InfoSec gap analyses are useful tools to understand the state of an organisation's security posture by measuring its compliance against a known standard.

An example of this could be a gap analysis against the causes and controls included in IEC/ISO 27001. Here an information security analyst would review an organisation's compliance against each requirement of the ISO 27001 standard. The output would be a percentage compliance rating with a breakdown of security domains where the org did well or poorly. 

Gay analyses' are useful in demonstrating where an org needs work to improve its exposure to breach or exploitation. 

### Risk Management in comparison
The following section will describe how using Risk Management methodologies correctly can address the shortcomings of Maturity Models and Gap Analyses. 

#### Risk Management Basics
To accurately describe the benefits of Risk Management, I'll first outline a number of key concepts and terms:

| **Term** | **Description** |
|--|--|
| Threat | Any circumstance, event or actor with the potential to harm an organisation through unauthorized access, destruction, disclosure, modification of product, data and/or denial of service. |
| Vulnerability | A weakness in an information system, process, internal control or implementation that could be exploited or triggered by a threat source.|
|Likelihood | This is the probability that a risk will manifest through exploitation of a vulnerability.
| Impact | Impact is the total damage the organisation would incur if a vulnerability were exploited by a threat. | 
| Proximity | Certain risks may have a window of time during which they will occur. The proximity describes how immediate the exploitation of a given risk is. This is different to likelihood as a risk may be understood to definitely manifest, but this it may be known that this might not happen for a number of months.|

#### Practical Measurement of Risk
Often, when you're working in Information Security there are so many projects, reports, queries and incidents that you have little time to properly implement risk management methodologies to improve your operating model.

Individual Risk Assessments don't often give you the high level strategic information to plan a year's work. This is because discrete risk assessments are often performed against new processes, products, services, etc. (e.g. a DPIA). 

Instead, I'd recommend you think about the organisation at a higher level and assess the risks of


- **The organisation's key assets** - What are the organisation's key processes, services, products and other assets? What are the corporate risks to these? And how does information security relate to these corporate risks?
- **Key calendar events** - Are there any key events throughout the year that if negatively impacted would cost the organisation? If so how could these be negatively affected?
- **Information Security Domains** - Similar to Gap Analyses and Maturity Models described above, it's recommended to measure the org's exposure to risk against a list of common InfoSec domains. The [Secure Controls Framework](https://www.securecontrolsframework.com/scf-domains "Secure Controls Framework") has a great list of domains to get started with.

### Risk Methodology

Asset identification (or event or domain)
Risk Description
Existing Controls
Risk Rating (consulted & approved)
	Impact, Likelihood, Proximity & VaR
Treatment Plan Design (consulted & approved)
Estimated Residual Risk after treatment plans (consulted and approved)
Delivery & Tracking of Treatment Plans
Review of risk reduction, residual risk - update to description, existing controls, rating and new treatment plans.

This can be used to consistently measure infosec risks and issues, which can then be used to prioritise their mitigation and remediation.

### Integration into Organsation Governance Structure

Senior Management aware?
Do they care? - if not then the risks are not an existential threat to the org OR management don't understand the risks. This may be related to how you are presenting these risks - see reporting below.
Are risks discussed by appropriate staff on a periodic basis? - if not you don't have a seat at the table...hmm.
Are strategic treatment plans designed and agreed upon, with ample funding and resourcing?  - if not then the risk committee could just be there for show.
Do management want to throw money at the problem? - often, improvements to infosec posture at an organisation requires significant changes to that org's working practices and culture. This needs to be understood by management if applicable. Although money is nice.

### Reporting

Does the org have a risk management policy, framework and group/committee?

Is infosec included in this? 
Are all strategic infosec risks considered here or is infosec considered one monolithic risk? - if so no problem but the treatment plan needs to be multifaceted. 

Are there robust governance structures in place?
	- changes and new things reviewed and approved with infosec in mind?
	- to ensure people are held responsible and accountable for their actions? 