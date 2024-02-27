# The Influence Of Population, Voting Turnout and Ethnicity on Voting Outcomes

This project explores the influence of various factors such as population demographics, voter turnout, and ethnicity on voting outcomes in the United States. The analysis delves into understanding the dynamics of elections, particularly focusing on the relationship between voter behavior and political outcomes.

## Introduction

In recent years, the political landscape in the United States has witnessed significant turbulence, characterized by heightened polarization and increased voter turnout. The 2020 elections, in particular, marked a historic moment with record-breaking voter participation. This project aims to investigate the impact of voter turnout and ethnicity on election results, exploring the hypothesis that increased turnout favors certain political parties. By analyzing voting data at the county level, this study seeks to understand the factors influencing electoral outcomes and predict potential swing counties and states.

## Hypotheses

1. **Voter Turnout and Party Outcome**
   - Null Hypothesis: There is no significant relationship between voter turnout and the difference in votes between Democrat and Republican parties.
   - Alternative Hypothesis: There is a significant relationship between voter turnout and the difference in votes between Democrat and Republican parties.

2. **Ethnicity and Party Outcome**
   - Null Hypothesis: There is no significant relationship between the percentage of ethnic minorities and the percentage of votes for the Democrat party.
   - Alternative Hypothesis: There is a significant relationship between the percentage of ethnic minorities and the percentage of votes for the Democrat party.

## Data Setup

The project begins by loading necessary libraries and preparing the data for analysis. Various statistical packages are utilized, and the dataset is divided into training, querying, and testing samples for further exploration.

## Exploratory Analysis

**Turnout by County and State** - Visualizations are created to map voter turnout across different counties and states, providing insights into the distribution of voting patterns.

**Statewise Voting Results** - Maps depicting differences in voting percentages between Republican and Democrat parties are generated, shedding light on the political landscape at the state level.

## Winning Elections

**Adding the Electoral College Variable and State Averages** - The project incorporates the electoral college variable and calculates average voting statistics for each state, considering factors such as total votes, party percentages, and population proportions.

**Applying the Proportional Electoral Vote System** -  An alternate electoral vote system is implemented, allocating votes proportionally based on party support within each state.

**Regressions on Election Results** - Linear regression models are utilized to analyze the relationship between voting turnout, ethnicity, and Democrat vote percentages.

**Predicting County Level Election Outcome** - Support Vector Machine (SVM) models are employed to predict election outcomes based on variables such as population demographics, turnout, and total votes cast.

## Conclusion

The project concludes by discussing the findings and implications of the analysis. It highlights the significance of voter turnout and ethnicity in shaping electoral outcomes and evaluates the effectiveness of predictive models in forecasting election results.

## Sources

- Relevant sources and datasets utilized in the project are listed for reference.

For detailed analysis and code implementation, refer to the R Markdown files provided in this repository.
