# Fishery Population Dynamics and Harvest Profitability

## Overview

This project is an undergraduate mathematical modelling report that explores fishery population dynamics under harvesting pressure. It applies the logistic growth model to describe how a fish population changes over time, then extends the model by introducing a harvesting term to examine the conditions under which a fishery can remain sustainable or collapse.

The project also connects ecological sustainability with economic profitability. It discusses how fishing effort, harvest rate, population size, revenue, and cost interact when determining an appropriate fishing strategy.

Although this is a smaller early-stage modelling project, it demonstrates important applied mathematics skills, including model interpretation, equilibrium analysis, sustainability reasoning, and the use of mathematical models to support real-world decision-making.

## Project Objective

The main objective of this project is to understand how harvesting affects fish population stability and profitability.

The project investigates:

- How logistic growth describes fish population dynamics
- How harvest rate changes the long-term population outcome
- When a fish population reaches equilibrium
- When over-harvesting leads to population collapse
- How sustainable yield relates to economic profit
- How fishing effort affects revenue, cost, and fleet size decisions

## Mathematical Background

The project begins with the logistic growth model:

\[
\frac{dN}{dt} = rN\left(1 - \frac{N}{K}\right)
\]

where:

- \(N(t)\) is the fish population biomass at time \(t\)
- \(r\) is the intrinsic growth rate
- \(K\) is the carrying capacity of the environment

This model describes how a fish population grows quickly when resources are abundant, then slows as the population approaches the environmental carrying capacity.

## Harvesting Model

The model is then extended by adding a harvesting term. The fishery harvesting model is:

\[
\frac{dN}{dt} = rN\left(1 - \frac{N}{K}\right) - hN
\]

where:

- \(h\) is the harvesting rate
- \(hN\) represents the number of fish removed from the population through harvesting

This model captures the interaction between natural population growth and human fishing activity.

## Key Model Interpretation

The project studies two major outcomes:

### 1. Sustainable Equilibrium

A sustainable equilibrium can occur when the harvest rate does not exceed the population’s ability to regenerate.

In general, when:

\[
h \leq r
\]

the fish population can remain stable under harvesting pressure, provided that the population is not already too depleted.

### 2. Population Crash

A crash can occur when the harvesting rate is too high relative to the population growth rate.

When:

\[
h > r
\]

the population may decline toward zero because fish are being removed faster than they can reproduce. This represents an overfishing scenario.

## Non-Dimensional Analysis

The report also considers a non-dimensional version of the model:

\[
\frac{dx}{dt} = x(1 - x) - \alpha x
\]

where:

\[
\alpha = \frac{h}{r}
\]

This transformation simplifies the model and helps analyse equilibrium behaviour more clearly.

The equilibrium condition becomes:

\[
x(1 - x - \alpha) = 0
\]

which gives the equilibrium points:

\[
x^* = 0
\]

and

\[
x^* = 1 - \alpha
\]

This shows that a positive sustainable equilibrium exists only when:

\[
\alpha < 1
\]

or equivalently:

\[
h < r
\]

## Maximum Sustainable Harvest

The project identifies that the largest sustainable harvest occurs when the balance between population growth and harvest is optimised.

The harvest expression is:

\[
\alpha x^* = \alpha(1 - \alpha)
\]

This reaches its maximum when:

\[
\alpha = \frac{1}{2}
\]

giving a maximum harvest rate of:

\[
\frac{1}{4}
\]

This result illustrates the idea that the most sustainable harvest does not occur when the fish population is maximised, but when the population is at a level where growth is strongest.

## Profitability and Sustainability

The project then connects the biological model to economic interpretation.

The analysis considers:

- Fishing effort
- Harvest quantity
- Revenue from catch
- Cost of fishing effort
- Profit maximisation
- Maximum Sustainable Yield
- Maximum Economic Yield

The report explains that increasing fishing effort may initially increase catch and revenue, but excessive effort reduces the fish population and eventually lowers profitability.

A key distinction is made between:

### Maximum Sustainable Yield

The harvest level that maximises sustainable catch while preserving the fish population.

### Maximum Economic Yield

The level of fishing effort where profit is maximised after considering both revenue and cost.

The project argues that maximum economic yield may occur at a lower catch level than maximum sustainable yield, because profit depends not only on catch quantity but also on fishing cost.

## Key Findings

- Fish population growth can be represented using a logistic growth model.
- Carrying capacity limits long-term population growth.
- Adding a harvesting term allows the model to represent fishing activity.
- If the harvest rate is lower than the natural growth rate, a stable positive equilibrium can exist.
- If the harvest rate exceeds the natural growth rate, the population may collapse.
- The maximum sustainable harvest occurs when \(\alpha = 1/2\).
- Profitability depends on the relationship between revenue, cost, and fishing effort.
- Maximum economic yield and maximum sustainable yield are related but not identical.
- Overfishing can reduce both ecological sustainability and long-term profitability.

## Project Files

| File | Description |
|---|---|
| `Fishery_Population_Dynamics_Modelling_Report.docx` | Written mathematical modelling report discussing logistic growth, harvesting equilibrium, overfishing risk, sustainability, and profitability |


## Tools and Techniques

- Mathematical modelling
- Logistic growth modelling
- Differential equations
- Equilibrium analysis
- Non-dimensionalisation
- Sustainability modelling
- Economic interpretation
- Conceptual model analysis
- Technical writing

## Skills Demonstrated

- Applied mathematics
- Population dynamics
- Differential equation interpretation
- Sustainability analysis
- Harvest rate modelling
- Equilibrium and stability reasoning
- Profitability analysis
- Scientific communication
- Model-based decision reasoning

## Limitations

This project is a conceptual mathematical modelling report rather than a data-driven empirical study.

The model uses simplified assumptions, including:

- Constant growth rate
- Constant harvest rate
- Fixed carrying capacity
- Simplified cost and revenue relationships
- No stochastic environmental variation
- No age structure or species interaction
- No real-world fishery dataset calibration

In real fisheries, population dynamics may also depend on environmental shocks, migration, changing reproduction rates, policy restrictions, market demand, and ecosystem interactions.

## Future Improvements

This project could be extended by:

- Adding numerical simulations of fish population over time
- Plotting population trajectories under different harvest rates
- Comparing stable and unstable equilibria visually
- Introducing real fishery data
- Estimating model parameters from observed catch data
- Adding stochastic environmental effects
- Modelling price and cost variation over time
- Building a Python or R simulation notebook

## Conclusion

This project demonstrates how mathematical modelling can be used to analyse the balance between ecological sustainability and economic profitability in fisheries.

By extending the logistic growth model with a harvesting term, the project shows how overfishing can lead to population collapse, while carefully controlled harvesting can support both sustainable equilibrium and long-term profit.

The project provides a clear example of how applied mathematics can support decision-making in environmental management, resource economics, and sustainability planning.
