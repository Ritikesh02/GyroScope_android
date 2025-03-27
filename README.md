Gyroscope Sensor Example 📱🔄
This Android app demonstrates how to use the gyroscope sensor to detect rotation along the x, y, and z axes and display the sensor values on the screen.

📌 Features
Detects rotation movement using the gyroscope sensor.

Displays real-time x, y, and z rotation values.

Shows a Toast message when sensor values change.

Checks if the device has a gyroscope and registers the listener accordingly.

🛠 Technologies Used
Kotlin

Android Sensor API

ConstraintLayout

📜 Code Explanation
MainActivity.kt (Main Activity)
This class implements SensorEventListener to listen for gyroscope sensor events.

🔹 onCreate()
Initializes the SensorManager to access the gyroscope sensor.

Finds the TextView (gyroscopeData) for displaying sensor values.

Checks if the gyroscope is available on the device and registers the listener if it exists.

🔹 onSensorChanged()
Reads the gyroscope x, y, and z values when a rotation is detected.

Updates the TextView with real-time sensor data.

Displays a Toast message when values change.

🔹 onResume()
Re-registers the gyroscope listener when the
