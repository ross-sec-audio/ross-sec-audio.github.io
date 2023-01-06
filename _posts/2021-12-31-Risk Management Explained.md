---
title: InfoSec Risk Management - Benefits & Common Pitfalls
date: 2021-12-31
tags: [infosec, risk management]     # TAG names should always be lowercase
excerpt_separator: <!--more-->
image:
  src: /assets/img/imgs/banner2.jpg
  width: 1000   # in pixels
  height: 400   # in pixels
  alt: abstract banner
---

>How Information Security (InfoSec) Risk Management can practically improve the security posture of your organisation if implemented correctly.
<!--more-->

## Introduction
The purpose of this article is to clearly describe how InfoSec Risk Management can tangibly improve the security posture of your organisation while outlining some common pitfalls and mistakes.

## TL;DR
Risk Management provides methodologies to consistently measure your organisation’s exposure to threats and vulnerabilities. This allows your organisation to prioritise your InfoSec projects based on urgency and their potential benefits. This allows InfoSec teams to create adaptive and informed strategic roadmaps for the coming months or years.

However, the benefits of this approach will only be realised
1. If your organisation properly embeds Risk Management frameworks and processes into its governance structures and strategic planning
2. If your organisation ensures that each step of your Risk Management processes include self-reflective feedback loops

Risk Management stops organisations from unnecessarily attempting to “secure all the things”, as security controls are only implemented when there is a risk present. The effort, cost and scope of controls will always be commensurate to their associated risk, resulting in less waste.  

## Risk Management vs Gap Analyses vs Maturity Models
Risk Management is only one method of developing an InfoSec strategy. There are many ways to strategise but performing gap analyses against InfoSec standards and modelling your InfoSec maturity are both common to this industry. 

In future posts, I might cover InfoSec maturity models and gap analysis properly, but in this post, I’m only giving a brief overview.

### Maturity Models
InfoSec maturity models are useful tools to understand the current state of an organisation’s security posture, across many security controls or domains, by assigning a maturity measurement to each.

> **Note:** An Information Security Control is a measure taken to reduce an information security risk, such as breaches, theft or unauthorised access. An example of a control would be full disk encryption on an endpoint device to protect against unauthorised access. 
{: .prompt-tip } 

Below is an example of a maturity rating scale:

| **Maturity** | **Description** |
|-----------------------------|-----|
| Level 1 - **Initial** | Undocumented. Dependency on individual knowledge and efforts. Not repeatable or scalable. |
| Level 2 - **Developing** | Mostly repeatable due to documentation, but not properly embedded. |
| Level 3 - **Defined** | Completely documented, standardised and has maintenance support. |
| Level 4 - **Managed** | Periodically reviews the effectiveness in place, through data collection and analysis. |
| Level 5 - **Optimising** | Continuous monitoring, review and improvement processes are embedded. |  
 
Maturity models are particularly useful in demonstrating the security controls and domains that are lacking in an organisation. 

Unfortunately, maturity models have their limitations:
 - You might think the purpose of models is to reach the highest level on the maturity scale. This assumes that improvement is linear and doesn't need to include continuous improvement 
 - The scales described in most maturity models lack real advice on how to improve the security of each control, outside general process improvement. They're not context-driven.

### Gap Analyses
InfoSec Gap Analyses are useful tools to understand the state of an organisation's security posture by measuring its compliance against a known standard.

An example of this would be to review the management clauses and Annex A controls included in ISO 27001 and check where your organisation is compliant. The output would be a percentage compliance rating, with a breakdown of security domains where the org did well or poorly.

These tools are a snapshot of the current compliance posture of an organisation. So, other than obtaining 100% compliance with the given standard, which won't take into account the context of the organisation, they don't provide any insight into how to continually improve information security.

## Risk Management Basics
The following section describes how Risk Management methodologies can address the shortcomings of Maturity Models and Gap Analyses.

>When Risk Management is implemented correctly it will include feedback loops at each stage of the framework, ensuring continuous improvement of the whole framework and the treatment of identified risks.
>
>When implemented incorrectly Risk Management won't provide accurate insights and will be mostly ignored by management. 

To accurately explain this, I'll first outline several key Risk Management concepts and terms:

| **Term** | **Description** |
|--|--|
| Threat | Any circumstance, event or actor with the potential to harm your organisation through unauthorised access, destruction, disclosure, modification of assets and/or denial of service. |
| Vulnerability | A weakness in an information system, process, internal control or implementation that could be exploited or triggered by a threat.|
|Likelihood | This is the probability that a risk will manifest through the exploitation of a vulnerability.
| Impact | Impact is the total damage your organisation would incur if a vulnerability were exploited by a threat. | 
| Proximity | Certain risks may have a window of time when they are expected to occur. The proximity describes how immediate the exploitation of a given risk is. This is different to likelihood as a risk may be expected to manifest, but it may be known that this might not happen for several months. |

Proximity does not increase the risk rating itself but does change the decisions around when that risk is addressed.

Threats & Vulnerabilities are the variables that make up the perceived risk (e.g. you receive threat intelligence that a ransomware actor is actively attacking your industry using a new vulnerability that you have not yet had the chance to patch)

>**Note**: I'll write separate posts on Threat Modelling and Vulnerability Management, as each of these is a beast in its own right. 

### Risk Measurement Formula
~~~
Risk = Impact x Likelihood
~~~

## Risk Management Benefits
Often, when you're working in InfoSec there are so many projects, reports, queries and incidents that you may feel you have little time to think strategically or to properly implement a Risk Management framework.

However, if you take the time to embed Risk Management practices you'll probably find you're able to improve your time management through the consistent prioritisation it delivers. 

A simple working example of this would be Organisation A, which has identified approximately 30 significant and strategic InfoSec risks. Of these 30, 5 have scored "Very High" in Likelihood and "Very High" in Impact. This score has been given due to an understanding of the probability of this risk manifesting and the negative consequences of its occurrence. Because of this understanding, you can prioritise the remediation of these 5 risks. If you are questioned about this, you already have a justification documented.

This should grant you some space to address your organisation's critical security threats and vulnerabilities, and you'll be able to justify the resource cost.

The following is a list of potential benefits if Risk Management is implemented and embedded correctly:
- An exhaustive view of the security posture of your assets, through defined risk identification and registration methods
- A consistent and agreed method to describe and measure the criticality of each risk
- Using the above measurement provides you with a method to consistently prioritise your team’s work
- After agreeing on the measurements and the prioritisation of treatment, stakeholders can agree on strategic and tactical treatment plans for each identified risk. This grants your team flexible roadmaps for the coming months/years and creates accountability in your organisation through those commitments to security.
- When treatment plans are completed, their results are added to the existing mitigating controls of a given risk. This new mitigating control will reduce the overall risk rating and will result in a residual risk rating. This new rating is reviewed by stakeholders to agree on whether it can be accepted (i.e. ignored) or if further treatment is required. This process is continuous. 

## Risk Methodology & Process
The following section gives an example of a recursive risk management process. The feedback loops included help to ensure your InfoSec posture continually improves. It also ensures that the process itself is under constant review and improvement through iteration.

This example includes 11 steps (plus a bonus 12th step), but you could have as many or as few steps as you want.

![Risk Lifecycle](/assets/img/imgs/Risk_Lifecycle.jpg)
_Example Risk Lifecycle_

#### 1. Identification 
Risks can be identified through many sources including but not limited to:
- Threat Intelligence Gathering and Review
- Business Impact Assessments
- Formal Risk Assessments
- Maturity Modelling & Gap Analyses
- Vulnerability Management
- Incident & Change Management
- Responsible Disclosure from external & internal parties

Identifying InfoSec risk is both a simple and complicated process. You may be able to automatically identify many significant risks off the top of your head, but how can you be sure you've not missed anything?

There are several ways you can reduce the operational risk of leaving some InfoSec risks unidentified. These can include
1. With a list of business-critical assets, perform a triage InfoSec survey on each. The survey could include questions about how these assets are developed, tested, hosted, patched, used, maintained, decommissioned, etc. 
2. Consider your organisation's calendar. Are there any dates, periods or events that are critical to the running of the organisation? Can you now think of any InfoSec risks that would negatively affect these dates?
3. Review your company's posture against a list of InfoSec domains (e.g [Secure Control Framework's List of Security Domains](https://www.securecontrolsframework.com/scf-domains "Secure Control Framework's List of Security Domains")) and then through understanding your gaps in these areas you can identify risks relating to each.
    - Yes, this is essentially a gap analysis with the results converted into risks.

#### 2. Description 
These identified risks then need to be described consistently. The following format is an example of a consistent description method.
<br>

1. Where relevant, briefly describe the risks and affected asset's context  
    - If the affected asset is a website, where is it hosted? How is it accessed? etc.
2. Briefly describe the causes of this risk
    - This would include the threats and vulnerabilities, including their Likelihood and Proximity
3. Briefly describe the consequences of this risk manifesting
    - What would the operational, financial, legal and reputational impact on the organisation be?

This format will ensure that: <br>
You have a clear, agreed and documented explanation of the risk. <br>
You have a documented justification for the chosen risk rating.

When risks are not adequately or consistently described it can be very difficult to understand their subsequent quantitative risk rating. This is a common issue resulting in a more subjective view of risk severity.

#### 3. Initial Measurement 
Using the consistent descriptions above, you'll then need to assign quantitative ratings to each risk.

The example ratings below could be used, but there are pros and cons to using less and more complex rating systems. The following ratings are easy to use but can be considered overly simple when trying to measure the severity differences of two or more similar risks. 
<br>

- **Impact** - scoring from 1 to 4 (Low to Very High) <br>
- **Likelihood** - scoring from 1 to 4 (Low to Very High)
<br>

> Separate Threat Ratings with the variables "source quality", "specificity", "veracity" and "proximity" can be considered here also. <br>

~~~
Risk = Impact x Likelihood (+ Threat Rating if applicable)
~~~

![Risk Rating](/assets/img/imgs/risk_rating.JPG){: width="470" height="600" }
_Example Risk Rating Matrix_

The above example gives us a rating between 1 and 16 with 16 being the most severe.

Ratings will provide us with a consistent measurement to prioritise our risks and treatment plans.

#### 4. Description & Initial Rating Approval
Once you have described and measured your risks, they will need to be shared with relevant stakeholders in your organisation for consultation and to ensure that are formally agreed upon.

This and each of the other approval steps below are governance measures that should foster accountability in your organisation. 

When agreements on risk severity are agreed upon and documented, your organisation will only be able to accept these, without remediation, in good faith. 

#### 5. Treatment Plan Creation
Once everyone has agreed on the risk and its severity, what do you do with it?

Risks can be treated in several ways. These can be categorised into:
- Termination - Risks and their sources are completely removed or avoided
- Action - Risks are reduced, mitigated and/or contained through the implementation of controls.
- Transfer - Risks are shared with another party (i.e. Insurance)
- Acceptance - Risks are accepted as falling within the organisation's risk appetite and subsequently don't require remediation. 

If a risk is described and measured adequately it is much more likely that an organisation will choose the appropriate treatment option. 

Treatment plans are the names of projects that action, transfer or terminate a risk. These should have owners and where appropriate they should have project managers.

These should be designed collaboratively with stakeholders, who may have a greater contextual understanding of the affected assets.

#### 6. Treatment Plan Approval
Treatment plans are shared with relevant stakeholders and are formally agreed upon.

Once you have designed treatment plans for your identified risks, they will need to be formally agreed upon.

Like before, this approval step should foster accountability in your organisation. 

#### 7. Estimated Residual Risk Approval
Treatment plan designs should be indicative of a reduction in risk. This estimated reduction should be identified and agreed upon. This may result in a residual risk that is not addressed by a treatment plan.

This residual risk will need to be approved, by an appropriate governing board or committee to confirm that the organisation is happy with the plans and that they are happy to accept the residual risk going forward.

#### 8. Treatment Plans Started & Progress Tracking
Once the above approvals have been obtained, plans should be passed to their owner for delivery.

Implementation of a treatment plan may not start immediately as it may be put into a team's backlog, depending on the severity. 

The progress of treatment plans, their agreed deadlines and individual deliverables should be tracked, monitored and periodically reviewed. It is recommended that the InfoSec team and treatment plan owners meet periodically to discuss progress, blockers and impediments.

#### 9. Reporting & Escalation
Security Reports of various levels and types should be written in agreed schedules and presented at appropriate governance boards and to key personnel.

Security Reports will include key metrics including:
- Significant changes in the threat landscape
- The number of new and current risks
- Progress trends for treatment plans
- Escalations where progress is delayed or there is a blocker/impediment in place
- Decisions & approvals for the appropriate governance board/personnel

This step should foster accountability in your organisation. Without it, treatment plans could be deprioritised without approval or oversight.

#### 10. Milestones Reached in Treatment Plans
When significant progress is made or a treatment plan is completely implemented, a description of these new InfoSec controls should be added to the Existing Controls column of the organisation's Risk Register, for the relevant risk.

These new existing mitigating controls should reduce the risk rating.

Appropriate stakeholders should formally agree on the reduction of this risk rating to ensure everyone is on the same page about the significance of the progress made and the severity of the remaining risk.

#### 11. Residual Risk Re-Review
Once a treatment plan is completely delivered and if there is any residual risk, this should be re-reviewed.

Appropriate stakeholders should confirm whether the residual risk can continue to be accepted or if it needs to be addressed and treated in another way. 

If it's agreed that the residual risk can be accepted, stakeholders also need to confirm whether this acceptance is perpetual or if it's a short term acceptance until another solution becomes available.

#### 12. Bonus 12th Step
Throughout this whole process, if the state of relevant threats, vulnerabilities and assets changes then the risk descriptions, ratings and treatment plans may need to be updated accordingly. 

This could also change the priority of your risks and hence change the order of your treatment plans.

Risk registers should not be a piece of shelf-ware that is filled out once and then only checked and updated once every quarter/year/never. They need to be continually updated and reviewed to be useful. 

## Integration into Organisation's Governance Structures
The example risk process above ensures that relevant stakeholders are included in risk decisions, however, you will need to ensure that management is engaged and aware of the gravity of the decisions they make.

If management is not engaged this could mean that they believe your organisation's InfoSec risks are not an existential threat or it could mean that they don't fully understand the risks.

It is the information security team's job to ensure that management grasps each InfoSec risk completely.  

That said, your management team may have a higher tolerance or appetite for risk than you. This is fairly normal but shouldn't stop you from expressing your own measured and justified concerns. 

## Strategic Risk Management
Individual risk assessments don't often give you the high-level information needed to strategically address an organisation's security shortfalls. This is because discrete risk assessments are often performed against individual processes, products, services, etc. An example of this would be a Data Protection Impact Assessment (DPIA) performed on a new organisational process to ensure continued compliance with GDPR (or the Data Protection Act 2018 here in the UK).

Instead, I'd recommend you think about your organisation at a higher level. Consider the following and the potential information security risks associated with each:

- **The organisation's key assets** - What are the organisation's key processes, services, products and other assets? What are the corporate risks to these? And how does information security relate to these as corporate risks?
- **Key calendar events** - Are there any key events throughout the year that if negatively impacted would cost the organisation? If so how could these be negatively affected by security incidents?
- **Information Security Domains** - Similar to Gap Analyses and Maturity Models described above, it's recommended to measure the organisation's exposure to risk against a list of common InfoSec domains. The [Secure Controls Framework](https://www.securecontrolsframework.com/scf-domains "Secure Controls Framework") has a great list of domains to get started with. 

These are just three of many perspectives you could use to help you identify your organisation's most critical assets, and events and how they may be exposed to InfoSec risks. 

Using perspectives like those above can give you a basic strategic skeleton, which you can then build upon through more data and context.

## Conclusion
If implemented and embedded correctly, Risk Management can save time, improve consistency, help to prioritise work and can foster accountability in your organisation.  

While a bit of work to get going, it is worthwhile investing in these methods.

However, if risk analysis is completed and registers are populated, but their results don't inform an organisation's strategic decision making, it's not going to be much use to you or anyone else.

If you have any questions or would like to know more about Information Security Risk Management, please don't hesitate to [get in touch](mailto:ross.d.prendergast@gmail.com "get in touch")
