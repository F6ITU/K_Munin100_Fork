# MUNIN-100
MUNIN 100 is a 100W HF Power Amplifier using the MRF101AN/MRF101BN at 48V DC supply voltage.

Munin amps belongs to the OpenHPSDR familly

Original design by Kjell LA2NI

Some small mods by f6itu (just some kicad settings and design)


![Munin, a 100W HF linear amplifier](https://github.com/F6ITU/K_Munin100_Fork/blob/main/MUNIN%20100-B.png)

This amplifier board is part of a set consisting of a 100 W LD-Mos based RF power amplifier (Munin 100), 
a medium power Zolotarev low pass filter (600 or 1500 W), an Automatic Antenna Tuner (ATU) nickname « Aries » 
and a 4 port antenna switch.

But the power level is compatible with the traditional "Alexiares" filter frontend, (https://wiki.electrolab.fr/Projets:Lab:2017:Peripheriques_Angelia )
in lpf/hpf configuration or it's up to date evolution (lpf and dual bpf) 


All these developments are the work and intellectual property of Kjell Karlsen LA2NI and Laurence Barker G8NJJ.

This original work can be downloaded from

https://github.com/LA2NI/

https://github.com/laurencebarker


This board was originally developed in 2022 by Kjell LA2NI.

This fork (convertion/translation) is placed under the CERN Open source/ Open hardware Licence.

Kicad is an Opensource EDA software maintained by the European Reseach Center CERN (Conseil européen pour la recherche nucléaire)

The original work is protected by the TAPR Open Hardware licence

Mythology and openHPSDR codename conventions

Munin and Hugin are the two "messenger" ravens of the Norse god Odin - just as Hermes is the messenger-god in Greek mythology, 
and the masterpiece of the OpenHPSDR architecture 

This LDMoS transistor-based amplifier brings speech over the great distances of the "Midgard" of the waves


# Work in progress
do NOT use these files as long as this footnote hasn't been deleted

As far as I know, this amp has never been build. Some minor kicad errors and design hickups have been fix

the pcb has been design to accomodate two feedback techniques : 
- coupling from a "secondary" winding in the first TLT
- or direct pickup of the drain signal
Value or R16/19 should be changed accordingly 

ibidem : the  the 1:4 input impedance transformer could be replaced with a simple coax strap (with or without ferrite core) as the combined impedance of the two transistors is approximately 50 Ohms at 55 MHz. On lower frequencies, the value of Z
is determined by the value of R4-R11 (22 Ohms, not yet tested) 





