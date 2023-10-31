## Massive MIMO Definition & M-MIMO Antenna Arrays :
### what is massive mimo ? 
- an important part of 5G mmwave and sub-6 GHz deployments
- Antenna array : pre requisite to m-mimo
  - a panel with many antennas each of which is very small
  - high frequency of 5G operation makes small antennas possible ( high freq = high pathloss )
- beamforming: enabled by m-mimo:
  - focusing trasmitted signal only in the desired direction  (directivity) => narrow beam
  - multiple narrow beams can be generated
  - horizontal and vertical beamforming => 3D coverage
  - individual beams can serve diff users

![Screenshot from 2023-10-31 19-13-24](https://github.com/KRIISHSHARMA/5G/assets/86760658/e257666a-023c-458d-93a4-dd402e2be91e)

## what is beamforming ? 
- beamforming: enabled by m-mimo:
  - focusing trasmitted signal only in the desired direction  (directivity) => narrow beam
  - multiple narrow beams can be generated . *depends on gnodeb sophistication*
  - horizontal and vertical beamforming => 3D coverage
  - individual beams can serve diff users
- all the antennas in the array acts cohesively as one entity 

![Screenshot from 2023-10-31 19-25-19](https://github.com/KRIISHSHARMA/5G/assets/86760658/229671b7-8c50-4464-b535-588ddd40d62b)
![Screenshot from 2023-10-31 19-27-01](https://github.com/KRIISHSHARMA/5G/assets/86760658/4afd5f68-58bb-4179-8869-91092e9f64d8)
- improvement in SNR = Better Spectral efficiency = more throughput

![Screenshot from 2023-10-31 19-33-39](https://github.com/KRIISHSHARMA/5G/assets/86760658/b184e961-c389-4c66-bb74-6387d58f6c6e)
- called MU-MIMO { multi user MIMO } => would not be posible w//o beamforming 
- what about the frequency channel that those beams use? Do those two beams use the same frequency channel or do those two beams have to go over different frequency channels. Thereby increasing the resource requirement of the system and does making the system more expensive? Well, the answer is the former in that these two beams sent by the same antenna panel of the same gNodeB. Can indeed go over the same frequency channel and why? Although the technical explanation is somewhat beyond us at this moment, recall the analogy that we had given you when discussing massive MIMO. In that there was a role that was initially built on land and because of traffic requirement increased. We built another role as a deck on top of the existing rules and then we built another deck and then we built another deck. All the decks were built on the exact same piece of land because they used not more land space but they used more airspace. And by doing so, those multiple decks significantly improved your traffic carrying capacity at the same time. However, because the car's going on, two different decks were moving at two different levels. They wouldn't collide or interfere with each other. That was the basic premise of MIMO for massive MIMO. And the same premise, although with a different extension is also seen in practice over here. In that these two beams sent by the gNodeB are encoded differently. And because they are encoded differently, they do not interfere with each other, although they are transmitted by the same gNodeB. And because they do not interfere with each other, that is the reason why beams one and beams two can safely use the same frequency channel. And that is the benefit of beforming in that all the beams transmitted by the gNodeB as long as they are carefully encoded, can use the same frequency channel.

![Screenshot from 2023-10-31 19-39-47](https://github.com/KRIISHSHARMA/5G/assets/86760658/5c39efef-b15e-4662-bb60-4fd500b031af)

## Beamsweeping 
![Screenshot from 2023-10-31 19-45-46](https://github.com/KRIISHSHARMA/5G/assets/86760658/c6145c39-020d-4f94-8cc8-86b2f6e9a525)

- One simpler way to understand this would be to compare a likable and a flashlight. Let's assume that both of those operate and the same power in order to have a fair comparison. Now, imagine that you have a light bulb at the center of the room. Sure, it will illuminate the whole room. But the brightness or the intensity of the light will be somewhat loom. In that if you really want to focus on one corner of the room, chances are the light bulb installed at the center of the room will not help you take a closer look at one of the corners for example. However, that is where a flashlight comes into picture. So if you have a flashlight that nonetheless uses the same amount of power because it focuses its outward light only in a limited direction. And if you point that flashlight to that corner, it will illuminate that corner much more brightly as compared to the light bulb. And that is simply because flashlight is only focusing its energy in the desired direction of interest and nowhere else. So light bulb is a good tool in order to illuminate the whole room, albeit a little less brightly. Whereas flashlight is a tool that is used to illuminate only a certain area of interest but with much more brightness or much higher intensity as compared to a light bulb. And that is a simpler way to understand a non-beamformed system. i.e. a light bulb versus a beamformed system that is a flashlight.

- beansweeping is used to transmit generic info on the control plane

## benefits of M-MIMO :
![Screenshot from 2023-10-31 20-01-23](https://github.com/KRIISHSHARMA/5G/assets/86760658/73e20e9b-5e9e-4a4e-a841-802e49fcde5d)

## Real life M-MIMO case studies :
![Screenshot from 2023-10-31 20-01-23](https://github.com/KRIISHSHARMA/5G/assets/86760658/1b1fbb85-7b0f-4a80-ad2c-b398bfc4ba44)
