## evolution of the radio access network :
![Screenshot from 2023-10-31 21-04-59](https://github.com/KRIISHSHARMA/5G/assets/86760658/0eefbb08-abf0-431b-9ce0-5eb1176ab907)

- baseband : Every portion of the data before it is converted into radiofrequency ( carrier wave ) can be thought of as baseband in technical terms. 
![Screenshot from 2023-10-31 21-06-26](https://github.com/KRIISHSHARMA/5G/assets/86760658/f7fcc859-b059-4132-9151-ffb05946bef9)

## motivation for RAN virtualization

![Screenshot from 2023-10-31 21-13-03](https://github.com/KRIISHSHARMA/5G/assets/86760658/2ce6a260-4159-49b9-b495-16153173d92a)

## RAN functional unit 
- LTE RAN is comperised of :
   - baseband unit (BBU) responsible for all baseband processing
   - RRH comprised of antenna and responsible for RF processing
- 5G RAN architecture enables the functional split of BBU into :
   1. centralized unit ( CU )
      - upper layer(s) processing
      - typically resides in central office ( edge cloud)
      - can be connected to multiple DU
      - its like an upper management in office ,responsible for making long term strategies and hence located in central office
    2. distributed unit (DU)
       - lower layer(s) processing
       - may or may not reside in the cloud
       - connected to one CU
       - its like a middle manager or staff and supervisor that are located at many more location mainly responsible for makin real time day to day operations
    ![Screenshot from 2023-10-31 21-38-34](https://github.com/KRIISHSHARMA/5G/assets/86760658/bb05e736-deae-4b36-aa8f-86355e6c96bc)

## Traditional RAN vs. Virtualized RAN (vRAN)

![Screenshot from 2023-10-31 21-56-46](https://github.com/KRIISHSHARMA/5G/assets/86760658/1a49459a-fa28-444f-83ce-c32a0f78a70a)

