# CRTC 6845 register quick reference (CPC)

Standard CPC CRTC (type 0) register set, as used by 16K/64K machines:

- R0 horizontal total
- R1 horizontal displayed
- R2 horizontal sync position
- R3 sync widths (HSYNC/VSYNC)
- R4 vertical total
- R5 vertical adjust
- R6 vertical displayed
- R7 vertical sync position
- R8 interlace and skew
- R9 maximum raster
- R12/R13 start address (screen base)

Selected via I/O port #BCxx (select) and #BDxx (write), or via
OUT (C),r / OUT (C),data pairs in assembly.
