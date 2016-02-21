---
layout: post
title:  "Esquema do PIC16F690 e PIC18F4550"
subtitle:
date:   2015-11-08 23:34:01
categories: [microcontroladores]
visible: true
---

Ano passado criei um desenho do PIC16F690 e do PIC18F4550 através de texto para colocar nos meus códigos e facilitar a programação. Como várias pessoas pediram, pensei que seria interessante postar aqui.

PIC16F690:
{% highlight ruby %}
                      PIC16F690
                      ---------------
                  ---1|VCC        GND|20---
                  ---2|RA5        RA0|19---
                  ---3|RA4        RA1|18---
                  ---4|RA3        RA2|17---
                  ---5|RC5        RC0|16---
                  ---6|RC4        RC1|15---
                  ---7|RC3        RC2|14---
                  ---8|RC6        RB4|13---
                  ---9|RC7        RB5|12---
                 ---10|RB7        RB6|11---
                       --------------
{% endhighlight %}

PIC18F4550:
{% highlight ruby %}

      PIC18F4550
     -----------------------------------------------
 ---01|MCLR/VPP/RE3                      RB7/KBI3/PGD|40---
 ---02|RA0/AN0                           RB6/KBI2/PGC|39---
 ---03|RA1/AN1                           RB5/KBI1/PGM|38---
 ---04|RA2/AN2/VREF-/CVREF        RB4/AN11/KBI0/CSSPP|37---
 ---05|RA3/AN3/VREF+                 RB3/AN9/CCP2/VPO|36---
 ---06|RA4/T0CKI/C1OUT/RCV           RB2/AN8/INT2/VMO|35---
 ---07|RA5/AN4/SS/HLVDIN/C2OUT  RB1/AN10/INT1/SCK/SCL|34---
 ---08|RE0/AN5/CK1SPP      RB0/AN12/INT0/FLT0/SDI/SDA|33---
 ---09|RE1/AN6/CK2SPP                             VDD|32---
 ---10|RE2/AN7/OESPP                              VSS|31---
 ---11|VDD                               RD7/SPP7/P1D|30---
 ---12|VSS                               RD6/SPP6/P1C|29---
 ---13|OSC1/CLKI                         RD5/SPP5/P1B|28---
 ---14|OSC2/CLKO/RA6                         RD4/SPP4|27---
 ---15|RC0/T1OSO/T13CKI                 RC7/RX/DT/SDO|26---
 ---16|RC1/T1OSI/CCP2/UOE                   RC6/TX/CK|25---
 ---17|RC2/CCP1/P1A                         RC5/D+/VP|24---
 ---18|VUSB                                 RC4/D-/VM|23---
 ---19|RD0/SPP0                              RD3/SPP3|22---
   ---20|RD1/SPP1                              RD2/SPP2|21---
       ----------------------------------------------

{% endhighlight %}