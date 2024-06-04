<h1>Testing Project for Opensky.com</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **https://opensky.com/**

Tools used: Jira, Zephyr Squad, Google Slides.

**<h2>Functional specifications:</h2>**

The below story's was created in Jira and describes the functional specifications of the "Caracteristics, Constraints and Checkout flow for a user " module's, for which the final project is performed upon.

![image](https://github.com/OctavianGriga/Octavian-Griga/assets/128740240/9a7641f8-cd2e-4852-a568-fd93d47e3df3)
![image](https://github.com/OctavianGriga/Octavian-Griga/assets/128740240/47ff00b1-d46a-453a-bb8a-28a35dde2e8b)

Here you can find the release that was created for this project:

![image](https://github.com/OctavianGriga/Octavian-Griga/assets/128740240/e644eb56-4575-4dd7-b37b-eeb6ea59c64e)




**<h2>Testing process</h2>**

The test process was performed based on the standard test process as described below.

**<h3>1.1 Test planning</h3>**

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **https://docs.google.com/presentation/d/1GP44-vzpmuDYUpKp-sZC1dg_a5oWn8IkESrMXzVBUNQ/edit#slide=id.p**

**<h4>1.1.1. Roles asigned to the project and persons allocated</h4>**

<ul>
  <li>Dumitrescu Sorin- Project manager</li> 
 <li>Costin Andreea- Product owner</li>
 <li>Banciulesc Vasile- Software developer</li>
 <li>Griga Octavian- QA Engineer</li>
</ul>

**<h4> 1.1.2 Entry criteria defined </h4>**

  <li>Availability of the requirements document (both functional and non-functional).</li>
  <li>Acceptance criteria defined.</li>
  <li>Availability of the application architecture document.</li>
  <li>Performant hardware.</li>
  <li>Availability of the team.</li>
  <li>Windows vesions 10 or higher.</li>

**<h4> 1.1.3 Exit criteria defined </h4>**

  <li>85% passed test cases.</li>
  <li>Test cases must be written and examined.</li>
  <li>No Critical test case open.</li>
  <li>Test data needs to be prepared and recognized.</li>
  <li>Test closure report.</li>

**<h4> 1.1.4 Test scope</h4>**

**<h5> Tests in scope: </h5>**

  <li>Unit Testing (we test the smallest functional unit of code and helps ensure code quality, and it's an integral part of software development).</li>
  <li>We test module within the application (we are testing a subset of UI elements that together builds the complete user interface).</li>
  <li>Integration testing(we test if the components of the software unified as a group they are working properly together.</li>
  <li>We are testing if 1 single user can log in.</li>
  <li>We are testing if the information is deleted at the time of logging out.</li>
  <li>we are testing the process of complete order and payment.</li>

**<h5>Tests not in scope: </h5>**

  <li>Performance Testing(performance testing check that the software is literally performing at optimal levels: loading speed, software crash rates, memory, latency time etc).</li>
  <li>Load Testing(Load tests check how well a system handles increased load, such as from too many users logging in and shopping at the same time).</li>
  <li>Security Testing(Security tests check the software’s weaknesses and vulnerabilities to external attacks).</li>
  <li>Responsive Testing(Responsive tests monitor and evaluate if an app/site renders well on screen sizes and resolutions offered by different devices, mobile, tablets, desktops).</li>

<h4>1.1.5 Risks detected</h4>

**<h5>Project risks:</h5>**

<li>Riscul lipsei de comunicare și colaborare intre angajați.</li>
<li>Riscul lipsei de resurse suficiente - fonduri, personal.</li>
<li>Riscul de a avea o calitatea scăzuta a codului.</li>
<li>Riscul schimbării cerințelor de business foarte frecvent.</li>
<li>Riscul lipsei de experienta a testerilor și presiune a timpului.</li>


 **<h5> Product risks: </h5>**
 <li>Riscul incapacității produsului de a îndeplini așteptările clientului.</li>
 <li>Riscul de performanța scăzuta a aplicației.</li>
 <li>Riscul de a pierde clienții din cauza problemelor care nu au fost rezolvate.</li>
 <li>Riscul softului de a nu își îndeplini funcțiile pentru care a fost creat conform specificaților.</li>
 <li>Riscul de a avea un timp de răspuns prea mare pentru funcțiile importante.</li>


**<h4>1.1.6 Evaluating entry criteria</h4>**

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

**<h3>1.2 Test Monitoring and Control<h3>**
In this phase, the project is monitored and controlled to ensure that it is delivered according to plan. The project team will monitor performance, budget and delivery timelines, identifying issues and risks and implementing corrective actions if necessary.

**Test monitoring:**
Monitoring is the process of evaluating test activities and efforts.
The goal is to track the current progress of testing activity, find and track relevant metrics, estimate future actions based on those metrics, and provide feedback to the team.
To monitor effectively, we follow these steps:
<li>Create a monitoring plan.</li>
<li>Updates the progress log.</li>
<li>Analyze the recording and make adjustments.</li>
<li>Produce a report.</li>

**Test control:**
After monitoring, we enter the control phase of the test.
<li>Here, we prioritize testing activities, review the testing schedule, and make other changes to improve the quality and efficiency of the future testing process.</li>
<li>Control is a feedback loop that helps us keep the project on the tracks.</li>

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**
