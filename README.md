Car Price Prediction with TensorFlow
This project demonstrates the use of TensorFlow to build a predictive model for car prices based on features like mileage, horsepower, and top speed.

Requirements
Python 3.x
TensorFlow
Pandas
NumPy
Seaborn
Matplotlib
Install dependencies with:

bash
Copy code
pip install -r requirements.txt
Data Overview
The dataset includes features like mileage, hp, top speed, and current price (target variable). The data is normalized, split into training, validation, and test sets, and processed using TensorFlow.

Model Architecture
The model is a simple feedforward neural network with three hidden layers. It is trained to predict the car price using mean absolute error loss and root mean squared error metric.

python
Copy code
model = tf.keras.Sequential([
    InputLayer(input_shape=(8,)),
    normalizer,
    Dense(128, activation="relu"),
    Dense(128, activation="relu"),
    Dense(1)
])
Training
The model is trained for 100 epochs using the Adam optimizer.

python
Copy code
model.compile(optimizer='adam', loss='mae', metrics=['rmse'])
history = model.fit(x_train, y_train, epochs=100, validation_data=(x_val, y_val))
