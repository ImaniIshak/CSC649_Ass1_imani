PART B: REQUIREMENTS

B1. FUNCTIONAL REQUIREMENTS

FR1 - The system shall display real time service disruption alerts on the main screen to inform users of any train service interruptions.
FR2 - The system shall automatically generate alternative routes using other rail line and Rapid KL feeder buses when train service disruption happens.
FR3 - The system shall display crowd levels at transit station platforms and feeder bus stops using three categories which is Low, Moderate and High.
FR4 - The system shall allow users to enter their current location and destination using text search bar.
FR5 - The system shall display and compare the estimated time of arrival (ETA) for the original disrupted route and the suggested alternative routes.

B2. NON-FUNCTIONAL REQUIREMENTS

NFR1 - The system shall process user route and alternative route requests effectively, to ensure that the requested transportation information and recommendations are displayed without any unnecessary delays.
NFR2 - The system shall provide a simple and user friendly interface with clear labelled search bar, buttons and information displays, that allow the users to understand and navigate the system easily.
NFR3 - The system shall display the most recent transportation information that available when updated information cannot be retrieved. It shall also notify the users that the displayed information may be outdated.
NFR4 - The system shall remain accessible during normal operation conditions, that allow the users to access service disruption alerts, route searches and route alternative recommendations when needed.

USER STORIES

1. As a daily commuter user, I want to search for my location and destination using a search bar, so that I can quickly plan my journey without needing to manually search through maps. (FR4)

Acceptance Criteria: 
•	The system should allow users to enter current location and destination through the search box.
•	The system shall display matching location suggestions when users enter a location and destination

2.	As a public transportation user, I want to receive alternative route recommendations when train service is disrupted, so that I can continue my journey without having to figure out other alternative routes manually. (FR2)

Acceptance Criteria: 
•	The system shall generate alternative route recommendations when a train service detected a disruption.
•	The system should include an available alternative rail line and Rapid KL feeder buses in the suggested routes.

3.	As a public transportation user, I want to check the crowd density levels for station platforms and feeder bus stops, so that I can avoid overcrowded stations and choose a less crowded transit option. (FR3)

Acceptance Criteria: 
•	The system should display crowd level density information for the station platform and feeder bus stops.
•	The system shall classify crowd level into three categories which is Low, Moderate and High.



