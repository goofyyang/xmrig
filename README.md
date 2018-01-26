# xmring miner

Miner support xmr krb etn and all cryptonote algorithm coins. Miner default with no fee</br>
usage:</br></br>

for cpu</br>
cpu64.exe -o pool.minexmr.com:443 -u your_wallet_address -t 20 -k --donate-level=0</br>
cpu32.exe -o pool.minexmr.com:443 -u your_wallet_address -t 20 -k --donate-level=0</br></br>
notice: the -t 20 means how many threads you should run (always the -t should set your cpu L3 cache size divided by 2) </br>
For example: your cpu's L3 cache is 40Mb and cpu has 24 thread then -t should set 20 not 24 </br> </br>
for nvidia</br>
nvidia.exe -o pool.minexmr.com:443 -u your_wallet_address -k --cuda-max-threads= 32 --donate-level=0</br></br>
notice: if nvidia cannt run you shoud lower the cuda-max-threads ,the default command is 32 threads</br>

for amd</br>
amd.exe -o pool.minexmr.com:443 -u your_wallet_address -k --donate-level=0 </br> </br>

All of the above command lines you can add -B parameter to run in the background


