# FM-using-Python

Aim


To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program

<img width="830" height="601" alt="image" src="https://github.com/user-attachments/assets/83d008cf-f42b-4f15-9015-f95110c6d5dd" />


Output Waveform

<img width="928" height="637" alt="image" src="https://github.com/user-attachments/assets/781a19b1-de74-41fd-966b-655d7d4bbfc1" />


Tabular Column

<img width="1537" height="950" alt="image" src="https://github.com/user-attachments/assets/00cc6022-e95f-4422-9efc-b3277baed361" />


Calculation

<img width="711" height="608" alt="image" src="https://github.com/user-attachments/assets/d25b568b-ebe9-4b3e-8d11-9fe5923dbf34" />

Result

The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.
