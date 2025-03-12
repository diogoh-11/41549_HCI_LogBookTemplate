[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative.



## B.1a. Competitors


| **Competitor** | **Description**                                                                                                                                                      | Information repository                                                                        |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Emporía Energy | Emporia Energy is a home energy monitoring system that provides real-time electricity usage tracking, helping users optimize consumption to reduce costs and waste.  | [Competitor Analysis Emporía Energy](./competitors/Competitor%20Analysis%20Emporia_Energy.md) |


## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method

For the heuristic evaluation, three experts analyzed the app using Nielsen’s heuristics. Since testing required specific hardware, we relied on the app itself, online reviews, and user opinions for assessment. Each expert conducted an independent review, identifying usability issues based on a predefined [severity scale](heuristic_evaluations/severity_scale_heuristic_evaluation.md). After the evaluations, we gathered the most common and critical issues to reach a consensus on the key usability concerns.


#### Individual Evaluations


- [Expert1's Heuristic Evaluation](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [Expert2's Heuristic Evaluation](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [Expert3's Heuristic Evaluation](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

|                                                                                 **Issue**                                                                                 | **Expert 1** | Expert 2 | Expert 3 |                                                             Recommendations                                                             |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------: | :------: | :------: | :-------------------------------------------------------------------------------------------------------------------------------------: |
|                                                 Users who accidentally remove a device must set it up again from scratch                                                  |      3       |    2     |    2     |                                   Implement an "Undo" option or confirmation before removing devices.                                   |
| Customization options do not follow the natural flow of user expectations, as the app mixes data from different time periods (e.g., part of yesterday in the "day" view). |      2       |    2     |    3     | Making each view display only the relevant timeframe (e.g., today, this week, this month) would improve clarity and user understanding. |
|                                              The terminology used could be hard to understand as it is relatively technical.                                              |      2       |    3     |    2     |                                     Use simpler and easier to understand terminology and images ...                                     |
|                                                        Some useful information is not displayed on the main page.                                                         |      2       |    3     |    3     |                 Display useful information on the main page, making it so users don't have to navigate to other pages.                  |
|                                                     Dashboard contains excessive information, making it overwhelming.                                                     |      3       |    3     |    3     |                              Simplify the UI with a customizable dashboard that shows only relevant data.                               |



---
### - Cognitive Walkthrough

#### Method

The Cognitive Walkthrough method was used to evaluate the usability of the Emporia Energy app by analyzing key tasks users perform. This method focuses on understanding whether users can successfully complete tasks without prior knowledge of the system. The evaluation follows a structured process to assess user knowledge, feedback clarity, and overall task success.

#### Task Selection and Task Analysis

The following tasks were selected because they are core functionalities of the app and essential for user experience. Each task was broken down into subtasks.


| Task                                 | Subtasks                      |
| ------------------------------------ | ----------------------------- |
| **1. Consulting consumption report** | 1. Navigate to "Home" section |
|                                      | 2. Choose unit of measurement |
|                                      | 3. Analyze the report         |


| Task                                          | Subtasks                                            |
| --------------------------------------------- | --------------------------------------------------- |
| **2. Checking solar panel energy production** | 1. Navigate to the solar energy section             |
|                                               | 2. View production, consumption, and grid injection |
|                                               | 3. Compare with past data for efficiency tracking   |

| Task                                       | Subtasks                                          |
| ------------------------------------------ | ------------------------------------------------- |
| **3. Verifying Electric Vehicle Charging** | 1. Navigate to the "EV charging" section          |
|                                            | 2. Check battery status and estimated charge time |
|                                            | 3. Adjust charging schedule if needed             |

| Task                                | Subtasks                                |
| ----------------------------------- | --------------------------------------- |
| **4. Receiving Energy-Saving Tips** | 1. Navigate to "Management" section     |
|                                     | 2. Click on "Saving Opportunities"      |
|                                     | 3. Read personalized energy-saving tips |
|                                     | 4. Implement suggestions                |


#### Results

#### Task 1: Generating a Consumption Report 

| Step # | Task/Action to Perform     | Will User Know What to do at this step? (Yes/No) | Notes                                              | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                    | Is Action Successful? (Yes/No) | Suggestions for Improvement                                               |
| ------ | -------------------------- | ------------------------------------------------ | -------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------ | ------------------------------ | ------------------------------------------------------------------------- |
| 1      | Navigate to "Home" section | Yes                                              |                                                    | Yes                                                                                       |                          | Yes                            |                                                                           |
| 2      | Choose unit of measurement | Yes                                              | As there are to many options it could be confusing | Yes                                                                                       |                          | Yes                            | Improve readability and clarification by display less more useful options |
| 3      | Analyze report data        | Yes                                              | Users might not understand the graphs              | Yes                                                                                       | Requires prior knowledge | No                             | Provide tooltips or explanations for metrics                              |




### Task 2: Checking Solar Panel Energy Production (Não sei se está correto mas n consegui percber qual era a zona da app que tinha de entrar)

| Step # | Task/Action to Perform               |  Will User Know What to do at this step? (Yes/No)| Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No)| Suggestions for Improvement |
|--------|--------------------------------------|---------------------------|-------|--------------------------------------|-------|----------------------|---------------------------|
| 1      | Navigate to solar section           | Yes                      | May not be obvious for new users | Yes                                   | If well labeled         | Yes                      | Improve menu labeling |
| 2      | View energy production & grid data  | Yes                      | Graphs might be confusing        | No                                    | Needs clear separation | No                       | Use color-coded graphs and legends |
| 3      | Compare data with past days         | No                         | Feature may not be intuitive      | No                                    | Lacks trend visualization | No                       | Add a comparison mode for past data |




### Task 3: Verifying Electric Vehicle Charging

| Step # | Task/Action to Perform        | Will User Know What to do at this step? (Yes/No) | Notes                                                | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                       | Is Action Successful? (Yes/No) | Suggestions for Improvement                   |
| ------ | ----------------------------- | ------------------------------------------------ | ---------------------------------------------------- | ----------------------------------------------------------------------------------------- | --------------------------- | ------------------------------ | --------------------------------------------- |
| 1      | Navigate to "EV charging"     | Yes                                              | As it is an important feature, could be more visible | Yes                                                                                       | -                           | Yes                            | Ensure easy access from main screen           |
| 2      | Check battery and charge info | Yes                                              | Users may not understand cost estimates              | No                                                                                        | Needs better data breakdown | Yes                            | -                                             |
| 3      | Adjust charging schedule      | No                                               | Settings unavailable                                 | No                                                                                        | Needs to add this feature   | No                             | Offer guided scheduling with time suggestions |


### Task 4: Receiving Energy-Saving Tips

| Step # | Task/Action to Perform               | Will User Know What to do at this step? (Yes/No) | Notes                                                                          | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes                                                                          | Is Action Successful? (Yes/No) | Suggestions for Improvement                        |
| ------ | ------------------------------------ | ------------------------------------------------ | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------ | -------------------------------------------------- |
| 1      | Navigate to "Management" section     | Yes                                              | -                                                                              | Yes                                                                                       | -                                                                              | Yes                            | -                                                  |
| 2      | Click on "Saving Opportunities"      | Yes                                              | Make menu less cluttered and intuitive                                         | Yes                                                                                       | -                                                                              | Yes                            | -                                                  |
| 3      | Read personalized energy-saving tips | Yes                                              | It could be hard to understand                                                 | Yes                                                                                       | -                                                                              | Yes                            | -                                                  |
| 4      | Implement suggestions                | No                                               | The user may need a step to step guide on how to implement certain suggestions | Yes                                                                                       | Eventually, if the suggestion is useful, the user will feel it on it's reports | Yes                            | Guide the user on how to implement the suggestions |


---

## B.1c. Overall Analysis

Emporia Energy provides a comprehensive platform for monitoring household energy consumption and solar energy production. Its strengths include real-time data tracking, integration of solar and grid energy, and features aimed at cost savings through automation and optimization. However, the platform has notable weaknesses, such as an overloaded interface that presents too much information at once, making navigation complex and challenging for new users. There are opportunities for improvement, including a more intuitive user interface, enhanced customization options, and better data visualization. Additionally, expanding smart integrations with home automation systems could increase its value. Despite its advantages, Emporia Energy faces threats from competitors with more user-friendly interfaces, evolving market expectations, and the need to maintain high data accuracy to retain user trust.


# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

The users were approached in an informal manner. Since the interviews were conducted inside the classroom with little background knowledge about the interviewees, some did not provide useful information, as certain users were not familiar with the topics in question and/or used any type of app to manage there energy related expenses. Nonetheless, some valuable insights were gained, including useful improvements and features that we had not necessarily considered yet.
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

## Interview List  
| Date       | Participant / Role          | Key Insights                                                      | Link to Notes                              |  
|------------|----------------------------|-------------------------------------------------------------------|--------------------------------------------|  
| 2025-02-27 | André Anjos / Student      | Needs better energy monitoring, struggles with multiple apps.    | [📄 Notes](../stage1_context/interviews/interview-André.md)             |  
| 2025-02-27 | Henrique & Gonçalo / Students | Want detailed appliance tracking and an intuitive interface. | [📄 Notes](../stage1_context/interviews/interview-HenriqueGoncalo.md) |  

---

## Common Themes & Patterns  

- **Recurring Problems:**  
	- Lack of detailed consumption breakdown (by device, room, or time).  
	- Difficulty comparing solar energy production vs. consumption.  
	- Current apps are unintuitive and require manual analysis.  
	- No centralized tool for all needs (electric car, solar panels, home consumption).  

- **Frequently Used Tools:** 
	- General energy monitoring apps.  
	- EDP reports for tariff checking.  
	- Manual tracking of energy usage patterns.  

- **Desired Features / Solutions:**   
	- A dashboard showing energy consumption by room and device.  
	- AI-based recommendations for optimizing energy use.  
	- Notifications for abnormal consumption or savings opportunities.  
	- Integration of electric cars with charging controls.  
	- Clear visualizations (graphs, intuitive UI) for easier decision-making.  

- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
