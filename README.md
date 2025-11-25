# Home-assistant-Climate-helpers

The following helpers will create 3 climate prediction sensors.<br>
First implemented to montior the performace of my newly installed ducted heating and cooling system.

# Create the sensors

Derivative sensor:<br>
Name: sensor.room_temperature_derivative<br>
Precision: 2<br>
Time window: 0:15:00<br>
Time unit: Minutes<br>

Template Sensor:<br>
Entity ID naming Convention: sensor.room_temperature_future

Template Sensor:<br>
Entity ID naming Convention: sensor.room_time_to_setpoint

Dashboard card pulling airtouch information combinded with the prediction sensors.<br>
![alt text](image.png)

# Limitations
Time to setpoint sensor only works for heating currently.<br>
Needs an update to account for cooling modes.