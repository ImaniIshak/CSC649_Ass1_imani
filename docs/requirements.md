## PART B: REQUIREMENTS

**B1. FUNCTIONAL REQUIREMENTS**

**FR1** - The system shall display real-time service disruption alerts on the main screen to know about any interruptions to train services.<br>
**FR2** - The system shall automatically generate alternative routes using other rail lines and Rapid KL feeder buses when train service is disrupted.<br>
**FR3** - The system shall display crowd levels at transit station platforms and feeder bus stops in three categories (Low, Moderate and High).<br>
**FR4** - The system shall let users to enter their current location and destination in a text search bar.<br>
**FR5** - The system shall show and compare the estimated time of arrival (ETA) for the original disrupted route and the suggested alternative routes.<br><br>

**B2. NON-FUNCTIONAL REQUIREMENTS**

**NFR1** - The system shall handle route and alternative route requests quickly, so that the information and recommendations appear without any unnecessary delay.<br>
**NFR2** - The system shall have a simple, user-friendly interface with clearly labelled search bar, buttons and information displays, so users can understand and move around with the system easily.<br>
**NFR3** - When updated information cannot be retrieved, the system shall show the most recent transport information available and let users know it may be out of date..<br>
**NFR4** - The system shall stay accessible under normal operation conditions, so users can check disruption alerts, search for route and get alternative route recommendations whenever they need them.<br><br>

**B3. USER STORIES**

1. As a daily commuter user, I want to search for my starting point and destination using a search bar, so that I can plan my journey quickly without need to manually search through maps. (FR4)

**Acceptance Criteria:**<br>
•	The system should let users to type their current location and destination through the search box.<br>
•	The system shall show matching location suggestions when users enter their starting point and destination<br>

2.	As a public transportation user, I want to get alternative route recommendations when a train is disrupted, so that I can continue my journey without have to figure out another route by myself. (FR2)<br>

**Acceptance Criteria:** <br>
•	The system shall generate alternative route recommendations when a disruption is detected on train service.<br>
•	The suggestion routes should include any available alternative rail line and Rapid KL feeder buses.

3.	As a public transport user, I want to check how crowded station platforms and feeder bus stops are, so that I can avoid packed stations and pick a less crowded option. (FR3)<br>

**Acceptance Criteria:** <br>
•	The system show crowd  density information for the station platform and feeder bus stops.<br>
•	The system shall sort crowd level into three categories which is Low, Moderate and Heavy.



