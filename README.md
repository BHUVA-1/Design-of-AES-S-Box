# Design-of-AES-S-Box
This is my major project. In this i have designed AES S-box using 45nm CMOS Technology using Xilinx ISE14.7 and Tanner EDA Tools.

Abstract: The most widely known algorithm of Symmetric key cryptography is Advanced Encryption Standard (AES). Advanced Encryption Standard (AES) algorithm consists of an important component called the Substitution Box (S-Box) w     hich creates confusion using byte substitution method. S – Box impacts high power consumption due to usage of many CPU cycles. So, to increase the efficiency of hardware implementation of AES, it is necessary to optimise power, delay and Silicon area of S – Box. In this paper, AES S – Box is implemented using Galois Field composite arithmetic logic. Xilinx ISE 14.7 is used for verifying the functional correctness using Verilog HDL, and Tanner EDA is used for transistor level implementation with 45nm CMOS technology node. Demonstration of reduced power consumption and improved efficiency is shown through simulation results, making this design suitable for IoT devices and embedded systems which are energy constrained applications. 
# Results:
<img width="506" height="226" alt="image" src="https://github.com/user-attachments/assets/8c339e27-786c-46a8-ad68-63f68a44b805" />
 Fig 1: Waveform of S – box implementation with composite field logic in Xilinx Ise 14.7

<img width="507" height="210" alt="image" src="https://github.com/user-attachments/assets/cc1e211d-35ab-4fe8-bd3d-b1c9d103ef01" />
Fig.2: Waveform of S – box using composite field arithmetic logic using Tanner tools.

<img width="507" height="197" alt="image" src="https://github.com/user-attachments/assets/c563556b-b149-4d4a-b3c8-e638dc36771f" />
 Fig.4: Waveform of GF multiplier using CMOS XOR and CMOS AND blocks of 45nm in Tanner EDA.

<img width="507" height="197" alt="image" src="https://github.com/user-attachments/assets/b22965d0-58b0-4fbc-8c53-dbe6c8fd7e5a" />
Fig 5: Waveform of GF squarer using GF multiplier and CMOS XOR blocks in Tanner EDA.

<img width="507" height="200" alt="image" src="https://github.com/user-attachments/assets/ab3098ee-d6d6-490d-9e2f-5dd69579d6a8" />
Fig 6: Waveform of GF(24) inverse using GF multiplier, GF squarer and CMOS inverter blocks in Tanner EDA.

<img width="507" height="198" alt="image" src="https://github.com/user-attachments/assets/d7c3a482-d279-4500-8319-40913c95b09c" />
Fig 7: Waveform of GF(28) inverter using GF(24) inverter blocks, GF multiplier and GF squarer blocks in Tanner EDA.

<img width="507" height="195" alt="image" src="https://github.com/user-attachments/assets/c56a9f9c-9c20-4ea4-a115-f0a077ddce8c" />
Fig 8: Waveform of Affine transformation using CMOS XOR blocks.



