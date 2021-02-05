##  Portable Sell Only Mode Toggle V1.4  -  (Tuned for use with Binance market indicators)

### Windows Client:

####  Prerequisites:

1. 64bit Windows operating system 

2. Profit Trailer 

3. PT Feeder

#### Download and Run PSOMT

1. Download [PSOMT_WinClientV1_4_4.exe](./PSOMT_WinClientV1_4_4.exe) and [config.ini](./config.ini) to the same directory on your PT Bot local system.

2. Open the config.ini file with an editor and set your parameters

3. Run your PSOMT_WinClientV1_4_4.exe application

4. That's it!  When SOM signals from Trading View arrive, the client will receive and set your PTBot.

### Linux Client

####  Prerequisites:

1. 64bit Linux operating system 

2. Profit Trailer

3. PT Feeder

4. Python 2.7+

#### Download and Run PSOMT

1. Download [PSOMT_LinuxClientv1_4_3.bin](./PSOMT_LinuxClientv1_4_3.bin) and [config.ini](./config.ini) to the same directory on your PT Bot local system.

2. Open the config.ini file with an editor and set your parameters

3. Run your PSOMT_LinuxClientv1_4_3.bin

    `./PSOMT_LinuxClientv1_4_3.bin`

4. That's it!  When SOM signals from Trading View arrive, the client will receive and set your PTBot.

#### For slower Linux systems

1. Consider downloading the .zip file version with the support files in one directory. [PSOMT_LinuxClientv1_4_3.zip](./PSOMT_LinuxClientv1_4_3.zip)

2. Unzip and cd into PSOMT_LinuxClientv1_4_3 directory

3. Open the config.ini file with an editor and set your parameters

4. Run your PSOMT_LinuxClientv1_4_3.bin

    `./PSOMT_LinuxClientv1_4_3.bin`

** Bonus tip:  Consider installing screen and running this in a screen session

** apt-get install screen

** screen -S SOMT

** ./PSOMT_LinuxClientv1_4_0.bin

** ctrl+a ctrl+d to return to normal terminal

** screen -dr SOMT to return to screen session at any time

