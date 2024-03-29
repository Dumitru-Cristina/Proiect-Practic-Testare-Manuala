

# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://altex.ro/


**The final project will be split into 2 sections: [Testing section](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/tree/main#1-testing-section) and [Conclusions](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/tree/main#2-conclusions).**

Tools used: JIRA, Zephyr Squad

# Functional specifications

-> The below Epic was created in JIRA and describes the functional specifications of the Comenzi module, for which the final project is performed upon.

![image](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/assets/130222619/84b5c163-8277-4ae8-b155-2ded89d9d04d)


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the Comenzi module from the http://Altex.ro website.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan


#### 1.1.1 Roles assigned to the project and persons allocated

* Project manager – Marian Dragomir
* Product owner – Ana Maria Dumitrache
* Software developer – Ioana Lazar
* QA Engineer – Cristina Dumitru

#### 1.1.2 Entry criteria defined

* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated

#### 1.1.3 Exit criteria defined

* all tests have been executed
* all resolved bugs have been re-tested and approved by the QA team
* deadline was reached
* no detected major risk remained un-mitigated
* exploratory regression testing must be performed on the Cont module, which includes the Comenzi section

#### 1.1.4 Test scope

* __Tests in scope:__ All the feature of Comenzi module which were defined in software requirement specs need to be tested: functional testing and GUI testing 
* __Tests not in scope:__ Performance testing, integrations of the Comenzi module with other modules, compatibility testing with multiple browsers, API testing

#### 1.1.5 Risks detected

•	Project risks: 
* The risk that the business requirements are unclear, ambiguous and incomplete
* The risk that the configuration of the test environment is inadequate
* The risk that team members are inexperienced
* Tight deadline risk
* Risk of poor management
   
•	Product risks: 
* Risk of incorrect display of orders
* Risk of missing information for certain orders
* Security risk
* Risk of incorrect display of order statuses
* Risk of complex and unintuitive interface



#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 60% of the test cases were executed, on 1st of June 2023: 

![image](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/assets/130222619/d4a2f791-a440-43b1-a181-950da657be36)


## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Comenzi module. The following test conditions were found:

*![image](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/assets/130222619/3c6f3fb0-e115-45ac-b1b2-9ffd1e5b274b)


## 1.4 Test Design

Functional test cases were created in Zephyr Squad. 

The test cases with steps can be viewed here: [Comenzi_test_cases.pdf](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/blob/main/Comenzi_test_cases.pdf)

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running:   https://altex.ro/
* Access to the testing environment is given: 
   * Email :   fghjyt@yahoo.com| 
   * Password : 1234
* Cycle summary was created
* Test cases were added to the cycle summary


## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [Comenzi_cycle_summary_execution.pdf](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/blob/main/Comenzi_cycle_summary%20_execution.pdf)
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [Comenzi_created_bugs.pdf](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/blob/main/Comenzi_created_bugs.pdf)
   * The Comenzi section does not display any message when the customer has not placed any order yet
   * The user cannot cancel an order that has not been shipped yet from the Comenzi section
* Full regression testing is needed after the bugs are fixed



## 1.7 Test Completion`12

* Exit criteria was evaluated and passed
* The traceability matrix was generated and can be found here: [Traceabilitiy matrix.xlsx](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/blob/main/Traceability%20matrix.xlsx)
* Test execution chart was generated, the final report shows that a number of 2 tests have failed of a total of 15
* A number of 15 test cases were planned for execution and all of them were executed
* A number of 2 total bugs were found, from which the priority is: 1 is medium and 1 is high

![image](https://github.com/Dumitru-Cristina/Proiect-Practic-Testare-Manuala/assets/130222619/be180141-53f1-42ff-bce0-d173043276c1)


# 2 Conclusions

During testing, all 6 stories were covered, and 15 tests were written and executed.

In the testing process, a total of 2 bugs were identified, whose priorities are: 1- medium and 1- high, each having an impact on functionality and user experience.

* The first bug consists in the lack of a message or information when a customer has not yet placed an order. The absence of any message or indicator could lead to frustration and confusion, ultimately leading to a negative user experience.
* The second bug consists in the inability of the user to cancel an order that has not yet been shipped. It prevents users from efficiently managing their orders, potentially causing frustration and dissatisfaction. Users expect to be in control of their orders and may lose confidence in the platform due to this limitation.

Addressing these issues promptly is essential to ensure a seamless user experience and maintain user trust. Rigorous patch testing, coupled with comprehensive regression testing, is vital to verify that patches fix problems without introducing new defects. Collaboration between the development and testing teams is imperative to quickly resolve these errors and provide an accurate, functional and easy-to-use order tracking feature for Altex.ro users.

