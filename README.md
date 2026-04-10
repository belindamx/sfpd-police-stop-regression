## San Francisco Police Stop Duration by Perceived Demographic Characteristics

This analysis examines how stop duration varies across perceived race, age, and gender using San Francisco Police Department (SFPD) data. Stop duration is highly skewed, so it is modeled with linear regression on a log scale.

**Key Findings**
- Stop duration varies across perceived demographic groups  
- Some race-based differences remain **statistically significant** even after adding controls  
- Adding age and gender reduces the magnitude of some effects, suggesting confounding factors  

**Methodology**
- Dataset: SFPD stop data from San Francisco Open Data Portal  
- Target: stop duration (log-transformed)  
- Features: perceived race, age, gender  
- Approach: linear regression (descriptive, not causal)  
- Compared models with and without additional controls  

**Data source:** San Francisco Open Data Portal  
https://data.sfgov.org/Public-Safety/Count-of-Individuals-Stopped-by-Reason-for-Stop-by/a5da-x8ji  

**Files**
- `sfpd_stop_duration_regression.rmd`
- `sfpd_stop_duration_regression.pdf`
