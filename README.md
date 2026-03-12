# Simulation des Portes Logiques et Additionneur 2 Bits sous Proteus
Description

This project contains simulations of basic logic gates and a 2-bit full adder implemented in Proteus Design Suite. The purpose of this laboratory work is to understand how fundamental digital circuits function and to verify their behavior through simulation.

The lab includes:

Simulation of basic logic gates: AND, OR,XOR

<img width="417" height="342" alt="image" src="https://github.com/user-attachments/assets/5e284b6c-cebd-425d-bee7-cdf6c2dabec1" />

<img width="427" height="265" alt="image" src="https://github.com/user-attachments/assets/4778a336-d0df-4bc5-a7b6-472e6c111f4f" />


<img width="452" height="263" alt="image" src="https://github.com/user-attachments/assets/0e8c91a6-4ae1-4dff-934a-6d274b8ae0fa" />


Full adder construction using logic gates (XOR, AND, OR)

2-bit ripple carry adder obtained by cascading two full adders

<img width="525" height="321" alt="image" src="https://github.com/user-attachments/assets/3ce2d9bf-2087-4715-ad52-18586edb4cd7" />



Simulation of sequential circuits: D Flip-Flop and JK Flip-Flop

<img width="446" height="241" alt="image" src="https://github.com/user-attachments/assets/7d1e3105-dc7e-4a1f-b186-0fdd78f775b9" />

<img width="409" height="251" alt="image" src="https://github.com/user-attachments/assets/15ca89db-e4eb-4f75-a106-288992695432" />

<img width="445" height="211" alt="image" src="https://github.com/user-attachments/assets/5c9a4898-a158-4c75-a1ab-8abe26c32cf3" />

<img width="404" height="253" alt="image" src="https://github.com/user-attachments/assets/51786555-bc4a-41b1-ac39-d9ae7f7ae1d5" />

Objectives

Learn the behavior of basic logic gates

Verify truth tables through simulation

Build a full adder using logic gates

Construct a 2-bit adder with carry propagation

Understand and simulate sequential circuits (flip-flops)

Components Used
Logic Gates

XOR, AND, OR, NOT

Flip-Flops

D Flip-Flop

JK Flip-Flop

Other Proteus Components

LogicState (input generator)

LogicProbe (output observation)

Clock source

VCC and GND

Simulations and Features
1. Logic Gates

AND, OR, NOT, XOR gates were tested individually

Outputs verified against theoretical truth tables

LogicProbe used to monitor outputs in real time

2. Full Adder

Constructed from XOR, AND, OR gates

Inputs: A, B, Cin

Outputs: S (sum), Cout (carry)

Verified with example: 3 + 2 = 5, propagation details checked

3. 2-bit Adder

Two full adders cascaded

Carry propagation verified

Output: 2-bit sum + final carry (Cout)

Simulation confirms binary addition logic

4. Sequential Circuits

D Flip-Flop: stores 1 bit on clock edge

JK Flip-Flop: can set, reset, toggle or hold depending on J/K inputs

Demonstrated state memory and clocked behavior
