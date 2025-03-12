[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             | Information repository              |
| ----------------- | ------------------------------------------- | ----------------------------------- |
| [Amazon Shoes]    | [Online platform selling shoe laces]        | [[Competitor Analysis AmazonShoes]] |
| [Fnac Atacadores] | [Smartphone app to buy and sell shoe laces] |                                     |
| ...               |                                             |                                     |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]


#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       | **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- | ------------ | -------- | -------- | ------------------------------------------- |
| Something wrong | 3            | 1        | 0        | Something could be done to the button to... |
| Another thing   | 4            | 3        | 4        | Other thing to recommend                    |
| ...             |              |          |          |                                             |



---
### - Cognitive Walkthrough

#### Method
[Briefly described  the method you used for the Cognitive Walkthrough analysis. ]

The Cognitive Walkthrough method was used to evaluate the usability of the Emporia Energy app by analyzing key tasks users perform. This method focuses on understanding whether users can successfully complete tasks without prior knowledge of the system. The evaluation follows a structured process to assess user knowledge, feedback clarity, and overall task success.

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]

The following tasks were selected because they are core functionalities of the app and essential for user experience. Each task was broken down into subtasks.


| Task                        | Subtasks                               |
| --------------------------- | -------------------------------------- |
| **1. Generating a consumption report by room** | Navigate to the reports/analytics section       |
|                                                 | Select “Consumption by Room”                    |
|                                                 | Analyze the report and energy-saving insights   |
|                                                 | Take action based on the recommendations        |


| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **2. Checking solar panel energy production** | Navigate to the solar energy section            |
|                                                 | View production, consumption, and grid injection |
|                                                 | Compare with past data for efficiency tracking  |

| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **3. Verifying Electric Vehicle Charging**      | Navigate to the EV charging section             |
|                                                 | Check battery status and estimated charge time  |
|                                                 | Adjust charging schedule if needed              |

| Task                          | Subtasks                                |
| ----------------------------- | --------------------------------------- |
| **4. Receiving Energy-Saving Tips**             | Access the recommendations section              |
|                                                 | Read personalized energy-saving tips            |
|                                                 | Implement suggestions (scheduling device usage) |


#### Results



Task: [This is the task]

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | [Step 1 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | [Step 2 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | [Step 3 description]   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| ...    | [Further steps]        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

### Task 1: Generating a Consumption Report by Room

| Step # | Task/Action to Perform               |  Will User Know What to do at this step? (Yes/No)| Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No)| Suggestions for Improvement |
|--------|--------------------------------------|---------------------------|-------|--------------------------------------|-------|----------------------|---------------------------|
| 1      | Navigate to reports section         | Yes                      | Could be unclear where to find this  | Yes                                   | A progress indicator would help | Yes                      | Improve discoverability (e.g., prominent label) |
| 2      | Select “Consumption by Room”        | Yes                      | Some users might not know where this is | Yes                                   | If selected correctly | Yes                      | Add search or filter option for easier access |
| 3      | Analyze report data                 | No                         | Users might not understand the graphs | No                                    | Requires prior knowledge | No                       | Provide tooltips or explanations for metrics |
| 4      | Take action based on insights       | No                         | No clear recommendations for action | No                                    | Users may not know what to do next | No                       | Offer actionable recommendations with buttons |



### Task 2: Checking Solar Panel Energy Production

| Step # | Task/Action to Perform               |  Will User Know What to do at this step? (Yes/No)| Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No)| Suggestions for Improvement |
|--------|--------------------------------------|---------------------------|-------|--------------------------------------|-------|----------------------|---------------------------|
| 1      | Navigate to solar section           | Yes                      | May not be obvious for new users | Yes                                   | If well labeled         | Yes                      | Improve menu labeling |
| 2      | View energy production & grid data  | Yes                      | Graphs might be confusing        | No                                    | Needs clear separation | No                       | Use color-coded graphs and legends |
| 3      | Compare data with past days         | No                         | Feature may not be intuitive      | No                                    | Lacks trend visualization | No                       | Add a comparison mode for past data |




### Task 3: Verifying Electric Vehicle Charging

| Step # | Task/Action to Perform               |  Will User Know What to do at this step? (Yes/No)| Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No)| Suggestions for Improvement |
|--------|------------------------------|---------------------------|-------|--------------------------------------|-------|----------------------|---------------------------|
| 1      | Navigate to EV charging      | Maybe                      | Depends on UI clarity | Yes                                   | If icon is clear         | Yes                      | Ensure easy access from main screen |
| 2      | Check battery and charge info| Yes                      | Users may not understand cost estimates | No                                   | Needs better data breakdown | No                       | Display charge costs in simpler terms |
| 3      | Adjust charging schedule     | No                         | Settings unavailable | No                                    | Needs to add this feature | No                       | Offer guided scheduling with time suggestions |


---




# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 03-09-2000 | Bob / student      | Does most things on paper and would require a complete solution | [📄 Notes](interview-Bob.md) |     |
| ...        |                    |                                                                 |                              |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Issue 1
	- Issue 2
- **Frequently Used Tools:** 
	- Tool 1
	- Tool 2
- **Desired Features / Solutions:** 
	- Feature 1
	- Feature 2
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
