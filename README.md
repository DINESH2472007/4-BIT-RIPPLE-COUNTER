![Screenshot 2024-12-25 175134](https://github.com/user-attachments/assets/5655cb2b-6031-4368-92bf-0704201f3d21)# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

![Screenshot 2024-12-25 175321](https://github.com/user-attachments/assets/cce4d1cc-427b-41e2-81b8-811745ae1038)


/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: DINESH S
 
 RegisterNumber:  24900543
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-25 175134](https://github.com/user-attachments/assets/a6e10f6c-dda0-4be3-84e3-e9965368ea85)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot 2024-12-25 175307](https://github.com/user-attachments/assets/df44a532-6a49-485d-98c2-6629fe03854e)


**RESULTS**
