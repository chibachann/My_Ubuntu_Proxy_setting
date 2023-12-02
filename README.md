# My_Ubuntu_Proxy_setting

https://abrupt-bike-7aa.notion.site/PC-Ubuntu-ff304d5052dd40f3a787d0bde51831f4?pvs=4


sudo nano ~/.bashrc

export PATH=/usr/local/cuda-12.3/bin:$PATH

export LD_LIBRARY_PATH=/usr/local/cuda-12.3/lib64:$LD_LIBRARY_PATH

Reading package lists... Done
Building dependency tree       
Reading state information... Done
Some packages could not be installed. This may mean that you have
requested an impossible situation or if you are using the unstable
distribution that some required packages have not yet been created
or been moved out of Incoming.
The following information may help to resolve the situation:

The following packages have unmet dependencies:
 cuda : Depends: cuda-11-1 (>= 11.1.0) but it is not going to be installed
E: Unable to correct problems, you have held broken packages.

