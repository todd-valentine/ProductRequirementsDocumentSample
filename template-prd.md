# [Product Name]
***
- [Product Name] Product Requirements Document (PRD)
- Status: {Draft, Stable Draft, Under Review, In Discussion, Approved, In Work, Shipped, Archived}
- Product Owner: {Product Owner Name}
- PRD Author: {PRD Author Name}
***

## Table of Contents
{TOC}

## <a name='Scope'>Scope</a>
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
- {Target Segment1}
- {Target Segment2}
- {Target Segment3}
- {Repeat as necessary}
### <a name='TargetPersonas'></a>Target Persona(s)
Target personas include:
- ***{Persona 1}*** 
  - {Descriptive Narrative}
- ***{Persona 2}*** 
  - {Descriptive Narrative}
- {Repeat as necessary}
## <a name='BusinessGoals'>Business Goals</a>
### <a name='CompanyGoals'>Company Goals</a>
[Product Name] is the {goal} for the {company}. 
- {Monetizations}. 
- {Monetization Methods}. 
### <a name='ProductGoals'>Product Goals</a>
#### <a name='MinimumViableProductis:'>Minimum Viable Product is:</a>
Minimum Viable Product is:
- {Data Model}
- {Business Model}
- {Security Model}
- {SDLC Model}
- {Design Scope}
- {Product Metrics Model}
- {Acceptance use cases}
#### <a name='SteadyStateGoals'>Steady State Goals</a>
Ultimately , the goal is to have [Product Name] to be {superlative} [Product Name] product for the {user base} This would include:
- {Stretch Goal 1}
- {Stretch Goal 2}
- {Stretch Goal 3}
#### <a name='SupportingJustifyingData'>Supporting Justifying Data</a>
{Supporting Justifying Data}
## <a name='UserRiskandorcriticalelementstosuccess'>User Risk and/or critical elements to success</a>
- Listing these here ensures it gets attention later. 
	- For example, for a ‘limitation in the XYZ (dependency)’ and in the specification process we should pay a lot of attention to it.
	- If we don’t get it right, success is at risk for a potentially foreseeable complication or risk. 
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
- There are both product metrics and business metrics. They will help teams understand:
	- if the product is successful
	- if the product has had the expected impact on the business
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
	- (Most teams will align these outside the PRD, in a tool like GitHub, JIRA, or ProductBoard.)

```
Specific use cases are organized by priority:
	- P0 ‘Must Haves’ (release blockers) 
	- P1 ‘Nice to haves’ (Fast Follow features, but not release blockers)
	- P2 'Nice to haves' (not required in the fast follow phase.)

MVP is composed of all P0s, and P1s may be:
  - 0 - Moved up to a P0 and included in MVP.
  - 1 - Moved to a different priority or prioritized lower in other P1 user-stories if they are still essential elements but not as urgent as the others.
  - 2 - migrated to ‘out of scope’

The goal here is to work the P0 scope to get an MVP released, e.g. do not block the release of the product with P1s but acknowledge that they must be added soon thereafter.
```

### <a name='KeyUserFlows'>Key User Flows </a>
```
(UX Designer Input Ideal Here)
```
- {See individual user stories for specific flows as they're developed, or user flow directory for them overall.} 
	- Each user story contains key flows for the target users- for each step on the flow, what is the goal/task/decision/action that needs to be performed.
	- Note that these flows are functional flows in that they may not correspond to different pages. 
	- They may be condensed in the UI/UX.
	- It helps shows logical steps and what is required to support a decision etc.
#### <a name='FlowOutstandingQuestions'>Flow Outstanding Questions </a>
```
Links to discussions, RFCs, Designs, etc. linked here.
```
### <a name='KeyWireframesComponentsPagesViews'>Key Wireframes, Components, Pages, Views</a>
```
Add Links and Descriptions as Necessary
```

| Short Name | Link       | Description/User Story         |
| ---------- | ------------------ | ------------------------------ |
| Core UX    | www.figma.com/link | As a user, I want to, so that, |

#### <a name='WireframeOutstandingQuestions'>Wireframe Outstanding Questions</a>
- {Questions or Links}

### <a name='ProductObjectsandInteractions'> Product Objects and Interactions </a>
- These objects are core objects in [Product Name].

### <a name='Edge-cases'>Edge-cases</a>
#### Typically: 
- Default Values
- First time users flow and UI (including WalkMe requirements) 
	- This is critical to improve onboarding and TTV
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
	- Don't reinvent the wheel. 
	- Use best of breed tooling. 
	- Use technologies that we can hire for. 
	- Dogfood it/drink our own champagne.
```
#### <a name='ApplicationStack'>Application Stack</a>
- Front End: {e.g. React}
	- Because: {it's common, well known, easy to hire for, performant.}
- Middleware: {e.g. Node.js} 
	- Because: {Responsiveness. Asynchronous event-driven JavaScript runtime. Node.js is designed to build scalable network applications.}
- Backend: {e.g. Neo4j}
	- {Performance, Backup and restore functionality.}
- APIs
	- What API operations need to be fully described. {Typically completed with engineering lead input after reading through the PRD.}
#### <a name='Security'> Security </a>
- Data encrypted in transit
- Data encripted at rest
- Access, procedure, corner cases
- Abuser prevention, detection and reporting
#### <a name='SLA'>SLA</a>
- Latency
	- {User perceived low latency at browser level}
- Availability
	- {99% (sure why not?)}
- Uptime
	- {99.9% (sure why not? It's not like AWS US E2 ever goes down ;) >.)}
- Scalability
	- {Global Scalability}
- Reliability
	- {Trusted by the enterprise}
- Quality
	- {Trusted by the enterprise}
### <a name='Supportability'>Supportability</a>
- User tooltips and other non-intrusive in-product help 
- Documentation
- Report a bug inside product. Capture screenshot, submit a ticket.
- Usability metrics can stem from the product metrics that exist from 3rd parties.
### <a name='Localizability'>Localizability</a>
- English only?
- USD only currency in scope?
- Timezone, languages, currencies, time display formats, special characters - no special requirements, although design must be flexible enough to allow for this in the future.
### <a name='LegalObligations'>Legal Obligations</a>
- {EULA}
- {Terms and Conditions}
- {Privacy Policy} 
- {GDPR - For EU Customers}
- {FedRamp - For Gov't agencies and contractors}
- {HIPAA - For HealthCare Orgs}
- {CCPA - For Californians}
### <a name='Data'>Data</a>
Typically addresses:
- retention - 
- freshness and/or refresh rate - Speed and responsiveness.
- granularity - No end user data to inform this need or requirement.
- encryption - Data encrypted at rest and in transit.
- security - 
- segmentation - 
### <a name='MeasurementInstrumentationforproductmetrics'>Measurement Instrumentation for product metrics</a>
- TBD - Look into metrics by Amplitude, HotJar, etc.
## <a name='TestScenarios'>Test Scenarios</a>
- TBD - (write extensively and naively here.)
## <a name='DeploymentPlan'>Deployment Plan</a>
- Kickoff - 
- Criteria / MVP Scope Drafted - 
- MVP scope agreed on - 
- MVP Running - 
- Alpha - 
- Marketing starts - 
- Beta - 
- Paywall is Up - 
- Go/no-go review
- SHIPIT!
##  <a name='GoToMarket'>Go To Market</a>
###  <a name='PricingandRevenueModel'>Pricing and Revenue Model</a>
- Pricing Tiers
	- Top
		- includes ...
		- excludes ...
	- Middle
		- includes ...
		- excludes ...
	- Low 
		- includes ...
		- excludes ...
	- Free
		- includes ...
		- excludes ...
- Pricing benchmarks to a competitior
- Placeholder pricing?

### <a name='MarketingPlan'>Marketing Plan</a>
Outlets 
- Industry groups
	- Target members
    - Podcasts (e.g. This is Product Management)
- Industry Influencers
- Social Media
  - AI gen Content policy?
    - LinkedIn 
    -  Target Titles:
- Roadshow:
  - MVP.
  - Get out and demo. automate and synthesize feedback.
- Evangelical Content
  - Blogs
  - Education
  - Community - (Paywalled?)
- Cheap Academia
	- Student licenses
	- Speaker and Presenting Opportunities
	- Certifications
- Marketing Team
  - Paid?
  - Social?
  - SEO?
  - etc?
##  <a name='AcceptanceCriteria'>Acceptance Criteria</a>
- This determines the release blockers. 
- Anything else may be filed as ‘issues requiring immediate attention post launch ie sprint post launch’ or a plan to get to the steady state.
- For MVP: 
  	- All P0 features for the Individual use cases, not necessarily the "reach" level
  	- usability testing
  	- passing all test scenarios
- Feedback?
- Commercials?
- Paywalls?
	- Enterprise 
		- includes ...
		- excludes ...
	- Mid-Market
        - includes ...
		- excludes ...
	- Personal 
    	- includes ...
		- excludes ...
##  <a name='ReferenceDocuments'>Reference Documents</a>
Any document that hasn’t been linked already.
## <a name='Furtherreading:'>Further reading</a>
 - As Required...

