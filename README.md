# Weather-forecast
An AI-powered weather forecast system which predict the weather status based on the data gathering temperature, humidity, air pressure,... 
Using dataset from https://www.worldweatheronline.com/. The dataset consists of 18 features collected over the time period of 7 years, recorded once per hour. Location: Weather Station: Ho Chi Minh city, Viet Nam.
A lot of powerful time-series models such as CNN, RNN, LSTM, BiLSTM have been tried to achieve the best result. LSTM for numerical prediction so far is our most optimal option in terms of accuracy despite their disadvantage on the trainning time. The prediction for categorical value of raining will be applied BiLSTM. 
