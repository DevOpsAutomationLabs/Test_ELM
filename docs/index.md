# Connect DevOps Test with Engineering Test Management (ETM) to accelerate the test cycle automating test execution.

### About this integrated IBM Testing Solution

**IBM Engineering Test Management Overview**</br>
| **Product Name** | <div style="width:250px">**Description**</div> | **Additional Information** |
|:-------------:|:------------- |:------------- |
| Engineering Test Management | ETM is a collaborative, web-based tool for planning, constructing, managing, and executing tests throughout the development lifecycle for test teams of all sizes. To learn more about Engineering Test Management | [Overview](https://www.ibm.com/docs/en/engineering-lifecycle-management-suite/test-management/7.1.0?topic=overview-engineering-test-management) |

**IBM DevOps Test Automation Overview**

| **Product Name** | <div style="width:250px">**Description**</div> | **Additional Information** |
|:-------------:|:------------- |:------------- |
| DevOps Test Hub | Test Hub, a web-based continuous testing platform, enables test teams to run a breadth of tests that includes API, functional, and performance tests as well as bringing together test data, test environments, and test runs and reports into a single, web-based browser for testers and non-testers. | [Overview](https://www.ibm.com/docs/en/devops-test-hub/11.0.6?topic=guide-introduction-devops-test-hub) |
| DevOps Test UI | Test UI is an object-oriented automated testing tool that tests a wide range of desktop, Web, and mobile applications. Test UI provides automated testing capabilities for functional, regression, GUI, and data-driven testing. | [Overview](https://www.ibm.com/docs/en/SSBLQQ_11.0.6/docs/topics/IntrotoRobotJ.html) |
| DevOps Test Integrations and APIs | Test Integrations and APIs is an integration testing and virtualization tool that includes capabilities to automate and run tests earlier and more often to find problems sooner in the development cycle.| [Overview](https://www.ibm.com/docs/en/devops-test-workbench/11.0.6?topic=started-overview-devops-test-integrations-apis) |
| DevOps Test Performance | Test Performance is a scripting-free environment for automating load and scalability testing of web, ERP, and server-based software applications. Test Performance provides rich and customizable reporting to help you identify the presence and cause of system bottlenecks. It captures the network traffic that is rendered when the application under test interacts with a server. This network traffic is then emulated on multiple virtual users while you play back the test. | [Overview](https://www.ibm.com/docs/en/devops-test-workbench/11.0.6?topic=started-devops-test-performance-overview) |

### Why integrate IBM DevOps Test Automation with IBM Engineering Test Management
While test automation is not a "silver bullet" replacement all manual testing and is often misused as a means or reason to reduce the size of test teams, test automation does provide organizations with many benefits, including:</br>
| **Value Proposition** | **Explaination** |
|:-------------:|:------------- |
| Saving organizations time and money | While not all tests should be automated or can be automated, automated testing reduces the cost of testing by reducing the expensive of manual effort for those tests which are candidates for test automation. |
| Helping test increase test coverage | Freeing testers from having to execute test scripts manually allows them to focus on improving the overall test effort. |
| Improving testing accuracy | Let's face it, people make mistakes. Where automated testing is software designed to repeat a series of steps against the application under test over and over. |
| Accelerating feeback on software quality | As automated testing is faster, can be run as part of a deployment process, and consistently executes to verify software quality, the results of those test executions can be shared directly back to the development team providing continuous feedback on software quality. |
| Improving team morale | By allowing Testers to focus on improving the testing practice and providing Developers accelerated feedback on the sofware they are developing can only lead to improved morale. |

### About this workbook
This workbook is limited to sharing details for how engineering teams can connect automated test scripts (authored in one of the many DevOps Test solutions) with test cases (managed in Engineering Test Management) for the purpose of automating test execution and delivering feedback on software quality to developers faster. If you are interested in learning more about test management and test automation capabilities offered by IBM Software:</br> 
To learn more about test management in ETM visit[IBM's ETM documentation webpage.](https://www.ibm.com/docs/en/engineering-lifecycle-management-suite/test-management/7.1.0?topic=overview-engineering-test-management). </br>
To learn more about test automation with DevOps Test visit [IBM's DevOps Test documentation webpage](https://www.ibm.com/docs/en/devops-test-workbench/11.0.6). </br>

**In this workbook, you will learn how to:**</br>
1. Configure Test Adapters creating a communication channel between ETM AND DevOps Test
2. Add and automated test script to ETM and link to the DevOps Test script
3. Execute the test from ETM and observe the DevOps Test autoamted test playback
4. Review the test execution results returned to ETM from DevOps Test
