<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Diogo Duarte
**Date**: [25-02-2025]
**Product**: [Emporia Energy]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Energy data updates are sometimes delayed | 2            | Improve data refresh rates and ensure real-time updates with clear status indicators like last time updates and similar logic              |
| No clear indication when an action is registered   | 2            |  Provide instant feedback for user actions like color changes or confirmation messages             |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Uses techical language for energy metrics | 2            |  Use simpler language or provide explanation for complex terms              |
| Some icons are not intuitive    | 1            | Redesign icons to better represent functions with real-world recognized symbols                |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Users who accidentally remove a device must set it up again from scratch | 3 | Implement an "Undo" option or confirmation before removing devices.
| Limited ability to manually correct energy readings   | 2            | Allow users to adjust incorrect readings with confirmation prompts               |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Different UI Across Platforms | 2 | Ensure consistent UI and navigation structure across all platforms |
| Inconsistent terminology and design across app and website ( "Energy Usage" vs. "Consumption Report") | 2            | Standardize terminology across all platforms.               |
| Some buttons follow different styles across screens. | 2  | Apply consistent styling for all buttons and interactive elements. |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No warning before making major changes (resetting energy data). | 3  | Add a confirmation dialog before performing irreversible actions. |
| The system does not proactively notify users when unusual energy consumption occurs | 3 |  Implement automatic alerts for unusual energy patterns |
| Some data inputs lack validation (setting an unrealistic energy cost value). | 2  | Implement input validation and alerts for incorrect values. |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Users must navigate to see power consuption instead of being visible in main panel | 2            | Show keu metrics on the home screen with quick acces to details               |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No advanced filtering options for energy reports. | 2  | Allow users to customize reports with advanced filters. |
| Users cannot set personalized alerts   | 2            | Add custom alert settings for better control               |
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|  Dashboard contains excessive information, making it overwhelming.   | 3 | Simplify the UI with a customizable dashboard that shows only relevant data. |
| Some charts and buttons have unnecessary color variations, making them harder to read. | 2  | Improve visual hierarchy and avoid excessive colors. |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Error messages lack actionable solutions (e.g., "Connection Failed" without troubleshooting steps). | 2  | Provide error messages with specific solutions (e.g., "Check your Wi-Fi connection"). |
| Some error codes are displayed instead of human-readable messages   | 2            | Use user-friendly explanations rather than technical codes.               |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| No guided onboarding for new users. | 2 | Add a step-by-step tutorial for first-time users. |
| Help section is as just have resolution for a few problems leaving the client to search for themselves | 1  | Provide contextual help links to more problems. |

