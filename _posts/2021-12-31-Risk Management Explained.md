---
title: InfoSec Risk Management Explained
date: 2021-12-31
tags: [infosec, risk management]     # TAG names should always be lowercase
excerpt_separator: <!--more-->
---

> How Information Security Risk Management can practically and significantly improve the security posture of your organisation.
<!--more-->

## Introduction
The purpose of this article is to clearly describe how Information Security Risk Management can tangibly improve the security posture of your organisation while outlining some common pitfalls and mistakes.

## TL;DR
Risk Management provides methodologies to consistently measure an organisation’s exposure to threats and vulnerabilities. This allows that organisation to prioritise information security work based on the most pressing needs (i.e. the likelihood and proximity of a risk) and the benefits of those improvements (i.e. the impact).

However, the benefits of this approach will only be realised if the organisation properly embeds Risk Management frameworks and processes into its governance structures and strategic planning.

Lastly, Risk Management stops organisations from unnecessarily attempting to “secure all the things”, as security controls are only implemented when there is a risk present. The effort, cost and scope of controls will always be commensurate to their associated risk, resulting in less waste.  

## Risk Management vs Gap Analyses vs Maturity Models
In future posts, I might cover information security maturity models and gap analysis properly, but in this post, I’m only giving a brief overview.

### Maturity Models
InfoSec maturity models are useful tools to understand the current state of an organisation’s security posture, across many security controls or domains, by assigning a maturity measurement to each.

> **Note:** An Information Security Control is a measure taken to reduce an information security risk, such as breaches, theft or unauthorised access. An example of a control would be full disk encryption on an endpoint device to protect against unauthorised access. 

Below is an example of a maturity rating scale:

| **Maturity** | **Description** |
|-----------------------------|-----|
| Level 1 - **Initial** | The control and its processes are undocumented and unstructured, as there is a dependency on individual knowledge and efforts. Processes are not repeatable or scalable. |
| Level 2 - **Developing** | The control and its processes are mostly repeatable due to them being documented, but they are not properly embedded. |
|Level 3 - **Defined** | The control and its processes are completely documented, standardised and have maintenance support.
|Level 4 - **Managed** | The organisation periodically reviews the effectiveness of the control through data collection and analysis.
|Level 5 - **Optimising** | This control has continuous monitoring, review and improvement processes embedded in it. |  
 
Maturity models are particularly useful in demonstrating the security controls and domains that are lacking at an organisation. Due to maturity scales, organisations can imagine a basic roadmap to improve the security posture (i.e. document your processes and introduce continuous improvement).

Using some paid for and proprietary maturity models, organisations can gain insights into how they fare against their peers in the same country and industry. An example of this kind of model is Gartner's ITScore for Information Security.

Unfortunately, maturity models have their limitations:
 - Users may misinterpret the purpose and end goal of models as reaching the highest level on the scale. The mistake here is to consider an end goal at all while missing the mention of continuous improvement which requires ongoing review.
 - The maturity scales described in most maturity models lack real advice on how to improve the security of each control, outside general process improvement.

### Gap Analyses
InfoSec Gap Analyses are useful tools to understand the state of an organisation's security posture by measuring its compliance against a known standard.

An example of this could be a gap analysis against the management clauses and Annex A controls included in ISO 27001. Here an information security analyst would review an organisation's compliance against each requirement of the ISO 27001 standard. The output would be a percentage compliance rating, with a breakdown of security domains where the org did well or poorly.

Gap analyses are useful in demonstrating where an org needs work to improve its exposure to attack or mishandling of information.

However, these tools are generally just a snapshot of the current compliance posture of an organisation. Other than obtaining 100% compliance with the given standard, which won't take into account the context of the organisation, they don't provide any insight into how to improve information security.

## Risk Management Basics
The following section describes how Risk Management methodologies, when used correctly, can address the shortcomings of Maturity Models and Gap Analyses.

>"When Risk Management is implemented correctly it will include feedback loops at each stage of the framework, ensuring continuous improvement of the whole framework and the treatment of identified risks."

To accurately explain this, I'll first outline several key Risk Management concepts and terms:

| **Term** | **Description** |
|--|--|
| Threat | Any circumstance, event or actor with the potential to harm an organisation through unauthorised access, destruction, disclosure, modification of asset and/or denial of service. |
| Vulnerability | A weakness in an information system, process, internal control or implementation that could be exploited or triggered by a threat.|
|Likelihood | This is the probability that a risk will manifest through the exploitation of a vulnerability.
| Impact | Impact is the total damage an organisation would incur if a vulnerability were exploited by a threat (i.e. if a risk is manifested). | 
| Proximity | Certain risks may have a window of time during which they will occur. The proximity describes how immediate the exploitation of a given risk is. This is different to likelihood as a risk may be expected to manifest, but it may be known that this might not happen for several months. |

>**Note**: I'll write separate posts on Threat Modelling and Vulnerability Management, as each of these is a beast in its own right. 

~~~
Risk = Impact x Likelihood
~~~

Proximity does not increase the risk rating itself but does change the decisions around when that risk is addressed.

Threats & Vulnerabilities are the variables that make up the perceived risk (e.g. you receive threat intelligence that a ransomware actor is actively attacking your industry using a new vulnerability that you have not yet had the chance to patch)

## Risk Management Benefits
Often, when you're working in Information Security there are so many projects, reports, queries and incidents that you feel you have little time to think strategically or to properly implement a Risk Management framework.

However, if you take the time to implement and embed Risk Management practices you'll find you're able to improve your time management through consistent prioritisation. This should grant you some space to address your organisation's critical security threats and vulnerabilities, as you'll be able to justify the resource cost.

The following is a list of potential benefits if Risk Management is implemented and embedded correctly
- An exhaustive view of the security posture of your assets, through defined risk identification and registration methods
- A consistent and agreed method to describe and measure the criticality of each risk
- Using the above measurement provides you with a method to consistently prioritise your team’s work (i.e address the big, bad things first)
- After agreeing on the measurements and the prioritisation of treatment, stakeholders can agree on strategic and tactical treatment plans for each identified risk. This grants your team flexible roadmaps for the coming months/years and creates accountability in your organisation.
- When treatment plans are completed, their results are added to the existing mitigating controls of a given risk. This new mitigating control will reduce the overall risk and will result in a residual risk rating. This new rating is reviewed by stakeholders to agree whether it can be accepted or if further treatment is required. This process is continuous. 

## Risk Methodology & Process
To ensure your Risk Management framework continuously improves, it should take the form of a cycle with several feedback loops.

The following is an example of a risk management cycle

![Risk Lifecycle](/assets/img/imgs/risk_lifecycle.png){: width="700" height="400" }
_Risk Lifecycle_

#### 1. Identification 
Risks are identified flexibly, through several sources including
- Threat Intelligence
- Business Impact Assessments
- Formal Risk Assessments
- Maturity Modeling & Gap Analysis
- Vulnerability Management
- Incident & Change Management
- Responsible Disclosure

#### 2. Description 
Risks will be described using the following format
<br>
A. Context  - Assets, Threats, etc. <br>
B. Causes - Threats, Vulnerabilities and Weaknesses, including their Likelihood and Proximity <br>
C. Consequences - Impact <br>

This format will ensure that:
You have a clear, agreed and documented explanation of the risk
You have a documented justification for the chosen risk rating

#### 3. Initial Measurement 
Quantitative Ratings will be assigned to each Risk, covering impact & likelihood.

The following example could be used:
<br>
Impact score- 1 - 4: Going from Low to Very High <br>
Likelihood score - 1 - 4: Going from Low to Very High
<br>
>Separate Threat Ratings (with variables: source quality, specificity, veracity and proximity) can be considered here. <br>

~~~
Risk = Impact x Likelihood (+ Threat Rating)
~~~

![Risk Rating](/assets/img/imgs/risk_rating.png){: width="700" height="400" }
_Risk Rating_

The above example gives us a score between 1 and 16.

Ratings will provide us with a consistent way to prioritise our treatment plans.

#### 4. Description & Initial Rating Approval
Risk Descriptions & Ratings are shared with relevant stakeholders and are formally agreed upon.

#### 5. Treatment Plan Creation
To address the identified Risks, Treatment plans are created collaboratively with stakeholders.

#### 6. Treatment Plan Approval
Treatment plans are shared with relevant stakeholders and are formally agreed upon.

#### 7. Estimated Residual Risk Approval
The Treatment Plan will indicate a level of risk reduction and may include a residual risk that is not addressed in the Treatment Plan.

This residual risk will need to be approved, by an appropriate governing board or committee to confirm that the organisation is happy with the approach to address the identified risks and that they are happy to accept the residual risk.

#### 8. Treatment Plans Started & Progress Tracking
Once approvals have been sought, the treatment plan is passed to the already agreed implementer/owner to deliver.

Progress in line with agreed deadlines and deliverables is tracked and monitored.

#### 9. Reporting & Escalation
Security Reports of various levels and types are written in agreed schedules and are presented at appropriate governance boards and to key personnel.
Security Reports will include key metrics including:
- Significant changes in the threat landscape
- The number of new and current risks
- Progress trends for treatment plans
- Escalations where progress is delayed or there is a blocker/impediment in place
- Decisions & approvals for the appropriate governance board/personnel

#### 10. Milestones Reached in Treatment Plans
Significant progress or the complete delivery of treatment plans, in the form of newly delivered controls and capabilities will be added to the Existing Controls section of the organisation's Risk Register.
The risk rating of this given row of the register will also be appropriately reduced.
Appropriate stakeholders must agree on the reduction of the risk rating.

#### 11. Residual Risk Re-Review
Once a Treatment Plan is completely delivered, the residual risk should be re-reviewed and addressed where possible.
Appropriate stakeholders should confirm whether the residual risk can continue to be accepted or if it needs to be addressed in the short, medium or long term.
The process for approving these decisions is as above - Residual 

Risks should go through the same process recursively.

## Integration into Organisation's Governance Structures
The example risk process above ensures that appropriate management and stakeholders are included in risk decisions, however, you will need to ensure that management is engaged and are aware of the gravity of the decisions they make.

If senior management is not engaged this could mean that they believe the organisation's information security risks are not an existential threat or they don't fully understand the risks.

It is the information security team's job to ensure that management grasps each information security risk completely.  

**Does management want to throw money at the problem?**  Often, improvements to Information Security requires significant changes to an organisation's working practices and culture. This needs to be understood by management if applicable. 

Although money/funding is nice and can help a great many things.

## Strategic Risk Management
Individual risk assessments don't often give you the high-level information needed to strategically address an organisation's security shortfalls. This is because discrete risk assessments are often performed against individual processes, products, services, etc. (e.g. a DPIA performed for GDPR compliance).

Instead, I'd recommend you think about your organisation at a higher level. Consider the following and the potential information security risks associated with each:

- **The organisation's key assets** - What are the organisation's key processes, services, products and other assets? What are the corporate risks to these? And how does information security relate to these as corporate risks?
- **Key calendar events** - Are there any key events throughout the year that if negatively impacted would cost the organisation? If so how could these be negatively affected by security incidents?
- **Information Security Domains** - Similar to Gap Analyses and Maturity Models described above, it's recommended to measure the org's exposure to risk against a list of common InfoSec domains. The [Secure Controls Framework](https://www.securecontrolsframework.com/scf-domains "Secure Controls Framework") has a great list of domains to get started with. 

Using those three perspectives you should be able to identify your organisations most critical assets, events and how they may be exposed to security risk. 

This will give you a basic strategic skeleton which you can then build on through more data and context.

## Conclusion
If implemented and embedded correctly, Risk Management can save time, improve consistency, help to prioritise work and can foster accountability in your organisation.  

While a bit of work to get going, it is worth while investing in these methods.

If you have any questions or would like to know more about Information Security Risk Management, please to hesitate to get in touch [Email](mailto:info@example.com "Email me")