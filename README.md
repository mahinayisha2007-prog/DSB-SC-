# DSBSC


EX NO: 2	DSB-SC-AM MODULATOR AND DEMODULATOR

AIM:

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED

•	Computer with i3 Processor
•	SCI LAB

Note: Keep all the switch faults in off position

Algorithm:

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
PROCEDURE

•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
 
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

<img width="703" height="679" alt="image" src="https://github.com/user-attachments/assets/e7c7c7f8-ccf2-41ac-b1f3-325989941a6f" />

Program

<img width="678" height="708" alt="Screenshot 2025-11-15 133718" src="https://github.com/user-attachments/assets/f2636459-a3fc-45fa-a879-aec5f1ac16e5" />


Output Graph

<img width="755" height="699" alt="Screenshot 2025-11-15 133450" src="https://github.com/user-attachments/assets/30fdbcc1-90ae-4aa8-a3b2-7e4a33396e98" />


Tablular Column

![WhatsApp Image 2025-11-15 at 13 25 04_a182811d](https://github.com/user-attachments/assets/981673bf-2c98-4d36-9065-ddf43845bfd0)

Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

