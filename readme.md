# ZDE 1.6 (Z-System Display Editor) reconstituted source

Using the source code of [VDE
2.67](http://www.classiccmp.org/cpmarchives/cpm/Software/WalnutCD/enterprs/cpm/utils/s/vde267sc.lbr)
as a guide, I've reconstituted the source code for ZDE 1.6.

The source has been assembled with:

* Al Hawley's ZMAC: assemble as is.
* MicroSoft's M80: rename to ZDE16.MAC, un-comment the first two lines
  and assemble. Use RELHEX to create ZDE16.HEX.
* ZASM (Cromemco's ASMB): Rename to ZDE16.Z80 and assemble. Use RELHEX
to create ZDE16.HEX.

Use MLOAD to create ZDE16.COM.

There are still a couple of routines new to ZDE that I haven't figured
out (yet). But most of them have been sussed out.
