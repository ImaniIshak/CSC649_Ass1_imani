## C: SPEACIALIZED TECHNOLOGY 

**C1. CONCEPT OF DECISION SUPPORT SYSTEM (DSS)**<br>

A Decision Support System (DSS) is a computer-based system that helps people to make decisions by gathering, processing and analysing important information. It supports the decision-making process by weighing up different options and giving users the information they need to pick a suitable one.

According to Kovari (2024), Ai based DSS can analyze large amounts of information and offer recommendations to support the decision-making. However, the accuracy, transparency and liability of those recommendations are important to keeping user trust.

In the purposed of MyRapid PLUSE Decision Support System (DSS) aims to help public transport users make a better travel decisions. For example, when train service is disrupted, the system can gather the available transport information and generate alternative route recommendations. Users then can compare the options before choosing the route they prefer.

![Flowchart of the MyRapid PLUSE DSS](System_flowchart.drawio.png)<br>
Diagram 1: Flowchart of the MyRapid PLUSE DSS

**Key Concepts of Decision Support System (DSS)**

**1.	Data-Driven Decision Making**<br>
Data driven decision-making means relevant information to guide a decision. A DSS collects and examines the available data to give users useful information. In the proposed for MyRapid PULSE system, transport information such as train service disruptions, alternative routes, estimated travel time and crowd level is used to support route recommendations.

**2.	Interactive Decision Supports**<br>
Interactive decision support lets users communicate with the system by entering information and viewing the results or recommendations provided by the system. In this system, users type their starting point and destination into a search bar and the system then shows the relevant route information and alternative routes.

**3.	Human Decision Making**
A DSS is built to support human decisions, not replace them. It offers useful information and recommendations, but the final choice stays with the user, based on their own needs and preferences. In this system, users can view the recommended routes and choose whether to accept or decline them.


**C2. FRAMEWORK, MODELS, METHODS AND TOOLS**

**1.	Framework**

**•	Human-in-the-Loop (HITL) Framework**<br>
The Human-in-the-Loop (HITL) framework keep users involved in the decision-making process. The system offers recommendations but users need to make the final decision. In the system, passengers can review the alternative routes, compare the ETAs and the crowd levels and decide whether to accept or reject the suggestions.

**•	Data Driven Decision Framework**<br>
This framework relies in available information rather than guesswork to support decisions. In this system, transport information such as service availability, frequency and route conditions will analysed to produce a suitable alternative routes.

**2.	Models**

**•	Four-Component DSS Architecture Model**<br>
This model is made up of four components which is Database, Model base , Knowledge Base and Graphical User Interface (GUI). The database store transport information, the Model Base will handle route calculations, the Knowledge Base holds the decision rules and the GUI presents recommendations to passengers. Together, these components support the decision-making process.

**•	Multi-Criteria Decision Analysis (MCDA) Model**
MCDA evaluates different options based on some criteria. In this project, alternative routes are compared based on ETA, number of transfers and station crowd level, which helps passengers choose a route that suits their preferences.

**3.	Methods**

**•	Rule-Base Reasoning and Decision Tree Classification**<br>
Rule-based reasoning use IF-THEN condition to decide what the system should do. For example, if a train is delayed by more than 10 minutes, the system will suggest alternative routes. Then, Decision tree classification is used to sort information such as station crowd levels into Low, Moderate and Heavy.

**•	Data Preprocessing and Real-Time Stream Processing**<br>
Data processing clean and organize the information, while real-time stream processing handle data as it continuously comes in. In the proposed system, these methods prepare transport information, such as train disruptions and station crowd levels before itshown to the users.



**4.	Tools**

**•	Figma **<br>
Figma used to design the app interface including the main page with the journey search screen, the route recommendations screen and the screen shown during crowd alerts.

**•	Draw.io**<br>
This tool is used to create system diagrams, decision trees and flowcharts that explain how the system is structured and how it processes the work.

**•	Visual Studio Code**<br>
Visual Studio Code is used to edit data files, build the system and test the system logic.

**C3. FIT YOUR PROBLEM**

**1.	How the Technology can address the problem.**<br>

The purposed MyRapid PLUSE DSS tackels the difficulty public transport users face in finding other alternative routes during train service disruptions. It analyses transport information and suggests other routes using different rail lines and Rapid KL feeder buses. It also shows ETA comparisons and crowd levels to help passengers make better travel decisions without manually checking different transport sources.

**2.	Key Benefits**<br>

**Fast Making Decision** - The system will compare some alternative routes base on ETA, transportation connections and crowd levels to make it easier for users to pick suitable routes.<br>

**Reduce Crowding** - Crowd indicators help passengers spot less crowded stations and feeder bus stops.<br>

**User Control** - Based on the Human in-the-Loop approach, passengers can review each recommendation and decide whether to accept or reject it.<br>

**3.	Limitations and Risks**<br>

**System Availability Risks** - Technical issues such as app errors or network problems may stop the users from getting route recommendations when they need them.<br>

**Information Overhead** - Showing too much information at once may confuse the users, especially during service disruption.<br>

**Limited Recommendation Flexibility** - The system may not fully account for personal preferences, such as avoiding multiple transfers, preferring walking routes or choosing more accessible stations. This system may not meet every passenger’s need.<br>

**Data Privacy and Security** - Using passenger location and journey information could put their privacy at risk if the data is not properly protected.<br>

**4.	Decision Support System (DSS) VS Deep Learning**<br>

   ![table](System_flowchart.drawio.png)<br>

   I would choose decision Support System (DSS) as approach for this project because it is easier to understand and more suitable for the system. It does not need a large historical dataset for model training and lets passengers compare route suggestions using clear information such as ETA and crowd levels. 

   
