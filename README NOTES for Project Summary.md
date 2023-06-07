# ANALYSIS-OF-LIFE-EXPECTANCY-USING-Panel-Data-Regression-Technique
In today's so called Fast-Paced world, that we live for earning more money, thinking that: Well, Having more money &amp; Being Rich will surely allow me to LIVE LONGER ! But is it the case ? Does having more money or living in a country with higher gdp_per_capita or living in a country with higher Co2_emissions causes life expectancy to be more or less ? Does Government policies also has effects on our LIFE EXPECTANCY ? Let's Check with proper PANEL DATA of more than 115 countries from 2008 to 2018, ie., last decade and check our common notions in form of Null Hypothesis !!!

Important Steps:
1. Visualizing data
2. Cleaning data
3. Filling missing values using Mean or Median fills
4. Building models using pooledOLS and panelOLS estimators with **TIME and ENTITY fixed effects** separately or simultaneoulsy !
5. Hypothesis testing for assumptions
6. Presenting conclusions with proofs from tests

Following conclusions are drawn from my study:
1. If we allow for the possibility that life expectancy changes over time because of global changes (like, e.g. medical discoveries, wars and conflicts, famine, draught, floods, pandemic diseases) and that countries come from different starting grounds (e.g., because of their geographic location), then we cannot observe a robust association of GDP per capita with life expectancy.
2. Yes, countries having higher GDP per capita do have higher life expectancy, but it’s not the caused/justified by sole effects of GDP per capita, the model requires supporting variables.
   So many different factors also have simultaneous effects on each other and dependent variable: LIFE_EXPECTANCY as well. So When considered their simultaneous effects, then we are somewhat capable of EXPLAIN the Errors and Justify relations and causality with each other !
   
   THIS IS MOST BEAUTIFUL CONCLUSION AND OBSERVATION from my project...
3. No, Co2 emission did not directly affected life expectancy during last decade !
   It might seem like that, increases Co2_emissions must reduce Life_Expectancy, but NO !!
   I found that, over 115 countries with Panel Data of over a decade from 2008 to 2018, when studied, then Co-relation of Co2_emission came out to be: 0.1797 !
   Now, How can this be POSITIVE ?
   Consider scenario, for developing countries, Co2_emission is increased becuase of High Energy Requirements from 1.HEALTH INFRASTRUCTURE 2.TRANSPORTATION 3.LARGE SECTER OF FARMING 4.INDUSTRIALIZATION
   Hence, Co2_emission is actually POSITIVELY CO-RELATED With HEALTH_EXPECTANCY !!!
