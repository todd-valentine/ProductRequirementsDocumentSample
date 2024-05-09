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
{Market Context}
### <a name='Marketcontext'>Market competition</a>
- What does the market look like?
{Narrative}
### <a name='Competitivecontext'>Competitive and Business context</a>
- What competition is there?
{Narrative}
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
- ***{Persona 1}}*** 
  - {Descriptive Narrative}
- ***{Persona 2}}*** 
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
- See the [project plan](LinkToProjectPlan) for the priorities.

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

```
A blurb on 'hot zones', throughout the user stories I reference something called a hotzone. This is an area in the GUI where a user can interact qiuckly. It should be accessible via mouse interaction and keyboard interaction. The goal with a hotzone is to capture the information in the users head as quickly and effortlessly as possible. The interaction should be faster or at least as fast as interacting with a spreadsheet. These are the goals of the hotzone. I'm not picky about the technology used to achieve or build a hot zone, but it is the primary key to initial success in the user's perceived performance of the product.
```

###  8.1. <a name='KeyUserFlows'></a>Key User Flows
[#7 Develop Key User Flows](https://github.com/ervaren/[Product Name]/issues/7) Key User Flows 
- See individual user stories for specific flows as they're developed, or user flow directory for them overall.
- - Each user story contains key flows for the target users- for each step on the flow, what is the goal/task/decision/action that needs to be performed.
- - Note that these flows are functional flows in that they may not correspond to different pages. 
- - They may be condensed in the UI/UX.
- - It helps shows logical steps and what is required to support a decision etc…

####  8.1.1. <a name='FlowOutstandingQuestions'></a>Flow Outstanding Questions 
- Should landing pages be profile specific (if so, what are they)?
- Related RAID Objects are also deleted when a project is deleted? (DA question: What about lessons learned?)
- [#236](https://github.com/ervaren/[Product Name]/issues/236) What about [Product Name].com admin screens?
- [#235](https://github.com/ervaren/[Product Name]/issues/235) What about tenant admin screens?
- [#29](https://github.com/ervaren/[Product Name]/issues/29) What system wide settings should we surface to the administrator? 
- [#234](https://github.com/ervaren/[Product Name]/issues/234) What about identity management?

###  8.2. <a name='KeyWireframesComponentsPagesViews'></a>Key Wireframes, Components, Pages, Views
[Key Wireframes](https://shawnhardy715486.invisionapp.com/console/share/P427YUCVWGJ/876407229) 
- [Product Name] User Management Page (List) [#86](https://github.com/ervaren/[Product Name]/issues/86)
- [Product Name] User Detail Page (Detailed Record) [#224](https://github.com/ervaren/[Product Name]/issues/224)
- New User Invitation Email [#151](https://github.com/ervaren/[Product Name]/issues/151)
- Login Page (Both SSO and UN/PW) [#221](https://github.com/ervaren/[Product Name]/issues/221)
- First Time User Username and PW creation page [#151](https://github.com/ervaren/[Product Name]/issues/151)
- User not authorized Page [#151](https://github.com/ervaren/[Product Name]/issues/151)
- Profile Management Page (switching between Noob PM and experienced PM) [#224](https://github.com/ervaren/[Product Name]/issues/224)
  - Landing Page per Profile 
  - Requires Definition of Profiles and associated functionality for each profile
- Administrator Setup Page [#29](https://github.com/ervaren/[Product Name]/issues/29)
- Settings Page [#90](https://github.com/ervaren/[Product Name]/issues/90)
- SSO Setup Page [#91](https://github.com/ervaren/[Product Name]/issues/91)
- RAID Objects [#12](https://github.com/ervaren/[Product Name]/issues/12)
- RAID object details [#14](https://github.com/ervaren/[Product Name]/issues/14) [#17](https://github.com/ervaren/[Product Name]/issues/17) [#15](https://github.com/ervaren/[Product Name]/issues/15) [#16](https://github.com/ervaren/[Product Name]/issues/16)
- Any advanced user story screens
- WalkMe Style Initial Tips (for noob PM)
####  8.2.1. <a name='WireframeOutstandingQuestions'></a>Wireframe Outstanding Questions
- How to pivot between visual representations of the same object (e.g. Risks in a list, vs risks in a chart)
###  8.3. <a name='ProductObjectsandInteractions'></a> Product Objects and Interactions
These objects are core objects in [Product Name].
####  8.3.1. <a name='Projects'></a> Project(s)
##### 8.3.1.1. Project Properties
[#13](https://github.com/ervaren/[Product Name]/issues/13) For the project object there are the following properties. 
| Field Label     | Priority | Field Type           | Required | Field Name         | Default Value               | Other Values                      | Error Message                                                   | Comments                                              |
| --------------- | -------- | -------------------- | -------- | ------------------ | --------------------------- | --------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------- |
| Name            | P0       | Text                 | TRUE     | ProjectName        | User Input                  | User Input                        | A name for the project is required.                             |                                                       |
| UUID            | P0       | UUID                 | TRUE     | ProjectUUID        | Automatic generated UUID    | None                              | The system failed to generate the project ID, please try again. |                                                       |
| Custom ID       | P0       | String               | TRUE     | ProjectID          | Automatic generated numeric | Enduser editable Shortform Text   |                                                                 | Duplicates allowed                                    |
| State           | P0       | Picklist             | TRUE     | ProjectState       | Draft                       | Active, On-Hold, Completed, Cancelled | Picklist error.                                                 |                                                       |
| Created on      | P0       | Datetime             | TRUE     | ProjectCreatedOn   | Automatic Datetime          | None                              | The system failed to generate the project, please try again.    |                                                       |
| Last Updated on | P0       | Datetime             | TRUE     | ProjectUpdatedOn   | Automatic Datetime          | None                              | The system failed to generate the project, please try again.    |                                                       |
| Label(s)        | P0       | Multi-label selector | FALSE    | ProjectLabels      | null                        |                                   |                                                                 |                                                       |
| Description     | P0       | Long form rich-text  | FALSE    | ProjectDescription | null                        |                                   |                                                                 |                                                       |
| Budget          | P0       | Currency             | FALSE    | ProjectBudget      | null                        |                                   |                                                                 |                                                       |
| Expected ROI    | P2       | Numeric              | FALSE    | ProjectExpectedROI | Calculated Value            | End User Editable Numeric         |                                                                 | include field explanation, if calulated or user input |
| ROI             | P2       | Numeric              | FALSE    | ProjectROI         | Calculated Value            | End User Editable Numeric         |                                                                 | include field explanation, if calulated or user input |

##### 8.3.1.2. Project Relationships
For the project object there are the following relationships.
| Relationship    | Relationship to     | Priority | Required | Error Message                                                                     |
| --------------- | ------------------- | -------- | -------- | --------------------------------------------------------------------------------- |
| created by      | Person              | P0       | TRUE     | The system failed to generate the project creator relationship, please try again. |
| last updated by | Person              | P0       | TRUE     | The system failed to generate the project update date, please try again.          |
| contains        | Risk(s)             | P0       | FALSE    |                                                                                   |
| contains        | Action Item(s)      | P0       | FALSE    |                                                                                   |
| contains        | Issue(s)            | P0       | FALSE    |                                                                                   |
| contains        | Decision(s)         | P0       | FALSE    |                                                                                   |
| contains        | Lesson(s)           | P0       | FALSE    |                                                                                   |
| contains        | Meeting Minutes(es) | P1       | FALSE    | [#53](https://github.com/Ervaren/[Product Name]/issues/53)                               |
| contains        | Meeting Agenda(s)   | P1       | FALSE    |                                                                                   |
| contains        | Milestone(s)        | P1       | FALSE    |                                                                                   |
| contains        | Change Request(s)   | P1       | FALSE    |                                                                                   |
| created from    | Risk                | P1       | FALSE    |                                                                                   |
| created from    | Issue               | P1       | FALSE    |                                                                                   |
| created from    | Action Item         | P1       | FALSE    |                                                                                   |
| created from    | Decision            | P1       | FALSE    |                                                                                   |
| generated       | lesson(s)           | P2       | FALSE    |                                                                                   |

##### 8.3.1.3. Project Components
For the project object there are the following components that are neither fields nor relationships.
| Component Name            | Priority | Component Type    | Required | User Story Issue                                                                |
| ------------------------- | -------- | ----------------- | -------- | ------------------------------------------------------------------------------- |
| Update History            | P0       | More than a field | TRUE     | [#197](https://github.com/ervaren/[Product Name]/issues/197)                           |
| Timeline of the [Product Name]   | P2       | Custom View       | FALSE    | [#197](https://github.com/ervaren/[Product Name]/issues/197) but specific to projects. |
| Resource Calendar         | P2       | Custom View       | FALSE    |                                                                                 |
| Project Schedule          | P2       | Custom View       | FALSE    | [#49](https://github.com/ervaren/[Product Name]/issues/49)                             |
| Statistical Analysis      | P2       | Custom View       | FALSE    | [#51](https://github.com/ervaren/[Product Name]/issues/51)                             |
| Dashboard                 | P2       | Custom View       | FALSE    | [#139](https://github.com/ervaren/[Product Name]/issues/139)                           |
| Meeting mode              | P2       | Custom View       | FALSE    | [#53](https://github.com/ervaren/[Product Name]/issues/53)                             |
| Fishbone Diagram          | P2       | Custom View       | FALSE    |                                                                                 |
| Monte Carlo Analysis      | P2       | Custom View       | FALSE    |                                                                                 |
| EMV Charting              | P2       | Custom View       | FALSE    |                                                                                 |
| Decision Preparation      | P2       | Custom View       | FALSE    |                                                                                 |
| Contacts and Contact Info | P2       | Multiple Strings  | FALSE    |                                                                                 |

####  8.3.2. <a name='Risks'></a> Risk(s)
##### 8.3.2.1. Risk Properties
[#14](https://github.com/ervaren/[Product Name]/issues/14) For a  Risk object there are the following properties. 
| Field Label                   | Priority | Field Type           | Required | Field Name              | Default Value               | Other Values                                                            | Error Message                                                  | Comments                                              |
| ----------------------------- | -------- | -------------------- | -------- | ----------------------- | --------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------- |
| Name                          | P0       | Text                 | TRUE     | RiskName                | User Input                  |                                                                         | A name for the risk is required.                               |                                                       |
| UUID                          | P0       | Automatic UUID       | TRUE     | RiskUUID                | Automatic UUID              |                                                                         | The system failed to generate the object ID, please try again. |                                                       |
| Custom ID                     | P0       | String               | TRUE     | RiskID                  | Automatic generated numeric | Editable Shortform Text                                                 |                                                                | Duplicates allowed                                    |
| Risk State                    | P0       | Picklist             | TRUE     | RiskState               | Raised                      | Raised, Open, Issue (with link), Closed, Monitoring                     | Picklist error.                                                |                                                       |
| Date Raised                   | P0       | Datetime             | TRUE     | RiskRaisedOn            | Automatic Datetime          |                                                                         | Auto generated datetime, end-user editable after creation.     |
| Last Updated on               | P0       | Datetime             | TRUE     | RiskUpdatedOn           | Automatic Datetime          |                                                                         | The system failed to generate the risk, please try again.      |                                                       |
| Date Closed                   | P0       | Datetime             | FALSE    | RiskClosedOn            | null                        |                                                                         |                                                                |                                                       |
| Trigger Date                  | P0       | Datetime             | FALSE    | RiskTriggerDate         | null                        |                                                                         |                                                                |                                                       |
| My Eyes Only                  | P0       | Toggle               | TRUE     | RiskPrivate             | FALSE                       | TRUE                                                                    |                                                                |                                                       |
| Label(s)                      | P0       | Multi-label selector | FALSE    | RiskLabels              | null                        |                                                                         |                                                                |                                                       |
| Source of Risk                | P0       | Shortform Text       | FALSE    | RiskSource              | null                        |                                                                         |                                                                |                                                       |
| Description                   | P0       | Shortform Text       | FALSE    | RiskDescription         | null                        |                                                                         |                                                                |                                                       |
| Schedule Impact               | P0       | Duration             | FALSE    | RiskSchedulImpact       | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Budget Impact                 | P0       | Currency             | FALSE    | RiskBudgetImpact        | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Expected Monetary Value (EMV) | P1       | Currency             | FALSE    | RiskValue               | null                        |                                                                         |                                                                | Automatic calculation @sndrup need formula here       |
| Probability of Occurrence     | P0       | Percentage           | FALSE    | RiskProbability         | null                        |                                                                         |                                                                | #198 was a picklist, using a percentage.              |
| Scope Impact                  | P0       | Percentage           | FALSE    | RiskScopeImpact         | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Quality Impact                | P0       | Percentage           | FALSE    | RiskQualityImpact       | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Resource Impact               | P0       | Percentage           | FALSE    | RiskResourceImpact      | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Impact of Occurrence          | P0       | Picklist             | FALSE    | RiskImpact              | null                        |                                                                         |                                                                | [#199](https://github.com/ervaren/[Product Name]/issues/199) |
| Risk Response State           | P0       | Picklist             | FALSE    | RiskResponseStatus      | null                        | Red, Amber, Green (with icons)                                          | Picklist error.                                                |                                                       |
| Response Strategy             | P0       | Picklist             | FALSE    | RiskResponseStrategy    | null                        | Avoid, Mitigate, Transfer, Accept, Escalate                             | Picklist error.                                                |
| Closure Reason                | P0       | Picklist             | FALSE    | RiskClosureReason       | null                        | Did not occur, Avoided by changes, Project ended, Converted to an issue | Picklist error.                                                |                                                       |
| Impact Category               | P1       | Picklist             | FALSE    | RiskImpactCategory      | null                        |                                                                         |                                                                | [#202](https://github.com/ervaren/[Product Name]/issues/202) |
| Ike Urgency                   | P1       | Numeric              | FALSE    | RiskUrgency             | null                        | Integers between 1 - 100                                                |                                                                |                                                       |
| Ike Importance                | P1       | Numeric              | FALSE    | RiskImportance          | null                        | Integers between 1 - 100                                                |                                                                |                                                       |
| Priority                      | P1       | Numeric              | FALSE    | RiskPriority            | null                        |                                                                         |                                                                |                                                       |
| Residual Probability          | P2       | Percentage           | FALSE    | RiskResidualProbability | null                        |                                                                         |                                                                | TBD. Residual is down to a P2.                        |
| Residual Impact               | P2       | Picklist             | FALSE    | RiskResidualImpact      | null                        |                                                                         |                                                                | TBD. Residual is down to a P2.                        |
| Residual Risk description     | P2       | Shortform Text       | FALSE    | RiskResidualDescription | null                        |                                                                         |                                                                | TBD. Residual is down to a P2.                        |
| Contract Reference            | P2       | Shortform Text       | FALSE    | RiskContractReference   | null                        |                                                                         |                                                                |                                                       |

##### 8.3.2.2. Risk Relationships
For a Risk object there are the following relationships.
| Relationship    | Relationship to | Priority | Required | Error Message |
| --------------- | --------------- | -------- | -------- | ------------- |
| contained in    | Project         | P0       | FALSE    |               |
| created by      | Person          | P0       | FALSE    |               |
| last updated by | Person          | P0       | FALSE    |               |
| created from    | Risk            | P0       | FALSE    |               |
| created from    | Issue           | P0       | FALSE    |               |
| created from    | Action Item     | P0       | FALSE    |               |
| created from    | Decision        | P0       | FALSE    |               |
| generated       | lesson(s)       | P0       | FALSE    |               |

##### 8.3.2.3. Risk Components
For the Risk object there are the following components that are neither fields nor relationships.
| Component Name                         | Priority | Component Type    | Required | Comments                                                       |
| -------------------------------------- | -------- | ----------------- | -------- | -------------------------------------------------------------- |
| Update History                         | P0       | More than a field | TRUE     | [#197](https://github.com/ervaren/[Product Name]/issues/197)          |
| P*I                                    | P0       | More than a field | FALSE    | Calculation = Probability * Impact                             |
| Quantified Probability (High)          | P1       | Percentage        | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Quantified Probability (Low)           | P1       | Percentage        | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Quantified Probability (Most Likely)   | P1       | Percentage        | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Financial cost of impact (Optimistic)  | P1       | Currency          | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Financial cost of impact (Pessimistic) | P1       | Currency          | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Financial cost of impact (Most Likely) | P1       | Currency          | FALSE    | 3 slider range where low, mid and high are on the same slider. |
| Residual P*I                           | P2       | More than a field | FALSE    | Calculation = Residual Probability *P0 Residual Impact         |


####  8.3.3. <a name='ActionItems'></a> Action Item(s)
##### 8.3.3.1. Action Properties
[#17](https://github.com/ervaren/[Product Name]/issues/17) For a  Action object there are the following properties. 
| Field Label      | Priority | Field Type           | Required | Field Name            | Default Value               | Other Values                                                           | Error Message                                                    | Comments                                                                         |
| ---------------- | -------- | -------------------- | -------- | --------------------- | --------------------------- | ---------------------------------------------------------------------- | ---------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Name             | P0       | Text                 | TRUE     | ActionItemName        | User Input                  |                                                                        | A name for the risk is required.                                 |                                                                                  |
| UUID             | P0       | Automatic            | TRUE     | ActionItemUUID        | Automatic UUID              |                                                                        | The system failed to generate the object ID, please try again.   |                                                                                  |
| Custom ID        | P0       | String               | TRUE     | ActionItemID          | Automatic generated numeric | Editable Shortform Text                                                |                                                                  | Duplicates allowed                                                               |
| Action Item      | P0       | Action Item State    | TRUE     | ActionItemState       | Created                     | Assigned, In Work, In Review, Done, Draft, On Hold, Delegated, Blocked | Picklist error.                                                  | None                                                                             |
| Created on       | P0       | Datetime             | TRUE     | ActionItemCreatedOn   | Automatic Datetime          |                                                                        | The system failed to generate the action item, please try again. |                                                                                  |
| Last Updated on  | P0       | Datetime             | TRUE     | ActionItemUpdatedOn   | Automatic Datetime          |                                                                        | The system failed to generate the action item, please try again. |                                                                                  |
| Due Date         | P0       | Date                 | FALSE    | ActionItemDueOn       | null                        |                                                                        |                                                                  |                                                                                  |
| Task Description | P0       | Shortform Text       | FALSE    | ActionItemDescription | null                        |                                                                        |                                                                  |                                                                                  |
| Source           | P0       | Shortform Text       | FALSE    | ActionItemSource      | null                        |                                                                        |                                                                  | descriptor that relates to the relationship the the action item was created from |
| Label(s)         | P0       | Multi-label selector | FALSE    | ActionItemLabels      | null                        |                                                                        |                                                                  |                                                                                  |
| My Eyes Only     | P0       | Toggle               | TRUE     | ActionItemPrivate     | FALSE                       | TRUE                                                                   |                                                                  |                                                                                  |
| Ike Urgency      | P1       | Numeric              | FALSE    | ActionItemUrgency     | null                        | Integers between 1 - 100                                               |                                                                  |                                                                                  |
| Ike Importance   | P1       | Numeric              | FALSE    | ActionItemImportance  | null                        | Integers between 1 - 100                                               |                                                                  |                                                                                  |
| Priority         | P1       | Numeric              | FALSE    | ActionItemPriority    | null                        |                                                                        |                                                                  |                                                                                  |

##### 8.3.3.2. Action Relationships
For a Action object there are the following relationships.
| Relationship    | Relationship to | Priority | Required | Error Message                        |
| --------------- | --------------- | -------- | -------- | ------------------------------------ |
| created by      | Person          | P0       | TRUE     | Error in creation. Please try again. |
| last updated by | Person          | P0       | TRUE     | Error in update. Please try again.   |
| assigned to     | user            | P0       | FALSE    |                                      |
| contained in    | Project         | P0       | FALSE    |                                      |
| created from    | Risk            | P0       | FALSE    |                                      |
| created from    | Action Item     | P0       | FALSE    |                                      |
| created from    | Issue           | P0       | FALSE    |                                      |
| created from    | Decision        | P0       | FALSE    |                                      |
| generated       | lesson(s)       | P0       | FALSE    |                                      |
| raised For      | Issue(s)        | P1       | FALSE    |                                      |
| remediated      | Issue(s)        | P1       | FALSE    |                                      |

##### 8.3.3.3. Action Item Components
For the Action Item object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.4. <a name='Issues'></a> Issue(s)
##### 8.3.4.1. Issue Properties
[#15](https://github.com/ervaren/[Product Name]/issues/15) For a  Issue object there are the following properties. 
| Field Label     | Priority | Field Type           | Required | Field Name          | Default Value               | Other Values                                                                                 | Error Message                                                  | Comments           |
| --------------- | -------- | -------------------- | -------- | ------------------- | --------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ------------------ |
| Name            | P0       | Text                 | TRUE     | IssueName           | User Input                  |                                                                                              | A name for the issue is required.                              |                    |
| UUID            | P0       | Automatic UUID       | TRUE     | IssueUUID           | Automatic UUID              |                                                                                              | The system failed to generate the object ID, please try again. |                    |
| Custom ID       | P0       | String               | TRUE     | IssueID             | Automatic generated numeric | Editable Shortform Text                                                                      |                                                                | Duplicates allowed |
| Last Updated on | P0       | Datetime             | TRUE     | IssueUpdatedOn      | Automatic Datetime          |                                                                                              |                                                                |                    |
| Created on      | P0       | Datetime             | TRUE     | IssueCreatedOn      | Automatic Datetime          |                                                                                              |                                                                |                    |
| Issue State     | P0       | Picklist             | TRUE     | IssueState          | Created                     | Active, Resolved, Pending Review Reviewed, Closed, Deescalated, Escalated                    | Picklist error.                                                | None               |
| Impact State    | P0       | Picklist             | TRUE     | IssueImpactState    | null                        | Resolved, Remediating impacts, Root cause analysis, Root cause identified for lesson learned | Picklist error.                                                | None               |
| Response State  | P0       | Picklist             | TRUE     | IssueResponseStatus | null                        | Red, Amber, Green (with icons)                                                               | Picklist error.                                                | None               |
| My Eyes Only    | P1       | Toggle               | TRUE     | IssuePrivate        | FALSE                       | TRUE                                                                                         |                                                                |                    |
| Impact          | P0       | Shortform Text       | FALSE    | IssueImpact         | null                        |                                                                                              |                                                                |                    |
| Schedule Impact | P1       | Shortform Text       | FALSE    | IssueScheduleImpact | null                        |                                                                                              |                                                                |                    |
| Cost Impact     | P1       | Numeric              | FALSE    | IssueCostImpact     | null                        |                                                                                              |                                                                |                    |
| Priority        | P0       | Numeric              | FALSE    | IssuePriority       | null                        |                                                                                              |                                                                |                    |
| Ike Urgency     | P1       | Numeric              | FALSE    | IssueUrgency        | null                        | Integers between 1 - 100                                                                     |                                                                |                    |
| Ike Importance  | P1       | Numeric              | FALSE    | IssueImportance     | null                        | Integers between 1 - 100                                                                     |                                                                |                    |
| Label(s)        | P0       | Multi-label selector | FALSE    | IssueLabels         | null                        |                                                                                              |                                                                |                    |
| Category        | P0       | Label(s)             | FALSE    | IssueCategory       | null                        |                                                                                              |                                                                | Do we need this?   |
| Description     | P0       | Shortform Text       | FALSE    | IssueDescription    | null                        |                                                                                              |                                                                |                    |
| Resolution      | P0       | Shortform Text       | FALSE    | IssueResolution     | null                        |                                                                                              |                                                                |                    |
| Root Cause      | P0       | Shortform Text       | FALSE    | IssueRootCause      | null                        |                                                                                              |                                                                |                    |
| Created on      | P0       | Datetime             | FALSE    | IssueCreatedOn      | null                        |                                                                                              |                                                                |                    |
| Date Resolved   | P0       | Datetime             | FALSE    | IssueResolvedOn     | null                        |                                                                                              |                                                                |                    |


##### 8.3.4.2. Issue Relationships
For a Issue object there are the following relationships.
| Relationship    | Relationship to | Priority | Required | Error Message                        |
| --------------- | --------------- | -------- | -------- | ------------------------------------ |
| created by      | Person          | P0       | TRUE     | Error in creation. Please try again. |
| last updated by | Person          | P0       | TRUE     | Error in update. Please try again.   |
| contained in    | Project         | P0       | FALSE    |                                      |
| created from    | Risk            | P0       | FALSE    |                                      |
| created from    | Issue           | P0       | FALSE    |                                      |
| created from    | Action Item     | P0       | FALSE    |                                      |
| created from    | Decision        | P0       | FALSE    |                                      |
| generated       | lesson(s)       | P0       | FALSE    |                                      |

##### 8.3.4.3. Issue Components
For the Issue object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.5. <a name='Decisions'></a> Decision(s)
##### 8.3.5.1. Decision Properties
[#16](https://github.com/ervaren/[Product Name]/issues/16) For a  Decision object there are the following properties.  
| Field Label            | Priority | Field Type           | Required | Field Name            | Default Value               | Other Values                        | Error Message                                                  | Comments                            |
| ---------------------- | -------- | -------------------- | -------- | --------------------- | --------------------------- | ----------------------------------- | -------------------------------------------------------------- | ----------------------------------- |
| Name                   | P0       | Text                 | TRUE     | DecisionName          | User Input                  |                                     | A name for the issue is required.                              |                                     |
| UUID                   | P0       | Automatic UUID       | TRUE     | DecisionUUID          | Automatic UUID              |                                     | The system failed to generate the object ID, please try again. |                                     |
| Custom ID              | P0       | String               | TRUE     | DecisionID            | Automatic generated numeric | Editable Shortform Text             | Duplicates allowed                                             |                                     |
| Decision               | P0       | Decision State       | TRUE     | DecisionState         | Created                     | Decided, In Review, Draft, Deferred | Picklist error.                                                | None                                |
| Last Updated on        | P0       | Datetime             | TRUE     | DecisionLastUpdatedOn | Automatic Datetime          |                                     | The system failed to generate [object], please try again.      |                                     |
| Created on             | P0       | Datetime             | TRUE     | DecisionCreatedOn     | Automatic Datetime          |                                     | The system failed to generate the object ID, please try again. |                                     |
| My Eyes Only           | P1       | Toggle               | TRUE     | DecisionPrivate       | FALSE                       | TRUE                                | The system failed to set the privacy, please try again.        |                                     |
| Label(s)               | P0       | Multi-label selector | FALSE    | DecisionLabels        | null                        |                                     |                                                                |                                     |
| Decision Needed by     | P0       | Datetime             | FALSE    | DecisionNeededBy      | null                        |                                     |                                                                |                                     |
| Date Resolved          | P0       | Datetime             | FALSE    | DecisionResolvedOn    | null                        |                                     |                                                                |                                     |
| Decision to be made    | P0       | Shortform Text       | FALSE    | DecisionDecsription   | null                        |                                     |                                                                |                                     |
| Decision Made          | P0       | Shortform Text       | FALSE    | DecisionChosen        | null                        |                                     |                                                                |                                     |
| Justification          | P0       | Shortform Text       | FALSE    | DecisionJustification | null                        |                                     |                                                                |                                     |
| Impact                 | P0       | Shortform Text       | FALSE    | DecisionImpact        | null                        |                                     |                                                                |                                     |
| Priority               | P1       | Numeric              | FALSE    | DecisionPriority      | Calculated                  |                                     |                                                                |                                     |
| Decision requested by  | P1       | Text                 | FALSE    | DecisionRequestor     | Logged In User              |                                     |                                                                | text because it might not be a user |
| Additional Description | P1       | Longform Text        | FALSE    | DecisionDescription2  | null                        |                                     |                                                                |                                     |
| Ike Urgency            | P1       | Numeric              | FALSE    | DecisionUrgency       | null                        | Integers between 1 - 100            |                                                                |                                     |
| Ike Importance         | P1       | Numeric              | FALSE    | DecisionImportance    | null                        | Integers between 1 - 100            |                                                                |                                     |

##### 8.3.5.2. Decision Relationships
For a Decision object there are the following relationships.
| Relationship    | Relationship to  | Priority | Required | Error Message                        |
| --------------- | ---------------- | -------- | -------- | ------------------------------------ |
| created by      | Person           | P0       | TRUE     | Error in creation. Please try again. |
| last updated by | Person           | P0       | TRUE     | Error in update. Please try again.   |
| created from    | Risk             | P0       | FALSE    |                                      |
| created from    | Issue            | P0       | FALSE    |                                      |
| created from    | Action Item      | P0       | FALSE    |                                      |
| created from    | Decision         | P0       | FALSE    |                                      |
| generated       | lesson(s)        | P0       | FALSE    |                                      |
| reviewed in     | meeting          | P1       | FALSE    |                                      |
| generated       | Response Actions | P1       | FALSE    |                                      |

##### 8.3.5.3. Decision Components
For the Decision object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Required | Field Name      | Comments                                              |
| -------------- | -------- | -------- | --------------- | ----------------------------------------------------- |
| Update History | P0       | TRUE     | Decision        | [#197](https://github.com/ervaren/[Product Name]/issues/197) |
| Options        | P0       | FALSE    | DecisionOptions |                                                       |

####  8.3.6. <a name='People'></a> People
##### 8.3.6.1. Person Properties
For a Person object there are the following properties.
| Field Label  | Priority | Field Type           | Required | Field Name      | Default Value      | Other Values              | Error Message                                                  | Comments                                            |
| ------------ | -------- | -------------------- | -------- | --------------- | ------------------ | ------------------------- | -------------------------------------------------------------- | --------------------------------------------------- |
| Name         | P0       | Text                 | TRUE     | PeopleName      | User Input         |                           | A name is required. Please try again.                          |                                                     |
| UUID         | P0       | ID                   | TRUE     | PeopleUUID      | Automatic UUID     |                           | The system failed to generate the person ID, please try again. |                                                     |
| People State | P0       | Picklist             | TRUE     | PeopleState     | Invited            | Active, Idle, Deactivated | Picklist error.                                                | [#27](https://github.com/ervaren/[Product Name]/issues/27) |
| Created on   | P1       | Datetime             | TRUE     | PeopleCreatedOn | Automatic Datetime |                           |                                                                |                                                     |
| Email        | P0       | email                | FALSE    | PeopleEmail     | null               |                           |                                                                | [#47](https://github.com/ervaren/[Product Name]/issues/47) |
| Phone        | P1       | Numeric              | FALSE    | PeoplePhone     | null               |                           |                                                                | [#47](https://github.com/ervaren/[Product Name]/issues/47) |
| Time Zone    | P1       | Picklist             | FALSE    | PeopleTimeZone  | UTC                | See [timezones.md]        |                                                                | [#46](https://github.com/ervaren/[Product Name]/issues/46) |
| Label(s)     | P1       | Multi-label selector | FALSE    | PeopleLabel     | null               |                           |                                                                |                                                     |

##### 8.3.6.2. Person Relationships
For a Person object there are the following relationships.
| Relationship       | Relationship to | Priority | Required | Error Message |
| ------------------ | --------------- | -------- | -------- | ------------- |
| member of          | Organization    | P0       | FALSE    |               |
| member of          | Project         | P0       | FALSE    |               |
| are informed about | decisions       | P0       | FALSE    |               |
| responsible for    | decision        | P0       | FALSE    |               |
| owns               | decision        | P0       | FALSE    |               |
| owns               | Issue(s)        | P0       | FALSE    |               |
| owns               | decision        | P0       | FALSE    |               |
| owns               | portfolio(s)    | P0       | FALSE    |               |
| are informed about | Issue(s)        | P0       | FALSE    |               |
| requests           | decision        | P0       | FALSE    |               |
| responsible for    | Project(s)      | P0       | FALSE    |               |
| responsible for    | Risk(s)         | P0       | FALSE    |               |
| responsible for    | Action Item(s)  | P0       | FALSE    |               |
| responsible for    | Decision(s)     | P0       | FALSE    |               |
| responsible for    | Dependencie(s)  | P0       | FALSE    |               |
| responsible for    | Issue(s)        | P0       | FALSE    |               |
| accountable for    | Project(s)      | P0       | FALSE    |               |
| accountable for    | Risk(s)         | P0       | FALSE    |               |
| accountable for    | Decision(s)     | P0       | FALSE    |               |
| accountable for    | Dependencie(s)  | P0       | FALSE    |               |
| accountable for    | Action Item(s)  | P0       | FALSE    |               |
| accountable for    | Issue(s)        | P0       | FALSE    |               |
| informed about     | Action Item(s)  | P0       | FALSE    |               |
| informed about     | Issue(s)        | P0       | FALSE    |               |
| informed about     | Risk(s)         | P0       | FALSE    |               |
| informed about     | Project(s)      | P0       | FALSE    |               |
| informed about     | Decision(s)     | P0       | FALSE    |               |
| informed about     | Dependencies(s) | P0       | FALSE    |               |
| consulted for      | Action Item(s)  | P0       | FALSE    |               |
| consulted for      | Issue(s)        | P0       | FALSE    |               |
| consulted for      | Risk(s)         | P0       | FALSE    |               |
| consulted for      | Project(s)      | P0       | FALSE    |               |
| consulted for      | Decision(s)     | P0       | FALSE    |               |
| consulted for      | Dependencies(s) | P0       | FALSE    |               |
| decided            | Decision        | P0       | FALSE    |               |
| assigned to        | Issue(s)        | P0       | FALSE    |               |
| assigned to        | Decision (open) | P0       | FALSE    |               |
| creates            | Project(s)      | P0       | FALSE    |               |
| creates            | Risk(s)         | P0       | FALSE    |               |
| creates            | Action Item(s)  | P0       | FALSE    |               |
| creates            | Issue(s)        | P0       | FALSE    |               |
| creates            | Decision(s)     | P0       | FALSE    |               |
| creates            | Lessons Learned | P1       | FALSE    |               |
| owns               | Project(s)      | P0       | FALSE    |               |
| owns               | Risk(s)         | P0       | FALSE    |               |
| owns               | Action Item(s)  | P0       | FALSE    |               |
| owns               | Issue(s)        | P0       | FALSE    |               |
| owns               | Decision(s)     | P0       | FALSE    |               |
| owns               | Lessons Learned | P1       | FALSE    |               |
| owns               | Dependecy       | P1       | FALSE    |               |
| updates            | Project(s)      | P0       | FALSE    |               |
| updates            | Risk(s)         | P0       | FALSE    |               |
| updates            | Action Item(s)  | P0       | FALSE    |               |
| updates            | Issue(s)        | P0       | FALSE    |               |
| updates            | Decision(s)     | P0       | FALSE    |               |
| updates            | Lessons Learned | P0       | FALSE    |               |
| marks for deletion | Project(s)      | P0       | FALSE    |               |
| marks for deletion | Risk(s)         | P0       | FALSE    |               |
| marks for deletion | Action Item(s)  | P0       | FALSE    |               |
| marks for deletion | Issue(s)        | P0       | FALSE    |               |
| marks for deletion | Decision(s)     | P0       | FALSE    |               |
| marks for deletion | Lessons Learned | P0       | FALSE    |               |
| deletes            | Project(s)      | P0       | FALSE    |               |
| deletes            | Risk(s)         | P0       | FALSE    |               |
| deletes            | Action Item(s)  | P0       | FALSE    |               |
| deletes            | Issue(s)        | P0       | FALSE    |               |
| deletes            | Decision(s)     | P0       | FALSE    |               |
| deletes            | Lessons Learned | P0       | FALSE    |               |
| approves           | Change Request  | P1       | FALSE    |               |
| creates            | Change Request  | P1       | FALSE    |               |

####  8.3.7. <a name='Portfolios'></a> Portfolio(s)
##### 8.3.7.1. Portfolio Properties
For a  Portfolio object there are the following properties. - RAID items for projects roll up when viewing multiple project(s) data. This is the key consideration for runtime generated portfolios of projects. [#36](https://github.com/ervaren/[Product Name]/issues/36)
- Project metadata defines the portfolio as runtime parameters.
- Selection of RAIDs for rollups can be filtered metadata. e.g. I only want to see runtime-portfolio risks and issues generated in the past week. 
  
| Field Label     | Priority | Field Type     | Required | Field Name         | Default Value               | Other Values                    | Error Message                                                  | Comments           |
| --------------- | -------- | -------------- | -------- | ------------------ | --------------------------- | ------------------------------- | -------------------------------------------------------------- | ------------------ |
| Name            | P0       | Text           | TRUE     | PortfolioName      | null                        |                                 | A name for the issue is required.                              |                    |
| UUID            | P0       | Automatic UUID | TRUE     | PortfolioUUID      | null                        |                                 | The system failed to generate the object ID, please try again. |                    |
| Custom ID       | P0       | String         | TRUE     | PortfolioID        | Automatic generated numeric | Editable Shortform Text         |                                                                | Duplicates allowed |
| Portfolio State | P0       | Picklist       | TRUE     | PortfolioState     | Created                     | Saved, Draft, In Review, Closed | Picklist error.                                                | None               |
| Created on      | P1       | Datetime       | TRUE     | PortfolioCreatedOn | Automatic Datetime          |                                 | The system failed to generate the portfolio, please try again. |                    |


##### 8.3.7.2. Portfolio Relationships
For a Portfolio object there are the following relationships.
| Relationship | Relationship to | Priority | Required    | Error Message |
| ------------ | --------------- | -------- | ----------- | ------------- |
| contains     | Project(s)      | P1       | Interaction |               |
| contains     | Risk(s)         | P1       | Interaction |               |
| contains     | Action Item(s)  | P1       | Interaction |               |
| contains     | Issue(s)        | P1       | Interaction |               |
| contains     | Decision(s)     | P1       | Interaction |               |


##### 8.3.7.3. Portfolio Components
For the Portfolio object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |


####  8.3.8. <a name='Lessons'></a> Lesson(s)
##### 8.3.8.1. Lesson Properties
For a  Lesson object there are the following properties. Lesson(s) can be generated from any project or RAID object. They can be 'relearned' or linked from another project or RAID object after they've been created.
| Field Label     | Priority | Field Type           | Required | Field Name        | Default Value               | Other Values                        | Error Message                                                  | Comments           |
| --------------- | -------- | -------------------- | -------- | ----------------- | --------------------------- | ----------------------------------- | -------------------------------------------------------------- | ------------------ |
| Name            | P0       | Text                 | TRUE     | LessonName        | User Input                  |                                     | A name for the lesson is required.                             |                    |
| UUID            | P0       | Automatic UUID       | TRUE     | LessonUUID        | Automatic UUID              |                                     | The system failed to generate the object ID, please try again. |                    |
| Custom ID       | P0       | String               | TRUE     | LessonID          | Automatic generated numeric | Editable Shortform Text             |                                                                | duplicates allowed |
| Lesson State    | P0       | Picklist             | TRUE     | LessonState       | Draft                       | Reviewed, Learned, Closed, Assigned | Picklist error.                                                | None               |
| Created on      | P1       | Datetime             | TRUE     | LessonCreatedOn   | Automatic Datetime          |                                     | The system failed to generate the lesson, please try again.    |                    |
| Labels          | P1       | Multi-label selector | FALSE    | LessonLabels      | null                        |                                     |                                                                |                    |
| Description     | P1       | Longform Text        | FALSE    | LessonDescription | null                        |                                     |                                                                |                    |
| Actions to Take | P1       | Multi-Step Checklist | FALSE    | LessonActions     | null                        |                                     |                                                                |                    |


##### 8.3.8.2. Lesson Relationships
For a Lesson object there are the following relationships.
| Relationship | Relationship to | Priority | Required | Error Message |
| ------------ | --------------- | -------- | -------- | ------------- |
| learned from | Project(s)      | P0       | True     |               |
| learned from | Risk(s)         | P1       | False    |               |
| learned from | Issue(s)        | P1       | False    |               |
| learned from | Action Item(s)  | P1       | False    |               |
| learned from | Decision(s)     | P1       | False    |               |

##### 8.3.8.3. Lesson Components
For the Lesson object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.9. <a name='Dependencies'></a> Dependencies
##### 8.3.9.1. Dependency Properties
For a  Dependency object there are the following properties.
| Field Label             | Priority | Field Type           | Required | Field Name            | Default Value                   | Other Values                                              | Error Message                                                   | Comments           |
| ----------------------- | -------- | -------------------- | -------- | --------------------- | ------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------- | ------------------ |
| Name                    | P0       | Text                 | TRUE     | DependencyName        | User input                      |                                                           | A name for the dependency is required.                          |                    |
| UUID                    | P0       | Automatic UUID       | TRUE     | DependencyUUID        | Automatically generated UUID    |                                                           | The system failed to generate the object ID, please try again.  |                    |
| Custom ID               | P0       | ID                   | TRUE     | DependencyID          | Automatically generated numeric | Editable Shortform Text                                   |                                                                 | Duplicates allowed |
| State                   | P0       | Picklist             | TRUE     | DependencyState       | Created                         | Assigned, In Review, Accepted, Rejected, Changes Required | Picklist error.                                                 | None               |
| Created On              | P0       | Datetime             | TRUE     | DependencyCreatedOn   | Automatic Datetime              |                                                           | The system failed to generate the dependency, please try again. |                    |
| Label(s)                | P1       | Multi-label selector | FALSE    | DependencyLabels      | null                            |                                                           |                                                                 |                    |
| Description             | P1       | Longform Text        | FALSE    | DependencyDescription | null                            |                                                           |                                                                 |                    |
| Impact if not delivered | P1       | Picklist             | FALSE    | DependencyImpact      | null                            | [TODO]                                                    |                                                                 |                    |
| Type                    | P1       | Picklist             | FALSE    | DependencyType        | null                            | [TODO]                                                    |                                                                 |                    |
| Due Date                | P1       | Datetime             | FALSE    | DependencyDueDate     | null                            |                                                           |                                                                 |                    |


##### 8.3.9.2. Dependency Relationships
For a Dependency object there are the following relationships.
| Relationship | Relationship to | Priority | Required | Error Message |
| ------------ | --------------- | -------- | -------- | ------------- |
| depends on   | Project(s)      | P0       | TRUE     |               |
| depends on   | Risk(s)         | P0       | FALSE    |               |
| depends on   | Action Item(s)  | P0       | FALSE    |               |
| depends on   | Issue(s)        | P0       | FALSE    |               |
| depends on   | Decision(s)     | P0       | FALSE    |               |
| depends on   | Lessons Learned | P0       | FALSE    |               |

##### 8.3.9.3. Dependency Components
For the Dependency object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.10. <a name='Escalations'></a>. Escalation(s)
##### 8.3.10.1. Escalation Properties
For a  Escalation object there are the following properties.
| Field Label      | Priority | Field Type     | Required | Field Name          | Default Value                   | Other Values                                              | Error Message                                                   | Comments           |
| ---------------- | -------- | -------------- | -------- | ------------------- | ------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------- | ------------------ |
| Name             | P0       | Text           | TRUE     | Escalation          | User input                      |                                                           | A name for the escalation is required.                          |                    |
| UUID             | P0       | Automatic UUID | TRUE     | Escalation          | Automatically generated UUID    |                                                           | The system failed to generate the object ID, please try again.  |                    |
| Custom ID        | P0       | String         | TRUE     | Escalation          | Automatically generated numeric | Editable Shortform Text                                   |                                                                 | Duplicates allowed |
| Created On       | P0       | Datetime       | TRUE     | EscalationCreatedOn | Automatic Datetime              |                                                           | The system failed to generate the escalation, please try again. | Not Editable       |
| Escalation State | P0       | Picklist       | TRUE     | EscalationState     | Created                         | Assigned, In Review, Accepted, Rejected, Changes Required | Picklist error.                                                 | None               |

##### 8.3.10.2. Escalation Relationships
For a Escalation object there are the following relationships.
| Relationship | Relationship to | Priority | Required | Error Message |
| ------------ | --------------- | -------- | -------- | ------------- |
| raised for   | Issue(s)        | P1       | FALSE    |               |
| raised for   | Risk(s)         | P1       | FALSE    |               |
| raised for   | Project(s)      | P1       | FALSE    |               |
| learned from | Action Item(s)  | P1       | FALSE    |               |
| learned from | Decision(s)     | P1       | FALSE    |               |

##### 8.3.10.3. Escalation Components
For the Escalation object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.11. <a name='ChangeRequests'></a>. Change Request(s)
##### 8.3.11.1. Change Request Properties
For a  Change object there are the following properties.
| Field Label     | Priority | Field Type           | Required | Field Name                  | Default Value                   | Other Values                                                                    | Error Message                                                  | Comments           |
| --------------- | -------- | -------------------- | -------- | --------------------------- | ------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------- | ------------------ |
| Name            | P0       | Text                 | TRUE     | ChangeRequestName           | User input                      |                                                                                 | A name for the change request is required.                     |                    |
| UUID            | P0       | Automatic UUID       | TRUE     | ChangeRequestUUID           | Automatically generated UUID    |                                                                                 | The system failed to generate the object ID, please try again. |                    |
| Custom ID       | P0       | ID                   | TRUE     | ChangeRequestID             | Automatically generated numeric | Editable Shortform Text                                                         |                                                                | Duplicates allowed |
| Change Request  | P0       | Change Request State | TRUE     | ChangeRequestState          | Created                         | Assigned, In Review, Accepted, Rejected, Changes Required, Integrated into Plan | Picklist error.                                                | None               |
| Description     | P1       | Longform Text        | FALSE    | ChangeRequestDescription    | null                            |                                                                                 |                                                                |                    |
| Schedule Impact | P1       | Shortform Text       | FALSE    | ChangeRequestScheduleImpact | null                            |                                                                                 |                                                                |                    |
| Budget impact   | P1       | Shortform Text       | FALSE    | ChangeRequestBudgetImpact   | null                            |                                                                                 |                                                                |                    |
| Scope impact    | P1       | Shortform Text       | FALSE    | ChangeRequestScopeImpact    | null                            |                                                                                 |                                                                |                    |
| Resource impact | P1       | Shortform Text       | FALSE    | ChangeRequestResourceImpact | null                            |                                                                                 |                                                                |                    |
| Quality impact  | P1       | Shortform Text       | FALSE    | ChangeRequestQualityImpact  | null                            |                                                                                 |                                                                |                    |

##### 8.3.11.2. Change Request Relationships
For a Change object there are the following relationships.
| Relationship  | Relationship to | Priority | Required | Error Message |
| ------------- | --------------- | -------- | -------- | ------------- |
| requested for | Project         | P1       | False    |               |

##### 8.3.11.3. Change Request Components
For the Change Request object there are the following components that are neither fields nor relationships.
| Field Label    | Priority | Comments                                              |
| -------------- | -------- | ----------------------------------------------------- |
| Update History | P0       | [#197](https://github.com/ervaren/[Product Name]/issues/197) |

####  8.3.12. <a name='Meetings'></a>. Meeting(s)
##### 8.3.12.1. Meeting Properties
For a  Meeting object there are the following properties. 
| Field Label   | Priority | Field Type     | Required | Field Name     | Default Value                   | Other Values                              | Error Message                                                  | Comments           |
| ------------- | -------- | -------------- | -------- | -------------- | ------------------------------- | ----------------------------------------- | -------------------------------------------------------------- | ------------------ |
| Name          | P0       | Text           | TRUE     | MeetingName    | User input                      |                                           | A name for the meeting is required.                            |                    |
| UUID          | P0       | Automatic UUID | TRUE     | MeetingUUID    | Automatically generated UUID    |                                           | The system failed to generate the object ID, please try again. |                    |
| Custom ID     | P0       | String         | TRUE     | MeetingID      | Automatically generated numeric | Editable Shortform Text                   |                                                                | Duplicates allowed |
| Meeting State | P0       | Picklist       | TRUE     | MeetingState   | Created                         | Scheduled, Completed, Cancelled, Deferred | Picklist error.                                                | None               |
| Date          | P0       | Date           | TRUE     | MeetingDate    | User input                      |                                           | A date and time is required to create a meeting.               |                    |
| Time          | P0       | Time           | TRUE     | MeetingTime    | User input                      |                                           | A date and time is required to create a meeting.               |                    |
| Minutes       | P1       | Longform Text  | FALSE    | MeetingMinutes | null                            |                                           |                                                                |                    |

##### 8.3.12.2. Meeting Relationships 
For a Meeting object there are the following relationships. Meetings can have 0 or 1 agendas.
| Relationship | Relationship to | Priority | Required | Error Message |
| ------------ | --------------- | -------- | -------- | ------------- |
| held for     | Project(s)      | P1       | FALSE    |               |
| reviewed     | Risk(s)         | P1       | FALSE    |               |
| reviewed     | Issue(s)        | P1       | FALSE    |               |
| reviewed     | Action Item(s)  | P1       | FALSE    |               |
| reviewed     | Decision(s)     | P1       | FALSE    |               |
| attended by  | person (people) | P1       | FALSE    |               |
| have         | Agenda(s)       | P1       | FALSE    |               |

####  8.3.13. <a name='Agendas'></a>. Agenda(s)
##### 8.3.13.1. Agenda Properties
For a  Agenda object there are the following properties. Agenda(s) must belong to 1 and only 1 meeting.
| Field Label | Priority | Field Type     | Required | Field Name  | Default Value                   | Other Values                 | Error Message                                                  | Comments           |
| ----------- | -------- | -------------- | -------- | ----------- | ------------------------------- | ---------------------------- | -------------------------------------------------------------- | ------------------ |
| Name        | P0       | Text           | TRUE     | AgendaName  | User input                      |                              | A name for the agenda is required.                             |                    |
| UUID        | P0       | Automatic UUID | TRUE     | AgendaUUID  | Automatically generated UUID    |                              | The system failed to generate the object ID, please try again. |                    |
| Custom ID   | P0       | String         | TRUE     | AgendaID    | Automatically generated numeric | Editable Shortform Text      |                                                                | Duplicates allowed |
| Agenda      | P0       | Agenda State   | TRUE     | AgendaState | Created                         | Scheduled, Discussed, Closed | Picklist error.                                                | None               |

##### 8.3.13.2. Agenda Relationships
For a Agenda object there are the following relationships.
| Relationship | Relationship to | Priority | Required | Error Message                                       |
| ------------ | --------------- | -------- | -------- | --------------------------------------------------- |
| contains     | Agenda Items    | P0       | TRUE     | At least one agenda item needs to be on the agenda. |

####  8.3.14. <a name='AgendaItems'></a>. Agenda Item(s)
##### 8.3.14.1. Agenda Item Properties
For a  Agenda object there are the following properties.
| Field Label | Priority | Field Type        | Required | Field Name      | Default Value                   | Other Values                | Error Message                                                  | Comments           |
| ----------- | -------- | ----------------- | -------- | --------------- | ------------------------------- | --------------------------- | -------------------------------------------------------------- | ------------------ |
| Name        | P0       | Text              | TRUE     | AgendaItemName  | User input                      |                             | A name for the agenda item is required.                        |                    |
| UUID        | P0       | Automatic UUID    | TRUE     | AgendaItemUUID  | Automatically generated UUID    |                             | The system failed to generate the object ID, please try again. |                    |
| Custom ID   | P0       | String            | TRUE     | AgendaItemID    | Automatically generated numeric | Editable Shortform Text     |                                                                | Duplicates allowed |
| Agenda Item | P0       | Agenda Item State | TRUE     | AgendaItemState | Created                         | Deferred, Discussed, Closed | Picklist error.                                                | None               |

##### 8.3.14.2. Agenda Item Relationships
For a Agenda object there are the following relationships.
| Relationship  | Relationship to | Priority | Required | Error Message |
| ------------- | --------------- | -------- | -------- | ------------- |
| generated for | meeting(s)      | P0       | FALSE    |               |
| to review     | Project(s)      | P0       | FALSE    |               |
| to review     | Risk(s)         | P0       | FALSE    |               |
| to review     | Issue(s)        | P0       | FALSE    |               |
| to review     | Action Item(s)  | P0       | FALSE    |               |
| to review     | Decision(s)     | P0       | FALSE    |               |

####  8.3.15. <a name='Workspaces'></a>. Workspace(s)
##### 8.3.15.1. Workspace Properties
For a  Workspace object there are the following properties.
| Field Label | Priority | Field Type      | Required | Field Name     | Default Value                   | Other Values            | Error Message                                                  | Comments           |
| ----------- | -------- | --------------- | -------- | -------------- | ------------------------------- | ----------------------- | -------------------------------------------------------------- | ------------------ |
| Name        | P0       | Shortform Text  | TRUE     | WorkspaceName  | User input                      |                         | A name for the workspace is required.                          |                    |
| UUID        | P0       | Automatic UUID  | TRUE     | WorkspaceUUID  | Automatically generated UUID    |                         | The system failed to generate the object ID, please try again. |                    |
| Custom ID   | P0       | String          | TRUE     | WorkspaceID    | Automatically generated numeric | Editable Shortform Text |                                                                | Duplicates allowed |
| Workspace   | P0       | Workspace State | TRUE     | WorkspaceState | Active                          | Idle, Archive           | Picklist error.                                                | None               |

##### 8.3.15.2. Workspace Relationships
For a Workspace object there are the following relationships.
| Relationship | Relationship to | Priority | Required | Error Message |
| ------------ | --------------- | -------- | -------- | ------------- |
| contains     | Project(s)      | P1       | FALSE    |               |
| contains     | Portfolio(s)    | P1       | FALSE    |               |
| contains     | Users(s)        | P1       | FALSE    |               |

###  8.4. <a name='Edge-cases'></a>Edge-cases
[#5 Define Edge Cases](https://github.com/ervaren/[Product Name]/issues/5) 
Typically: 
- Default Values
- First time users flow and UI (including WalkMe requirements) 
- - *This is critical to improve onboarding and TTV*
- No data available states
- Error handling
- Special states (logged in Vs not logged in for instance)
- Special users (for instance- free user Vs paid user, etc… if one is the main use-case, address what the other one will see- if at all.)

###  8.5. <a name='Outofscoperequirements'></a>Out of scope requirements
*Sometimes, it helps to clearly say ‘and we will NOT be solving in this spec for XYZ special case’*
- Budgeting for projects are out of scope
- Timelines and project schedules are out of scope
 
##  9. <a name='Non-functionalrequirements'></a>Non-functional requirements
*Please see below suggestions for non-functional requirements. It’s important to cover all of them (or add more if you’re missing something). The non-functional requirements must be user centric.*

###  9.1. <a name='ProductArchitecture'></a>Product Architecture
- [Product Name].com will be architected as modern SaaS. A general-purpose web application- Neo4j/Aura back-end, NodeJS middleware and React front end. Hosted on Google Cloud Platform.
- Guiding design thoughts
- - Don't reinvent the wheel. 
- - Use best of breed tooling. 
- - Use technologies that we can hire for. 
- - Dogfood it/drink our own champagne.
 
####  9.1.1. <a name='ApplicationStack'></a>Application Stack
- Front End: React
- - Because: it's common, well known, easy to hire for, performant.
- Middleware: Node.js 
- - Because: Responsiveness. Asynchronous event-driven JavaScript runtime. Node.js is designed to build scalable network applications.
- Backend
- - https://cloud.google.com/functions
- Neo4j Aura on GCP for the Database [#233](https://github.com/ervaren/[Product Name]/issues/233) Joe to look into backup and restore functionality.

####  9.1.2. <a name='Security'></a>1.9.1.2. Security
- Data encrypted in transit
- Data encripted at rest

###  9.2. <a name='SLA'></a>SLA
- Latency - User perceived low latency at browser level
- Availability - 99% (sure why not?)
- Uptime - 99% (sure why not?)
- Scalability - Global Scalability
- Reliability - Trusted by the enterprise
- Quality - Trusted by the enterprise

###  9.3. <a name='Supportability'></a>Supportability
- User tooltips and other non-intrusive in-product help 
- Docusaurus user site to host documentation (videos, articles, tutorials, Q&As, user videos)
- Report a bug inside product. Capture screenshot, submit a ticket.
- - There should be a 3rd party solution for reporting a bug. [#231](https://github.com/ervaren/[Product Name]/issues/231)
- Usability metrics can stem from the product metrics that exist from MixPanel and Hotjar. Anything further is out of scope currently.

###  9.4. <a name='Localizability'></a>Localizability
- English only is current MVP scope.
- USD is the only currency in MVP scope.
- Timezone, languages, currencies, time display formats, special characters - no special requirements, although design must be flexible enough to allow for this in the future.

###  9.5. <a name='LegalObligations'></a>Legal Obligations
- EULA [#70](https://github.com/ervaren/[Product Name]/issues/70) 
- Terms and Conditions [#71](https://github.com/ervaren/[Product Name]/issues/71) - P0: .
- Privacy Policy [#72](https://github.com/ervaren/[Product Name]/issues/72) - *include GDPR for Europe, CCPA for California, others as required.*
- - All of these would depend on the functionality provided GCP, and perhaps they have documents we can leverage.
- - GDPR - For EU Customers
- - FedRamp - For Gov't agencies and contractors
- - HIPAA - For HealthCare Orgs
- - CCPA - For Californians
- [#73](https://github.com/ervaren/[Product Name]/issues/73) Clickthrough agreement to the EULA, Ts&Cs and Privacy Policy.

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
