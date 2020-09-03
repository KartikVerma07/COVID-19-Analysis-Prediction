### COVID-19-Analysis-Prediction

**Analysis** of live time COVID-19 data is done, describing various plots such as:
*Conuntry & Continent wise Reported Cases
*World Map describing Confirmed Cases, Deaths, Mortality Rate 
*Heat map for Confirmed cases & Deaths for Various Countries
*COVID-19 Spread Analysis
*COVID-19 Mortality Rate variation over Time

Best possible **Prediction** of COVID-19 data was done using Deep Learning Approach(LSTMs), created a multi-step Univariate LSTM (with one feature variable) model to predict the next 15(high value not possible due to non-staionarity of data) values in the dataset separately for different countries. 

Main **Python Libraries** Used:
* Folium for representing data on a World Map  
* pycounty-convert
* Numpy & Pandas
* plotly=4.8.1
* keras in Tensor flow
* sklearn for Data Preprocessing
