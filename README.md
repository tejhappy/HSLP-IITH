# HIGH SPEED LOW POWER COMPARATOR

In this repo we will understand the architecture and the basic response of the High Speed Low Power(HSLP) current comparator with the help of transient response plotted with the help of the synopsys tool.

# TABLE OF  CONTENTS
1.[Introduction](#Introduction)

2.[Circuit design and details](#Circuit-design-and-details)

3.[Simulation waveforms](#Simulation-waveforms)

4.[Conclusion](#Conclusion)

5.[References](#References)

6.[Acknowledgement](#Acknowledgement)

7.[Author](#Author)


## Introduction
With the need for complex understanding on electrical  signals analog domain found to be ineeficient for the need so, the need for the digital domain has established in the industry. This function is established with the help of simple Mixed signal circuit knows as ADC -- Analog to Digital Converter. This repo has one such circuit which converts the analog input to digital output.

## Circuit design and details
![schematic](https://user-images.githubusercontent.com/100557113/156106636-74957a0f-dc08-4be2-8037-bbc2ef0d85d6.jpg)

The comparator circuit compares the two analog inputs, with the circuit producing the output swing whenever the analog input crosses the reference input.

The circuit has two parts - 1) decision circuit. 2) output voltage generation stage.
To the decision circuit the input is given and it is assumed that the input is already difference current of input and the reference and after passing throught the decision circuit the same is carried to the output voltage generation circuit which is basically two inverters connected to each other.The supply vultage is provided to the one end and the other end is connected to the ground, maintinaing the total potential difference postive.

## Simulation waveforms

Current comparator’s Speed and Power consumption had been simulated and measured in 28nm CMOS process. Transient response confirms the very high-speed operation of the reference Current Comparator. In addition to the above, the circuit has very low power of 1.855μW and operates at a frequency of 20MHz with a minimal supply voltage of 0.9v


The size of transistor’s is such that all nMOS have 100n/30n and pMOS have 250n/30n. The transient analysis has been attached in the results section showing the output swing for input -50nA to 50nA at the frequency of 20MHz and consumes average power of 1.855μW.

![TRANSIENT RESPONSE](https://user-images.githubusercontent.com/100557113/156106760-d9d93fa8-1f19-4431-9819-ef17ce2d6155.jpg)

## Conclusion
20MHz operating HSLP current comparator has been designed  using CMOS 28nm technology and simulated using the Synopys tools and the power conumsption is found to be around 1.855μW for the input of -50nA to 50nA.The main advantage of this circuit is its high speed operation and relatively low power consumption than other conventional comparator’s like Traff current comparator. It is well suited for High Speed applications such as Data converters and Digital switching circuits.


## References
1. Thrivikramaru V, Baghel RK. High speed low power CMOS current comparator. In2012 International Conference on Communication Systems and Network Technologies 2012 May 11 (pp. 764-768). IEEE

## Acknowledgement
1. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd.
2. Cloud Based Analog IC Design Hackathon
3. Synopsys India
4. Chinmay panda, IIT Hyderabad


## Author
GANTA TEJ CHARAN, Final Year B.TECH, ECE, Indian Institute of Information Technology,Design and Manufacturing,(IIITDM) Kancheepuram

Email: tejcharan72@gmail.com

