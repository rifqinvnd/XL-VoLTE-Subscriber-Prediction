# XL-VoLTE-Subscriber-Prediction
### Background
The development of technology in the world and in Indonesia is currently running fast and increasingly sophisticated so that it has an impact on daily life, especially the use of information technology in particular to predict the possibilities that will occur in the future in order to be able to prepare several things needed for several company needs including PT. XL Axiata Tbk. With a system that can accurately predict future data, companies can run their services quickly, effectively, and efficiently.

PT. XL Axiata Tbk has a problem in determining the time needed to upgrade all licenses and VoLTE for XL users as well as the number of active subscribers and the highest possible traffic. With this, I found a solution by creating a Machine learning model using the Supervised Learning method and a Deep learning model using the Time series forecasting method when doing practical work in the Service Operation Management team at PT. XL Axiata Tbk which can predict the time when all XL users' licenses and VoLTE have been upgraded. This Machine learning and Deep learning model uses data on the development of license and VoLTE improvements for XL users from September 2021 to December 2021. The time obtained from the machine learning predictions can be used to predict the highest number of active subscribers and traffic so that the metrics can be properly prepared. used as a reference, namely the Mean Absolute Error (MAE). With the prediction of this machine learning model, PT. XL Axiata Tbk is expected to get higher effectiveness and efficiency in its services.

### Tech
Language : Python
Library  :
- Data Preprocessing  : NumPy, Pandas, Matplotlib, Scikit-learn (MinMaxScaler), datetime
- Modeling            : TensorFlow, Keras, Scikit-learn.linear_model (LinearRegression, RANSACRegressor, QuantileRegressor)
- Evaluation          : Scikit-learn (metrics)
