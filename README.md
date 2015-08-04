## What is Software Defined Radio?

The implementation of modulators, demodulators, and other radio signal processing algorithms in a general programming language. The advent of modern computing allows most of the traditionally hardware radio based components to be implemented in software for a reconfigurable compute unit. This enables rapid protoyping for   signal processing and robust radios products that can reconfigure the signal processing chain on the fly.

## A $15 SDR?

The RTL-SDR is a very cheap software defined radio that uses a DVB-T TV tuner dongle based on the RTL2832U chipset. With the combined efforts of Antti Palosaari, Eric Fry and Osmocom it was found that the signal I/Q data could be accessed directly, which allowed the DVB-T TV tuner to be converted into a wideband software defined radio via a new software driver.

Essentially, this means that a cheap $15 TV tuner USB dongle with the RTL2832U chip can be used as a computer based radio scanner. This sort of scanner capability would have cost hundreds or even thousands of dollars just a few years ago.

| Tuners | Frequency |
| ------ | --------- |
| Elonics E4000 | 52 - 2200 MHz with a gap from 1100 MHz to 1250 MHz |
| Rafael Micro R820T | 24 - 1766 MHz |
| Rafael Micro R820T2 | 24 - 1766 MHz w/ better sensitivity |

## Demos
* 24-2200 MHz Spectrum Analyzer [http://gnuradio.org/redmine/projects/gnuradio/wiki]
* AM/FM Receiver
** Nexus 7
** ARM Chrombook https://github.com/google/radioreceiver
* Water Meter [http://bemasher.github.io/rtlamr/]
* ADS-B Beacon [https://github.com/MalcolmRobb/dump1090]




## Higherend hardware

* http://airspy.com/
* https://greatscottgadgets.com/hackrf/

## Open Source SDR Projects
http://gnuradio.org/redmine/projects/gnuradio/wiki
http://sdrsharp.com/#sdrsharp

## Where to go from here?
http://www.sigidwiki.com/wiki/Signal_Identification_Guide
