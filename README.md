# i4_dx_bin
Bootstrap code of PDP-11 compatible RX controller called I4 (И4). ROM is located on I4 board itself. Code starts at address 177300 (octal), that's kind of standard address for bootstrap loaders.
This 64 byte long code provides system booting from 8" RX compatible drive. First, it commands drive to read sector 1 from track 1. Then it reads drive buffer (128 bytes, one sector) to computers RAM starting from address 0. Then it jumps to address 0 to start OS.
