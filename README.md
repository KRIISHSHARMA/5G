# 5G
## Acronyms and Abbreviations 

![Screenshot from 2023-10-29 20-39-16](https://github.com/KRIISHSHARMA/5G/assets/86760658/e13b18af-2959-48e1-b2d3-3051393de929)

![Screenshot from 2023-10-29 20-40-01](https://github.com/KRIISHSHARMA/5G/assets/86760658/3996de20-ad2f-429d-8107-733db2f9fbdd)

![Screenshot from 2023-10-29 20-46-10](https://github.com/KRIISHSHARMA/5G/assets/86760658/7a2e1e48-8162-49aa-8ea3-5c3647b78aed)

# [MODULE 1 ](wireless_and_celullar_comm_overview.md)
## wireless communication : 
### allows transfer of info between a transmitor and a receiver without physical medium , communication link uses radio frequency signals (RF) .
- components of wireless communication :
- transmitter 
- wireless signal
- wirless channel
- receiver

## radio signal prop : 
- travels at speed of light
- RSF is related to its wavelength and frequency
- a wireless transmission is an electromagnetic signal which is characterized by its wavelenght and frequency ( f - 100km to 1mm , wl - 3khz to 300Ghz)

## Carrier waves / Modulation :
- info to be exchanged is "carried" by RF signals.
  { info can be analog such as voice or digital like an email }
- RF signals used as vehicle for info are called < CARRIER WAVE >
- MODULATION - process by which we impress info onto the carrier wave for transmission { analog or digital modulation depends on nature of the data}
- at the reciever we must demodulate the carrier to restore data
- Modulation changes specific attributes of a RS such as the wavelength and frequency
- MODEM - {MO = modulation ,DEM = demodulation}   
![Screenshot from 2023-10-29 21-41-39](https://github.com/KRIISHSHARMA/5G/assets/86760658/e3c24929-08b5-47b3-ad9c-930cc52c1a5c)

## Noise and Interference :reduce the quality of signal recieved by the user
- when info is sent over any wireless communication link , noise and possibly interference is introduced
- Noise is unwanted energy or signals
- noise is always present in any device or comm link
- some noise is generated within comm device
- when 2 nearby tranmitter use the same radio freq at the same time they create interference { n/i - interfare with attributes of RFS } 
- we quantify signal quality by the radio of desired signal to noise and or interference

## Radio spectrum : range of radio frequency over which wireless comm takes place
- mmWave : 39 GHz

 ![Screenshot from 2023-10-29 22-08-20](https://github.com/KRIISHSHARMA/5G/assets/86760658/38d82d77-d5f8-42a3-a4f8-eb199bfee769)

## Radio channel and bandwidth : 
- radio signal that carries info uses a range of frequencies over which comm link is established
- that range of frequencies is calles a CHANNEL and its width is called BANDWIDTH

![Screenshot from 2023-10-29 22-15-44](https://github.com/KRIISHSHARMA/5G/assets/86760658/2f9fc057-268b-4f39-9df5-eac55a74ea18)
- CDMA ( code division multiple access ) - CDMA is an example of multiple access, where several transmitters can send information simultaneously over a single communication channel. This allows several users to share a band of frequencies

## Two ways of sharing the spectrum - FDD(frequency division duplexing) and TDD(time division duplexing)

![Screenshot from 2023-10-29 22-40-56](https://github.com/KRIISHSHARMA/5G/assets/86760658/930d71c2-55b3-4d24-8836-866a7078f864)
![Screenshot from 2023-10-29 22-40-33](https://github.com/KRIISHSHARMA/5G/assets/86760658/9d21a1c3-90e8-424c-8323-fa5a96f97f08)

## Cellular concept : 
- AN FM radio { single tower in city center } and a mobile network cover the city diff
- a mobile networks coverage area is divided into cells
- eachcell is served by a base station aka tower
- the cells are designed to have "tessellating"( polygons, that fit together closely without gaps or overlapping) coverage
- as you drive , you are handed off from one base station to the next by the network

## cellular network :
![Screenshot from 2023-10-29 23-08-35](https://github.com/KRIISHSHARMA/5G/assets/86760658/48352042-23db-4c31-857a-feb5ec29ffd0)

![Screenshot from 2023-10-29 23-10-08](https://github.com/KRIISHSHARMA/5G/assets/86760658/5e34ede6-7230-4108-8a20-656cf42e96bb)
![Screenshot from 2023-10-29 23-10-29](https://github.com/KRIISHSHARMA/5G/assets/86760658/657af6af-9dd1-4f1c-810b-00e8ce3edc1f)

# [MODULE 2](5G_NR_Vision.md)
## Why do we need something better than 4G? 
- User generated content growing in volume and quality
- number of devices per person increasing
- ultra high speeds and network capacity
- low lag for real time , interactive apps
- diverse service under one umbrella
- connecting everything and everyone
  
![Screenshot from 2023-10-30 09-07-20](https://github.com/KRIISHSHARMA/5G/assets/86760658/f81fba94-3f2a-4278-92a9-4c1eaff739bf)

## 5G services classes
### eMBB {enhanced mobile bandwidth } : further high speed internet
- *use case* : used in real time streaming/gaming , cloud computing , thing which require high data network
- emphasis on higher speeds and spectral effeciency
     - bandwidth and power usage is secondory
- peak uer data rate > 10 Gbps
- network throughput > 1 Tbps
- operation in macro and small cells
    - macro cells : cell towers / bae stations , more broad , covers few sqkm
    - small cells :miniature vers of macro , eg malls etc
 - support for high-speed mobility upto 500 kmph

### mMTC/mIOT (massive machine type comm/massive internet of things} : connecting everthing around us .  
- *use case* :alld devices which otherwise wouldnt connect to a network will now be provided with reliable network connectivity regardless of where they are ex: home devices , sensors , industrial robotic devices , fitness tracker etc
- emphasis on power conservation and simplicity of protocols , instead of speed and effeciency
- support for high device effeciency upto 1 mill devices/km^2
- operation over long range and in challenging coverage conditions
- simple low cost devices
- long battery life ex upto 10 years

### URLLC { ultra reliable , low-latency communication } : real time interactive apps 
- *use case* : mission critical comm , remote surgery , self driving cars , where high reliability and low latency is needed
- emphasis on E2E latency , instead of speed ( ex less than 1ms )
- ultra high reliability and availability
- support for high speed mobility
- fundamental redesign of protocols 

