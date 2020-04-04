# FiO2mix - gas mixer device

## PURPOSE

The device described here is intended to mix two gasses.  One gas is injected into the device through the center port.  The other gas is drawn in through the side ports.  This is a form of injector pump - the flow of the first gas and the geometry creates suction which draws in the second gas.

The device is intended to operate at flow rates between 0 and 40 lpm at the outlet from a few psi in the center port and atmospheric pressure at the side port, and mixes the gasses at a ratio of roughly 1/3 center and 2/3 side (by volume at standard temperature and pressure) at most flow rates.  

In particular, the gasses may be oxygen and air, which would result in a 50% oxygen mix.

![Cross section](/fio2mix.PNG)

## DISCLAIMER

This is not a medical device, and is not intended to be used as part of a medical device.  It is especially not intended to be used in critical life support equipment.  It comes with ABSOLUTELY NO WARRANTY.  If you build it and use it, you do so at your own risk.  If you build devices incorporating this design and use them for any application, it is up to you to verify the performance is suitable for your application and complies with all applicable laws.

## CONSTRUCTION

In order for this device to work, it needs to have fairly precise tolerances of the channels where the gas flows.  In particular, any of the cross-sectional areas along the flow of gas (including the injector hole) should be within 5-10% of the cross section shown.  That means that the tolerances in some of the narrower areas are 0.05mm or preferably 0.02mm.  Additionally, the walls should be smooth, especially where the cross section is narrowest.  Deviations would result in a mix ratio different from 50%, and/or a mix ratio that varies with flow.

The parts can be injection molded, milled (with a very small cutter), or possibly 3D printed.  The easiest is injection molding plus a milling step for the side ports and thread.  If 3D printed, SLS or MJF are probably the best processes; the injector channel should be undersized in the print, and expanded with a milled steel pin of the right cross section in order to get the exact size and shape.

The two parts should be pressed against each other as shown.  They would be held in place by something else, presumably an inlet tube which is part of the body of another device.  Additional threads may be added to accomplish this.

The material is not critical.  However, if one of the gasses used is oxygen, the material must be oxygen compatible.  There are many materials which will SPONTANEOUSLY IGNITE in pure oxygen at moderate pressures.  It is up to you to VERIFY THE OXYGEN COMPATIBILITY of the specific material you use.  The following are some rough guidelines.  Probably okay: brass, stainless steels, nylon, (some) polycarbonates.  Probably NOT OK: carbon steels, aluminum, most other plastics.  

Make SURE there is no residual lubricant from machining or any other organic contaminants left on the parts.

## COPYRIGHT AND LICENSE

Copyright 2020 Alex Izvorski <aizvorski@gmail.com>

This Source (CAD files and other design materials) describes Open Hardware and is licensed under the CERN-OHL-S v2.

You may redistribute and modify this Source and make products using it under the terms of the CERN-OHL-S v2 (https:/cern.ch/cern-ohl).

This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source Location: https://github.com/aizvorski/fio2mix

As per CERN-OHL-S v2 section 4, should You produce hardware based on this Source, You must maintain the Source Location visible on the external case of the hardware or other product you make using this Source.

## DISCLAIMER OF WARRANTY, EXCLUSION AND LIMITATION OF LIABILITY

Additionally, the following important disclaimers from the CERN-OHL-S v2 license apply to all use (reproduced below for clarity).  Do not download or use these files unless you have read and agree with the following.

  6.1 DISCLAIMER OF WARRANTY -- The Covered Source and any Products
      are provided 'as is' and any express or implied warranties,
      including, but not limited to, implied warranties of
      merchantability, of satisfactory quality, non-infringement of
      third party rights, and fitness for a particular purpose or use
      are disclaimed in respect of any Source or Product to the
      maximum extent permitted by law. The Licensor makes no
      representation that any Source or Product does not or will not
      infringe any patent, copyright, trade secret or other
      proprietary right. The entire risk as to the use, quality, and
      performance of any Source or Product shall be with You and not
      the Licensor. This disclaimer of warranty is an essential part
      of this Licence and a condition for the grant of any rights
      granted under this Licence.

  6.2 EXCLUSION AND LIMITATION OF LIABILITY -- The Licensor shall, to
      the maximum extent permitted by law, have no liability for
      direct, indirect, special, incidental, consequential, exemplary,
      punitive or other damages of any character including, without
      limitation, procurement of substitute goods or services, loss of
      use, data or profits, or business interruption, however caused
      and on any theory of contract, warranty, tort (including
      negligence), product liability or otherwise, arising in any way
      in relation to the Covered Source, modified Covered Source
      and/or the Making or Conveyance of a Product, even if advised of
      the possibility of such damages, and You shall hold the
      Licensor(s) free and harmless from any liability, costs,
      damages, fees and expenses, including claims by third parties,
      in relation to such use.
