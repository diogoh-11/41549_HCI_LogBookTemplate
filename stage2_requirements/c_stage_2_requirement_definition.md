[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas
## Persona: [Alberto Pais] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Persona Name](path/to/photo.jpg)            |
| **Name**         | Alberto Pais                                |
| **Age**          | 52                                 |
| **Occupation**   | Electrical Engineer                           |
| **Location**     | Madrid, Spain                              |
| **Goals**        | Alberto aims to optimize his home's energy consumption while maintaining comfort, integrate solar panels and his electric vehicle into a seamless energy system          |
| **Pain Points**  | Finding a reliable system to automate and optimize energy usage              |
| **Motivation**   | I want my home to be as energy-efficient and as possible while teaching my kids the value of sustainability.               |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---

# Scenarios

## Scenario 1: Alberto wants to know which of his devices installed in the living room are consuming the most energy.

Alberto wants to monitor the energy consumption of his devices in the living room. Using his smart energy management system, he aims to identify which devices are consuming the most power. With this information, he can adjust usage patterns and potentially reduce electricity costs.

## Scenario 2: Checking how much energy the solar panel has produced this month.

Alberto wants to review his solar panel's energy production this month to evaluate if his investment was a good decision.

## Scenario 3: Alberto needs to see how long it will take for his car to be fully charged.

Since Alberto is going on a long trip, he needs his vehicle to be fully charged. He wants to see if charging will take too much time.

## Scenario 4: Alberto automates his smart home energy system.

After configuring the system, Alberto wants it to prioritize charging his electric vehicle and powering major appliances during peak solar energy production.

## Scenario 5: Alberto compares rates from different energy companies.

Alberto thinks he is spending too much money on energy at the end of the month, so he wants to compare his costs with other companies to see if he would save more money by switching to another electricity provider.

# Requirements

## C.1. Functional requirements

**1. Energy expenses**
- User should be able to see real time energy usage
- User must be able to choose the time-span of the data
- Different views should be offered
- User should be able to change the units of measurement

**2. EV chargers**
- User must be able to see how much time until charging is finished
- User must be able to schedule charging times

**3. Solar panels**
- User must be able to check how much energy is being produced
- User must be able to see how much produced energy is being wasted
- User must be able to redirect extra produced energy
- User must be able to toggle production on or off

**4. Insights and energy saving tips**
- User must be able to receive Personalized energy-saving recommendations
- User must be able to see a comparison with similar households

**5. Notifications and Alerts**
- User should receive real-time alerts for high energy consumption or unexpected spikes
- User should receive weather-based insights for optimizing energy usage/production.

**6. Data reporting and exporting**
- Users can generate reports in PDF, CSV, or Excel formats

## C.2. Non-functional requirements

**1. Operational requirements**
- The system will operate on a mobile environment (IOS and Android)
- The app should be able to connect to different appliances wirelessly
**2. Performance requirements**
- Energy related graphs should be fast and responsive to changes
**3. Security and privacy**
- User data must be stored in a safe way
- Log in required to access some parts of the app
**4. Usability and Accessibility**
- The app should have an intuitive design
- The app should have a clean aesthetic
- The app may have some accessibility features
**5. Availability and maintainability**
- The system should be available 99.9% of the time without downtime
- Regular updates updates and/or bug fixes
**6. Integration and Compatibility**
- The app should be compatible with various smart appliances


---
[Back to main Logbook Page](hci_logbook.md)