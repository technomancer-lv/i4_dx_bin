# i4_dx_bin
Bootstrap cote of PDP-11 compatible DX controller called I4 (И4).
This is code, read from soviet made 8" DX floppy drive controller. This 64 byte long code provides system booting from DX drive. First, it sends drive command to read sector 1 from track 1. Then reads drive buffer (128 bytes, one sector) to computers RAM starting from address 0. THen it jumps to address 0.

