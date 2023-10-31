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

# [MODULE 3](5G_network_and_features.md)

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

![Screenshot from 2023-10-30 21-12-15](https://github.com/KRIISHSHARMA/5G/assets/86760658/76eeec9e-b11d-4363-b044-30c545dc7284)

##  network slicing 
- a slice is a subset of the available network components that provides E2E service.
- a slice can be designed and commissioned depending upon the needs of a service
- diverse requirments of different services can be met by serving then with different slices of the same network i.e diff components of the same infra
**benefits** :
  - dynamic and efficient resources allocation and utilization ; resource isolation among services
  - flexible subscription mode
##   SDN and NFV { software defined network and network functionality virtualization }
### SDN
- SDN is about making your network more software oriented then they were before
- network control func/task are decoupled from network devices/boxes
- migration of control from individual network devices / boxes into accessiable distributed computing devices/func
- underlying infra can be abstracted for diff applications and network services
**benefits**
  - centralized management and control of network devices
  - rapid innovation on new network capabilities and services
  - programmability by diff uses and developers
  - increased network reliability and services
  - more granular network control
 ### NFV 
- upto 4G , networks required specialised software running on specialialized software
- NFV aims to transfer network arch .
    - involves implementation of network func (NF) in software
    - NF's can reside in cloud , operator premisis
**benefits**
- decoupling softawre from hardware
- flexible , scalable , dynamic network deployments
- cost effective operation

## mobile edge computing (MED)
- brings compute , storage and networking resources closer to application , devices and users
- shift of resources from centralized  data centres far away from the end user to network edge
- can faciliate service with strict latency , security and bandwidth requirements
- SDN , NFV and 5G technologies promote to development of edge computer

# [MODULE 4](5G_spectrum_and_mmwave.md)

## 5G NR spectrum
![Screenshot from 2023-10-31 16-34-49](https://github.com/KRIISHSHARMA/5G/assets/86760658/37486e02-e26c-473c-b50a-94761b0025b0)

![Screenshot from 2023-10-31 16-34-10](https://github.com/KRIISHSHARMA/5G/assets/86760658/99fba220-382f-4318-b9d4-8524e83f1c55)

## Motivation & Challenges Behind mmWave Deployments
![Screenshot from 2023-10-31 16-53-26](https://github.com/KRIISHSHARMA/5G/assets/86760658/cc5c3b28-82d8-465e-a116-bc355b18db74)

### why mmwave ?
- currently mmwave is largely unused => ample spectrum available
- enormous bandwidth => mmwave can fullfill the demand of data hungry 5G use cases
  
### challenges of mmwave 
![Screenshot from 2023-10-31 16-57-31](https://github.com/KRIISHSHARMA/5G/assets/86760658/76a0c20f-307f-4619-bc0a-771f4bbb1cf6)
- despite these challenges , 5G can leverage certain adv of mmwave

### advantages of high frequency :
![Screenshot from 2023-10-31 16-59-28](https://github.com/KRIISHSHARMA/5G/assets/86760658/a39a6c91-3939-4add-832d-a22a80cda62c)

- more antennas : the size of the antenna needed to work at a specific frequency is inversely proportional to that frequency, meaning that as your frequency of operation goes higher and higher, the size of the antenna that is needed to optimally send or receive signals and that wireless frequency begins to reduce and reduce .
  
- directivity : When you have these more antennas on the Ginobil which are typically arranged in a two dimensional rectangular panel, you have two options. You can either let each antenna work as an individual and do its own thing or you have the option to make some or all of those antennas work together in unison as one unit and coordinate the kind and amount of energy that they transmit outwards. And when you execute some smart signal processing algorithms in the back end to make multiple antenna elements work together in unison. What happens is that rather than just translating their energy in any random direction, what they can do is they can coordinate with each other and focus their energy in a certain precise direction of interest.

- spacial reuse : Let's say that you have access to two frequencies: frequency f_1 and frequency f_2. Let's say that f_2 is substantially higher than frequency f_1. If you were to build a cellular base station at frequency f_1, let's say this is the base station, then at frequency f_1, maybe this would be the coverage of a cell at frequency f_1. Let's say that at frequency f_1 you have access to channel bandwidth of W megahertz and that leads to a network capacity of C bits per second. Let's assume that for now. Now, imagine that at frequency f_2, you have access to the same channel bandwidth, W. Let's not toy around with those variables just yet. If you play your cards right, it should be possible for you to get capacity C while operating at frequency f_2 as shown. There are certain assumptions in wireless and digital communications involved here that I have prepared upon but stay with me here for a minute. Let's assume that at frequency f_1 channel bandwidth of W gives you network capacity of C. This is your cell radius at frequency f_1. Now because frequency f_2 is significantly higher than f_1, its Pathloss will be significantly higher than that for f_1 as well. As such, the signal that you might send from this base station at frequency f_2 will attenuate much quicker as compared to the signal at frequency f_1. That would mean that the coverage radius of a hypothetical cell deployed from the same location at frequency f_2 will be substantially lower than that at frequency f_1. Let's say that this is the cell coverage at frequency f_2. I hope you are with me up to this point. What it means is that if you were to deploy a cellular network on frequency f_2, you would get coverage in the smaller dotted circle but outside that dotted circle, you wouldn't get coverage at f_2. You don't have to stop there either, you can deploy another base station here at f_2 and it'll give you coverage like this and you can continue doing so N times in a given geographical area. Now, once again, one might ask a basic question, hey, if two things operate at the same time on the same frequency, you said earlier that they'll interfere with each other. Well, that premise still holds true but keep in mind that the wireless coverage of this cell, let's say cell 1, ends over here. In this region there is no coverage by cell 1, that is, the wireless signal from cell 1 ends so to speak ''At about this point beyond which you can start building a new cell.'' That is the reason why because coverage is naturally limited at frequency f_2. These cells: cell 1 and cell 2, will not interfere with each other in the coverage area of the other cell. That is how interference will be mitigated or altogether eliminated. Just by taking advantage of the fact that naturally the wireless coverage of cell 1 dies over here and coverage of cell 2 will die over here. Wherever the coverage of one cell attenuates, that is when you can begin a new cell. Given that, a given cell at f_2 is still capable of giving us a capacity of c bits per second. If you have N cells at f_2, the area two-port that you'll be able to get at frequency f_2 will be N times C bits per second, whereas the area throughput at frequency f_1 is just C bits per second because you are able to accommodate only one cell at frequency f_1 in that area. Notice something remarkable that has happened. Without utilizing additional bandwidth just by taking advantage of the natural fact that at higher frequencies coverage is limited, you are able to deploy multiple cells at higher frequency within the same geographical area , and as such, you are able to boost the network capacity offered in that geographical area by N fold equivalent to the number of cells you're able to deploy. Such magnification of network throughput or capacity that is achieved by deploying more cells in the same area or packing the cells more densely is called cell densification. That is the third principle that gives us a significant advantage in terms of millimeter-wave. That is where higher Pathloss leads to better spatial reuse, meaning you could reuse the same space for multiple cells, i.e, fit many more cells, pack them densely, that is, network densification. Spatial reuse and network densification share this relationship. It is higher Pathloss and brilliantly taking advantage of that fact is what allows us and millimeter-wave deployments to densify the network and ultimately significantly improve not just the network capacity, but data speeds that are achievable by individual users
![Screenshot from 2023-10-31 17-20-20](https://github.com/KRIISHSHARMA/5G/assets/86760658/c77cafc7-ab02-45d1-9a9b-a25f64d22d44)

## mmWave Deployment Opportunities Overview :

![Screenshot from 2023-10-31 17-23-07](https://github.com/KRIISHSHARMA/5G/assets/86760658/85fc29b9-693b-4e02-b22a-6f75342593bb)

## mmWave for Urban & Suburban Deployments : 
- dense urban deployment = dense no. of UE =  more building penetration loss so ,  => small coverage , smaller size = more cells , densifying the network , big band width = less interfernce
- isp wire connection => expensive
   - if isp uses 5G mmwave base station it would to easier to add subscribers 

## mmWave for Rural Deployments : homes sperated from each other

-From an Internet service provider's viewpoint, it becomes not just expensive, but somewhat prohibitive to run individual cables from a local hub to those individual homes that are separated far apart. That's why rural areas don't garner much attention from established ISPs for economical reasons, and that is one prominent reason why rural areas have traditionally been underserved, and have lagged behind as far as a broadband Internet connectivity is concerned. 

- Can millimeter wave in any way solve this challenge? Well, it definitely can. Imagine a rural area. Let's say these are your target homes. Traditionally, this would be, for example, an ISP hub. An ISP would have to run miles long cables from the hub to individual homes, which would be prohibitive, as we mentioned. Imagine on the other hand, how a millimeter wave deployment would look like. Let's say instead of a hub, the ISP, or equivalently, a cellular network operator builds a millimeter wave base station atop a tall tower, so to speak, so that it has line of sight with the entire village. Once you have a millimeter wave base station atop a tall tower, it's millimeter wave signal can reach all these homes and all the other homes in this particular town as well. On account of it's large bandwidth and other benefits, you can see that this millimeter wave base station will be in a position to provide wireless broadband connectivity to all these homes, and all the advantages regarding flexibility and scalability continue to apply.

- For example, if you have a new home over here interested in getting wireless broadband service, no worries, the wireless signal already reaches that home, and all you need to do is subscribe to that service, buy the necessary hardware and voila, within a matter of an afternoon, you have wireless broadband connectivity to your home, something that would earlier take weeks or months, if at all, it were possible. So millimeter wave is not only beneficial in urban areas, but it has some practical use cases in rural areas as well. 
- how are you going to connect it to the core network in the back-end? Wouldn't you have to run a cable after all, going to the core network, which may be located several miles away? 
- One might ask, hey, how are you going to solve that problem? Well, with the advent of millimeter wave, you don't even have to run that miles-long cable anymore. That solution technically is called the backhaul or integrated or access and backhaul solution. What happens here? Is that considered the front end? There is a millimeter wave base station, and it is providing wireless broadband service to all these homes using millimeter wave find each channel. That part is well understood. However, what about the connectivity from the base station to the core network, which in technical terms is called backhaul? What about the backhaul? Well, the backhaul in modern terms can also be millimeter wave, in that this millimeter wave base station will treat the core network just as any other user and transmit a long range millimeter wave signal back to the core network, and if you have a receiver millimeter wave base station at the core network site, it should be possible for you to receive, demodulate and decode that signal. By making this particular backhaul link work over 5G millimeter wave wireless, you have effectively obviated any need that you would

  ![Screenshot from 2023-10-31 17-59-40](https://github.com/KRIISHSHARMA/5G/assets/86760658/485e1136-4190-4b89-b5f2-317374fa9997)
  
- given that mmwave signals can travel upto 5-6 miles this solution can be truly wireless for rural deployments
- *mmwave basestation dont have to rooted to ground they can be placed on trucks to provide mobility and flexibility*
- millimeter wave base station would have a wireless backhaul to the core network instead of a traditional wired backhaul.

## mmWave for Fixed Wireless Access:
- In principle, if WA devices are very similar to the internet modem and WIFI router pair that many of us have in our homes but there are crucial differences. Let's see the similarities was. In that your modem is connected via a cable to your ISP sub your internet signal gets to your home over that wire and your modem and WIFI router put together translate that signal from the wired medium into a wireless medium. However, some of the disadvantages of that paradigm is that because your ISP's cable comes to your home at pretty much one designated point, your modem and router have to be a station at that point. If it is in your living room, we all know how ugly that arrangement looks. If it is for example in your basement or in your attic, you know that you will have coverage or signal propagation challenges and you will probably get a good spirit and some of the rooms but you will probably get poorer spirits in some of the rooms. Those are some of the disadvantages of the current cable internet environment.
- But contrast to that with a potential fixed wireless access device. This FWA device is truly wireless on both ends, it has no tether wire. On one end it will receive millimeter wave signals transmitted by the nearest G Norby. And at the other end all the devices in your home, be it your laptop, your phone, fitness trackers, you're smart appliances, smart home devices, whatever they may be, they will connect to this FWA device on the other end in a wireless manner. And that is what makes FWA truly portable. In that if you want better coverage in your living room, keep an FWA in your living room. If you want better coverage inside your home office or in your kitchen or in your bedroom, you can very well keep at those locations. Furthermore, you can buy more than one FWA as you want to unlike your current internet service wherein you are limited to one modem and one router. And you can strategically place those FWAs around the house so that your house has ubiquitous high speed connectivity that is ultimately facilitated by this G Norby. So once a wireless device in your home connects to the FWA, it has end to So once a wireless device in your home connects to the FWA, it has end to end connectivity with the G Norby that is facilitated by this FWA in a fully wireless manner. And FWA essentially, it ultimately brings wireless broadband facilitated by millimeter of devices to your home. 

## Indoor & Venue Deployments of mmWave { high connection density } :
![Screenshot from 2023-10-31 18-21-23](https://github.com/KRIISHSHARMA/5G/assets/86760658/335fe274-4b1c-48bf-b932-017504750444)

- for dense event venues :
![Screenshot from 2023-10-31 18-24-48](https://github.com/KRIISHSHARMA/5G/assets/86760658/96872969-e80d-4706-97f8-6d685b274557)

## real life mmwave case studies :
![Screenshot from 2023-10-31 18-31-36](https://github.com/KRIISHSHARMA/5G/assets/86760658/67cbce6a-06b7-4910-968a-3e8ebcb6e5c8)

![Screenshot from 2023-10-31 18-36-50](https://github.com/KRIISHSHARMA/5G/assets/86760658/fb66f494-e7ee-4f70-a199-847dcbf0b152)

![Screenshot from 2023-10-31 18-39-34](https://github.com/KRIISHSHARMA/5G/assets/86760658/10b82a82-b513-40a5-bf40-41584338dafc)











