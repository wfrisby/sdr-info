## What is Software Defined Radio?

Radio components such as modulators, demodulators and amplifiers are traditionally implemented in hardware components. The advent of modern computing allows most of these traditionally hardware based components to be implemented into software instead. Hence, the software defined radio. This enables easy signal processing and thus cheap wide band scanner radios to be produced.

## A $15 SDR?

RTL-SDR is a very cheap software defined radio that uses a DVB-T TV tuner dongle based on the RTL2832U chipset. With the combined efforts of Antti Palosaari, Eric Fry and Osmocom it was found that the signal I/Q data could be accessed directly, which allowed the DVB-T TV tuner to be converted into a wideband software defined radio via a new software driver.

Essentially, this means that a cheap $15 TV tuner USB dongle with the RTL2832U chip can be used as a computer based radio scanner. This sort of scanner capability would have cost hundreds or even thousands of dollars just a few years ago.

## Why do we care?

## Demos
* 24-2200 MHz Spectrum Analyzer [http://gnuradio.org/redmine/projects/gnuradio/wiki]
* AM/FM Receiver (Nexus 7)
* Water Meter [http://bemasher.github.io/rtlamr/]
* ADS-B Beacon [https://github.com/MalcolmRobb/dump1090]


| Tuners | Frequency |
| ------ | --------- |
| Elonics E4000 | 52 - 2200 MHz with a gap from 1100 MHz to 1250 MHz |
| Rafael Micro R820T | 24 - 1766 MHz |
| Rafael Micro R820T2 | 24 - 1766 MHz w/ better sensitivity |

## Other More Hardware

## Open Source SDR Projects
