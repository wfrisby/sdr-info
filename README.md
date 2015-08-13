## What is Software Defined Radio?

The implementation of modulators, demodulators, and other radio signal processing algorithms in a general programming language. The advent of modern computing allows most of the traditionally hardware radio based components to be implemented in software for a reconfigurable compute unit. This enables rapid protoyping for   signal processing and robust radios products that can reconfigure the signal processing chain on the fly.

![Flow](https://cdn.rawgit.com/wfrisby/sdr-info/master/imgs/SDR_et_WF.svg)

## RTL-SDR - a $15 SDR receiver?

The RTL-SDR is a very cheap software defined radio that uses a DVB-T TV tuner dongle based on the RTL2832U chipset. With the combined efforts of Antti Palosaari, Eric Fry and Osmocom it was found that the signal I/Q data could be accessed directly, which allowed the DVB-T TV tuner to be converted into a wideband software defined radio via a new software driver.

Essentially, this means that a cheap $15 TV tuner USB dongle with the RTL2832U chip can be used as a computer based radio scanner. This sort of scanner capability would have cost hundreds or even thousands of dollars just a few years ago. If you want to get started quickly there are Live DVD/USB [images] (http://gnuradio.org/redmine/projects/gnuradio/wiki/GNURadioLiveDVD) [available]
(http://skywavelinux.com/) to download. If you use Microsoft Windows, you can install [SDR#](http://sdrsharp.com/#sdrsharp). 

![Dongle](https://cdn.rawgit.com/wfrisby/sdr-info/master/imgs/ezcap_top.jpg)

| Tuners | Frequency |
| ------ | --------- |
| Elonics E4000 | 52 - 2200 MHz with a gap from 1100 MHz to 1250 MHz |
| [Rafael Micro R820T](http://www.amazon.com/RTL2832U-Low-Cost-Software-Compatible-Packages/dp/B00SXZDUAQ/) | 24 - 1766 MHz |
| Rafael Micro R820T2 | 24 - 1766 MHz w/ better sensitivity |

## Demos
* [Visual DSP introduction] (http://visual-dsp.switchb.org/presentation)
* [24-2200 MHz Spectrum Analyzer] (http://gnuradio.org/redmine/projects/gnuradio/wiki])
* AM/FM Receiver
    * Android RLT-SDR [app](https://play.google.com/store/apps/details?id=marto.androsdr2)
       * 99.5 MHz ([RDS](https://en.wikipedia.org/wiki/Radio_Data_System) BPSK station info)
       * 162.55 MHz (SLC NOAA Weather)
    * Chrome [app](https://github.com/google/radioreceiver)
* [Water Meter](http://bemasher.github.io/rtlamr/)
* [ADS-B Beacon](https://github.com/MalcolmRobb/dump1090)

## More sophisticated hardware
* http://www.ettus.com/product/details/UB210-KIT
* http://www.ettus.com/product/details/E310-KIT
* http://airspy.com/
* https://greatscottgadgets.com/hackrf/

## Open Source SDR Projects
http://sdr.osmocom.org/trac/wiki/rtl-sdr
http://gnuradio.org/redmine/projects/gnuradio/wiki
http://cgit.osmocom.org/cgit/gr-osmosdr/

## Where to go from here?
http://openbsc.osmocom.org/trac/wiki/OsmocomOverview
http://www.sigidwiki.com/wiki/Signal_Identification_Guide

## AD RF-Frontends
http://www.analog.com/en/products/rf-microwave/integrated-transceivers-transmitters-receivers/wideband-transceivers-ic/ad9361.html#product-overview
