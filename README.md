# i4_dx_bin
Bootstrap cote of PDP-11 compatible RX controller called I4 (И4).
This is code, read from soviet made 8" RX floppy drive controller. This 64 byte long code provides system booting from RX drive. First, it sends drive command to read sector 1 from track 1. Then reads drive buffer (128 bytes, one sector) to computers RAM starting from address 0. Then it jumps to address 0.

