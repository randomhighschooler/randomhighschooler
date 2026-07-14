# 🛡️ Phoenix-Guard / Project Phoenix
### A Post-Quantum, GNSS-Denied UAV with Custom RISC-V Silicon


# 📡 The Mission
### Making the world's first fully open-architecture drone with a custom 5-stage pipelined RISC-V CPU, Zero-Knowledge Proofs (zk-SNARKs), and Post-Quantum Cryptography (Kyber/Dilithium) taped out via open-source ASIC tools.

#### As quantum computing advances and gps jamming tools become more advanced many drones in our modern world rely on architectures that become increasingly more vulnerable. This project designs the whole drone from the silicon to the flight controller:
* Custom CPU: A 5-stage RV32I core written in Verilog.
* Hardware Security: A fully taped-out ASIC accelerator for PQC and ZKPs.
* True Autonomy: Visual-Inertial Odometry (VIO) for GPS-denied navigation.
* Sovereign Tech: Fully designed in Canada using open-source tools.


## The Threat We Face
### Almost every single drone either flying today or not which is military or civilian has encryption that a quantum computer at some point will be able to crack in seconds. The transition to Post-Quantum Security is not a add on but a rather a must. Which is driven by the expectation of fault-tolerant quantum computers which will be capable to break most encryptions systems in the world.
#### Let's look at the current math:
* RSA-2048: Broken by a quantum computer with around 4 thousand logical qubits.
* ECC-256: Broken by a quantum computer with around 2 thousand logical qubits.
* Timneline: Around 5-15 years.
### What makes everything even worse is that drone are like flying blocks of data. Encrypted transmissions, GPS signals all of it will be readable by a state that has a quantum computer.
