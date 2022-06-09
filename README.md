### Hi there 👋

Those familiar with docker-compose.yml files will very likely already assume that a bluetooth-compose.yml file does something similarly very special.

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

- feeding a mobile app with a bluetooth-compose.yml file and have it automatically connect to a bluetooth device - with or without user-permissions, as required - to also auto-generate the associated UI - and then to forward those readings to another app, or to the cloud?

### Or what about:

- feeding a bluetooth peripheral IoT device with a bluetooth-compose.yml file and have it auto-configure it's advertisements, services, characteristics, and descriptors, so that a bluetooth central mobile app, or another bluetooth device, can connect to it!

*We can!*

As these are the two ravens in the bluetooth-compose logo, bluetooth-compose as a common language, with one such bluetooth-compose.yml file being the voice of the ble central raven, and the other such bluetooth-compose.yml file being the voice of the ble peripheral raven ~ both speaking to the bluetooth king!

This is the new era of Bluetooth-Compose-On-Demand (BCOD) where an app or device can dynamically consume bluetooth-compose.yml files for dynamic bluetooth engagement where even IoT devices can dynamically adjust to the changing environment around them.

*And if that's not powerful enough to consider, just imagine bluetooth-compose.yml files being passed around as bluetooth extended advertisements! Bluetooth 'mists' of bluetooth-compose.yml files in the bluetooth advertisements atmosphere consolidating to become droplets, droplets consolidating to become bluetooth rain, bluetooth rain falling upon the bluetopth escarpment and turning from streamlets into brooks into rivers, which all flood into and become the bluetooth ocean - with ravens flying across the waters of the deep until the dove-of-peace is released: dynamic customer satisfaction!*

## So let's explain the Bluetooth-Compose logo!

When the Bluetooth name and logo were coined, over two decades ago, it was important to choose a name and logo that acted as a metaphor about how the new technology worked. 'Bluetooth', of course, was an ancient Norse king who united the surrounding tribes to work as a coordinated whole. And the logo is actually the ancient runic 'b' and 't' superimposed into a singularity. We take the logo for granted now, because we understand how it represents the technology.

However *now*, over two decades later, we need to extend the metaphor - how do we explain Bluetooth in a new context where a standardised 'bluetooth-compose' yaml will effectively be a new language that is a bridge between ble centrals and ble peripherals, but maintaining the evolving yet 'quintessential bluetooth' protocol in the middle?

We've gone back to the Norse god, Odin, who had a raven on each shoulder!

- Two ravens who talk to the king betwixt - that old Norse king, 'Bluetooth', with a raven upon one shoulder, and a raven upon the other shoulder, with communication between them perfectly composed!

*Bluetooth-Compose!*

## It's all about communication!

So we've registered the following domains, and engaged a graphic artist to create the logo:

- bluetooth-compose.com
- bluetooth-compose.net
- bluetooth-compose.org
- bluetooth-compose.co.uk

We're just getting started but you can email us at super.admin@bluetooth-compose.com if you are at all enthusistic about this!

### Our Initial Aim

Our initial aim is to create an alpha bluetooth-compose.yml specification as a candidate for community discussion, to move onwards towards beta.

Andthere's a lot to discuss, not least of which is maintaining a separation of concerns between automatically generated UI and the underlying automatically generated advertisements, peripherals, services, characteristics, and descriptors - not to forget the complexity of how to connect to such devices, engage with user-permissions, etc.

And a full-blown discussion must also include the adjacent but not unconnected topic of Augmented Reality, where not only are devices pictorially identified in the visual AR-space - with or without visual information that a user can read in a 'Bluetooth-Up' context similar to fighter-jet head-up displays - but also incorporating the capacity of Bluetooth Device Object Detection that allows a user to visually scan a device, which once recognised, will cause the app to autoconfigure to take a reading.

The new space we are in is imaging an environment that has plenty of bluetooth devices in it, each which are electronically conspicuous to an Augmented Reality application, and dependant upon user-engagement with the device in that AR-space, the dynamic auto-configuring of channels between the AR app and BCOD device so that they can be read, or written to, on demand.

*Bluetooth-Compose-On-Demand.*

#### But first-things-first

Naturally, the specification will be all about how to generate the yml files however as an interoperability proof we will wish to demonstrate their consumption in the following frameworks, hence will create demo bluetooth-compose engines for the following frameworks:

- Xamarin / .Net Maui
- Kotlin Multi Platform
- Swift

And for simulating devices for Integration Testing, we are focussing on two device series:

-    C# Meadow F7v2 boards, using the Meadow API at http://developer.wildernesslabs.co/Meadow/Meadow.OS/Bluetooth/
-    C++ Nordic's nRF52 series at https://www.nordicsemi.com/Products/Bluetooth-Low-Energy/Development-hardware

To consume these peripherals we will simultaneously create an Augmented Reality app (initially, just in Kotlin Multiplatform, using Unity AR, but with the Unity library exportable to Xamarin, .Net Maui, and Swift).

The Bluetooth AR app and it's associated architecture (that is, it's underlying Unity AR module/s that will be capable of being exported to any suitable platform), will also need to be capable of importing relevant ML (machine learning profiles) so that specific devices can be detected in the user's local AR space.

To make this project exciting, but also giving it the opportunity to go viral, this project will be Augmented-Reality led, and that means that our incremental advances in the bluetooth-compose.yml specification must be capable of being demonstrated in our Bluetooth Compose Augmented Reality app.

The focus, however, will be the specification itself, and we would be delighted that as the specification matures, that third parties will create their own bluetooth-compose engines, as well as Augmented Reality applications, on any platform that they desire.

## Current Status

MVP Milestones:

- **(Currently undertaking)** Unity AR 'hello-world' module in a Kotlin Multiplatform hello-world world application from here called the Bluetooth-Compose AR App ('BCAR app') capable of deploying to iOS and Android devices
- The creation of a 3D Printed bluetooth device container that will be ultimately used by AR-space object detection to identify a bluetooth-compose.yml specified object using Machine Learning object detection.
- The built-in capability of the BCAR app to identify the 3D Printed Bluetooth Device Container
- The creation of a bluetooth-compose.yml specification that the BCAR App loads and consumes under user-selection, which identifies a web-based ML file that the AR module seeks, consumes, then uses, to identify that particular 3D Printed Bluetooth Device Container
- The creation of a second 3D Printed Bluetooth Device Container, with instructions on how to create further device ML files, allowing community developers to both create them, and upload them to a common BCAR ML file repo.
- The extension of the bluetooth-compose.yml specification to allow demo Meadowboard and/or nRF bluetooth devices to be placed in respective 3D Printed Bluetooth Device Containers, which when identified in AR-space by the BCAR App, will cause the bluetooth device's advertised name to be displayed adjacent the identified device.
- The extension of the bluetooth-compose.yml specification to allow a user tapping on such a Bluetooth Device that has been so identified in AR-space, to connect to the device and read it's service GUIDs and display them in a Console.
- The creation of a community event to allow the bluetooth-compose specification, as developed so far, to be demonstrated, discussed in a retrospective context, and a wide-range of use cases gathered from the ommunity to steer the project forward.
- The creation of new milestones, based upon feedback from the community event.


