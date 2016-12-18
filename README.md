# nrf51_input1
copy of nordic semi conductor sdk simple input program. Some files have been moved around so it compiles in eclipse

I have replaced the button with a simple PIR and the program works
I plan to add this code to the mqtt code so that the sensor state can be published when the sensor goes off. 
This wil mean modifying the interupt handler 
void in_pin_handler(nrf_drv_gpiote_pin_t pin, nrf_gpiote_polarity_t action)
