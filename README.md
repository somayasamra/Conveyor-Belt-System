# Conveyor-Belt-System

a system which is composed of: a conveyor belt and two Sensors. 
  • The 1st sensor is going to send a pulse to microcontroller whenever a box passed through it. 
  • The 2nd Sensor will measure the total weight of the boxes.
  
The system counts the boxes normally using TMR0, knowing that each box ≈ 1KG.       
Once the count reaches 9, the system should stop the motor for 5 seconds to allow the workers to take the 9 boxes. Then the system restarts the counting again.
The total weight should be within the expected range which is 8 to 10 KG.
If the Total Weight is not within the expected range, then notify the workers by turning on a Red LED. 
Otherwise keep the Red Led Turned Off and Keep the Green LED Turned ON.
 Language used: Pic language
