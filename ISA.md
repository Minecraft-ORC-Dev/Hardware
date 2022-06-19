# OSRISA

The Open Source Redstone Instruction Set (OSRIS) is the main component of ORC-Dev. It is important to note that the instuction set should be as backwards as compatiable as possible.

## VERSION CONTROL

The latest version of the instduction set is

- [ ] Create insctruction set file

The version number shall be in the format <Major>.<Minor>.<Update>. 
  
  * The Major Version shall update only when backwards compatability is borken
  * The minor version number shall update when new capabilties are added
  * The Update Number shall update when changes in documentation (ie Rewording of Text or labels)
  
When the `Major` version number increments the `Minor` and `Update` numbers shall go to 0. When the `Minor` version number increments the `Update` value shall return to 0.

## Storage
  
All Versions of OSRIS shall be stroed in the ISA folder with file names corresponding to its version number using a `-` in place of the `.`. These files shall be in the `markdown` format.
