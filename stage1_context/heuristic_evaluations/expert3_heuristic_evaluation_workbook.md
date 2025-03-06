<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Tomás Hilário
**Date**: 24/2/2025
**Product**: Emporía Energy

---

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|Too many customization options for viewing statistics that aren't necessarily useful. For example, it gives the user the possibility of seeing how much energy they are using per second and per minute   |  2           |          Give less options that are more useful (Day, Wk, Mo and Yr)      |
|If you have more than one of solar panel, they show up as separate panels, so you cannot see totals without doing the math in your head. |3|Combine information about similar products|

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**                                                                                                                                                               | **Severity** | Recommendation                                                                                                                          |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| The terminology used could be hard to understand by new users as it is relatively technical                                                                             | 2            | Use simpler and easier to understand terminology                                                                                        |
| Customization options do not follow the natural flow of user expectations, as the app mixes data from different time periods (e.g., part of yesterday in the day view). | 3            | Making each view display only the relevant timeframe (e.g., today, this week, this month) would improve clarity and user understanding. |
| Data is not accessible locally other than through a CSV export which could be inconvenient                                                                              | 2            | Make data accessible in a simpler way                                                                                                   |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Users who accidentally remove a device must set it up again from scratch | 3            |          Set up undo button      |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| The same icon is used to refer to different spaces inside the application | 2      |          Use  different icons for differents spaces within the app     |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |

# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**                                                                   | **Severity** | Recommendation                                                                                        |
| --------------------------------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------- |
| Some useful information is not displayed on the main page                   | 2            | Display useful information on the main page, making it so users don't have to navigate to other pages |
| Some of the data that gets exported through the CSV file could be displayed | 3            | Option to vizualize the data along with exporting it                                                  |
# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|App has some unwanted ads|1|Remove ads|

# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Confusing menus | 3            |    Make menus simpler and more aesthetic            |

# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Only offers solution to simpler errors and problems | 2            |    Offer solution to more complex problems            |


# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |

