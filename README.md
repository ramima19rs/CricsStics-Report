# CricStics – A web-based application for ICC Men's Cricket World Cup 2023

1. Introduction
CricStics is a web-based application, which aims to provide a comprehensive platform devoted to one of the world's most esteemed sporting events—the ICC Men's Cricket World Cup 2023. This website intends to provide a one-stop solution for fans, teams, sponsors, and other stakeholders to access information, schedules, scores, highlights, and many more. As the tournament's primary digital interface, the website must provide a seamless user experience, great performance, and abundant content to meet the different needs of its global audience. This SRS defines the specific requirements, functionalities, and constraints required for the website's design, development, and maintenance.
Purpose: 
The purpose of this document is to detail the requirements for the ICC Men's Cricket World Cup Website. This website aims to be the primary portal for fans, teams, and stakeholders to access information, news, schedules, scores, and other related details about the ICC Men's Cricket World Cup.
Scope of project:
The website will provide a comprehensive platform covering all facets of the ICC Men's Cricket World Cup. It will cater to fans looking for match schedules, live scores, team stats, player profiles, and news updates. Additionally, the platform will serve as a hub for ticket bookings, merchandise purchases, and streaming if permissible.
Target audience: Cricket enthusiasts, journalists, and teams participating in the ICC Men's Cricket World Cup.
2. Features and Functionalities
a)	Login System:
-	Goal: Protect user authentication and provide a secure entry point to the website.
-	 Functionality: Users will login in with their assigned email/ID and password. Special rights, such as admin access, will be controlled by a unique ID and password.

b)	Player Information:
-	Goal: Provide thorough information on individual tournament participants, including statistics and other pertinent information.
-	Information shown includes full name, date of birth, age, playing position, teams, career statistics, and most recent performances.

c)	Team Information:
-	Goal: Provide in-depth information about all of the teams competing in the tournament.
-	Highlighted facts include team data, squad details, history records, and significant players to monitor.

d)	Match Schedule and Reminders:
-	Goal: Keep users up to current on match schedules.
-	Functionality: Shows the entire tournament schedule, including match dates and timings, in a dynamic calendar style. Users can set up reminders.
e)	Stadium Locator and Virtual Tours:
-	Goal: Give users a virtual tour of the stadium and aid with venue navigation.
-	Functionality: Includes a virtual tour feature and a map that may be used to identify stadiums. includes the coordinates for the stadium and media assets for the virtual tour. Users can take immersive virtual tours and engage with an interactive stadium map.

f)	News and Updates:
-	Goal: Inform fans with the most recent World Cup developments.
-	Content: Compiles and displays news stories, interview highlights, and video content. area of news and updates with categories and multimedia materials.

g)	Predictions and Polls:
-	Goal: Involve people in interactive exercises that focus on opinions and match results.
-	Functionality: Enables users to forecast match results and take part in various polls. displays poll selections and user predictions together with the outcomes and results.
Overall Description
The website aims to provide a comprehensive platform covering all aspects of the ICC Men's Cricket World Cup. It caters to fans seeking match schedules, live scores, team stats, player profiles, and news updates. Additionally, the platform serves as a hub for ticket bookings, merchandise purchases, and streaming, if permitted.

3. Functional Requirements:

a)	Player Profiles:

I.	View Player Profile
The players who are competing in the competition have full profiles that users can browse and examine. Player profiles will include:
•	Full Name
•	Date of Birth
•	Nationality
•	Playing Role
•	Batting Style
•	Bowling Style
•	Career Statistics (Runs, Wickets, Average, Strike Rate, etc.)
•	Recent Performance Data (last 5 matches)
II.	Search Players
Users can conduct player searches based on a player's name, team, nationality, or position. A list of players who match your search should appear with their basic information.
III.	Favorite Players:
Players can be marked as favorites by users for easy access to their profiles. The list of players you've favorited should be displayed in a separate section.


b)	Team Information

I.	View Team Information
Users can access comprehensive data about all competing teams. Team information will include:
•	Team Name
•	Captain
•	Coach
•	Squad Details (Player Names, Playing Roles)
•	Historical Records (Wins, Losses, Win Percentage)
•	Key Players to Watch

II.	Search Teams
Users can look up teams by country or by name. In the list of matching teams in the search results, there should be some basic information.

c)	Match Schedule and Reminders

I.	View Match Schedule
The entire tournament calendar, including dates, locations, and match times, will be available to the users.

II.	Set Match Reminders
Reminders can be set by users for particular matches they want to remember. Before the contest begins, reminders can be made for a configurable time. Users, who have set reminders for matches, will receive notifications for those matches.

d)	Stadium Locator and Virtual Tours

i)	 View Stadium Map:
Users will have access to a map showing the locations of the competition sites.

ii)	 Virtual Tours:
To experience the ambience of the stadiums, users can digitally tour them. 360-degree views and points of interest should be available during virtual tours of the stadium.

e)	News and Updates

i)	Latest News Articles:
The program will compile and display the most recent World Cup-related news stories. The headlines, summaries, and publication dates of news pieces will be included.

ii)	Interviews and Video Highlights:
Users will have access to interviews, video highlights, and other World Cup-related multimedia content.

f)	Predictions and Polls

i)	 Match Predictions:
Users can guess how a match will turn out. Before a game begins, predictions can be made. Top predictors should be displayed on scoreboards.

ii)	Polls:
Users can take part in polls to express their opinions on several facets of the competition. Real-time poll results should be shown.

4. Business Rules
Specific business rules must be met during the usage of this system which include:
•	Users should have an option to edit, delete, and update.

•	News and updates should be real-time.

•	Stadium locator and virtual tour can be done using Google map

•	Content such as images, videos, and articles should respect copyright and intellectual property rights

•	Users should not engage in any form of real-money gambling or betting within the application, as it may violate local laws and regulations

•	Users must not engage in spamming, manipulation, or fraudulent activities related to match outcome predictions and polls.

•	Violation of these rules may lead to disqualification from prediction contests.

•	Inappropriate or offensive content should be promptly removed.
These business rules provide a framework for maintaining a safe, respectful, and compliant environment for users and stakeholders of the ICC Men's Cricket World Cup 2023 Fan Experience Application. They help ensure that the application operates by legal and ethical standards while providing an enjoyable experience for users.

5. External Interface Requirements:
a)	User Interfaces:
-	The application should have user-friendly interfaces for web, mobile (iOS and Android), and tablet devices to cater to a wide user base.
-	User interfaces should adhere to responsive design principles, adapting to various screen sizes and orientations.
b)	Location Services:
-	If providing stadium locator and mapping features, the application should utilize device GPS or Wi-Fi positioning to provide accurate location information.
c)	Content Management Systems (CMS):
-	Using a CMS to manage and update content, such as news articles, player profiles, and match schedules, will ensure that content remains up-to-date and accurate.

These external interface requirements are essential for the ICC Men's Cricket World Cup 2023 Fan Experience Application to function effectively, provide a seamless user experience, and integrate with various external services and platforms. Compliance with these requirements is critical for the application's success and user satisfaction.

6. Non-functional requirements:

a)	Performance requirements: 
The maximum satisfactory response time to be experienced most of the time for each distinct type of user-computer interaction, along with a definition of most of the time.

b)	Security requirements:
The application ensures that only authorized users can access the system via protected routes, and MongoDB provides an added layer of security to the database to protect sensitive data.

c)	Usability and Accessibility requirements:

-	The application should have a user-friendly interface that adheres to accessibility standards to accommodate users with disabilities.
-	Usability testing should be conducted to ensure a positive user experience.

d)	Scalability requirements:
The system can handle increased workload and demand while maintaining consistent performance.

e)	Reliability requirements:
The application should be available 24/7 with an uptime of at least 99.9%. Backup and recovery procedures should be in place to handle potential data loss scenarios.

f)	Maintainability:
-	The codebase should follow best practices and be well-documented to facilitate maintenance and future development.
-	Updates, bug fixes, and enhancements should be efficiently deployed to minimize downtime.

g)	Cost-Effective Hosting:
The application should be hosted cost-effectively while meeting performance and security requirements.

h)	Load Testing:
Conduct load testing to verify the application's ability to handle the expected user load, focusing on peak times during matches.


7. Technology Stack:
a)	Front-end Technologies:
The front-end of the web application will be developed using:
-	HTML for structuring content.
-	CSS for styling and layout.
-	JavaScript for creating interactive user interfaces.

b)	Back-end Technologies:
The back-end of the application will be built using Laravel (PHP) and mySQL will be used for the database system, where user data and application data will be stored.

c)	Real-Time Data Feeds:
Real-time match scores and updates will be obtained through APIs from trusted cricket data providers.

d)	Hosting and Deployment:
-	The web application will be hosted on cloud infrastructure to ensure scalability and reliability. 
-	Continuous Integration/Continuous Deployment (CI/CD) pipelines will be established for automated deployment.

8. Project Plan Model
a)	Agile Development:

-	The project will follow an Agile software development methodology, specifically using the Scrum framework.
-	The development process will be divided into sprints, with each sprint typically lasting two to four weeks.

b)	Roles and Responsibilities:

-	The project team will consist of the following roles:
-	Product Owner: Responsible for defining and prioritizing features and user stories.
-	Scrum Master: Responsible for facilitating Scrum ceremonies and removing impediments.
-	Development Team: Responsible for implementing user stories and features.
-	QA/Test Team: Responsible for testing and quality assurance.
-	DevOps Team: Responsible for deployment and infrastructure management.

c)	Sprint Planning:

-	Before each sprint, a sprint planning meeting will be held to determine which user stories and features will be included in the upcoming sprint.

d)	Daily Stand-ups:

-	Daily stand-up meetings will be conducted to provide updates on progress, discuss challenges, and plan the day's work.

e)	Sprint Review and Retrospective:

-	At the end of each sprint, a sprint review will be conducted to demonstrate completed features to stakeholders.
-	A sprint retrospective will follow to reflect on the sprint and identify areas for improvement.

f)	Release Planning:

-	Releases will be planned after a set number of sprints to deliver new features and improvements to users.

9. Timeline and Milestones
a)	Project Timeline:

-	The project is expected to span approximately 2-3 week, starting from the 15th of October to the 4th of November, 2023.

b)	Milestones:

-	Milestone 1: Completion of Front-end Development [25.10.23]
-	Milestone 2: Back-end Development and Database Integration [31.10.23]
-	Milestone 3: Real-time Data Integration and Social Media Features [1.11.23]
-	Milestone 4: User Testing and Quality Assurance [2.11.23]
-	Milestone 5: Deployment and Launch [3.11.23]
-	Milestone 6: Post-launch Monitoring and Maintenance [3.11.23 to ongoing]

10. Constraints:
a)	Internet Connectivity:
-	The web application is dependent on users having a reliable internet connection. Lack of internet access may limit user engagement.

b)	Third-Party Data Sources:
-	The accuracy and availability of real-time match data and social media feeds are dependent on third-party APIs. Any downtime or disruptions from these sources may impact the application's functionality.

c)	Privacy and Compliance:
-	The application must adhere to data protection regulations, including GDPR and user privacy expectations. Compliance with these regulations is a constraint that must be maintained.

d)	Hosting and Infrastructure:
-	The choice of cloud hosting services and infrastructure providers may impose limitations on scalability, availability, and performance.

11. Future Enhancements
a)	Additional Tournaments:
-	Future versions of the application can expand to cover other cricket tournaments, such as domestic leagues and women's cricket events.

b)	Enhanced User Profiles:
-	Implement more comprehensive user profiles, allowing users to personalize their experience and track their engagement with the application.

c)	Augmented Reality (AR):
Integrate AR features to provide users with an immersive cricket experience, such as AR-based games, player overlays, and interactive stadium tours.

d)	Machine Learning and AI
 Implement machine learning algorithms to provide predictive analysis, player recommendations, and personalized content delivery.

e)	Multilingual Support
Offer support for multiple languages to reach a broader international audience of cricket enthusiasts.

f)	Offline Mode
Develop an offline mode to allow users to access limited functionality when internet connectivity is poor or unavailable.

g)	Monetization Strategies
Explore options for monetization, such as premium subscriptions, in-app purchases, or targeted advertising.

h)	Accessibility
Continuously improve accessibility features to ensure the application is usable by individuals with disabilities.

i)	Virtual Reality (VR):
-	Consider VR integration to offer a virtual viewing experience of matches for users with compatible devices.

j)	User-Generated Content:
-	Enable users to contribute content, such as match reviews, fan blogs, or user-generated polls, to enhance community engagement.

12. Prioritization and Roadmap
a)	Prioritization:
Future enhancements will be prioritized based on user feedback, market trends, and business goals. High-priority features will be addressed first.

b)	Roadmap:
-	A product roadmap will be created to outline the timeline and release plans for future enhancements. 
-	Regular updates to the roadmap will be made to align with evolving requirements and opportunities.
-	Agile development methodology will be followed, with bi-weekly sprints. 
-	Version control using Git and collaborative development on platforms like GitHub.

Modelling and Implementation Challenges
•	Stadium locator not working properly with Google Maps.
•	Frequent database connection problems.
•	Not being fully expert in implementing all the required features.
•	Lack of cooperation between team members.
•	Various development challenges.

Conclusion
In conclusion, the CricStics website is designed to serve as the ultimate online destination for cricket enthusiasts, journalists, and teams involved in the ICC Men's Cricket World Cup 2023. It aims to provide a seamless user experience, offering a wide array of information, schedules, scores, and interactive features. As the primary digital interface for this prestigious sporting event, CricStics will play a vital role in enhancing the overall experience for fans and stakeholders. 

 



