+++
title = "The Test Engineering Dictionary"
description = "Some key test engineering terms:"
author = "Chris Ryan"
date = ""
tags = ["Vocabulary"]
categories = ["Software Testing"]
comments = true
removeBlur = false
[[images]]
  src = "img/TestEngineeringDictionary.jpg"
  alt = "The Test Engineering Dictionary"
  stretch = "horizontal"
+++

### The Test Engineering Dictionary

Teams need to share a vocabulary; so everyone has clarity. Without it, misunderstanding occurs. It's vital to effective communication. Here's a list of some key terms:

<!--more-->

#### Key Terms:

## A

**acceptance criteria**: The exit criteria that a component or system must satisfy in order to be accepted by a user, customer, or other authorized entity. [IEEE 610]

**acceptance testing**: Formal testing with respect to user needs, requirements, and business processes conducted to determine whether or not a system satisfies the acceptance criteria and to enable the user, customers or other authorized entity to determine whether or not to accept the system. [After IEEE 610]

**accessibility testing**: Testing to determine the ease by which users with disabilities can use a component or system. [Gerrard]

**accuracy**: The capability of the software product to provide the right or agreed results or effects with the needed degree of precision. [ISO 9126] See also functionality testing.

**ad hoc testing**: Testing carried out informally; no formal test preparation takes place, no recognized test design technique is used, there are no expectations for results and randomness guides the test execution activity.

**agile testing**: Testing practice for a project using agile methodologies, such as extreme programming (XP), treating development as the customer of testing and emphasizing the test-first design paradigm.

**alpha testing**: Simulated or actual operational testing by potential users/customers or an independent test team at the developers’ site, but outside the development organization. Alpha testing is often employed as a form of internal acceptance testing.

**anomaly**: Any condition that deviates from expectation based on requirements specifications, design documents, user documents, standards, etc. or from someone’s perception or experience. Anomalies may be found during, but not limited to, reviewing, testing, analysis, compilation, or use of software products or applicable documentation. [IEEE 1044] See also defect, deviation, error, fault, failure, incident, problem.

**availability**: The degree to which a component or system is operational and accessible when required for use. Often expressed as a percentage. [IEEE 610]

## B

**back-to-back testing**: Testing in which two or more variants of a component or system are executed with the same inputs, the outputs compared, and analyzed in cases of discrepancies. [IEEE 610]

**behavior**: The response of a component or system to a set of input values and preconditions.

**benchmark test**: (1) A standard against which measurements or comparisons can be made. (2) A test that is be used to compare components or systems to each other or to a standard as in (1). [After IEEE 610]

**beta testing**: Operational testing by potential and/or existing users/customers at an external site not otherwise involved with the developers, to determine whether or not a component or system satisfies the user/customer needs and fits within the business processes. Beta testing is often employed as a form of external acceptance testing in order to acquired feedback from the market.

**black box testing**: Testing, either functional or non-functional, without reference to the internal structure of the component or system.

**boundary value test**: A black box test design technique in which test cases are designed based on boundary values.

**branch testing**: A white box test design technique in which test cases are designed to execute branches.

**business process-based testing**: An approach to testing in which test cases are designed based on descriptions and/or knowledge of business processes.

## C

**Capability Maturity Model (CMM)**: A five level staged framework that describes the key elements of an effective software process. The Capability Maturity Model covers practices for planning, engineering and managing software development and maintenance. [CMM]

**capture/playback tool**: A type of test execution tool where inputs are recorded during manual testing in order to generate automated test scripts that can be executed later (i.e. replayed). These tools are often used to support automated regression testing.

**classification tree method**: A black box test design technique in which test cases, described by means of a classification tree, are designed to execute combinations of representatives of input and/or output domains. [Grochtmann]

**code coverage**: An analysis method that determines which parts of the software have been executed (covered) by the test suite and which parts have not been executed, e.g. statement coverage, decision coverage or condition coverage.

**component integration testing**: Testing performed to expose defects in the interfaces and interaction between integrated components.

**component specification**: A description of a component’s function in terms of its output values for specified input values under specified conditions, and required non-functional behavior (e.g. resource-utilization).

**component testing**: The testing of individual software components. [After IEEE 610]

**concurrency testing**: Testing to determine how the occurrence of two or more activities within the same interval of time, achieved either by interleaving the activities or by simultaneous execution, is handled by the component or system. [After IEEE 610]

**condition testing**: A white box test design technique in which test cases are designed to execute condition outcomes.

**configuration management**: A discipline applying technical and administrative direction and surveillance to: identify and document the functional and physical characteristics of a configuration item, control changes to those characteristics, record and report change processing and implementation status, and verify compliance with specified requirements. [IEEE 610]

**coverage**: The degree, expressed as a percentage, to which a specified coverage item has been exercised by a test suite.

## D

**data driven testing**: A scripting technique that stores test input and expected results in a table or spreadsheet, so that a single control script can execute all of the tests in the table. Data driven testing is often used to support the application of test execution tools such as capture/playback tools. [Fewster and Graham] See also keyword driven testing.

**decision condition testing**: A white box test design technique in which test cases are designed to execute condition outcomes and decision outcomes.

**decision table**: A table showing combinations of inputs and/or stimuli (causes) with their associated outputs and/or actions (effects), which can be used to design test cases.

**defect**: A flaw in a component or system that can cause the component or system to fail to perform its required function, e.g. an incorrect statement or data definition. A defect, if encountered during execution, may cause a failure of the component or system.

## E

**equivalence partition**: A portion of an input or output domain for which the behavior of a component or system is assumed to be the same, based on the specification.

**error**: A human action that produces an incorrect result. [After IEEE 610]

**error seeding**: The process of intentionally adding known defects to those already in the component or system for the purpose of monitoring the rate of detection and removal, and estimating the number of remaining defects. [IEEE 610]

**exercised**: A program element is said to be exercised by a test case when the input value causes the execution of that element, such as a statement, decision, or other structural element.

**exhaustive testing**: A test approach in which the test suite comprises all combinations of input values and preconditions.

**exploratory testing**: Testing where the tester actively controls the design of the tests as those tests are performed and uses information gained while testing to design new and better tests. [Bach]

## F

**fault tolerance**: The capability of the software product to maintain a specified level of performance in cases of software faults (defects) or of infringement of its specified interface. [ISO 9126] See also reliability.

**fault tree analysis**: A method used to analyze the causes of faults (defects).

**feature**: An attribute of a component or system specified or implied by requirements documentation (for example reliability, usability or design constraints). [After IEEE 1008]

**functional requirement**: A requirement that specifies a function that a component or system must perform. [IEEE 610]

**functional testing**: Testing based on an analysis of the specification of the functionality of a component or system. See also black box testing.

## G

**glass box testing**: See white box testing.

## H

**heuristic evaluation**: A static usability test technique to determine the compliance of a user interface with recognized usability principles (the so-called “heuristics”).

## I

**impact analysis**: The assessment of change to the layers of development documentation, test documentation and components, in order to implement a given change to specified requirements.

**incremental development model**: A development life cycle where a project is broken into a series of increments, each of which delivers a portion of the functionality in the overal project requirements. The requirements are prioritized and delivered in priority order in the appropriate increment. In some (but not all) versions of this life cycle model, each subproject follows a ‘mini V-model’ with its own design, coding and testing phases.

**incremental testing**: Testing where components or systems are integrated and tested one or some at a time, until all the components or systems are integrated and tested.

**incident management**: The process of recognizing, investigating, taking action and disposing of incidents. It involves recording incidents, classifying them and identifying the impact. [After IEEE 1044]

**integration testing**: Testing performed to expose defects in the interfaces and in the interactions between integrated components or systems. See also component integration testing, system integration testing.

**interface testing**: An integration test type that is concerned with testing the interfaces between components or systems.

## L

**load test**: A test type concerned with measuring the behavior of a component or system with increasing load, e.g. number of parallel users and/or numbers of transactions to determine what load can be handled by the component or system.

## M

**maintenance**: Modification of a software product after delivery to correct defects, to improve performance or other attributes, or to adapt the product to a modified environment. [IEEE 1219]

**maintenance testing**: Testing the changes to an operational system or the impact of a changed environment to an operational system.

**memory leak**: A defect in a program’s dynamic store allocation logic that causes it to fail to reclaim memory after it has finished using it, eventually causing the program to fail due to lack of memory.

**metric**: A measurement scale and the method used for measurement. [ISO 14598]

## N

**negative testing**: Tests aimed at showing that a component or system does not work. Negative testing is related to the testers’ attitude rather than a specific test approach or test design technique. [After Beizer].

**non-functional testing**: Testing the attributes of a component or system that do not relate to functionality, e.g. performance, security, reliability, efficiency, usability, maintainability and portability.

## O

**operational profile testing**: Statistical testing using a model of system operations (short duration tasks) and their probability of typical use. [Musa]

**operational testing**: Testing conducted to evaluate a component or system in its operational environment. [IEEE 610]

## P

**page object model (pom)**: A design pattern for user interface automation that aims to separate UI elements/HTML (which can change frequently) and the interaction with them, from the automation application components. The pattern provides encapsulation and abstraction which prevents code duplication and aids maintainability.

**pass/fail criteria**: Decision rules used to determine whether a test item (function) or feature has passed or failed a test. [IEEE 829]

**performance testing**: The process of testing to determine the performance of a software product. See efficiency testing.

**phase test plan**: A test plan that typically addresses one test level.

**priority**: The level of (business) importance assigned to an item, e.g. defect.

## Q

**quality**: The degree to which a component, system or process meets specified requirements and/or user/customer needs and expectations. [After IEEE 610]

**quality assurance**: Part of quality management focused on providing confidence that quality requirements will be fulfilled. [ISO 9000]

**quality management**: Coordinated activities to direct and control an organization with regard to quality. Direction and control with regard to quality generally includes the establishment of the quality policy and quality objectives, quality planning, quality control, quality assurance and quality improvement. [ISO 9000]

## R

**random testing**: A black box test design technique where test cases are selected, possibly using a pseudo-random generation algorithm, to match an operational profile. This technique can be used for testing non-functional attributes such as reliability and performance.

**regression testing**: Testing of a previously tested program following modification to ensure that defects have not been introduced or uncovered in unchanged areas of the software, as a result of the changes made. It is performed when the software or its environment is changed.

**requirement**: A condition or capability needed by a user to solve a problem or achieve an objective that must be met or possessed by a system or system component to satisfy a contract, standard, specification, or other formally imposed document. [After IEEE 610]

**requirements-based testing**: An approach to testing in which test cases are designed based on test objectives and test conditions derived from requirements, e.g. tests that exercise specific functions or probe non-functional attributes such as reliability or usability.

**risk analysis**: The process of assessing identified risks to estimate their impact and probability of occurrence (likelihood).

**risk-based testing**: Testing oriented towards exploring and providing information about product risks. [After Gerrard]

**risk control**: The process through which decisions are reached and protective measures are implemented for reducing risks to, or maintaining risks within, specified levels.

**risk management**: Systematic application of procedures and practices to the tasks of identifying, analyzing, prioritizing, and controlling risk.

**root cause**: An underlying factor that caused a non-conformance and possibly should be permanently eliminated through process improvement.

## S

**safety**: The capability of the software product to achieve acceptable levels of risk of harm to people, business, software, property or the environment in a specified context of use. [ISO 9126]

**scalability testing**: Testing to determine the scalability of the software product.

**security**: Attributes of software products that bear on its ability to prevent unauthorized access, whether accidental or deliberate, to programs and data. [ISO 9126]

**security testing**: Testing to determine the security of the software product.

**smoke test**: A subset of all defined/planned test cases that cover the main functionality of a component or system, to ascertaining that the most crucial functions of a program work, but not bothering with finer details. A daily build and smoke test is among industry best practices. See also intake test.

**state transition testing**: A black box test design technique in which test cases are designed to execute valid and invalid state transitions. See also N-switch testing.

**static analysis**: Analysis of software artifacts, e.g. requirements or code, carried out without execution of these software artifacts.

**stress testing**: Testing conducted to evaluate a system or component at or beyond the limits of its specified requirements. [IEEE 610]

**stub**: A skeletal or special-purpose implementation of a software component, used to develop or test a component that calls or is otherwise dependent on it. It replaces a called component. [After IEEE 610]

**system integration testing**: Testing the integration of systems and packages; testing interfaces to external organizations (e.g. Electronic Data Interchange, Internet).

**system testing**: The process of testing an integrated system to verify that it meets specified requirements. [Hetzel]

## T

**technical review**: A peer group discussion activity that focuses on achieving consensus on the technical approach to be taken. A technical review is also known as a peer review. [Gilb and Graham, IEEE 1028]

**test automation**: The use of software to perform or support test activities, e.g. test management, test design, test execution and results checking.

**test case**: A set of input values, execution preconditions, expected results and execution postconditions, developed for a particular objective or test condition, such as to exercise a particular program path or to verify compliance with a specific requirement. [After IEEE 610]

**test charter**: A statement of test objectives, and possibly test ideas. Test charters are amongst other used in exploratory testing. See also exploratory testing.

**test condition**: An item or event of a component or system that could be verified by one or more test cases, e.g. a function, transaction, quality attribute, or structural element.

**test data**: Data that exists (for example, in a database) before a test is executed, and that affects or is affected by the component or system under test.

**test harness**: A test environment comprised of stubs and drivers needed to conduct a test.

**test infrastructure**: The organizational artifacts needed to perform testing, consisting of test environments, test tools, office environment and procedures.

**test level**: A group of test activities that are organized and managed together. A test level is linked to the responsibilities in a project. Examples of test levels are component test, integration test, system test and acceptance test. [After TMap]

**test log**: A chronological record of relevant details about the execution of tests. [IEEE 829]

**test performance indicator**: A metric, in general high level, indicating to what extent a certain target value or criterion is met. Often related to test process improvement objectives, e.g. Defect Detection Percentage (DDP).

**test phase**: A distinct set of test activities collected into a manageable phase of a project, e.g. the execution activities of a test level. [After Gerrard]

**test plan**: A document describing the scope, approach, resources and schedule of intended test activities. It identifies amongst others test items, the features to be tested, the testing tasks, who will do each task, degree of tester independence, the test environment, the test design techniques and test measurement techniques to be used, and the rationale for their choice, and any risks requiring contingency planning. It is a record of the test planning process [After IEEE 829]

**test process**: The fundamental test process comprises planning, specification, execution, recording and checking for completion. [BS 7925/2]

**test run**: Execution of a test on a specific version of the test object.

**test script**: Commonly used to refer to a test procedure specification, especially an automated one.

**test suite**: A set of several test cases for a component or system under test, where the post condition of one test is often used as the precondition for the next one.

**top-down testing**: An incremental approach to integration testing where the component at the top of the component hierarchy is tested first, with lower level components being simulated by stubs. Tested components are then used to test lower level components. The process is repeated until the lowest level components have been tested.

## U

**usability testing**: Testing to determine the extent to which the software product is understood, easy to learn, easy to operate and attractive to the users under specified conditions. [After ISO 9126]

**use case testing**: A black box test design technique in which test cases are designed to execute user scenarios.

**user test**: A test whereby real-life users are involved to evaluate the usability of a component or system.

## V

**V-model**: A framework to describe the software development life cycle activities from requirements specification to maintenance. The V-model illustrates how testing activities can be integrated into each phase of the software development life cycle.

**validation**: Confirmation by examination and through provision of objective evidence that the requirements for a specific intended use or application have been fulfilled. [ISO 9000]

**verification**: Confirmation by examination and through the provision of objective evidence that specified requirements have been fulfilled. [ISO 9000]

## W

**walkthrough**: A step-by-step presentation by the author of a document in order to gather information and to establish a common understanding of its content. [Freedman and Weinberg, IEEE 1028]

**white box testing**: Testing based on an analysis of the internal structure of the component or system.
