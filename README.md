# gradiometric-detection-1
Gradiometric detection of heart rate - analog model.

This is a project of PCB which includes:

- 10.7 MHZ sine generator (transmitting coil),
- place for receive a signal from receiver coil,
- synchronous demodulation,
- transmitting signal filtration.


How it works:

The generator transmits a signal to a transmitting coil, which is applied to the patient's chest. 
The carrier signal is received along with the wave signal from the mechanical operation of the heart through receiver coils arranged in an anti-parallel way. 
Then the signal is demodulated and filtered (we filter out the constant component of the carrier wave 10.7MHz). 

The resulting signal is a medium disturbance originating in the patient's chest.
