# DRAMCarrier

Convert an 8-4164 DRAM based Commodore to utilize 2 4464 DRAMs or an SRAM replacement system

## Options

Contrary to first glance, C64 motherboard models 250425 and 250466 do __NOT__ share the same 8 DRAM IC layout.  It's close, but just slightly off.  Therefore, there are two versions of this carrier design, one for each motherboard. 

There's no logic on the PCB, it just passively maps the 8 individual IO signals from each DRAM socket to one of the 2 4464 DRAM footprints.  Care has been taken to preserve the relative order, so D0 on the 4164 and D0 on the 4464 should be the same.

I designed this board to allow use of the new 2 Megabyte SRAM replacement 9which natively fits in 2 DRAM-IC motherboards, without having to create a brand new design.  This design is also useful to simply replace the 8 original 4164s with 2 4464 ICs, or a simple 64kB SRAM RAM replacement

I am considering creating a run of these designs.  Let me know if there is interest.

## License
Copyright (C) 2018  RETRO Innovations

These files are free designs; you can redistribute them and/or modify
them under the terms of the Creative Commons Attribution-ShareAlike 
4.0 International License.

You should have received a copy of the license along with this
work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

These files are distributed in the hope that they will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
license for more details.


