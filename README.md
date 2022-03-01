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






