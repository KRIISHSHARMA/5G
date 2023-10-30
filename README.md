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

## 5G network terminology and concepts :
![Screenshot from 2023-10-30 18-16-31](https://github.com/KRIISHSHARMA/5G/assets/86760658/4a31e6f9-74b0-4b43-b178-ba89d6e28526)

- gNODEb(gNB) : base station / towers for 5Gwireless networks ; supports onnectivity to 5G core networks (NGC)
- Access and mobility management function(AMF) : supports UE's network access and manages its mobility
- Session management function(SMF):supports signaling IP address allocation and connectivity
- User plane function(UPF) : Handles all the cpntent generated/consumed by apps eg web pages,photos,videos 

## Network Architecture options for 5G NR
![Screenshot from 2023-10-30 18-49-47](https://github.com/KRIISHSHARMA/5G/assets/86760658/2753b533-1b8f-49d5-9cfd-84b547e90f76)

## flexible slot based framework : for forward compatibility and ultra low latency 
- dynamically and effciently adapt to all traffic types and situations
- carefully utilizing your resources and making some changes in runtime to improve operational efficiency
- ex : traffic in road lane

## scalable OFDM based air interface (orthogonol frequency division multiplexing) : ofdm : allows you to send data on multiple narrow band channels
- for diverse services spectrum , deployments
- modular road design
   - exponentially scallable from single to multilane ; common design for all configurations
- in a real life system. At the beginning you have a two lane road, but if traffic demand goes up, you can have a four lane road. If there is less traffic demand, you can have only a single lane road.
- In FSBF , the road width would remain the same. What will change is the width of individual lanes at runtime. Whereas in this example, what is going to be fixed is the width of individual lanes and what is going to change is the width of the road itself.

## advanced channel coding : aka error control coding aka forward error correction code 
- channel coding provides additional metadata to wireless signals to minimize the effects of pathloss , noise and interference
-  Imagine that you have a precious glass, an ancient artifact that you have to send from one point to another. At the simplest end, what you can do is just put that glass in a box and send that box across. If the postal carrier handles that box carefully, sure the glass will safely reach your destination. But what if and the postal carrier happens to drop that box by mistake, or what if the road on the way is bumpy so that the artifact gets damaged a little? To avoid that, what you would naturally do is that you would probably wrap that glass in bubble wrap. You would pack it with packing foam, then fit that neatly in a tight box. Maybe write a note on that box saying fragile, handle with care. That way you're postal carrier will precisely know that this box needs to be handled very carefully. Even for example, the road is bumpy and the box happens to shake a little bit, your glass will be very protected because it is surrounded by bubble wrap and packing foam. Just like packing foam and bubble wrap help your precious glass artifact reach one point from another, even in presence of bumpy roads, etc, such channel coding metadata helps your intended transmission reach the other end even in presence of impediments such as pathloss, noise, and interference
-  improves efficiency of communication overall

## massive MIMO ( massive input (tx) massive output (rx)) :
-instead of sending just one wireless signal between two devices, you are now trying to send to different wireless signals between the same pair of devices. And if you do it carefully, it stands to reason that because those two wireless signals will carry a different data, you will have essentially doubled your data rate or output or your speed because some of the data will be carried on this wireless signal.
- *Are these two wireless signals going to require two different frequency channels and hence more spectrum? *
   - Well, surprisingly the answer to that question is no.
   - The headline here is that these two wireless signals are sent on the exact same frequency spectrum using the exact same frequency channels. So you don't need extra spectrum or an additional channel on top of the same channel you have, you can multiplex so to speak these two wireless signals. Hey, didn't you tell us earlier that if you send two different signals on the same channel at the same time, you will have interference. Well technically that's still is correct, but this is where the beauty of MIMO comes into picture.
   - At a high level the reason these two signals won't interfere with each other is because they are encoded by the transmitter differently.

## mobile mmwave :
-Millimeter wave simply is a certain range of frequencies where your signal wavelength is on the order of a few millimeters
- you can solve one of the most fundamental problems that plays communication systems of today. Which is scale setting of frequency spectrum because you have abundant unused frequency spectrum in the millimeter wave frequency range.
![Screenshot from 2023-10-30 20-59-35](https://github.com/KRIISHSHARMA/5G/assets/86760658/db578d64-61ac-4afa-b88f-4170b1165391)
- It is essentially roles in uncharted territories or unused lines. I am sure that you have been in a situation wherein you are stuck in slow crawling bumper-to-bumper traffic on a highway. Whereas on either side of the highway, you could see plenty of land that was unused for one or the other reason. Maybe that land was very rough and hilly or mountainous, wherein carving out a flat highway would have been difficult for any other reason. You see a lot of land sometimes on either side of a blocked highway and you think, "Hey, wouldn't it be more efficient if you could also build additional highways on the land that is currently unused for some other reason? Wouldn't it significantly alleviate the traffic congestion on this highway and make the overall flow of traffic significantly faster and thereby improve traffic capacity?
- If you could build a highway on those unused lines, you will have significantly improved your traffic capacity. Millimeter wave is about improving your technological capabilities and prowess so that you are now able to utilize some of the frequency spectra that were earlier unused and because they are unused, you will have access to abundant bandwidth in those frequency ranges on the order of 400 or 800 megahertz at a time. 
