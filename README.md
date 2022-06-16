### Hi there 👋

Those familiar with docker-compose.yml files will very likely already assume that a ```bluetooth-compose.yml``` file does something similarly very special.

### bluetooth-compose.yml
```
version: '0.1'

devices:
     breaths_per_minute:
        yardy-yardy: something
        etcetera:

     pulse_beats_per_minute:
        yardy-yardy: something
        etcetera:

logging:
        yardy-yardy: something
        etcetera:
```

We are a group of bluetooth-nutters who want to use yaml to not just automate the reading of bluetooth devices, but also to simulate devices to make integration testing easier.

### And for example, can you imagine:

- feeding a mobile app with a ```bluetooth-compose.yml``` file and have it automatically connect to a bluetooth device - with or without user-permissions, as required - to also auto-generate the associated UI - and then to forward those readings to another app, or to the cloud?

### Or what about:

- feeding a bluetooth peripheral IoT device with a ```bluetooth-compose.yml``` file and have it auto-configure it's advertisements, services, characteristics, and descriptors, so that a bluetooth central mobile app, or another bluetooth device, can connect to it!

*We can!*

As implied, these are the two ravens in the bluetooth-compose logo, bluetooth-compose as a common language, with one such bluetooth-compose.yml file being the voice of the ```ble central``` raven, and the other such bluetooth-compose.yml file being the voice of the ```ble peripheral``` raven ~ both speaking to the bluetooth king!

This is the new era of ```Bluetooth-Compose-On-Demand (BCOD)``` where an app or device can dynamically consume bluetooth-compose.yml files for dynamic bluetooth engagement where even IoT devices can dynamically adjust to the changing environment around them.

*And if that's not powerful enough to consider, just imagine ```bluetooth-compose.yml``` files being passed around as ```bluetooth extended advertisements```! Bluetooth 'mists' of bluetooth-compose.yml files in the bluetooth advertisements atmosphere consolidating to become bluetooth droplets, bluetooth droplets consolidating to become bluetooth rain, bluetooth rain falling upon the bluetooth escarpment and turning from streamlets of bluetooth into brooks of bluetooth into rivers of bluetooth, which all flood into and become the bluetooth ocean - with ravens flying across the waters of the deep until the dove-of-peace is released: dynamic customer satisfaction!*

## Introduction to Terminology

The following terms are used in this document and the reason for so many acronyms is that (in lower-case) they will be useful abbreviations that can become part of the actual bluetooth-compose.yml file syntax.

### Aide Memoire 

In general, letters sub-parts in acronyms **might** mean one of the following:

- A, App
- M, Module,
- F, file
- U, Unity or Unreal (graphic engines)
- AR, Augmented Reality
- BC, Bluetooth-Compose
- OD, On-Demand, or Object Detection
- ML, Machine Learning
- VR, Virtual Reality
- HUD, Head-Up Display

### Terminology

- .NET Maui
- AR App, ARA
- AR Module, ARM
- Augmented Reality, AR
- Augmented-Reality-Head-Up Display, ARHUD: a general Head-Up Display (HUD) in the Visual AR Space (VARS)
- BCAR ML File, BCARMLF
- Bluetooth Compose Augmented Reality, BCAR
- Bluetooth Compose Augmented Reality App, BCAR App, BCARA
- Bluetooth-Compose AR Module, BCAR Module, BCARM
- Bluetooth-Compose Specification, BCS
- Bluetooth-Compose-On-Demand, BCOD
- Bluetooth-Compose, BC
- bluetooth-compose.yml, BCY
- Bluetooth-Head-Up Display, BHUD: a bluetooth's device Head-Up Display (HUD) in the Visual AR Space
- Electronic Conspicuity, EC (contextual)
- Electronically Conspicuous, EC (contextual)
- Elspic, short for Electronic Conspicuity, Electronically Conspicuous (contextual)
- EoT
- GUID
- Head-Up Display, HUD
- IoT
- Kotlin Multiplatform
- Machine Learning On Demand, MLOD
- Machine Learning, ML
- Meadow F7v2 Board (Wilderness Labs)
- Minimal Viable Product, MVP
- MLOD File, MLODF
- nRF52 Series Board (Nordic)
- Object Detection, OD
- Repository ('repo')
- Swift
- Unity
- Unity AR Module, UAR Module, UARM
- Virtual Reality, VR
- Virtual-Reality-Head-Up Display, VRHUD: a general Head-Up Display (HUD) in the Visual VR Space
- Visual AR Space, VARS
- Wifi-Head-Up Display, BHUD: a wifi device Head-Up Display (HUD) in the Visual AR or VR Space
- Wonderwall
- Xamarin

## So let's first explain the importance of the Bluetooth-Compose logo!

When the Bluetooth name and logo were coined, over two decades ago, it was important to choose a name and logo that acted as a metaphor about how the new technology worked. 'Bluetooth', of course, was an ancient Norse king who united the surrounding tribes to work as a coordinated whole. And the logo is actually the ancient runic 'b' and 't' superimposed into a singularity. We take the logo for granted now, because we understand how it represents the technology.

However *now*, over two decades later, we need to extend the metaphor - how do we explain Bluetooth in a new context where a standardised 'bluetooth-compose' yaml will effectively be a new language that is a bridge between ble centrals and ble peripherals, but maintaining the evolving yet 'quintessential bluetooth' protocol in the middle?

We've gone back to the Norse god, Odin, who had a raven on each shoulder!

- Two ravens who talk to the king betwixt - that old Norse king, 'Bluetooth', with a raven upon one shoulder, and a raven upon the other shoulder, with communication between them perfectly composed!

*Bluetooth-Compose!*

## It's all about communication!

So we've registered the following domains, and engaged a graphic artist to create the logo:

```
- bluetooth-compose.com
- bluetooth-compose.net
- bluetooth-compose.org
- bluetooth-compose.co.uk
```

We're just getting started but you can email us at super.admin@bluetooth-compose.com if you are at all enthusistic about this!

### Where we began - the concept of a smart city being 'Electronically Conspicuous'

Although Bluetooth-Compose is an open-source project, it has it's roots in a private 'smart-city' project called [Electronically Conspicuous](https://www.youtube.com/watch?v=0K6vrWz2AuQ), whose prototype was rapidly run out using 'Wifi Aware', but which inevitably graduated to requiring Bluetooth 5 *extended-advertising* capability so that any ordinary smart-phone could engage with any 'little-red-box' (LRB) that sat upon any one of a number network-connected street-light posts that were 183 meters apart, or less. 

Although not relevant to the open-source specification, but important to understand because of the inherent synchronicity with the private smart city project (and any evolution of it), it is interesting that the figure of 183 meters actually derives from the matter that in the United Kingdom, a 'built-up area' is defined in legislation as being (paraphrased) 'where street-light-posts are 183 meters apart or less'.

- As it turns out, there is a commercial relationship between population density and the obligation of local authorities to provide street-lighting that meets a minimum distance-based specification - and that means that there is already the obligation of local authorities to provide street-light-posts as essentially being already available to be used as 'defacto-smart-city-transmission-towers' and which defacto smart-city-transmission-tower density is thus already budgetted to increase as population density increaeses.
- The knock-on effect of this - and which is the focus of the private venture - is that 'smart-cities' can be defined as places where smart-city radio-broadcast transmission-towers are placed 183 meters apart, or less, with the implication being that each street light post is a defacto 'transmission-tower' upon which a smart-city 'little-red-box' can be placed to be accessible to any mobile or static device that has Bluetooth radio-transmission  capability.

Where Bluetooth-Compose comes into play as part of the original patent-pending abstraction, is that a central hub that feeds all of the 'street-light-post LRBs' would need to feed each LRB with an auto-configuring text-stream - each tailored to each one's culturo-geographic context - and the result of that text-stream would be that each LRB device would be capable of broadcasting culturo-geographic (i.e. location-tailored) information that is based upon smart-phone accessible bluetooth-services that magically autoconfigured themselves according to the structure of the bluetooth-compose  text-stream; the advantage of this, of course, is that Bluetooth 5 would also allow each device to retrieve it's own bluetooth-compose file from each repective LRB  so that it could set up it's own symbiotic relationship with that LRB that was preconfigured by the original text-stream, to broadcast the presence of a specified peripherl.

- The correlation of the 183 meters or less spacing of the smart-city LRBs is that the Bluetooth specification is capable of scaling up to meet smart-city demands without becoming over-saturated.

Two concepts arose from this, 'bluetooth-peripheral-on-demand', and bluetooth-compose-on-demand, with the latter being the intrinsic cause of the former to be capable of manifesting.

Yet despite being a private project - with a patent application pending - it was realised that inevitably, for the Electronically Conspicuous service to be consumed en-mass, the bluetooth-compose specification would have to develop as open-source, with the advantage being that whereas it could still be consumed by the original private context (and in doing so, maintaining it's own patent-pending commercial significances), that bluetooth-compose could also be consumed in a myriad of circumstances that were unconnected with the original technology.

- An example of how bluetooth-compose can be used as totally unconnected with the original smart-city concept, is that the bluetooth-compose specification could also be used to auto-configure a simulated bluetooth peripheral, as part of an isolated overnight intergration-test build in a CI/CD pipeline. 

### Where we're going - as directed by an Open-Source Steering Committee

First of all, here's a shout-out to Chris Davies at [Velvet Skies](https://velvetskies.com/), who designed the Bluetooth-Compose logo. Chris was the UI head at Nokia Entertainment Worldwide, back in Nokia's glory-days, and given his demonstrated value-add to such a prominent global blue-chip, he is naturally this project's first port of call when it comes to UI and UX. The founder of this project worked with Chris at Nokia's Bristol office.

We are also seeking similarly qualified people to be part of the Bluetooth-Compose Steering Committee, the minimum job is to merely keep an eye on what's going on and feed back the occasional comment, and perhaps also attending the occasional steering committee Teams meeting (or something of that ilk).

Of course, you will be able to fill your boots and do as much as you want, but we will need qualified eyes that at a minumum will assist us to track onwards with integrity so that we can constantly and consitently, nudge the leading edge forwards.

If you are qualifed by some nuance to be on the Steering Committee, please either contact us using the above email address, or - if you already know someone who is involved - through a private channel that they'd recommend.

Members of the steering committee will be 'ravens flying back and forth over the waters of the deep', and as we know from history, 'ravens always get from one side of floods of adversity, to the other', doing so, so that 'the dove of peace can be released'.

*The question that the team has before it, is 'What does the dove of peace look like'?*

- Will it be IoT 1.0 graduationg to become IoT 2.0? 
- Will it be Web 3.0 maturing to become Web 4.0 by everything becoming Electronically Conspicuous?

*Those who fly back and forth over the waters of the deep will be the first to know!*

### Our Initial Aim

Our initial aim is to create an alpha ```bluetooth-compose.yml``` specification as a candidate for community discussion, to move onwards towards beta.

And there's a lot to discuss, not least of which is maintaining a separation of concerns between automatically generated UI and the underlying automatically generated advertisements, peripherals, services, characteristics, and descriptors - not to forget the complexity of how to connect to such devices, engage with user-permissions, etc.

And a full-blown discussion must also include the adjacent but not unconnected topic of ```Augmented Reality```, where not only are devices pictorially identified in the ```visual AR-space``` - with or without visual information that a user can read in a ```'Bluetooth-Head-Up Display' (BHUD)``` context similar to fighter-jet Head-Up Display (HUD) - but also incorporating the capacity of Bluetooth Device Object Detection that allows a user to visually scan a device, which once recognised, will cause the app to autoconfigure to take a reading.

The new space we are in is imagining an environment that has plenty of bluetooth devices in it, each which are [electronically conspicuous](https://github.com/HarrisonOfTheNorth/Elspic-IoT-the-next-generation) to an ```Augmented Reality application```, and dependant upon user-engagement with the device in that AR-space, the dynamic auto-configuring of channels between the ```AR app``` and ```BCOD``` device so that they can be read, or written to, on demand.

*Bluetooth-Compose-On-Demand, BCOD.*

#### But first-things-first

Naturally, the specification will be all about how to generate the yml files however as an interoperability proof we will wish to demonstrate their consumption in the following frameworks, hence will create demo bluetooth-compose engines for the following frameworks:

```
- Xamarin / .Net Maui
- Kotlin Multi Platform
- Swift
```

And for simulating devices for Integration Testing, we are focussing on two device series:

```
-    C# Meadow F7v2 boards, using the Meadow API at http://developer.wildernesslabs.co/Meadow/Meadow.OS/Bluetooth/
-    C++ Nordic's nRF52 series at https://www.nordicsemi.com/Products/Bluetooth-Low-Energy/Development-hardware
```

## Current Status

To consume these peripherals (the [C# Meadow F7v2 boards](http://developer.wildernesslabs.co/Meadow/Meadow_Basics/Hardware/F7v2/) and [C++ Nordic's nRF52 series](https://www.nordicsemi.com/Products/Bluetooth-Low-Energy/Development-hardware) devices)  we will simultaneously create an Augmented Reality app (initially, just in Kotlin Multiplatform, using Unity AR, but with the Unity library exportable to Xamarin, .Net Maui, and Swift).

The Bluetooth AR app and it's associated architecture (that is, it's underlying Unity AR module/s that will be capable of being exported to any suitable platform), will also need to be capable of importing relevant ML (machine learning profiles) so that specific devices can be detected in the user's local AR space.

To make this project exciting, but also giving it the opportunity to go viral, this project will be Augmented-Reality led, and that means that our incremental advances in the bluetooth-compose.yml specification must be capable of being demonstrated in our Bluetooth Compose Augmented Reality app.

The focus, however, will be the specification itself, and we would be delighted that as the specification matures, that third parties will create their own bluetooth-compose engines, as well as Augmented Reality applications, on any platform that they desire.

The current status of the specifications can be determined by the status of the progression of the following milestones.

### MVP Milestones:

- **(Currently undertaking)** The creation of a Unity AR 'hello-world' module in it's own repository that is consumed by a Kotlin Multiplatform hello-world world application that is separate in it's own repository but which loads that Unity AR module, which from here are collectively called the Bluetooth-Compose AR App ('BCAR app'), and which is capable of deploying to iOS and Android devices, with the initial intention being to ultimately deploy to the Google Play Store, and Apple App Store. 
- The creation of a 3D Printed bluetooth device container that will ultimately be identified by the app's AR-space object detection mechanism via a user-loaded bluetooth-compose.yml file pointing to an external Machine Learning (ML) object detection file that will allow the BCAR App to identify it.
- The built-in capability of the BCAR app to identify this specific 3D Printed Bluetooth Device Container.
- The creation of a bluetooth-compose.yml specification that the BCAR App can load and consume under manual user-selection, which bluetooth-compose.yml file will identify a web-based ML file that the AR module seeks, consumes, then uses, to identify that particular 3D Printed Bluetooth Device Container. Such a web based ML file will be stored in a separate Bluetooth-Compose repo (the 'BCAR ML file repo') that can be a hub for all future public BCAR ML files that are capable of being consumed by the application.
- The creation of a second 3D Printed Bluetooth Device Container, with instructions on how to create further device ML files, allowing community developers to both create them and upload them to the common BCAR ML file repo. The instructions should identify where the associated 3D Printing files are located, if pertinent.
- The extension of the bluetooth-compose.yml specification to allow demonstration Meadowboard and/or nRF series bluetooth devices to be placed in respective 3D Printed Bluetooth Device Containers, which when identified in AR-space by the BCAR App, will cause the bluetooth device's advertised name to be displayed within the BCAR App's visual AR-space, adjacent the identified device.
- The extension of the bluetooth-compose.yml specification to allow a user tapping on such a Bluetooth Device that has been so identified in AR-space, to connect to the device and read it's service GUIDs and display them in a Console.
- The creation of a community event to allow the bluetooth-compose specification, as developed so far, to be demonstrated, discussed in a retrospective context, and a wide-range of use cases gathered from the community to steer the project forward.
- The creation of new milestones, based upon feedback from the community event.

Naturally, once we get to this stage, users will be able to create AR ML files for any Bluetooth device on the market, enabling them to be intelligently object detected in the Bluetooth Compose AR Module, using such Machine Learning profiles as developers will create, and at this point we would hope that the project would begin to go viral as developers start to create AR ML files in anticipation of the Bluetooth-Compose specification being extended further to allow the devices to not just be identified in the local AR-space, but then read, and written to.

We recently [asked](https://www.youtube.com/watch?v=kzNXPFguYik&t=2701s) what IoT 2.0 will look like, and although we have some [idea](https://github.com/HarrisonOfTheNorth/Elspic-IoT-the-next-generation) of what this might look like, we surmise that this project will make a significant contribution!

### Further Reading

Given that Bluetooth-Compose in the context of Augmented Reality can be very easily seen to be 'Electronically Conspicuous' in the very real sense of the expression, you may be interested in looking at our thoughts [here](https://github.com/HarrisonOfTheNorth/Elspic-IoT-the-next-generation) that consider how ```IoT```, via the abstraction of *Electronic Conspicuity*, might transform ```IoT``` into becoming ```EoT```. 

- In that article, we propose that Electronic Conspicuity is IoT's wonderwall, and that Electronic Conspicuity will transform IoT into the next evolution of itself, EoT. 
