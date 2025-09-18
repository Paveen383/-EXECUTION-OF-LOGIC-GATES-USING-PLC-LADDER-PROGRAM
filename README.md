# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :Paveen Kumaran SV
 # REGISTER NUMBER :212224220071
 # DEPARTMENT : B.Tech-IT
 # YEAR : 2 year

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
AND GATE

<img width="467" height="359" alt="Screenshot 2025-09-18 083828" src="https://github.com/user-attachments/assets/cc8144fb-56fc-4d56-8683-de3971be012a" />

OR GATE 

<img width="460" height="358" alt="Screenshot 2025-09-18 083840" src="https://github.com/user-attachments/assets/11e996c1-d1b9-4f98-8508-a4c1a2d0468d" />

NOT GATE

<img width="284" height="218" alt="Screenshot 2025-09-18 083850" src="https://github.com/user-attachments/assets/fbfb55c0-576b-48ec-ae4b-6c6ac68c7210" />

NOR GATE

<img width="455" height="347" alt="Screenshot 2025-09-18 083859" src="https://github.com/user-attachments/assets/92f90f5e-ee7a-4296-a6b6-598a8eeb5a62" />

NAND GATE

<img width="437" height="352" alt="Screenshot 2025-09-18 083907" src="https://github.com/user-attachments/assets/2a4889dc-f322-405f-aaba-9e5ebd8fbd2c" />

XOR GATE

<img width="446" height="336" alt="Screenshot 2025-09-18 083917" src="https://github.com/user-attachments/assets/aa4055f8-1739-4e72-8993-30f148f57150" />

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS :
AND GATE
<img width="1919" height="160" alt="Screenshot 2025-09-18 082113" src="https://github.com/user-attachments/assets/3abba508-eb1a-4852-92fc-0ca265b7528a" />
<img width="1919" height="173" alt="Screenshot 2025-09-18 082407" src="https://github.com/user-attachments/assets/59853e3d-0580-4c75-871e-8d1ee56c125a" />
<img width="1919" height="163" alt="Screenshot 2025-09-18 082455" src="https://github.com/user-attachments/assets/0543ecb2-7b5b-4980-a4fe-bbebc9a97a70" />
<img width="1037" height="84" alt="Screenshot 2025-09-18 082547" src="https://github.com/user-attachments/assets/dee37bed-1274-44c4-b995-a641b79377bc" />

OR GATE
<img width="1032" height="142" alt="Screenshot 2025-09-18 082911" src="https://github.com/user-attachments/assets/b4b9b52e-19c2-461e-9444-4a042e5ff818" />
<img width="1033" height="142" alt="Screenshot 2025-09-18 082930" src="https://github.com/user-attachments/assets/b7822780-068d-4e2a-a20c-f6a2453992e2" />
<img width="1033" height="145" alt="Screenshot 2025-09-18 082944" src="https://github.com/user-attachments/assets/c62ca73b-bd09-456d-887c-db470882b35b" />
<img width="1032" height="145" alt="Screenshot 2025-09-18 082957" src="https://github.com/user-attachments/assets/8f351818-3f8f-4ec4-857c-4c42104dda9c" />

NOT GATE
<img width="819" height="101" alt="Screenshot 2025-09-18 083243" src="https://github.com/user-attachments/assets/6b6bc65f-3858-4946-9011-e96525bc7b94" />
<img width="821" height="86" alt="Screenshot 2025-09-18 083254" src="https://github.com/user-attachments/assets/b6020cb7-345c-4431-9676-50dbf4c9bba5" />

NOR GATE
<img width="821" height="64" alt="Screenshot 2025-09-18 083340" src="https://github.com/user-attachments/assets/d5e843b9-f182-4bf9-8fb1-964712495890" />
<img width="818" height="66" alt="Screenshot 2025-09-18 083351" src="https://github.com/user-attachments/assets/2e02e44f-6b74-4a6e-be15-9f7439051230" />
<img width="822" height="69" alt="Screenshot 2025-09-18 083401" src="https://github.com/user-attachments/assets/d929d09d-6498-4a80-9f21-8b4af56900e2" />
<img width="819" height="70" alt="Screenshot 2025-09-18 083414" src="https://github.com/user-attachments/assets/92bbc67e-f67f-4ac8-9853-2d7b98197161" />

NAND GATE
<img width="817" height="121" alt="Screenshot 2025-09-18 083529" src="https://github.com/user-attachments/assets/6db4c54e-d2a1-4f84-9c18-d249b56b809e" />
<img width="822" height="117" alt="Screenshot 2025-09-18 083537" src="https://github.com/user-attachments/assets/cfc2ccbe-34f6-4545-9c33-de154f019ab0" />
<img width="815" height="115" alt="Screenshot 2025-09-18 083548" src="https://github.com/user-attachments/assets/f5338d62-07bc-4a5f-ab6f-49a52257f0e5" />
<img width="819" height="112" alt="Screenshot 2025-09-18 083601" src="https://github.com/user-attachments/assets/e7653d4e-255d-45b7-a1cf-73ce4098e130" />

XOR GATE
<img width="817" height="111" alt="Screenshot 2025-09-18 083700" src="https://github.com/user-attachments/assets/bebb4076-ac66-451a-b2ed-870918261cd6" />
<img width="820" height="115" alt="Screenshot 2025-09-18 083712" src="https://github.com/user-attachments/assets/679707a6-9e13-40a5-a0ff-5852300e6de7" />
<img width="821" height="118" alt="Screenshot 2025-09-18 083722" src="https://github.com/user-attachments/assets/9245e5fc-b09a-453b-a760-cb6b56c5adac" />

#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
