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
