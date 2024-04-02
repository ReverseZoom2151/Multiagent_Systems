# 🦠 COVID Simulation Lab 🦠

## Project Overview

The COVID Simulation Lab is an exploratory data analysis and simulation project designed to understand the dynamics of COVID-19 spread under various public health intervention scenarios. Through a series of simulations, this lab investigates how different strategies, such as the implementation of quarantine centers and the enforcement of social distancing norms, affect the rate of COVID-19 spread within a hypothetical population. Starting with initial infection rates of 10%, 25%, and 50%, the project provides insights into the potential outcomes of public health decisions.

## Agents in Simulation 🤖

The simulations employ a model of agents representing individuals within the population. Each agent's behavior and interactions are defined based on several key characteristics:

- **Health Status:** Agents can be healthy, infected, or recovered. This status determines their interactions and mobility within the simulation environment.
- **Mobility:** Agents move within the simulation space, representing the daily movements of individuals. Mobility patterns are adjusted according to the scenario, such as reduced mobility under social distancing norms.
- **Interactions:** Agents interact with one another within the simulation space. The nature and frequency of interactions can lead to the spread of the virus among agents.
- **Compliance:** In scenarios involving social distancing or quarantine measures, agents may have varying levels of compliance, reflecting the diverse responses of a real population to public health directives.

These agents are at the core of the simulation, allowing for a dynamic and realistic modeling of COVID-19 spread under different public health interventions.

## Simulation Scenarios: 🧪

This project includes nine distinct scenarios, categorized into three main groups:

### No Quarantine Centers and No Social Distancing

- 🚫 **Scenario 1a:** Simulates the spread of COVID-19 with an initial infection rate of 10% without any public health interventions.
- 📈 **Scenario 1b:** Increases the initial infection rate to 25%, showcasing the rapid spread in the absence of interventions.
- 💔 **Scenario 1c:** Further increases the initial infection rate to 50%, highlighting the critical impacts on public health systems.

### Adding Quarantine Centers

- 🏥 **Scenario 2a:** Introduces quarantine centers into the model with a starting infection rate of 10%, examining their effectiveness in controlling the outbreak.
- 🔍 **Scenario 2b and Scenario 2c:** Evaluate the effectiveness of quarantine centers at higher initial infection rates (25% and 50%, respectively).

### Enforcing Social Distancing Norms

- 📉 **Scenario 3a:** Implements social distancing measures starting with a 10% infection rate, analyzing its impact on flattening the curve.
- 🤝 **Scenario 3b and Scenario 3c:** 🛑 Study the combined effect of social distancing and higher initial infection rates (25% and 50%).

## Results and Analysis 📝

The simulations reveal varying levels of effectiveness for each intervention strategy. Key findings include:

- 🆘 The absence of public health interventions leads to rapid and uncontrolled spread, overwhelming healthcare systems.
- ✅ Implementing quarantine centers significantly reduces the spread, with their effectiveness being more pronounced at lower initial infection rates.
- 🌍 Social distancing has a profound impact on flattening the epidemic curve, even at higher initial infection rates, emphasizing its importance as a public health strategy.
