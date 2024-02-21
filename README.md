In lab 3 we use both motor_driver and encoder_reader in order to control, record, and configure the movement of the motor using a Kp value and an inputted setpoint. 
We then use a response_test to record the values from the arduino into a list to then be graphed onto a Matplotlib plot. 

In each test, our setpoint was 65535 ticks. 

Test 1: Kp = 0.01
This test is too low of a Kp.
![kp 1E-2](https://github.com/ndavis26/Lab-3/assets/158105326/0a08b9dd-0ee2-412b-ac4b-a369605b5db5)

Test 2: Kp = 0.05
Optimal response.
![kp 5E-2](https://github.com/ndavis26/Lab-3/assets/158105326/ccd212dc-dd32-4e1f-995f-265ae04ed32e)


Test 3: Kp = 10
This test is too high of a Kp.
![kp 10](https://github.com/ndavis26/Lab-3/assets/158105326/668cc619-de77-4d6f-9deb-df0c92e18c0b)
