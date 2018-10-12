# NaturalDisasterPredict
Project Idea For CodeFunDo++. Team Members - Sarthak Srivastava, Abhay Agarwal, Harshit Goyal ;)

## IDEA:
1. In India, major natural disasters comprise of Floods, Droughts and Earthquake, each of which has a major toll on life of a large number of people - economically, mentally as well as physically. Most of this can be avoided/ dealt with via appropriate preparation through timely alerts and warnings.
2. The project aims at developing a probabilistic system to predict each of the three calamities using time series prediction algorithms(such as LSTMs) and considering scores of prediction from an ensemble of machine learning algorithms (such as Random Forest).
Training such algorithms on past records of seismic activities, rainfall records, soil quality records, previous calamity history, such disasters will be predicted for a particular region.
3. Bonus- If time permits, this idea will also explore prediction of epidemic disease breakout via analysis of local hospital records, effectively helping people take proper precautions in due time.
4. As of now, the app is expected to provide service through an online website hosted on azure server. 
5. In Case of successful prediction of a natural disaster, an email can also be sent to people from a common government database using Simple Mail Transfer Protocol(SMTP). In case of less developed areas lacking internet facilities, communication can be done through government offices having internet facilities.


### Algorithmic Detail:
Use of CNN+LSTM. CNN - convolution neural network to act as filter for deciding the relevant factors for prediction from a pool of available suspected features for natural disaster prediction. Long Short Term Memory Reccurrent Neural Nets for making a prediction out of the selected features regarding classes consisting of 1. No disaster 2. Drought 3. Flood 4. Storm 5. Epidemic.

### Earthquake prediction features:
1. Hydrochemical Precursors, 2. Temperature Change, 3. Water Level, 4. Oil Wells, 5. Theory of Seismic Gap, 6. Foreshocks, 7. Changes in Seismic Wave Velocity

### Drought Prediction: 
Among other features as rainfall records, soil quality, past data records and historical correlations, use of Standardized precipitation Index (SPI) as data input.
