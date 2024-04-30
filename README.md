# RPI-5-PCIE-GPU
Documentation of my work in getting an MSI Rx 580 to work on a Raspberry Pi 5

# Things I've completed:
1. Designed and manufactured a PCIE x16 adapter for the RPI 5
  - This is still being debugged currently. My adapter seems to work for an geforce 8600gt yet not the RX 580 unless I use a mining adapter. This is being investigated.
  - Initially used a generic 16 pin fpc cable however this resulted in an unstable connection. As a result I upgraded to [this](https://shop.pimoroni.com/products/pcie-flex-cable-for-nvme-base-and-raspberry-pi-5?variant=41449370910803) cable but it requried modifications to both my board (installing the fpc connector backwards) and to the cable itself (cutting off the extra two unneeded connectors). 
  - I initially tried to make the PC PSU turn on automatically however I was unsuccessful in doing so. I ended up shorting the two required pins to force the PSU to always be on.


# Tasks:

1. Hardware:
   - Creating an updated version of the board once I can fix/debug all problems with my current design
   
2. Software:
  - Installing Drivers
  - Running Programs to test functionality. (Box86/64)
