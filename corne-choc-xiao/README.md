Here's some gerbers to get yourself into trouble with. You should be able to just drop the gerber zip file into JLCPCB. If you also want to have some of the 
PCBA done, I've included a BOM and CPL that has all the info for the diodes and the battery connector.

Please Note: This is a Choc spaced board. Only standard Choc caps will work on this board. For example, the Worklouder caps that fit choc switches are actually MX spaced. You'll need the 18x17mm caps, nothing 19x19mm will work.


****UPDATE 05/20/23 PLEASE READ*****

If you do not opt for PCBA, please note that the diode markers should face the square through hole connection.

It's not the end of the world if you go the other way, but the firmware has to be adjusted to account for that. I've created a new generic firmware based on the startup files I included that goes row2col instead of col2row.

****END UPDATE****

SVG files can be imported into Fusion 360 to create a sketch to start the case making fun. They are pulled from the PCB Edge Cuts.

***EDIT***

04/14/23 Updated ZMK starter files to work with latest ZMK updates.

04/09/23 Adding some links to parts and pics.

More pics to look at for guidance on building: https://imgur.com/a/QKp5wG5

Power switches: https://www.amazon.com/gp/product/B0826XVZ8M/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1

XIAO BLE: https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html

Batteries: https://www.amazon.com/HAC-006-BPJMX-C0-Battery-Nintendo-HAC-015-Controller/dp/B08L3FWXS4/ref=sr_1_4?crid=2YZOVGUSZ9RTX&keywords=HAC-006&qid=1679153921&s=electronics&sprefix=hac-006%2Celectronics%2C110&sr=1-4

Nice!View: https://typeractive.xyz/products/nice-view

Mill-Max pins (used on Nice!View): https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/4147392?s=N4IgTCBcDaIKIBECMSDMAWAtAOQSAugL5A

Low profile sockets (used with Nice!View): https://www.digikey.com/en/products/detail/aries-electronics/40-0518-10/261892

03/12/23 added in ZMK starter files. These should go in the boards/sheilds directory of your ZMK branch. Then go in and modify the build.yml to include it.

If you get stuck on anything, the ZMK discord is very helpful. 

https://zmk.dev/

