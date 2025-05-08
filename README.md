# SprintFinal-

# README: Evaluating the Impact of #8CantWait on Racial Disparities in Police Use of Force (2020–2024)

## Project Overview

This project investigates the effectiveness of the #8CantWait police reform policies in reducing fatal police use-of-force incidents, particularly those involving Black individuals, from 2020 to 2024. The #8CantWait campaign, launched by Campaign Zero, outlines eight specific policies—such as banning chokeholds and requiring de-escalation—that aim to minimize police violence and improve accountability.

The goal of this study is to compare states that adopted #8CantWait policies with those that did not, in order to assess whether these reforms have led to measurable changes in fatal police interactions involving Black people. This work contributes to a broader understanding of racial disparities in policing and evaluates policy responses following the 2020 murder of George Floyd.

## Data Collection

### 1. Policy Data

Source: [Campaign Zero's #8CantWait](https://8cantwait.org/)
Process:

  * Reviewed official policy adoption across all U.S. states.
  * Created a binary variable:

    * `1` if a state implemented all 8 policies,
    * `0` if it implemented none.
  * This classification helped distinguish reform-heavy states from those with no reforms.

### 2. **Fatal Police Killings Data

Source: [Mapping Police Violence](https://mappingpoliceviolence.org/)
Process:

  * Extracted yearly fatal police killing data by state from 2020 to 2024.
  * Focused specifically on killings of Black individuals.
  * Standardized the data by calculating killings per million Black residents using U.S. Census population data.

### 3. **Dataset Integration

* Merged policy data and police killings data by state.
* Added demographic variables (e.g., % Black population) to better assess disparities.
* Final dataset allowed for comparison of trends in fatal police use-of-force in states with and without #8CantWait policies.

