# 0.6V-W-Power-Four-Stage-OTA-with-Minimal-Components
This repository presents the design and simulation of a 0.6 V, ultra-low power four-stage Operational Transconductance Amplifier (OTA) implemented in 65 nm CMOS technology. The design focuses on achieving stable operation at low supply voltage with minimal components while supporting a wide load range.  
The project is implemented and simulated using Cadence Virtuoso, and performance is evaluated in terms of gain, phase margin, noise, CMRR, and PSRR.


This repository presents the design and simulation of a 0.6-V, ultra-low-power four-stage Operational Transconductance Amplifier (OTA) implemented in 65 nm CMOS technology.
The design focuses on minimal component count, low supply voltage operation, and wide load range, making it suitable for low-power analog and mixed-signal applications.

🧠 Key Features

Supply Voltage: 0.6 V

Ultra-low power operation (μW range)

Four-stage OTA architecture

Minimal transistor count (14 transistors)

Wide load driving capability (100× load range)

Designed and simulated in Cadence Virtuoso

🏗️ Architecture

Technology: 65 nm CMOS

Number of Stages: 4

Total Transistors: 14

Reference Current: 180 nA

Supply Voltage (VDD): 0.6 V

🔬 Circuit Implementation

The OTA circuit is implemented and verified using Cadence Virtuoso.
Multi-stage gain is achieved using cascaded amplifier stages with frequency compensation to ensure stability.

📊 Simulation Results
🔹 Stage-Wise Gain

1st Stage Gain: 31 dB

2nd Stage Gain: 48 dB

3rd Stage Gain: 54 dB

🔹 Overall Performance

DC Gain: 77.93 dB

Unity Gain Frequency (UGF): 986.25 kHz

Phase Margin: 31°

PM = 180° − 149°

🔹 Frequency Compensation (Peaking Compensation)

𝑅a=400𝑘

Ca=700fF


📈 Additional Performance Metrics

AC Common-Mode Gain

Input-Referred Noise

Output-Referred Noise

Common-Mode Rejection Ratio (CMRR)

Power Supply Rejection Ratio (PSRR)

(Simulation plots available in the results section)

📑 Performance Comparison
Parameter	Original Work	This Work
Technology (nm)	180	60
No. of Transistors	14	14
VDD (V)	0.6	0.6
Gain (dB)	119	78
CMRR (dB)	182	75
PSRR (dB)	51	39
Noise (nV/√Hz)	750	63.2




🛠️ Tools Used

Cadence Virtuoso

Spectre Simulator

65 nm CMOS PDK

👤 Author

Aditi Dhibar
Analog / IC Design Enthusiast

