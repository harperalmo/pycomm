# Python Communication

THis is a project to get communication between a Rpi and 3 ATMega328p uprocessors.
The comm hardware will be the NRF24L01+ radio. Each chip will have it's own radio
and will be slaves to the RPi, i.e. the pi will initiate conversation. In fact,
communication will probably only go 1 way, pi to chip. 
