# Collection of mnemonic mappings for various thtk programs
Usage: add `-m mapfile` to the command line parameters when compiling/decompiling (this is the common for all thtk programs). `mapfile` is filename of the appropriate mnemonic map (refer to the list below). Do note that ECL mappings are in the new format, and won't work in old versions of thecl.  
  
As of now, this repository contains mappings for ECL and ANM, as thecl and thanm are the only programs that actually support them currently (not the latest releases; thecl has to be built from a reasonably-recent branch, and thanm has to be built from the `thanm-new-spec-format` branch as of writing). For thanm, mappings are in the `anmmap` folder, and for thecl in `eclmap`.  
  
**eclmaps**:
- TH06-TH07 - none at the moment
- TH08 - `th08.eclm`
- TH09-TH95 - none at the moment
- TH10-TH11 - `th11.eclm`
- TH12-TH128 - `th12.eclm`
- TH13 - `th13.eclm`
- TH14-TH143 - `th14.eclm`
- TH15 - `th15.eclm`
- TH16-TH165 - `th16.eclm`
- TH17 - `th17.eclm`
- alcostg - untested, but `th11.eclm` should be mostly fine  
  
**anmmaps**:
*Note: anmmaps are early WIP and instruction names could change between versions without warning.*
- TH06-TH09 - none at the moment
- TH09.5-TH12.8 - `v4.anmm`
- TH13-TH17 - `v8.anmm`
