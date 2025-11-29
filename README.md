
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="526" height="199" alt="image" src="https://github.com/user-attachments/assets/d9b577e8-63e8-47ae-baa1-6dbc21dba9e8" />


## CONNECTION DIAGRAM  

<img width="514" height="135" alt="image" src="https://github.com/user-attachments/assets/37e8025f-5485-474a-87de-45e66b5519cc" />


## TABULATION  
**Transmission through Digital Link**

V1=10V

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain (Vo/Vi) | Gain (dB) |
| -------------- | ---------------------------- | ------------ | --------- |
| 1 kHz          | 3.48 V                       | 0.496        | -6.08     |
| 5 kHz          | 4.74 V                       | 0.948        | -0.46     |
| 10 kHz         | 9.78 V                       | 1.986        | 5.827     |
| 20 kHz         | 11.47 V                      | 2.294        | 7.21      |
| 50 kHz         | 12.90 V                      | 2.58         | 8.23      |
| 75 kHz         | 12.85 V                      | 2.58         | 8.23      |
| 100 kHz        | 10.85 V                      | 2.19         | 6.729     |
| 150 kHz        | 8.47 V                       | 2.17         | 6.729     |
| 250 kHz        | 5.48 V                       | 9.694        | 4.878     |

![WhatsApp Image 2025-11-24 at 08 04 56_91e7548a](https://github.com/user-attachments/assets/de266c97-1f0c-4a9e-ac5a-725fcf89aca6)


## MODEL GRAPH

<img width="704" height="339" alt="image" src="https://github.com/user-attachments/assets/ce3bef6a-3b04-4399-ab0f-1938433d0c7b" />


![WhatsApp Image 2025-11-24 at 08 04 56_caa34713](https://github.com/user-attachments/assets/761ceedb-0296-432f-860e-39bebf8ad639)


## RESULT

Hence, the relationship between input and received signal of a 600nm fiber optic cable using digital link is verified
