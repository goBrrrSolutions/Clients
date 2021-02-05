##  Portable Sell Only Mode Toggle V1.4

### Windows Client:

####  Prerequisites:

1. 64bit Windows operating system 

2. Profit Trailer Bot

3. PT Feeder

#### Download and Run PSOMT

1. Download [PSOMT_WinClientv1_4_0.exe](./PSOMT_WinClientv1_4_0.exe) and [config.ini](./config.ini) to the same directory on your PT Bot local system.

2. Open the config.ini file with an editor and set your parameters

3. Run your PSOMT_WinClientv1_4_0.exe application

4. That's it!  When SOM signals from Trading View arrive, the client will receive and set your PTBot.

### Linux Client

####  Prerequisites:

1. 64bit Linux operating system 

2. Profit Trailer Bot

3. PT Feeder

4. Python 2.7+

#### Download and Run PSOMT

1. Download [PSOMT_LinuxClientv1_4_0.bin](./PSOMT_LinuxClientv1_4_0.bin) and [config.ini](./config.ini) to the same directory on your PT Bot local system.

2. Open the config.ini file with an editor and set your parameters

3. Run your PSOMT_LinuxClientv1_4_0.bin

    `./PSOMT_LinuxClientv1_4_0.bin`

4. That's it!  When SOM signals from Trading View arrive, the client will receive and set your PTBot.

** Bonus tip:  Consider installing screen and running this in a screen session

** apt-get install screen

** screen -S SOMT

** ./PSOMT_LinuxClientv1_4_0.bin

** ctrl+a ctrl+d to return to normal terminal

** screen -dr SOMT to return to screen session at any time

