[Product Name]
***
- [Product Name] Product Requirements Document (PRD)
- Status: {Draft, Stable Draft, Under Review, In Discussion, Approved, In Work, Shipped, Archived}
- Product Owner: {Product Owner Name}
- PRD Author: {PRD Author Name}
***

## Table of Contents
{TOC}

##  <a name='Scope'></a>Scope
The scope of this document is the initial product requirements document for the overall [Product Name] application.
The [Product Name] application will {end user benefit}. The application at Minimum Viable Product Stage (MVP) will allow [MVP functionality].

## <a name='Background'>Background</a>
### <a name='Marketcontext'>Market context</a>
- What does the market look like?
  - {Market Context}
  - {Narrative}
### <a name='Competitivecontext'>Competitive and Business context</a>
- What competition is there?
  - {Narrative}
#### <a name='Direct Competition'> Direct Competition (e.g. example1, example2)</a> ####
- {Category Summary}
	- {Weaknesses in Category}
	- {Strengths by Competition in Category}
	- {Opportunities to differentiate in Category}
	- {Risks in Category}
#### <a name='InDirect Competition'> InDirect Competition (e.g. example1, example2)</a> ####
- {Category Summary}
	- {Weaknesses in Category}
	- {Strengths by Competition in Category}
	- {Opportunities to differentiate in Category}
	- {Risks in Category}
#### <a name='LowCost/CostOfDoingNothing Competition'> Low Cost/Cost Of Doing Nothing Competition (e.g. example1, example2)</a> ####
- {Category Summary}
	- {Weaknesses in Category}
	- {Strengths by Competition in Category}
	- {Opportunities to differentiate in Category}
	- {Risks in Category}
#### <a name='Yet another tool Competition'> Yet another tool Competition (e.g. Custom, Homebaked) </a> ####
- {Category Summary}
	- {Weaknesses in Category}
	- {Strengths by Competition in Category}
	- {Opportunities to differentiate in Category}
	- {Risks in Category}
## <a name='ProblemStatement'>Problem Statement</a>
- {One Sentence Problem Statement}
## <a name='IdealClientProfiles'>Ideal Client Profiles</a>
### <a name='TargetMarket'>Target Market</a>
- Company Size: 
- Geography: 
- Productivity Tech. Stack: 
- Industry: 
- Use Case Methodology Maturity: 
###  <a name='TargetSegment'>Target Segment</a>
- {}
- {}
- {}
- {}
### <a name='TargetPersonas'></a>Target Persona(s)
Target personas include:
- ***{Persona 1}*** 
  - {Descriptive Narrative}
- ***{Persona 2}*** 
  - {Descriptive Narrative}
- {Repeat as necessary.}

## <a name='BusinessGoals'>Business Goals</a>
### <a name='CompanyGoals'>Company Goals</a>
[Product Name] is the {goal} for the {company}. {Monetizations}. {Monetization Methods}. 

### <a name='ProductGoals'>Product Goals</a>
#### <a name='MinimumViableProductis:'>Minimum Viable Product is:</a>
Minimum Viable Product is:
- {Data Model}
- {Business Model}
- {Security Model}
- {SDLC Model}
- {Design Scope}
- {Product Metrics Model}
#### <a name='SteadyStateGoals'>Steady State Goals</a>
Ultimately , the goal is to have [Product Name] to be {superlative} [Product Name] product for the {user base} This would include:
- {Stretch Goal 1}
- {Stretch Goal 2}
- {Stretch Goal 3}
#### <a name='SupportingJustifyingData'>Supporting Justifying Data</a>
{Supporting Justifying Data}

## <a name='UserRiskandorcriticalelementstosuccess'>User Risk and/or critical elements to success</a>
- Listing these here ensures it gets attention later. For example, for us ‘limitation in the XYZ’ and in the spec process we should pay a lot of attention to this as if we don’t get it right, success is at risk.
-  What might cause the product to not be successful or not meet the company goal?
	- {Risk 1}
	- {Risk 2}
	- {Risk 3}
	- {Abuser Story - Risk 1}
	- {Abuser Story - Risk 2}
	- {Abuser Story - Risk 3}

## <a name='SuccessMetrics'>Success Metrics</a>
- What does success look like?
	- {KPI 1} on [Product Name].
	- {KPI 2} on [Product Name].
	- {KPI 3} on [Product Name].
- In more detail there are both product metrics and business metrics. They will help us understand:
	- if the product is successful and 
	- if the product has had the expected impact on the business overall
## <a name='LaunchSteady'>It is helpful to establish ‘launch’ and ‘steady state’ objectives:</a>
- Launch highlights what we expect to see if we are on track to steady-state.
- Steady-state helps with monitoring i.e. if this metrics goes below XYZ threshold please alert me as it will probably require my attention.*

### <a name='Launch'>Launch</a>
#### <a name='Product'>Product</a>
- Commercial Viability: {}
- Adoption: {}
- Support & Reliability: {}
#### <a name='Business'>Business</a>
- Customer engagement: {}
- Revenue realization: {}
- Development Pipeline and Roadmap: {}
- Profitability: {}

### <a name='SteadyState'>Steady State</a>
#### <a name='ProductUsageEngagementChurn'>Product (Usage, Engagement, Churn)</a>
- Commercial Viability: {}
- Adoption: {}
- Support & Reliability: {}

#### <a name='Business-1'>Business</a>
- Customer engagement: {}
- Revenue realization: {}
- Development Pipeline and Roadmap: {}
- Profitability: {}

## <a name='FunctionalRequirements'>Functional Requirements</a>
High Level requirements are listed below. They should be tracked as individual Software Development items (e.g. JIRA, Github) issues/bugs as relevant objects.
- See the [project plan or Roadmap](LinkToProjectPlan) for the priorities.

```
Specific use cases are organized by priority:
- P0 ‘Must Haves’ (release blockers) 
- P1 ‘Nice to haves’ (Fast Follow features, but not release blockers)
- P2 'Nice to haves' (not required in the fast follow phase.)

MVP is composed of all P0s, and P1s may be:
  0- Moved up to a P0 and included in MVP.
  1- Moved to a different priority or prioritized lower in other P1 user-stories if they are still essential elements but not as urgent as the others.
  2- migrated to ‘out of scope’
The goal here is to work the P0 scope to get an MVP released, e.g. do not block the release of the product with P1s but acknowledge that they must be added soon thereafter.
```

### <a name='KeyUserFlows'>Key User Flows </a>
```
(UX/Design Input Ideal Here)
```
- {See individual user stories for specific flows as they're developed, or user flow directory for them overall.} 
- - Each user story contains key flows for the target users- for each step on the flow, what is the goal/task/decision/action that needs to be performed.
- - Note that these flows are functional flows in that they may not correspond to different pages. 
- - They may be condensed in the UI/UX.
- - It helps shows logical steps and what is required to support a decision etc.

#### <a name='FlowOutstandingQuestions'>Flow Outstanding Questions </a>
```
Links to discussions, RFCs, Designs, etc. linked here.
```

### <a name='KeyWireframesComponentsPagesViews'>Key Wireframes, Components, Pages, Views</a>
```
Add Links and Descriptions as Necessary
```

| Short Name | ```<Link>```       | Description/User Story         |
| ---------- | ------------------ | ------------------------------ |
| Core UX    | www.figma.com/link | As a user, I want to, so that, |

#### <a name='WireframeOutstandingQuestions'></a>Wireframe Outstanding Questions
- {Questions or Links}
###<a name='ProductObjectsandInteractions'> Product Objects and Interactions </a>
- These objects are core objects in [Product Name].

### <a name='Edge-cases'>Edge-cases</a>
#### Typically: 
- Default Values
- First time users flow and UI (including WalkMe requirements) 
- - This is critical to improve onboarding and TTV
- No data available states
- Error handling
- Special states (logged in Vs not logged in for instance)
- Special users (for instance- free user Vs paid user, etc… if one is the main use-case, address what the other one will see- if at all.)

### <a name='Outofscoperequirements'>Out of scope requirements</a>
*Sometimes, it helps to clearly say ‘and we will NOT be solving in this spec for XYZ special case’*
- e.g. we run out of money.
- e.g. customer xyz is screaming about abc.
 
## <a name='Non-functionalrequirements'> Non-functional requirements </a>
``` 
Please see below suggestions for non-functional requirements. It’s important to cover all of them (or add more if you’re missing something). The non-functional requirements must be user centric.
```

### <a name='ProductArchitecture'> Product Architecture </a>
- e.g. [Product Name] will be architected as modern SaaS. A {general-purpose} {web} {application}with a {Neo4j/Oracle} back-end, {NodeJS middleware or} and {React} front end. Hosted on {AWS, Azure, GCP, On-Prem}.
```
- Guiding design thoughts
- - Don't reinvent the wheel. 
- - Use best of breed tooling. 
- - Use technologies that we can hire for. 
- - Dogfood it/drink our own champagne.
```

#### <a name='ApplicationStack'>Application Stack</a>
- Front End: {React}
- - Because: {it's common, well known, easy to hire for, performant.}
- Middleware: {Node.js} 
- - Because: {Responsiveness. Asynchronous event-driven JavaScript runtime. Node.js is designed to build scalable network applications.}
- Backend: {Neo4j}
- - {Performance, Backup and restore functionality.}

#### <a name='Security'> Security </a>
- Data encrypted in transit
- Data encripted at rest

#### <a name='SLA'>SLA</a>
- Latency
 - - {User perceived low latency at browser level}
- Availability
 - - {99% (sure why not?)}
- Uptime
 - - {99% (sure why not?)}
- Scalability
 - - {Global Scalability}
- Reliability
 - - {Trusted by the enterprise}
- Quality
 - - {Trusted by the enterprise}

### <a name='Supportability'>Supportability</a>
- User tooltips and other non-intrusive in-product help 
- Documentation
- Report a bug inside product. Capture screenshot, submit a ticket.
- Usability metrics can stem from the product metrics that exist from 3rd parties.

### <a name='Localizability'></a>Localizability
- English only?
- USD only currency in  scope?
- Timezone, languages, currencies, time display formats, special characters - no special requirements, although design must be flexible enough to allow for this in the future.

###  9.5. <a name='LegalObligations'></a>Legal Obligations
- {EULA}
- {Terms and Conditions}
- {Privacy Policy} 
- {GDPR - For EU Customers}
- {FedRamp - For Gov't agencies and contractors}
- {HIPAA - For HealthCare Orgs}
- {CCPA - For Californians}

###  9.6. <a name='Data'></a>Data 
Typically addresses:
- retention - No end user data to inform this need or requirement.
- freshness and/or refresh rate - Speed and responsiveness.
- granularity - No end user data to inform this need or requirement.
- encryption - Data encrypted at rest and in transit.
- security - Identity and access management handled at the GCP level.
- segmentation - DB segmentation handled at the Aura/GCP level - handled at the GCP level.
- [#233](https://github.com/ervaren/[Product Name]/issues/70) Joe to look into more of what Aura offers us from a data rentention, segmentation, backup, encryption, etc.
- - Database back up and reliability
- - Do we rely on Aura built in DB?
- - And their backup and restore functionality?
- - Investigate
- - - What kind of SLAs do they offer?

###  9.7. <a name='MeasurementInstrumentationforproductmetrics'></a>Measurement Instrumentation for product metrics
- [#79](https://github.com/ervaren/[Product Name]/issues/79)
- How will these use cases be monitored in terms of usage?
	- Once the data starts flowing in at the early usage stages, we can start to segment the information for evaluating use cases. If we achieve high enough volumes, we can implement A/B testing.
- Do we need usage tags?
	- MixPanel and Usage Tags/Event Tags to be inserted into react Components.
	- HotJar for Recording Web Sessions.
	- Optimizely for AB Testing
	- https://chartmogul.com for revenue. Per Kim's recommendation.
- How does this change with the post-cookie era?
	- Nothing to worry about for now.

##  10. <a name='TestScenarios'></a>Test Scenarios
- [#3](https://github.com/ervaren/[Product Name]/issues/3)Generate Test Scenarios

##  11. <a name='DeploymentPlan'></a>Deployment Plan
- Workshop - November 17th - 18th
- Create risk/hello world - Target: November 29
- MVP scope agreed on - TBD
- MVP Running - 2/1
- Alpha - 3/1
- Marketing starts - 4/1
- Beta - 5/1
- Paywall is Up - 6/1
- Validation of product market fit - July 1 2022

##  12. <a name='GoToMarket'></a>Go To Market
###  12.1. <a name='PricingandRevenueModel'></a>Pricing and Revenue Model
- Paywalls - 2 tiers
	- Enterprise 
		- includes Aggregation and Permissions
		- Additional modules/addons/tabs
		- Presentation Mode/Meeting Mode
	- Personal 
		- More than 1 project
		- more than 1 users/collaborators (guest permissions)
		- Additional modules/addons/tabs
		- Presentation Mode/Meeting Mode

- Pricing benchmarks to a Clickup/Clarizen: $10/u/m - $60/u/m
- Placeholder pricing (from workshop): $19/u/m

###  12.2. <a name='MarketingPlan'></a>Marketing Plan
Outlets 
- University 
	- Student licenses
	- Speaker and Presenting Opportunities
	- PM Certifications
	- PM Masters 
- PMI / PMI Phoenix / PMI Mile High
	- Target members
- PMI
- Podcasts (e.g. PMHH, Digital PM, Projectify)
Project Management Influencers
- Social Media?
Titles:
- Project
- Program
- Portfolio
Roadshow:
- MVP
- Get out and demo.
Evangelical Content
- Blogs
- Education
- Community - (Paywalled?)

##  13. <a name='AcceptanceCriteria'></a>Acceptance Criteria
- This determines the release blockers. Anything else may be filed as ‘issues requiring immediate attention post launch ie sprint post launch’ or a plan to get to the steady state.
For MVP: 
- all P0 features for the Individual use cases, not necessarily the enterprise level
- low-latency across all test scenarios
- passing all test scenarios
- customer feedback form
- Payment processing (Braintree/Stripe)
- Paywalls - 2 tiers
	- Enterprise 
		- includes Aggregation and Permissions
	- Personal 
		- More than 1 project
		- more than 1 users/collaborators (guest permissions)
		- Additional modules/addons/tabs
		- Presentation Mode/Meeting Mode

##  14. <a name='ReferenceDocuments'></a>Reference Documents
Any document that hasn’t been linked already.

##  15. <a name='Furtherreading:'></a>Further reading:
- Predictably irrational as applied to project management
- Josh Ramirez - Behavioral PM
