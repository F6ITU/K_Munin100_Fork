# K_Munin400
LA2NI's OpenHPSDR 100W HF amplifier (Kicad Version)


This amplifier board is part of a set consisting of a 100 W LD-Mos based RF power amplifier (Munin 100 Fork), 
a medium power Zolotarev low pass filter (600 or 1500 W), an Automatic Antenna Tuner (ATU) nickname « Aries » 
and a 4 port antenna switch.

All these developments are the work and intellectual property of Kjell Karlsen LA2NI and Laurence Barker G8NJJ.

This original work can be downloaded from

https://github.com/LA2NI/

https://github.com/laurencebarker


This board was originally developed in December 2021 by Kjell LA2NI , with UltiBoard EDA. This repository is a fork 
of the original amplifier using the Opensource Kicad EDA. 
All these KiCad files are, consequently, the intellectual property of Kjell LA2NI.

# 100W mod short note

add C1/C38

R2 (5.6 Ohms) is DNI

T1 is a short "current balun" made of 
RG316 coax cable and not a BN202 transformer

transistors are MRF101 AN and BN now

T2 & T3 : direct strap with a short piece of RG252

R11 to R16 ! 2x 1K2 per each branch

add a symetric "in phase" current TLT 
supply transformer to route L4 output 
to each transistor drain. 
This supply transformer is made with 2.5 turns 8/10 on 264354000z Fair Rite (or equivalent)


This portage (convertion/translation) is placed under the CERN Open source/ Open hardware Licence.

Kicad is an Opensource EDA software maintained by the European Reseach Center CERN (Conseil européen pour la recherche nucléaire)

The original work is protected by the TAPR Open Hardware licence

Munin and Hugin are the two "messenger" ravens of the Norse god Odin - just as Hermes is the messenger-god in Greek mythology, 
and the masterpiece of the OpenHPSDR architecture 

This LDMoS transistor-based amplifier brings speech over the great distances of the "Midgard" of the waves


# Work in progress
do NOT use these files as long as this footnote hasn't been deleted

A new and updated pcb and Gerber files set will be released... when I'll find some time 


