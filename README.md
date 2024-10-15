# Machine_Failure_Prediction
Python code that predicts Machine Failure  using Sensor data and Machine Learning.
learning machine programme that predicts machine failures before they occur, allowing preventive maintenance to be carried out and avoiding loss of production due to unscheduled downtime and repair time.

As input data, 9 sensors have been used to measure:
    1.- footfall: The number of people or objects passing by the machine. Range 0--n
    2.- tempMode: The temperature mode or setting of the machine. Range=0--7
    3.- AQ: Air quality index near the machine. Range 1--7
    4.- USS: Ultrasonic sensor data, indicating proximity measurements.Range 1--7
    5.- CS: Current sensor readings, indicating the electrical current usage of the machine. Range 1--7
    6.- VOC: Volatile organic compounds level detected near the machine. Range 0--6
    7.- RP: Rotational position or RPM (revolutions per minute) of the machine parts. Range 1 --100
    8.- IP: Input pressure to the machine. Range 1--7
    9.- Temperature: The operating temperature of the machine. Range 0-30

The following models have been tested and compared:
    1.- Logistic Regression.
    2.- Decision Trees.
    3.- Random Forest.
    4.- Gradient Boosting (e.g., XGBoost, LightGBM).
    5.- Support Vector Machines (SVM).
    6.- K-Nearest Neighbors (KNN).

Resultando el mejor modelo SVM
Performance-optimised SVM model:
    Accuracy: 90%
    Precision: 0.8511

