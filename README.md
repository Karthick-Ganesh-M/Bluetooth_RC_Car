# Bluetooth_RC_Car

                                                         🚗 Bluetooth-Controlled RC Car

 The Bluetooth-Controlled RC Car is a DIY robotics project designed to remotely control a four-wheel drive car using a smartphone via Bluetooth communication. The system uses an Arduino UNO as the central controller, an L298N Motor Driver to control motor direction and speed, and an HC-05 Bluetooth module to interface with a mobile device. The car receives movement commands (forward, backward, turn, stop, etc.) wirelessly and executes them in real-time.
This project demonstrates the integration of basic motor control, wireless communication, and embedded systems to create an interactive, customizable robotic vehicle.

                                                            🧰 Components & Functions

      Component	                           Function
      
  1) Arduino UNO    	          Acts as the main microcontroller to read Bluetooth commands and control motor driver outputs.
  2) L298N Motor Driver   	    Controls the direction and speed of the 4 DC motors using PWM and digital signals from the Arduino.
  3) HC-05 Bluetooth Module   	Establishes wireless communication between the smartphone and the car for real-time control.
  4) DC Motors (x4)           	Provide motion to the wheels; connected via the motor driver to allow forward/reverse control.
  5) Battery Pack	              Powers the Arduino, motor driver, and Bluetooth module. Typically a 9V or 12V supply is used.                                                      
