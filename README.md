
#program to display the stats of a pc using the pyqt5 library \n
**author: WhiskyAKM (Patryk T) ** \n

app works with the following os:
windows 10 - partial support (only cpu cores, cpu usage, 
                              cpu base clock, ram, drives,
                              network, nvidia gpu)
linux - full support (cpu cores, cpu usage, cpu temperature, 
                      cpu current freq, usage, ram, drives, 
                      network, nvidia gpu, radeon gpu's)


supported gpu's:

nvidia gpu's: 
full support for all gpus newer than tesla 2.0 
tested on series: maxwell, pascal, turing 
radeon gpu's:
support for all gpus from HD7000 series
tested on series: HD7000, RX400

Needed modules:
pyqt5 (old TK version in /old)
psutil
cpuinfo
