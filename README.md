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

And for example, can you imagine feeding an Apple Watch or Android watch with a bluetooth-compose.yml file and have it act as a Personal Bluetooth Hub to monitor a user's personal local bluetooth devices, and forward those readings to an app or cloud?

We can!

## Let's explain the Bluetooth-Compose logo!

When the Bluetooth name and logo were coined, over two decades ago, it was important to choose a name and logo that acted as a metaphor about how the new technology worked. 'Bluetooth', of course, was an ancient Norse king who united the surrounding tribes to work as a coordinated whole. And the logo is actually the ancient runic 'b' and 't' superimposed into a singularity. We take the logo for granted now, because we understand how it represents the technology.

However *now*, over two decades later, we need to extend the metaphor - how do we explain Bluetooth in a new context where a standardised 'bluetooth-compose' yaml will effectively be a new language that is a bridge between ble centrals and ble peripherals, but maintaining 'quintessential bluetooth' in the middle?

We've gone back to the Norse god, Odin, who had a raven on each shoulder!

Two ravens who talk to each other with that old Norse king, 'Bluetooth', in the middle between them!

## It's all about communication!

So we've registered the following domains, and engaged a graphic artist to create the logo:

- bluetooth-compose.com
- bluetooth-compose.net
- bluetooth-compose.org
- bluetooth-compose.co.uk

We're just getting started but you can email us at super.admin@bluetooth-compose.com if you are at all enthusistic about this!

### Our Initial Aim

Our initial aim is to create an alpha bluetooth-compose.yml specification as a candidate for community discussion, to move onwards towards beta.

Naturally, the specification will be all about how to generate the yml files however as an interoperability proof we will wish to demonstrate their consumption in the following frameworks, hence will create demo bluetooth-compose engines for the following frameworks:

- Xamarin / .Net Maui
- Kotlin Multi Platform
- Swift

And for simulating devices for Integration Testing, we are focussing on two device series:

-    C# Meadow F7v2 boards, using the Meadow API at http://developer.wildernesslabs.co/Meadow/Meadow.OS/Bluetooth/
-    C++ Nordic's nRF52 series at https://www.nordicsemi.com/Products/Bluetooth-Low-Energy/Development-hardware

The focus, however, will be the specification itself, and we would be delighted that as the specification matures, that third parties will create their own bluetooth-compose engines on any platform that they desire.
