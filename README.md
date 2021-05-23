# awesome-hamradio

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A collection of the best free and open source hamradio projects!**

## Software

### Networking
+ [HBLink3](https://github.com/n0mjs710/hblink3) Open Source HomeBrew Repeater Proctol Client/Master, can be used to create links between hotspots and repeaters.

### Replacement Radio Firmwares and Reverse Engineering

+ [MD380Tools](https://github.com/travisgoodspeed/md380tools) and [TyMD380Tools](https://github.com/KG5RKI/TyMD380Tools) have reverse engineered the MD380 and MD-2017/MDUV380 series radios respectively and have tools to build and work with replacement firmwares. MD380tools has most of what you need to understand the TYT .rdt codeplug format.
+ [OpenGD77](https://github.com/rogerclarkmelbourne/OpenGD77)  Firmware for DMR transceivers using the NXP MK22 MCU, AT1846S RF chip and HR-C6000 DMR chipset. Including the Radioddiy GD-77, Baofeng DM-1801 and Baofeng RD-5R. 
+ [G90Tools](https://github.com/OpenHamradioFirmware/G90Tools)  Tools and guides for working with the Xiegu G90 HF radio firmware 

### Decoding

+ [multimon-ng](https://github.com/EliasOenal/multimon-ng) decodes many paging, AFSK modes, and similar, including POCSAG, FLEX, EAS.

### POCSAG

+ [UniPager](https://github.com/rwth-afu/UniPager) Universal POCSAG transmitter controller written in Rust.

### SDR

+ [GNU Radio](https://github.com/gnuradio/gnuradio) a software development toolkit that provides signal processing blocks to implement software radios.
+ [gqrx](https://github.com/csete/gqrx) is an open source software defined radio (SDR) receiver implemented using GNU Radio and the Qt GUI toolkit.
+ [linhpsdr](https://github.com/g0orx/linhpsdr) linux hpsdr software.
  + [pihpsdr](https://github.com/g0orx/pihpsdr) Raspberry Pi 3 standalone code for HPSDR
+ [quisk](http://james.ahlstrom.name/quisk/) SDR software to control different radios like the Hermes-Lite or HiQSDR
+ [CubicSDR](https://github.com/cjcliffe/CubicSDR) a Cross-Platform Software-Defined Radio Application.
+ [insprectrum](https://github.com/miek/inspectrum) is a tool for analysing captured signals, primarily from software-defined radio receivers.
+ [ShinySDR](https://github.com/kpreid/shinysdr) is the software component of a software-defined radio receiver like the HackRF or RTL-SDR.
+ [SDRangel](https://github.com/f4exb/sdrangel) SDR and signal analyzer frontend to various hardware.
+ [PyMultimonAPRS](https://github.com/asdil12/pymultimonaprs) can take an RTLSDR or audio input and Igate APRS traffic.
+ [OpenWebRX](https://github.com/jketterl/openwebrx)  Open source, multi-user SDR receiver software with a web interface, forked and improved from [HA7ILM's](https://github.com/ha7ilm/openwebrx) excellent initial project.
+ [Qradiolink](https://github.com/qradiolink/qradiolink)  Multimode SDR transceiver for GNU radio 

### Logging

+ [CQRLOG](https://github.com/ok2cqr/cqrlog) an advanced ham radio logger based on MySQL database.
+ [KLog](http://www.nongnu.org/ea4k/klog) a minimal logging program for Amateur Radio Operators.
+ [PyQSO](https://github.com/ctjacobs/pyqso) is a contact logging tool for amateur radio operators.
+ [Xlog](http://www.nongnu.org/xlog/) a minimal logging program for Amateur Radio Operators.


### Digimodes

+ [WSJT](https://sourceforge.net/projects/wsjt/) five programs designed for amateur radio communication
  + **WSJT:** Modes optimized for meteor scanner, ionospheric scatter, and EME at VHF/UHF/Microwaves.
  + **WSJT-X:** Modes JT65, JT9. Primarily for use at HF.
  + **MAP65:** For EME an VHF and higher frequencies. Implements a panoramic, polarization-matching receiver for JT65.
  + **WSPR:** Probe potential propagation paths using low-power transmissions.
  + **WSPR-X:** Experimental version of WSPR, including the slow mode WSPR-15.

+ [fldigi](https://sourceforge.net/projects/fldigi/) is a modem program for most of the digital modes used by radio amateurs today.

### Libraries

+ [Hamlib](https://github.com/Hamlib/Hamlib) libraries for amateur radio equipment control applications.
+ [pyhamtools](https://github.com/dh1tw/pyhamtools ) is a set of functions and classes for Amateur Radio purposes.
+ [Codec2](https://github.com/drowe67/codec2) is a FOSS ultra-low bitrate voice codec that's competitive from 3200 bits/s down to 450 bits/s. Also includes [FreeDV](https://freedv.org/), an HF digital voice mode. [PyCodec2](https://github.com/gregorias/pycodec2) is an easy Python wrapper.
+ [CSDR](https://github.com/ha7ilm/csdr) csdr is a command line tool to carry out DSP tasks for Software Defined Radio.

### Radio programming

+ [CHIRP](https://chirp.danplanet.com/projects/chirp/wiki/Home) a free, open-source tool for programming your amateur radio.
+ [editcp](https://github.com/DaleFarnsworth/codeplug/tree/master/editcp) a codeplug editor  for the Tytera MD380 and MD390 as well as the Alinco DJ-MD40 radios.

### Satellite operation

+ [Gpredict](http://gpredict.oz9aec.net/) a real-time satellite tracking and orbit prediction application.
+ [gr-satellites](https://github.com/daniestevez/gr-satellites) GNU Radio decoders for several Amateur satellites.

### Training
+ [AFU Group Trainer](https://github.com/ccoors/afu-group-trainer) a tool that eases the collaborative learning for the (German) HAM exam by allowing each student to answer the questions during a learning session instead of just one person answering. (Currently only in german)

## Hardware

+ [MMDVM](https://github.com/g4klx/MMDVM) Multi-Mode Digital Voice Modem
  + [MMDVM_HS_HAT](https://github.com/mathisschmieder/MMDVM_HS_Hat) for the Raspberry Pi (Zero)

+ [HPSDR](http://openhpsdr.org/) a hardware and software project intended as a "next generation" Software Defined Radio (SDR) for use by Radio Amateurs.
+ [SM1000 FreeDV adapter](http://www.rowetel.com/wordpress/?page_id=3902) FreeDV in hardware. Purchasable on [tindie](https://www.tindie.com/products/edwin/sm1000-freedv-adpapter/)
+ [Mobilinkd TNCs](https://github.com/mobilinkd) have open firmware, unsure if hardware is open. [Homepage](http://www.mobilinkd.com/)
+ [TR-9](https://github.com/sp5wwp/TR-9) implements an [M17](https://github.com/sp5wwp/M17_spec) (fully open source DMR/D*/P25 competitor) radio.
+ [QCX-SSB](https://github.com/threeme3/QCX-SSB)  This is a simple and experimental modification that transforms your QCX into a (class-E driven) SSB transceiver. 
+ [uBITx](https://www.hfsignals.com/index.php/ubitx/) An understandable general coverage HF SSB/CW transceiver kit 
