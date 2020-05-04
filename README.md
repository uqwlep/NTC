# STM32 NTC Library

* http://www.github.com/NimaLTD   
* https://www.instagram.com/github.nimaltd/   
* https://www.youtube.com/channel/UCUhY7qY1klJm1d2kulr9ckw   

reference https://arduinodiy.wordpress.com/2015/11/10/measuring-temperature-with-ntc-the-steinhart-hart-formula/

How to use this Library:
* Enable your ADC on cubeMX.   
* config "ntcConfig.h" file.
* Enter your adc value ntc_convertToC(adcValue) and get temperature.

     VREF
     _____
      |
      |
      /
      \
      /   R REF
      \
      |
      |   V ADC
      |
      /
      \
      /   NTC
      \
      |
      |
      |
    ______
     GND
