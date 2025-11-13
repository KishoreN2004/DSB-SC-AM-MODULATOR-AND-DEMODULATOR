# DSB-SC-AM-MODULATOR-AND-DEMODULATOR
## AIM:
To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

## EQUIPMENTS REQUIRED
•	Computer with i3 Processor 
•	SCI LAB

Note: Keep all the switch faults in off position

## ALGORITHM:

1.	Define Parameters:
   
    •	Fs: Sampling frequency.
    
    •	T: Duration of the signal.
    
    •	Fc: Carrier frequency.
    
    •	Fm: Frequency of the message signal.
    
    •	Amplitude: Maximum amplitude of the message signal.

2.	Generate Signals:
 
  •	Message Signal: A sinusoidal signal that will be modulated.
  
  •	Carrier Signal: A high-frequency sinusoidal signal used for modulation.

3.	DSBSC Modulation:
   
  •	Modulated Signal: Multiply the message signal by the carrier signal to produce the DSBSC signal.

4.	DSBSC Demodulation:

  •	Multiplication: Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).

  •	Low-pass Filtering: Apply a Butterworth low-pass filter to remove the high- frequency components and recover the original message signal.

5.	Visualization:
   
  Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.

## PROCEDURE

  •	Refer Algorithms and write code for the experiment.
  
  •	Open SCILAB in System
  
  •	Type your code in New Editor
  
  •	Save the file
   
  •	Execute the code
  
  •	If any Error, correct it in code and execute again
  
  •	Verify the generated waveform using Tabulation and Model Waveform
  
## MODEL GRAPH:
<img width="503" height="479" alt="image" src="https://github.com/user-attachments/assets/9f4fdea5-8f1d-44ae-a75a-8c3737088c0a" />

## PROGRAM:

<img width="541" height="847" alt="Screenshot 2025-08-21 153631" src="https://github.com/user-attachments/assets/73521030-b372-4615-838c-f01f7685a077" />

<img width="537" height="113" alt="Screenshot 2025-10-16 184641" src="https://github.com/user-attachments/assets/302e2303-2547-43c7-80ec-ec43f1ef36dc" />


## TABULATION:

![IMG-20251016-WA0022](https://github.com/user-attachments/assets/534c3885-cb74-42cc-abbd-479ddb73affd)


## OUTPUT:

<img width="809" height="744" alt="image" src="https://github.com/user-attachments/assets/d8eff769-bb77-4611-a760-7df655982c0b" />


## RESULT:

Thus the DSB-SC-AM Modulation and Demodulation is generated.
