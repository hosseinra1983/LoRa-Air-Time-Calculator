# LoRa-Air-Time-Calculator

A Calculator that calculate the time on air of LoRa packet. Based on the formula in Semtech's
datasheet.

![Untitled](https://user-images.githubusercontent.com/49698257/210788675-6782643f-9268-4989-a23a-873b81482891.png)

TL;DR: This calculator is for pure LoRa modem, not for LoRaWAN. The demo is avaliable here.
LoRa is a exteremely powerful modulation method that can transmit data over 3km away. But one
of the down side of LoRa is the very long, up to a few milliesecond, symbol time. Result in the very
long time on air of the packet. Thus, calculating the total time on air is crutial for designing the
timing of upper layer protocol. However, the tool to calculate air-time provided by Semtech is only
avaliable on Windows operation system. Moreover, most of the calculator tha I had found aim to
LoRaWAN, not for pure LoRa. As a result, this little project was borned.
