CE3_Stolze
==========

Computer Exercise 3 

# Moore Waveform

![alt text](https://raw.github.com/aaronstolze/CE3_Stolze/master/Moore_Waveform.PNG "MooreWaveform")

# Mealy Waveform

![alt text](https://raw.github.com/aaronstolze/CE3_Stolze/master/Mealy_Waveform.PNG "Mealy Waveform")

# Analysis

I was able to confirm that both simulations were correct since the floor number would change on the rising edge of the clock which occured when up_down was set to '1'.  The elevator would then stay on the current floor for two clock cycles (20 ns) before it would move again.  

# Questions and Answers

What is the clock frequency?  
The clock frequency is 100MHz.

What value would we set to simulate a 50MHz clock?
A 50MHz clock would be set at a 20 ns period.  

Is reset synchronous or asynchronous?
Reset is synchronous.

Will the Mealy shell be different than the Moore shell?
No, they will both have the same state-process.  
