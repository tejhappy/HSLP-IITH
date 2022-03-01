This repo explains the CMOS Current Comparator circuit suitable for High Speed and Low Power applications. Current comparator’s Speed and Power consumption had been simulated and measured in 28nm CMOS process. Transient response confirms the very high-speed operation of the reference Current Comparator. In addition to the above, the circuit has very low power of 1.855μW and operates at a frequency of 20MHz.

The comparator circuit compares the two analog inputs, with the circuit producing the output swing whenever the analog input crosses the reference input. This paper assumes the one input to the circuit as the difference between the input and the reference. The circuit will drive the output swing for the difference input. The circuit includes 3 parts Decision circuit, CMOS Inverter, Power supply.The size of transistor’s is such that all nMOS have 100n/30n and pMOS have 250n/30n. The transient analysis has been attached in the results section showing the output swing for input pulse -50nA to 50nA at the frequency of 20MHz and consumes average power of 1.855μW.



![schematic](https://user-images.githubusercontent.com/100557113/156106636-74957a0f-dc08-4be2-8037-bbc2ef0d85d6.jpg)




The main advantage of this circuit is its high speed operation and relatively low power consumption than other conventional comparator’s like Traff current comparator. It is well suited for High Speed applications such as Data converters and Digital switching circuits.


