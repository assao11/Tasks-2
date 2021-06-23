# Tasks-2
use DC  Motor , we will connect external 9V power supply to the Vcc2 pin.

Next, we need to supply 5 Volts for the L293D’s logic circuitry. Connect Vcc1 pin to 5V output on Arduino. Make sure you common all the grounds in the circuit.

Now, the input and enable pins(ENA, IN1, IN2, IN3, IN4 and ENB) of the L293D IC are connected to six Arduino digital output pins(9, 8, 7, 5, 4 and 3). Note that the Arduino output pins 9 and 3 are both PWM-enabled.

Finally, connect one motor to across OUT1 & OUT2 and the other motor across OUT3 & OUT4.
