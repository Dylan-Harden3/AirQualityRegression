### Setup/Installation
You can run the Regression.ipynb on colab or any jupyter notebook environment.

### Approach
Using the following 11 features we can predict the Air Quality or PT08.S1(CO)
| Feature          | Definition                                            |
|------------------|-------------------------------------------------------|
| NMHC(GT)         | Hourly averaged overall Non Methanic Hydrocarbons (NMHC) concentration in µg/m³ |
| C6H6(GT)         | Hourly averaged Benzene concentration in µg/m³         |
| PT08.S2(NMHC)    | Hourly averaged sensor response to NMHC                |
| NOx(GT)          | Hourly averaged NOx concentration in ppb               |
| PT08.S3(NOx)     | Hourly averaged sensor response for NOx                |
| NO2(GT)          | Hourly averaged NO2 concentration in µg/m³             |
| PT08.S4(NO2)     | Hourly averaged sensor response for NO2                |
| PT08.S5(O3)      | Hourly averaged sensor response for O3                 |
| T                | Temperature in Celsius                                 |
| RH               | Relative Humidity                                      |
| AH               | Absolute Humidity                                      |
| PT08.S1(CO)      | TARGET VARIABLE - Hourly averaged sensor response for CO|
