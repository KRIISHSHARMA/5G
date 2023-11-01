## Overview of Security in 5G
![Screenshot from 2023-11-01 16-14-42](https://github.com/KRIISHSHARMA/5G/assets/86760658/00cd835f-3391-4c4f-ac2e-9db0fa90ea67)

## Enhanced System-Level Design
- 3GPP: Is when a user is trying to access 5G core network over either a 5G public network or a 5G private network, but at the end of the day It is a 5G Ran.
- Non 3GPP: in this context means a different air interface or wireless technology than 5G such as Wifi.
- non 3GPP ex : let's say that maybe there is going to be a pop up concert at a certain place or maybe there is a celebrity going to sign the book at a mall. And there is going to be some temporary crowd and that location for which the operator might need extra capacity and extra throughput. Keep in mind that deploying of 5G at such locations for temporary purposes may not be very economically viable. So under such a representative conditions, what the operator might choose to do is the following. Instead of deploying a five G base station, just have a wifi hotspot at that point. And instead of the Wifi hotspot connecting to a third party ISPS network, that hotspot in the end will be connecting to that cellular network operators or 5G core network. So all the users in that particular area, such as the shopping mall, the users particularly of that cellular network operator, the subscribers of that operator will also be able to connect to this Wifi hotspot using the Wifi connection on their 4, not 5G but Wifi connection. But in the end, that connection will go back to a five G core network, thus allowing those subscribers to be able to access all the features of a typical 5G core network over a Wifi access channel rather than a 5G air interface.So that is a quick high level background on non 3GPP access and just one of the representative use cases that it might be deployed under. 

- Unified Authentication Framework :
   - same auth. for both 3gpp and non 3gpp access
   - security level can be tailored/scaled for a wide range of use cases and deployments
   - non-sim credentials can be used for security suitable eg private networks
 
- security anchor function(SEAF):
  - mobility/session management can move to the edge without compormising security , which stays deeperin thenetwork pysical security is highest
   
![Screenshot from 2023-11-01 16-25-11](https://github.com/KRIISHSHARMA/5G/assets/86760658/be79a0e3-86f1-4594-9314-30727f0ffc77)

![Screenshot from 2023-11-01 16-35-04](https://github.com/KRIISHSHARMA/5G/assets/86760658/13ac5323-2471-44bc-a1ed-3fe638fa6388)

- authentication and encryption data is still hosted on the core network

![Screenshot from 2023-11-01 16-37-22](https://github.com/KRIISHSHARMA/5G/assets/86760658/563e4c55-9b14-4656-8193-262b859b0cad)

- deeper key hierarchy - no matter where the user is located, home network or a different rooming network, some of the fundamental security mechanisms, including your security keys, etc, will always be hosted in the home network. In a simple language, no matter where the user is, the user will always have an end-to-end secure data tunnel, so to speak, with its home network and thereby ensuring that no matter where the user is, it's security is not compromised because it follows the same grid as a security in the home network because there is this secure virtual data tunnel going from the home network to the user no matter where he is located.

- improved data protection : Legacy technologies such as LT, did have the mechanism of integrity protection, wherein you add a certain metadata with your data of interest so that if an attacker in the middle got access to the data, and maliciously changed are some of the data to a different set of bits and bytes, the ultimate receiver, using the metadata, would still be able to tell whether somebody tampered with the data in transit or whether that data came in without being tampered. That is the basic premise of integrity protection. Legacy technologies like LT limited that integrity protection only to control plane. But 5G has now expanded our integrity protection to user plane as well. That even not just the signaling but even user plane data, if it is tampered with by an attacker in the middle, such as your picture or your email, your 5G phone will be able to tell that that data was tampered with and as such to discard that data if it is observed to have been tampered with, and it will ask the network for a different copy of the same data. In addition to integrity protection goes without saying that both control and user plane feature encryption, meaning that the data that is sent on control or user plane can be successfully decoded only by the user for which that data is intended for because when you subscribe to the service from a cell phone operator, as I said, in most cases, at least in everyday parlance, you'll get a SIM card, the keys corresponding to those that are stored in your SIM card are also stored in the operator score network. that is how 5G network precisely knows what encryption keys we use in order to encrypt data for a specific user so that that transmission can be successfully decoded only by that user and no other user. 

## Protecting User Privacy :
- IMSI = international mobile subscriber identity

![Screenshot from 2023-11-01 16-53-51](https://github.com/KRIISHSHARMA/5G/assets/86760658/49bd7a1d-a13a-48fc-9c1d-f9fcdabf5e32)

![Screenshot from 2023-11-01 16-58-41](https://github.com/KRIISHSHARMA/5G/assets/86760658/63380602-8fb8-4d5b-b858-5d0daaec51bd)

![Screenshot from 2023-11-01 16-59-04](https://github.com/KRIISHSHARMA/5G/assets/86760658/79b84d27-63ca-44f0-ad3e-cdf2e68da7e6)

- But at this point, a question might have popped in your mind. That, hey, you mention that all the important business happens after authentication and encryption context has been established. But how does the network establish authentication or encryption context, or the security context. In general, with the UE without knowing what that UE is. Isn't that kind of a catch-22 wherein you are looking to establish security framework, but you haven't yet verified who that UE is. How do we solve that Catch-22. To speak. 5G operates its security mechanisms in a bootstrap manner in that, when the UE tries to connect to a 5G network. The UE doesn't send all their personal information in one go. It sends a little bit of information to the network information that is actually nonsensitive generic in nature. Using that information, the network establishes the first phase of the security. Based on that, UE sends the second batch of information. Based on that, the network establishes second stage of security. In this step-by-step bootstrap manner by establishing incremental authentication and security in multiple steps. That is how 5G network ensures that the user has been fully authenticated before it can access the service. UE on
the other hand, makes sure that it is sending sensitive information if at all, only after the requisite security and authentication framework has been completely established. These are some of the high level mechanisms that 5G uses in order to not just provide enhanced data security, but also enhanced user privacy for a wide variety of user devices and applications.

