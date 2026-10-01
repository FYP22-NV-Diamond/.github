# A Quantum-Assisted ELF Magnetometer for Drone Detection and Classification

Nitrogen-vacancy (NV) diamonds have recently been popular for quantum magnetometry
due to their exceptional sensitivity and their potential for microscale miniaturization.This
project proposes a NV diamond based extremely low frequency (ELF) magnetometer for
passive unmanned aerial vehicle (UAV) detection and classification. This address the
physical limitations of conventional radar, acoustic, RF, and inductive-coil sensing meth
ods. The system exploits NV center ensembles in diamond, whose spin-triplet ground
states respond to surrounding magnetic fields through the quantum Zeeman effect, en
abling direct optical readout of the local field via optically detected magnetic resonance
(ODMR). This can be miniaturized far below the size of traditional coil antennas while
retaining sensitivity to the DC and ELF signatures emitted by drone BLDC motors.
The proposed architecture uses continuous-wave ODMR (CW-ODMR) method to recon
struct the 3D magnetic field vector using low-cost, commercial-off-the-shelf components.
Detected magnetic signatures will be converted to spectrograms via short-time fourier
transform (STFT) and classified using a lightweight 2D convolutional neural network.
The system will detect and classify UAVs at a 50 cm standoff distance.
