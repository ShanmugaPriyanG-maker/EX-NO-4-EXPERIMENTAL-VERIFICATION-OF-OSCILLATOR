# EX-NO-4-EXPERIMENTAL-VERIFICATION-OF-OSCILLATOR
4. ##**EX.NO:* ## EXPERIMENTAL VERIFICATION OF RC Phase Shift and Wien Bridge oscillators 
	DATE:
 ##AIM:
To construct a RC phase shift and Wien bridge oscillator to generate sine wave using op-
amp.
---
 ##THEORY:
 ##RC PHASE SHIFT OSCILLATOR
RC phase shift oscillator produces 360° of phase shift in two parts. Firstly,each and every RC pair in the feedback network produces 60° phase shift and totally there were three pairs, thus producing 180° Phase shift and secondly, the feedback input is given to the inverting terminal of op-amp to produce another 180° phase shift and a total phase shift of 360°.
The frequency of oscillation is given by fo = 1 /  6 (2RC ).If an inverting amplifier is used, the gain must be atleast equal to 29 to ensure the oscillations with constant .
---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 6   | Connecting wires and probes     | As required   | —        |
| 



---
## CIRCUIT DIAGRAM
RC PHASE SHIFT OSCILLATOR
![20251203_214250](https://github.com/user-attachments/assets/26ab2162-2ef7-4e51-b214-58ce18522287)

---

## MODEL GRAPH
![20251203_214311](https://github.com/user-attachments/assets/6989cee6-935b-4977-852c-59ba5610bb73)

## DESIGN
![20251203_214349](https://github.com/user-attachments/assets/83087884-8d3a-4467-931a-97a79974c879)

## RC PHASE SHIFT OSCILLATOR
fo = 1 /  6 (2RC) Rf  29 R1
C = 0.01F, fo = 200 Hz.
R = 1 /  6 (2  f C ) = 3.3 k
Therefore, Choose R = 3.3k
To prevent loading,
R1   10 R
R1 =10 R = 33 k. Rf = 29R1=1MΩ

---
## PROCEDURE
1.	Connect the circuit as shown in fig. With the design values.
2.	Observe the output waveforms using a DSO.For obtaining sine wave adjust Rf.
3.	Measure the output wave frequency and amplitude.
---
## TABULATION/OBSERVATION
![20251203_214324](https://github.com/user-attachments/assets/403d2873-c4e6-487f-942e-3119e95d6665)

---
## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_214424](https://github.com/user-attachments/assets/f6b23792-c322-46ae-b292-5850102c9c52)

---
## THEORY
 ##WIEN BRIDGE
A bridge circuit with two components connected in series and parallel combination is used to archived the required of phase shift of 0o. When the bridge is balanced the phase shift of 0o is achieved and the feedback signal is connected to the positive terminal; of Op-amp. So the Op-amp is acting as a non-inverting amplifier and the feedback network do not provide any phase shift.
The frequency of oscillation is given by fo = 1/2πRC
## APPARATUS REQUIRED

| S.No | Name of the Apparatus          | Range         | Quantity |
|------|---------------------------------|---------------|----------|
|1    | DSO                             | 30 MHz        | 1        |
|2   | Dual RPS                        | (0–30) V      | 1        |
| 3    | Op-amp                          | µA741         | 1        |
|4    | Bread Board                     | —             | 1        |
|5   | Resistors                       | 1K, 3.3K, 1.5K, 33K, 15K, 1MΩ | 2 |
|6    | Capacitor                       | 0.1 µF        | 3        |
| 7 | Connecting wires and probes     | As required   | —        |

---

## CIRCUIT DIAGRAM
WIEN BRIDGE OSCILLATOR
![20251203_214533](https://github.com/user-attachments/assets/85b81a40-3290-499c-b25c-5529771eb21f)

---
## MODEL GRAPH
![20251203_214603](https://github.com/user-attachments/assets/a0f3a5af-0f73-4d60-b6a6-c47873523db1)

---

## DESIGN
![20251203_214612](https://github.com/user-attachments/assets/94661561-df20-4cbb-9633-f53614aa2d03)

## WIEN BRIDGE OSCILLATOR
Select frequency f0 = 1KHz
fo = 1/2πRC
A = 1+(Rf / R1) = 3.
To find R & Rf.
Therefore Rf = 2R1 & assume C = 0.1μf & find R from
R=1/2πfC
=1/2*3.14*1*103*0.1*10-6
= 1.59KΩ.
Assume R1 = 10R & find Rf from Rf = 2R1
Therefore R1 = 1.5K *10=15KΩ
Rf = 15K *2=30KΩ
---

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.
---

## TABULATION/OBSERVATION
![20251203_214626](https://github.com/user-attachments/assets/08e7adb8-31dd-4f69-9f51-bee63502b3f1)

---

## OUT PUT WAVEFORM AND DISCUSSION 
![20251203_214643](https://github.com/user-attachments/assets/b06bf2c0-7b49-465c-8ed9-7527fa6e2a3f)

---

## RESULT:
![20251203_214654](https://github.com/user-attachments/assets/b569524a-0167-4a6a-8997-ac4d5dd86367)

Thus the RC Phase Shift and Wien Bridge oscillators are designed and tested using op-amp IC 741.
