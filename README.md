# CMOS Full Adder and VCO Circuit
This repository documents the  design of Full Adder and VCO in 28nm technology using Synopsis Custom Compiler.

# Design and Analysis of a Full Adder

Full adder is the functional building block and basic component in several architectures found in VLSI and DSP applications, Adder is a versatile component and mainly used in addition and multiplication as the basic processing element. In branch based design some constraints are applied to nMOS and pMOS networks.
1-bit full adder will be designed using 28 transistors in 28 nm technology.

# Circuit Details:
Full adder circuit and truth table are as shown below, by replacing the corresponding gates in the below picture with equivalent CMOS circuits, we get the CMOS equivalent circuit as shown in below figure.

![image](https://user-images.githubusercontent.com/40283371/156193114-80c695d6-1ba1-4306-b961-01ce7f67aec3.png)

Truth Table:

![image](https://user-images.githubusercontent.com/40283371/156193498-d14a8ccb-3433-4e8a-8cc7-1fd256caeb73.png)

Equations:

Sum = A⊕B⊕C

Carry = AB+BC+CA

# Circuit Diagram

![image](https://user-images.githubusercontent.com/40283371/156193792-40d8670a-aabd-4723-bb2d-cb476b75ff26.png)


# Implemented Circuit:

Carry Part:

![image](https://user-images.githubusercontent.com/40283371/156193918-7a064888-fb47-4ea8-8880-e6eda79ea84a.png)

Sum with Carry:

![image](https://user-images.githubusercontent.com/40283371/156194017-cffbb3e3-f6ef-4896-984b-caa1398bea28.png)


# Waveforms: 

![image](https://user-images.githubusercontent.com/40283371/156194107-4e4365a0-f6ec-4f82-842c-13f525991c6c.png)





# Design and Analysis of VCO in 28nm CMOS Technology

A VCO plays a vital role in communication system, providing a periodic signal required for digital circuit and also a frequency transmission in digital circuit. Their output frequency is a function of control input voltage.
The proposed circuit is implemented in a 28nm CMOS
technology


# Circuit Diagram

![image](https://user-images.githubusercontent.com/40283371/156200218-093bc9a1-9878-4d47-a67a-dbd391adad4e.png)


# Implemented Circuit

![image](https://user-images.githubusercontent.com/40283371/156201120-be1873b2-b4bf-4033-b7a4-deed513edd21.png)



# Output Waveforms: 

Input Voltage:  1 V

![image](https://user-images.githubusercontent.com/40283371/156200434-fd54d9a2-bbf3-4caf-b912-141a4ae67386.png)


Input Voltage:  0.5 V

![image](https://user-images.githubusercontent.com/40283371/156200519-4ecfc9a6-bfd0-4f7e-8162-9384a1510df5.png)

From the above two waveforms we can see that as input voltage increases the frequency of the VCO increases.


# Authors 
Khoushikh S

# Acknowledgements:

1. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
2. Cloud Based Analog IC Design Hackathon
3. Synopsys India
4. Sameer Durgoji, NIT Karnataka
5. Chinmay panda, IIT Hyderabad

# Referneces:

1. [1] Keivan Navi and Omid Kavehei Low-Power  and High-        Performance 1-Bit CMOS Full-Adder Cell
2. [2] NidhiTiwari, Ruchi Sharma, Rajesh Parihar Implementation of area and energy efficient Full adder cell
3. [3] N. H. E. Weste. Cmos vlsi design : A circuits and sys- tems perspective. 
4. [4] Sandhiya.S, Revathi.S, Dr.B.Vinothkumar: Design of Voltage Controlled Oscillator in 180 nm CMOS Technology
      






