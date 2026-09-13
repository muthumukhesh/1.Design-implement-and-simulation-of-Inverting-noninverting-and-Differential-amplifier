# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1600" height="535" alt="image" src="https://github.com/user-attachments/assets/c1fb4b95-f11c-4a73-a7ce-12fa95af1ee8" />


**INVERTING AMPLIFIER:**

  **CIRCUIT DIAGRAM**
  <img width="1422" height="701" alt="image" src="https://github.com/user-attachments/assets/0db32525-bbef-4b75-809d-f6ae0ac67efe" />



  **MODEL GRAPH:**
  <img width="1406" height="946" alt="image" src="https://github.com/user-attachments/assets/7c09ab82-5af8-4a00-8776-05bd13b78392" />



  **TABULATION:**
  <img width="1306" height="784" alt="image" src="https://github.com/user-attachments/assets/e7991e7d-7056-4795-bc1e-d37da6a914a8" />

 

**MODEL CALCULATION:**
<img width="1600" height="683" alt="image" src="https://github.com/user-attachments/assets/e0a61493-4e9c-4613-b09a-1827926fe3da" />
GRAPH:
<img width="1600" height="1033" alt="image" src="https://github.com/user-attachments/assets/d1c47dd4-b3be-42c3-8b49-1183a4034b15" />


**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1600" height="994" alt="image" src="https://github.com/user-attachments/assets/7a353bf1-c781-4843-9bb7-6ca7be938640" />



  **MODEL GRAPH:**
  <img width="1600" height="984" alt="image" src="https://github.com/user-attachments/assets/656ca91d-c2c3-4a9f-aeae-636e102e0e83" />



  **TABULATION:**
  <img width="1600" height="928" alt="image" src="https://github.com/user-attachments/assets/66258aea-0f34-4e94-a760-3dfb41d4fe26" />
  GRAPH:
  <img width="1600" height="892" alt="image" src="https://github.com/user-attachments/assets/31249dad-f78c-4e31-82ae-cfad63dc14d9" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  <img width="1600" height="867" alt="image" src="https://github.com/user-attachments/assets/568b4587-791b-445a-a99f-ec6a34f44e22" />



  **MODEL GRAPH:**
  <img width="1323" height="826" alt="image" src="https://github.com/user-attachments/assets/bcabe669-b2e5-4f12-8708-13ec92124d38" />



  **TABULATION:**
  <img width="1600" height="951" alt="image" src="https://github.com/user-attachments/assets/460502c0-d267-40d1-a44c-8b5c174cb35f" />
<img width="1600" height="632" alt="image" src="https://github.com/user-attachments/assets/6f826880-46b4-4f00-a588-15b492818396" />
<img width="1600" height="1526" alt="image" src="https://github.com/user-attachments/assets/5ef4f225-7a27-4979-a59b-be2888e59ccc" />


**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
  <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/a457de86-967d-46aa-9e3b-74f5323827d5" />
  <img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/3c48d634-27c7-4c15-bf8d-2fa662302555" />
<img width="821" height="413" alt="image" src="https://github.com/user-attachments/assets/1be6a2d9-8d81-4c0c-8e4d-92ec73b5c3c8" />

  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






