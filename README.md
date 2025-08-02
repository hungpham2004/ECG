# ECG
Biomedical Electronics Project: ECG Signal Processing
Description
This project, developed by Group 3, focuses on designing and simulating an Electrocardiogram (ECG) circuit for biomedical applications. The ECG system is designed to capture and process the electrical activity of the heart, which is characterized by low-amplitude (0.2-2mV) and low-frequency signals, often affected by environmental and biological noise. The project includes the following key components:

Overview:

Introduction to ECG as a non-invasive clinical tool for visualizing heart electrical activity.
Explanation of ECG signal characteristics, including P, Q, R, S, T, and U waves, representing atrial and ventricular depolarization and repolarization.
Applications in heart monitoring, pacemakers, and cardiac diagnostics in clinical settings such as operating rooms and ambulances.


Design and Calculations:

Differential Amplifier: Amplifies the low-amplitude ECG signal to a measurable level.
4th-Order Low-Pass Filter: Designed with a cutoff frequency of 150Hz to remove high-frequency noise, using capacitors (470nF) and resistors (2.2kΩ, 1.8kΩ, 270Ω).
Notch Filter: Configured with a cutoff frequency of 50Hz to eliminate powerline interference, using capacitors (47nF, 100nF) and resistors (33kΩ, 68kΩ).


Simulation and Results:

Simulated using LTspice to model the complete ECG circuit, including signal amplification, low-pass filtering, and notch filtering.
Frequency response and signal outputs analyzed before and after filtering to validate noise reduction and signal clarity.
Practical implementation results compared with simulations to ensure real-world applicability.

Repository Contents

LTspice simulation files for the ECG circuit.
Documentation and slides detailing the project overview, design calculations, and simulation results.
Images and media showcasing circuit schematics, simulation outputs, and practical implementation.

This project demonstrates the application of biomedical electronics principles in designing a reliable ECG system for heart monitoring, with potential for further optimization and real-world deployment.
