# TASK 4 :Controlling servo motor through web server

## What is servo motor?

servo motors have low speed but has high torque and their rotation is limited only to 90, 180 or 270 degrees. Servo motor needs a control signal using which we can control the position of the shaft.

## How does servo motor works?

A servo motor is a motor with a built-in “servomechanism”.
The servomechanism uses a sensor to monitor the motor shaft position and a controller to control the motor. It is fed a signal that indicates the position that the shaft should be set to. It then moves the motor into the required position.  

In the analog servo motors, we will be working with that control signal is a PWM signal whose pulse width determines the angle the motor shaft is to be positioned at.  The motor itself is a simple DC motor with a lot of gearing to slow down its speed and to increase its torque.

In order to function properly the servo motor needs a sensor that can accurately measure its shaft position. On some industrial and high-end hobby servos this is done using an optical interrupter disc, but in most standard hobby servo motors the sensor is a potentiometer.  This works well as these servos typically travel 180 to 270 degrees, well within the range of a potentiometer. However, the accuracy of potentiometers, especially in low-cost servo motors, can affect the overall accuracy of the servomechanism.


## Connections to run a servo motor

* Connect the control pin of servo motor to pin 18 of esp32.
* Connect vcc and gnd of servo to vcc and gnd in esp32.

## Procedure 
*	Open arduino ide and write the code
  code :
* Save and compile the code.
*	Select the appropriate com port and board(esp32 devmodule).
*	Upload the code to esp32.
*	Now, servo motor will start rotating.

## Working 
 https://drive.google.com/file/d/173DHjtRFwmZHysfmCXCid9Uza5A6J-h-/view?usp=sharing
 
 # Controlling servo motor using potentiometer
 
 ## Connections for controlling servo motor using potentiometer
 ![this is an image](https://github.com/bhooshan11/Controlling-servo-motor-through-web-server/blob/main/circuit%20for%20servo%20motor%20controlling%20using%20potentiometer.jpg)
 
 **Code for controlling servo motor using potentiometer :**- 
 
 ## Working 
  https://drive.google.com/file/d/10ClpV2dcTy-nv8FdkwQvSkRxsCX_dRNO/view?usp=sharing
  
  # Controlling servo motor using web server
  
  ## Connections :
* Connect the control pin of servo motor to pin 18 of esp32.
* Connect vcc and gnd of servo to vcc and gnd in esp32.

**Code for controlling servo motor using web server**


## Procedure 
*	Copy and  paste the above code in Arduino ide.
*	Select the appropriate board and com port.
*	Compile the code.
*	Upload the code to esp32.
*	Open the serial monitor.
*	Press reset button in esp32.
*	Now you can see esp32 connecting to WIFI.
*	 Once esp32 is connected to wife, serial monitor will display an Ip address. Note down the Ip address.
*	Go to the web browser like google chrome.
*	Enter the Ip address obtained earlier in the search tab.
*	You can see a website with a slider. Move the slider to control the position of the servo motor.

## Working
https://drive.google.com/file/d/10ClpV2dcTy-nv8FdkwQvSkRxsCX_dRNO/view?usp=sharing
## Problems faced

* The website was not loading in computer, then i tried in mobile it worked.


## Refrences
https://dronebotworkshop.com/esp32-servo/  
