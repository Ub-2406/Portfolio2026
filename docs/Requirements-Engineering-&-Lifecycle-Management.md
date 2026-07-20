---
title: "04 Requirements Engineering & Lifecycle Management for National Informtaion Systems"
sidebar_label: Requirements Engineering & Lifecycle Management
sidebar_position: 4
slug: /reqirements-engineering-lifecycle-management
---
----

_To maintain confidentiality and internal security protocols, specific entity names and geographic locations have been replaced with descriptive architectural identifiers throughout this document._

----

## **Requirements Engineering & Lifecycle Management for National Informtaion Systems**

### SDLC

The Software Development Life Cycle (SDLC) represents a structured framework detailing the methodologies for developing, designing, and maintaining a project to ensure that all goals, objectives, and user requirements are fulfilled. The primary objective of the SDLC is the delivery of high-quality software that aligns with the expectations of the Regional Public Sector Client. This process ensures the software operates efficiently, remains within budget constraints, and adheres to the client's established deadlines ([Dharmender2006](References.md#Dharmender2006)).

While the SDLC outlines specific activities for every phase of the life cycle and is executed with rigorous attention to detail, errors and limitations can still occur. Such discrepancies frequently arise from misalignments between the client’s demands, the Lead Software Engineer of CyberInfoSec’s interpretation of the proposed system, and the final functional outcome. Consequently, selecting an appropriate SDLC is a design necessity; it is the responsibility of the analyst or developer to recommend the most suitable SDLC model to effectively meet the client’s requirements ([Ritika2016](References.md#Ritika2016)).

The SDLC framework is comprised of four fundamental phases: Planning, Analysis, Design, and Implementation. While specific initiatives, such as the Regional Academic Data Management System or the Central Financial Commission Unit integration, may prioritize certain stages over others, all projects must incorporate the core elements of these four phases. Each phase consists of a sequence of steps utilizing specific techniques to generate technical documentation that provides a comprehensive overview of the project ([Alan2012](References.md#Alan2012)).

### Eight Models of SDLC

>#### (a) Waterfall Model

This methodology is recognized as the traditional and inaugural process model, frequently utilized by major corporations and the Regional Public Sector Client. The model prioritizes intensive documentation and meticulous planning, making it highly effective for initiatives where quality control is the paramount concern. Key features include: the partitioning of the development process into distinct stages; each phase corresponding to a specific project activity; and every completed stage yielding a specific deliverable. Any input for a subsequent stage is derived directly from the deliverables of the previous one, following a strict, one-way sequence. A project cannot revert to or repeat a phase once finalized, making rework exceptionally difficult  ([Rastogi2015](References.md#Rastogi2015)).

>#### (b) Rapid Application Development (RAD) Model

RAD is an incremental process model centered on short development cycles, justifying the term "Rapid." This velocity is achieved through component-based design, the use of off-the-shelf components, and a streamlined implementation approach. Development adheres to rigorous deadlines, such as the Regional Academic Data Management System, where each stage is delivered and integrated into a functional prototype. This allows a team to produce a fully operational system within a compressed timeframe, typically 60 to 90 days. RAD eschews third-generation programming languages and is unsuitable for systems that are not modularized, carry high requirement risks, or involve frequent interface changes ([Yu2018](References.md#Yu2018)).

>#### (c) Component-Based Development (CBD)

In this model, software is constructed by integrating pre-developed packages and components. These may include business-related, off-the-shelf modules or elements previously engineered by the Lead Software Engineer of CyberInfoSec. The core philosophy of CBD is "write once, reuse many times," requiring little to no modification for subsequent implementations.

>#### (d) The Formal Methods Model

This approach focuses on generating mathematical and formal requirements for a software project. Because the software is developed according to these precise specifications, its behavior is strictly verified to ensure compliance. Formal methods are essential for developing safety-critical software, such as medical devices or aircraft avionics. However, adopting this model can be costly and time-consuming, requiring extensive training for developers and presenting communication challenges with the client and non-technical stakeholders ([Ashwini2012](References.md#Ashwini2012)).

>#### (e) The Unified Process or Rational Unified Process (RUP)

RUP serves as an iterative software development framework. Rather than being a rigid, single-perspective model, it is an adaptable framework that can be tailored to select elements appropriate for specific needs. The concept is rooted in a set of building blocks or content elements that define the outputs, the necessary skills, and the incremental goals to be achieved.

>#### (f) Agile Model

Agile methodology utilizes adaptive teams capable of responding quickly to shifting requirements. It prioritizes customer satisfaction through the rapid delivery of functional software. This model is designed to handle requirement changes even during late development stages, ensuring that working software is released frequently—in cycles of weeks rather than months ([Balaji2012](References.md#Balaji2012)).

>#### (g) Spiral Model

The spiral model offers an evolutionary, iterative approach that combines the step-by-step characteristics of the Waterfall model. It is designed for large-scale, complex projects, such as a Central Financial Commission Unit integration, providing rapid development of progressively more complete software versions. Each iteration produces a release, which might initially be a conceptual paper model. Every phase begins with a design objective and concludes with a client progress review. Starting at the center, the process moves clockwise in traversals, with each flow resulting in a deliverable that evolves until the project's ultimate goal is realized ([Rastogi2015](References.md#Rastogi2015)).

>#### (h) Prototype Model

This is a straightforward and widely adopted development model. The core concept allows developers to identify critical user requirements at the earliest stages, enabling the rapid creation of a software prototype. Developers perform continuous modifications based on feedback until the user is satisfied. This model is particularly effective when user requirements are ambiguous or uncertain at the start of development ([Yu2018](References.md#Yu2018)).

### The Suitable Four SDLC Models

The following table presents a comparative analysis of the four selected methodologies ([Sami2012](References.md#Sami2012)):

| Features (ability to develop systems with) | Waterfall Model | Prototype | Spiral | Agile |
| --- | --- | --- | --- | --- |
| Unclear User Requirement | Poor | Good | Excellent | Excellent |
| Short time schedule | Poor | Good | Poor | Excellent |
| Strong project management | Excellent | Excellent | Excellent | Excellent |
| Visibility of Stakeholders | Good | Excellent | Excellent | Excellent |
| Unfamiliar technology | Poor | Excellent | Excellent | Good |
| Complex system | Good | Excellent | Excellent | Good |
| Reliable System | Good | Poor | Excellent | Good |

SDLC frameworks provide a structured roadmap for development teams, ensuring that the chosen methodology aligns with the project's scale and fulfills the client's specific demands. Every model possesses distinct strengths and weaknesses; consequently, one model is typically favored over others based on how its inherent properties correspond to the requirements of the project.

Based on the current objectives, the Regional Public Sector Client intends to execute a two-phased strategy. The first phase involves establishing an information system across all district levels to oversee academic activities under the Regional Academic Data Management System. This will be achieved by aggregating data from every educational tier. The second phase, projected for completion within a ten-year timeframe, involves integrating the data from the Regional Academic Data Management System with the Central Financial Commission Unit and various other state departments. The Lead Software Engineer of CyberInfoSec has been tasked with engineering this comprehensive information system for the Regional Public Sector Client.

In my capacity as the head of the software development unit, I recommend the application of the Waterfall, Prototype, Spiral, and Agile models. While all eight previously discussed models could technically be applied to the tasks defined by the Regional Public Sector Client, these four are preferred due to their industry-standard status and proven reliability. The comparative analysis provided in the table above highlights the specific attributes of these four methodologies.

Specifically, I propose that the Waterfall and Prototype models are most suitable for the initial phase of aggregating educational data for the Regional Academic Data Management System. For the subsequent, more complex integration between the Regional Academic Data Management System and the Central Financial Commission Unit, the Spiral and Agile models are the superior choices.

### Eight Requirements Gathering Technique

The tables shows eight requirement gathering techniques ([Axia2018](References.md#Axia2018)) and ([Eid2015](References.md#Eid2015)):

| Requirements Gathering | Definition | Advantages | Disadvantages |
| --- | --- | --- | --- |
| Group interviews and one-to-one interviews/meetings | Group sessions involve multiple stakeholders/users for collective input; one-to-one meetings require extensive pre-design, post-interview documentation, and targeted groundwork. | Group formats accelerate data collection; individual meetings extract detailed insights from participants who are less comfortable in open forums. | Group settings require complex preparation and are harder to facilitate; individual interviews present scheduling difficulties and are time-consuming for both parties. |
| Requirements Gathering Tools (e.g., Axia’s RFI/RFP) | These consist of extensive catalogs of potential tools, allowing users to select options that align with their specific needs through a user-friendly interface. | They facilitate rapid documentation and can be seamlessly integrated or combined with other requirement-gathering methodologies. | Users may face difficulty selecting the most appropriate tool and often risk including features that exceed the project's actual requirements. |
| Brainstorming and Workshops | Organized as group sessions or individual preparations where users draw on past readings and experiences. Workshops typically involve fewer than 10 participants and use timed, repetitive exercises (e.g., 3-hour sessions) to pinpoint requirements. | Excellent for defining core requirements and generating innovative ideas; workshops often secure results faster than standard group interviews. | Participants may struggle with the creative demands of brainstorming; sessions require intensive preparation, experienced facilitators, and potential IT support for recording, which can increase costs. |
| Feasibility Study and Current System Documentation | An analysis of existing systems to determine how to enhance or replace them based on new requirements; involves utilizing current materials, such as user manuals, to inform the development of a successor system. | Streamlines the gathering and recording of details by building on established system knowledge; existing documentation provides a functional foundation that simplifies the creation of the new system. | Detailed data collection may be hindered if previous records are misplaced; there is a risk that existing documentation is outdated, inaccurate, or entirely lost. |
| Use Case Modelling (e.g., UML) | Utilizes "stories" to describe specific task processes, illustrating the system's functionality strictly from the user's perspective. | Overcomes the difficulty users often face when trying to specify technical requirements by allowing them to simply describe their intended actions and necessary workflows. | Requires significant time to analyze and translate these narrative stories into formal, documented requirements. |
| Observation and Questionnaires | Observation involves studying users as they perform specific tasks; questionnaires collect specific data points from users, including those in remote geographic locations. Questionnaires can be web-based or offline, requiring careful question design to avoid biasing the results. | Provides practical insights for improving process activities in the new system; questionnaires enable data collection from a large user base at a minimal cost. | Observation can be slow, time-consuming, and carries the risk of the Hawthorne effect (users changing behavior when watched). Questionnaires often suffer from low response rates, are viewed as low priority by participants, and require significant time to design effectively. |
| Prototyping | Involves gathering initial requirements to construct a preliminary version of the software, which is then iteratively refined and reworked until it fully meets user expectations. | Excellent for exploring functional logic and system behavior; allows for early identification and rectification of problems during each iteration until the final objectives are met. | Challenging to prototype numerous integrated systems and subsystems simultaneously; unsuitable for large-scale applications as it can become a prohibitively expensive method for requirement discovery. |
| Joint Requirements Development (JRD) | A collaborative approach similar to workshops, but with a specific focus on ensuring requirements are formally identified, documented, and approved by users during the initial project phase. | Highly effective for resolving specific issues in previously documented requirements and securing a final, formal agreement among stakeholders. | Often necessitates multiple supporting workshops and meetings; can be difficult to implement or less productive at the very beginning of a project if users have not yet clearly defined their needs. |

### The Suitable Four Requirements Gathering Technique

In my capacity as the Lead Software Engineer of CyberInfoSec, I have identified specific requirement-gathering techniques to bolster the four selected frameworks: Waterfall, Spiral, Prototype, and Agile. To support these models, the most effective techniques include requirements gathering tools (such as Axia’s RFI/RFP), feasibility studies, current system documentation, Use Case Modeling (e.g., UML), and Joint Requirements Development (JRD) ([Adetoba2018](References.md#Adetoba2018)).

Regarding the project milestones:

* **Phase 1: Data Collation**
    The Regional Public Sector Client must first aggregate data across all educational tiers. This objective is best served by utilizing requirements gathering tools (e.g., Axia’s RFI/RFP), feasibility studies, and current system documentation. These techniques are ideal because most educational institutions already maintain some form of recorded data, which simplifies the collation process. Furthermore, these methodologies align effectively with the Waterfall and Spiral models ([Saurabh2012](References.md#Saurabh2012)).

* **Phase 2: System Integration**
    The second initiative involves connecting the data within the Regional Academic Data Management System and merging it with the Central Financial Commission Unit and other state agencies. This complex integration is best executed through the Prototype and Agile models. The corresponding gathering techniques for this phase should include Use Case Modeling (e.g., UML) and Joint Requirements Development (JRD) ([Saurabh2012](References.md#Saurabh2012)).

### Dynamic System Development Methods

Dynamic Systems Development Method (DSDM) is an Agile-based framework utilized for software engineering (Aydal, 2005). As an analytical approach favored by information systems professionals, it was derived from the Rapid Application Development (RAD) methodology. Both RAD and DSDM were established by a UK-based consortium of corporations. The framework evolved through several iterations: Version 1 debuted in January 1995, followed by Version 2 in October 1995, and Version 3 in September 1997 ([Stapleton1997](References.md#Stapleton1997)).

DSDM aligns with core Agile principles, such as empowering development teams, ensuring consistent user involvement, and maintaining frequent product delivery. However, it possesses unique characteristics that distinguish it, specifically the use of facilitated workshops, prototyping, and the **MoSCoW** prioritization technique (Must have, Should have, Could have, and Won’t have this time) ([Waters2012](References.md#Waters2012)).

Under this methodology, the Lead Software Engineer of CyberInfoSec must prioritize requirements, quality, cost, and schedule. The primary goal of DSDM is the timely delivery of a project—such as a Regional Academic Data Management System — while ensuring all stakeholders remain actively engaged. It is particularly effective for business systems due to its "time-boxing" approach, where fixed intervals for iterations are set, and a working software deliverable must be produced at the end of each period, similar to Sprints in Scrum. Testing and incremental development are integrated from the initial stages and maintained throughout the project lifecycle ([Sivaranjani2017](References.md#Sivaranjani2017)).

According to ([Render2019](References.md#Render2019)), the DSDM framework is governed by eight fundamental principles:

* **Focus on business needs:** Aligning the project with the goals of the Regional Public Sector Client.
* **Deliver on time:** Adhering to strict project schedules.
* **Collaborate:** Ensuring active cooperation between developers and users.
* **Never compromise quality:** Maintaining high standards throughout development.
* **Build incrementally from firm foundations:** Establishing a solid base before adding features.
* **Develop iteratively:** Refining the system through constant feedback.
* **Communicate continuously and clearly:** Ensuring transparency across the team.
* **Demonstrate control:** Managing the project effectively, particularly during complex tasks like a Central Financial Commission Unit integration.

The DSDM framework is structured into three sequential phases: Pre-project, Project Life Cycle, and Post-project ([Render2018](References.md#Render2018)).

#### 1. Pre-project

This foundational phase involves identifying potential projects, securing necessary funding, and confirming project commitments. Addressing these critical factors early is essential to mitigate risks and prevent structural issues in later development stages.

#### 2. Project Life Cycle

This central phase comprises five distinct stages. The initial two stages are sequential and provide balance, while the subsequent three are executed through iterative and incremental development ([Islam2011](References.md#Islam2011)).

* **(a) Feasibility Study:** The problem for the intended application, such as the Regional Academic Data Management System, is defined, and technical feasibility is verified. Developers determine if the RAD approach is suitable; if validated, development proceeds.
* **(b) Business Study:** A high-level analysis of information and business requirements is performed. A basic architectural outline is drafted, and the team explores various features. Because DSDM is incremental, the Lead Software Engineer of CyberInfoSec must establish maintainability and quality control standards at this point.
* **(c) Functional Model Iteration:** The focus shifts to building prototypes iteratively. Through demonstrations and user feedback, the prototype is refined until a functional model is approved. Key outputs include the analysis model and major software components.
* **(d) Design and Build Iteration:** This stage ensures the prototype is properly planned and refined to meet rigorous standards. The result is a fully tested, high-quality version of the application ready for deployment.
* **(e) Implementation:** In this final stage, the application is transitioned to the operational site, and users are provided with training. While rare, if a missing functional area is discovered, the process can revert to previous stages to resolve the issue.

#### 3. Post-project

The final phase ensures the system—such as the Central Financial Commission Unit integration—operates efficiently through continuous maintenance, fixes, and enhancements. Under DSDM principles, maintenance is treated as ongoing development; the project may return to earlier phases to refine deliverables for the Regional Public Sector Client as needed.

The advantages and disadvantages of DSDM ([Ramsin2017](References.md#Ramsin2017)):

| Advantages of DSDM | Disadvantages of DSDM |
| --- | --- |
| **Strict Resource Management:** Adheres rigorously to established budget and time constraints. | **Code Integrity Risks:** Focus on Rapid Application Development (RAD) can potentially decrease overall code robustness. |
| **Adaptable Development:** Offers high flexibility in evolving and refining project requirements. | **Process Rigidity:** Demands total organizational commitment to the specific DSDM methodology. |
| **Agnostic Framework:** Provides a process that remains independent of specific technical tools or techniques. | **High User Demand:** Requires significant and continuous involvement from the Regional Public Sector Client. |
| **Stakeholder Integration:** Ensures clients and stakeholders are deeply integrated into the development lifecycle. | **Resource Expertise:** Necessitates a development team highly skilled in both technical and business domains. |
| **Quality Assurance Priority:** Mandates heavy emphasis on testing, requiring at least one dedicated tester per team. | **Documentation Overhead:** Results in heavy documentation due to the high volume of products generated in each phase. |
| **Value-Driven Delivery:** Prioritizes high-business-value deliverables as the primary objective. | **Cost Implications:** Membership in the DSDM consortium may involve expensive fees. |
| **Requirement Prioritization:** Utilizes a specific, structured approach to determine requirement importance within each iteration. | **Requirement Volatility:** Progressive requirement development can be difficult to manage without strict adherence to the framework. |

### Extreme Programming Approaches

In a payroll-based initiative involving fifteen team members, Kent Beck refined the Extreme Programming (XP) methodology, leading to its global recognition between 2000 and 2001 ([Livermore2008](References.md#Livermore2008)).

XP is a prominent Agile methodology characterized by being lightweight, efficient, and flexible. It is designed to mitigate risks and remain adaptable to anticipated changes through rapid, iterative development. A core tenet of XP is the continuous emphasis on communication among all team members. To ensure the successful execution of projects—such as the Regional Academic Data Management System — it is essential to foster active cooperation between management, the Regional Public Sector Client, and the Lead Software Engineer of CyberInfoSec ([Qumer2008](References.md#Qumer2008)).

This framework is specifically engineered for environments with volatile and rapidly changing requirements. By prioritizing flexibility, XP effectively reduces the costs associated with late-stage changes. As a key member of the Agile family, XP significantly enhances software quality through the rigorous application of specialized development practices ([Darwish2011](References.md#Darwish2011)).

The Extreme Programming (XP) framework is built upon four core values: Simplicity, Feedback, Communication, and Courage ([Kunwar2018](References.md#Kunwar2018)).

To uphold these values, XP utilizes twelve specific practices: the Planning Game, Metaphor, Small Releases, Testing, Pair Programming, Simple Design, Continuous Integration, Refactoring, Collective Code Ownership, On-site Customer involvement, a 40-hour work week, and strict Coding Standards ([Pekka2002](References.md#Pekka2002))

The XP development lifecycle is organized into six distinct phases ([Faiza2017](References.md#Faiza2017)):

#### (a) Exploration

In this initial stage, which can span from a few weeks to several months, requirements for the Regional Academic Data Management System are gathered as "story cards." These cards describe specific features desired by the Regional Public Sector Client. Concurrently, the Lead Software Engineer of CyberInfoSec assesses the necessary technology stack and the development environment.

#### (b) Planning

Lasting only a few days, this phase involves developers and customers establishing priorities and agreeing on a primary release date. Developers estimate the time required for each story card, and the roadmap for the initial release is finalized.

#### (c) Iterations to Release

This is the execution phase where the schedule is broken down into series of iterations, typically lasting at least four weeks each. The user selects the most beneficial stories, and the developers implement the functionality. This approach of frequent, small releases reduces the risk of "misinformed growth." Coding begins with unit tests, and once iterations are complete, all functionalities are verified against the original story cards.

#### (d) Productionizing

This phase involves rigorous final testing and system execution. Any newly identified changes are evaluated by the user and the Lead Software Engineer of CyberInfoSec for immediate or future inclusion. Any delayed iterations must be accelerated, and late-stage proposals are documented for the next phase.

#### (e) Maintenance

Ongoing support requires active participation from both the developers and the user. The team ensures the system satisfies all requirements and operates efficiently in the live production environment, while any remaining stories are scheduled for future iterations.

#### (f) Death

The final phase occurs when the Regional Public Sector Client has no further stories or demands. All system documentation is clearly scripted, and code alterations cease. "Death" can also occur if the system fails fundamentally or if the project faces a complete halt due to funding constraints.

The following section outlines the advantages and disadvantages associated with the Extreme Programming (XP) methodology ([Kenneth2007](References.md#Kenneth2007)):

| Advantages of XP | Disadvantages of XP |
| --- | --- |
| **Customer Focus:** Prioritizes the specific needs and feedback of the Regional Public Sector Client. | **Scalability Issues:** Proves difficult to implement when developing expansive, large-scale systems. |
| **Simple Design:** Encourages straightforward architecture to minimize complexity. | **Documentation Gaps:** Often lacks formal design documentation; while feasible for small systems, it is often bypassed. |
| **Continuous Measurement:** Maintains ongoing assessment of project progress and software performance. | **Code Readability:** The rapid pace can make it challenging to produce consistently readable code for all team members. |
| **Recurrent Redesign:** Utilizes constant refactoring to improve code structure and maintainability. | **Verification Limits:** Faces a lack of formal inspection processes compared to traditional methodologies. |
| **Frequent Testing:** Ensures high reliability through a rigorous and repetitive testing cycle. | **Model Absence:** Development methods are only briefly described, with few formal models created during the process. |
| **Uninterrupted Reviews:** Employs pair programming to provide real-time code analysis and knowledge sharing. | **Management Support:** The Lead Software Engineer of CyberInfoSec may find it difficult to secure full buy-in from management. |
| **Quality and Teamwork:** Places significant importance on software excellence, clear communication, and collaborative effort. | **Transition and Scope:** Lacks support for transitioning from other models (e.g., Waterfall to XP) and remains heavily code-oriented rather than process-oriented. |

### References

* Adetoba, B. T., and I. O. Ogundele. 2018. “Requirements Engineering Techniques in Software Development Life Cycle Methods: A Systematic Literature Review.” International Journal of Advanced Research in Computer Engineering and Technology 7: 733–43.
* Alan, D., H. W. Barbara, and T. David. 2012. Introduction to Systems Analysis and Design. 4th ed. S.l.:s.n.
* Ashwini, M., M. Gayathri, and P. Chawan. 2012. “Analysis of Various Software Process Models.” IJERA 2 (3): 2015–21.
* Asif, K., Noor-ul-Qayyum, and A. K. Usman. 2012. “An Improved Model for Component Based Software Development.” Software Engineering 2 (4): 138–46.
* Axia. 2018. “Requirements Gathering Techniques - 12 Techniques for Specifying the Requirements for Packaged Systems.” In [Online] Available at: <https://Www.axia-Consulting.co.uk/Html/Requirements_gathering.html>.
* Balaji, S., and M. M. Dr. Sundararajan. 2012. “Waterfall Vs v-Model Vs Agile : A Comparative Study on SDLC.” International Journal of Information Technology and Business Management 2 (1): 26–30.
* Darwish, N. R. 2011. “Improving the Quality of Applying eXtreme Programming (XP) Approach.” International Journal of Computer Science and Information Security 9 (11): 16–22.
* Dharmender, S. K., and A. Mishra. 2006. “Cognitive Software Development Process and Associated Metrics - a Framework.” IEEE 1: 255–60.
* Eid, M. 2015. “Requirement Gathering Methods.” In [Online] Available at: <https://Www.umsl.edu/Sauterv/Analysis/F2015/Requirement>.
* Faiza, A., and A. Shabib. 2017. “SXP: Simplified Extreme Programming Process Model.” International Journal of Modern Education and Computer Science 9 (6): 25–31.
* Islam, N. 2011. “Overview of DSDM : Phases of DSDM Life-Cycle.” [Online] Available at: <https://Nazrul.me/2011/11/22/Dsdm-Overview-Phases-of-Dsdm-Life-Cycle/>.
* Kenneth M., A. 2007. “Agile Development and Extreme Programming : Foundations of Software Engineering.” S.l.:University of Colorado.
* Kunwar, S. 2018. “Extreme Programming (XP) Simplified.” European Journal of Advances in Engineering and Technology 5 (3): 198–206.
* Livermore, J. A. 2008. “Factors That Significantly Impact the Implementation of an Agile Software Development Methodology.” Journal of Software - Academy Publisher 3 (4): 31–36.
* Pekka, A., S. Outi, R. Jussi, and W. Juhani. 2002. “Agile Software Development Methods: Review and Analysis.” S.l.: S.n.
* Qumer, A., and B. Henderson-Sellers. 2008. “An Evaluation of the Degree of Agility in Six Agile Methods and Its Applicability for Method Engineering.” Information and Software Technology 50: 280–95.
* Ramsin, R. 2017. “Agile Methodologies : DSDM - Lecture 12 - Software Development Methodologies.” Sharif University of Technology: Department of Computer Engineering.
* Rastogi, V., A. Singh, and S. Kumar. 2015. “Software Development Life Cycle Models- Comparison, Consequences.” International Journal of Computer Science and Information Security 6 (1): 168–72.
* Render, J. 2018. “A Full Lifecycle Agile Approach: Dynamic Systems Development Methodology (DSDM).” [Online] Available at: <https://Agile-Mercurial.com/2018/07/09/a-Full-Lifecycle-Agile-Approach-Dynamic-Systems-Development-Methodology-Dsdm/>.
* Render, J. 2019. “8 Principles of DSDM - Agile PM.” In [Online] Available at: <https://Agile-Mercurial.com/2019/02/09/the-8-Principles-of-Dsdm/>.
* Ritika, A., and A. Neha. 2016. “Analysis of SDLC Models.” International Journal of Current Engineering and Technology 6 (1): 268–72.
* Sami, M. 2012. “Choosing the Right Software Development Life Cycle Model.” [Online] Available at: <https://Melsatar.blog/2012/03/21/Choosing-the-Right-Software-Development-Life-Cycle-Model/>.
* Saurabh, T., S. R. Santosh, and G. Atul. 2012. “Selecting Requirement Elicitation Techniques for Software Projects.” Conference Paper, 1–10.
* Sivaranjani, J., and S. Rajeswari. 2017. “A Study on Software Development Methodologies.” International Journal of Innovative Research in Computer and Communication Engineering 5 (4): 7727–37.
* Stapleton, J. 1997. “Dynamic System Development Method : The Method in Practice.” S.l.: Addison Wesley - ISBN 0-201-17889-3.
* Waters, K. 2012. “Prioritization Using MoSCow-All about Agile.” In UK: S.n.
* Yu, J. 2018. “Research Process on Software Development Model.” IOP Conference Series: Materials Science and Engineering 1: 1–8.
  