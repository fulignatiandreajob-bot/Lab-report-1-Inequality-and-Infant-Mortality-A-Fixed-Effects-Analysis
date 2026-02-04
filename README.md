# Lab-report-1-Inequality-and-Infant-Mortality-A-Fixed-Effects-Analysis
# Inequality and Infant Mortality: A Fixed-Effects Analysis

## Abstract
This study investigates the relationship between economic inequality (measured by the Gini index) and infant mortality rates globally. Using data from the Quality of Government (QoG) dataset, we apply Fixed Effects (FE) models to control for country-specific characteristics and time trends.

## Hypothesis
**H1:** Higher inequality is associated with higher levels of infant mortality.
This relationship is theorized to stem from unequal access to healthcare systems in economically inequitable societies.

## Methodology
The analysis proceeds in four steps:
1. **Descriptive Statistics:** Overview of Gini, Infant Mortality, GDP, Democracy, and Urbanization.
2. **Pooled OLS:** A baseline bivariate analysis ignoring panel structure.
3. **Fixed Effects (FE):** Within-country analysis to remove time-invariant national characteristics.
4. **Multivariate FE:** Adding time-varying controls (GDP per capita, Democracy Index, Urban Population).

## Data
The analysis uses the **Quality of Government (QoG) Standard Time-Series Dataset (Jan 25)**.
* **Dependent Variable:** Infant Mortality Rate (per 1,000 births).
* **Independent Variable:** Gini Index.
* **Controls:** GDP per capita (log), Liberal Democracy Index, Urban Population (%).
