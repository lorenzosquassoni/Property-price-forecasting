# Property-price-forecasting

![Descrizione dell'immagine](Property_Price_Forecasting_Outline.png)

## TABLE OF CONTENTS

1. Loading and dataset manipulation
2. Dataset exploration and correlation analysis
3. Time series pattern analysis on single states
4. Forecasting models
   

**TESTED MODELS**

| State          | Tested Models |
|---------------|--------------|
| **California** | Simple models (mean, naive, seasonal naive, drift); ETS (Single, double, triple); Manual SARIMA (1,1,1)(0,1,0,12); Manual SARIMA (1,1,1)(0,1,1,12); Auto SARIMA (1,0,1)(3,0,0,12) |
| **Florida** | Simple models (mean, naive, seasonal naive, drift); ETS (Single, double, triple); Manual ARIMA (1,1,0); Manual ARIMA (1,1,1); Auto ARIMA (1,0,1); Auto SARIMA (1,0,1)(5,0,0,12) |
| **Illinois** | Simple models (mean, naive, seasonal naive, drift); ETS (Single, double, triple); Manual ARIMA (1,1,0); Manual ARIMA (1,1,1); Auto ARIMA (1,0,1); Auto SARIMA (1,0,1)(5,0,0,12) |
| **Michigan** | Simple models (mean, naive, seasonal naive, drift); ETS (Single, double, triple); Manual ARIMA (1,1,0); Manual ARIMA (1,1,1); Auto ARIMA (1,0,1) |
| **North Carolina** | Simple models (mean, naive, seasonal naive, drift); ETS (Single, double, triple); Manual ARIMA (1,1,0); Manual ARIMA (1,1,1); Auto ARIMA (1,0,2) |


**BEST MODEL FOR STATE BASED ON AIC**

| State          | Best Model |
|---------------|--------------|
| **California** | Manual SARIMA (1,1,1)(0,1,0)m=12|
| **Florida** | Auto SARIMA (1,0,1)(5,0,0)m=12 |
| **Illinois** | Manual ARIMA (1,1,0) |
| **Michigan** | Manual ARIMA (1,1,0) |
| **North Carolina** | Manual ARIMA (1,1,0) |




**BEST MODELFOR STATE BASED ON MAE**

| State          | Best Model |
|---------------|--------------|
| **California** | Auto SARIMA (1,0,1)(3,0,0)m=12|
| **Florida** | Auto SARIMA (1,0,1)(5,0,0)m=12 |
| **Illinois** | Manual ARIMA (1,1,1) |
| **Michigan** | Manual ARIMA (1,1,0) |
| **North Carolina** | Manual ARIMA (1,1,1) |
