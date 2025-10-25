![Quansheng USB Charging Cradle](doc/images/powerbank-charge.jpg?raw=true "Quansheng USB Charging Cradle")

# Quansheng Charger Modification for USB Type-C Input
This is a mod for the original Quansheng (UV-K5) charging cradle so you can charge your radio using via USB--C

# Order at JLCPCB
Use the production files in the kicad folder to directly order at JLCPCB.

- Upload [GERBER-quansheng-usb-charger.zip](kicad/quansheng-usb-charger/jlcpcb/production_files/GERBER-quansheng-usb-charger.zip?raw=true) to JLCPCB.
- Choose 1.6mm PCB thickness, LeadFree HASL
- Enable "PCB Assembly" with "Economic" type. Select "Tooling Holes Added by Customer"
- Press NEXT button
- Upload [BOM-quansheng-usb-charger.csv](kicad/quansheng-usb-charger/jlcpcb/production_files/BOM-quansheng-usb-charger.csv?raw=true) and [CPL-quansheng-usb-charger.csv](kicad/quansheng-usb-charger/jlcpcb/production_files/CPL-quansheng-usb-charger.csv?raw=true) files. 
- Press Continue for the Error message of some missing parts (It's okay). 
- **Make sure all parts are selected for placement** and Press Next
- Check Placement and Press Next
- Select Production Description (e.g. Smart Products and Accessories -> Charger)
- Save To Cart 

# Assemble
1. Buy a new Quansheng UV-K5 charging cradle from AliExpress, if you want to keep your current one
  ![](doc/images/1_Quansheng-Cradle.jpg?raw=true)

2. Open up charging cradle
  ![](doc/images/3_Unscrew.jpg?raw=true)

3. Remove the original PCB, slightly push one of the hooks to the side with your finger for easier release
  ![](doc/images/4_Remove-PCB.jpg?raw=true)

4. Desolder the two large spring contacts (3 solder joints each) and the 3-Pin LED at the bottom e.g. using desoldering wick.
  ![](doc/images/5_Unsolder.jpg?raw=true)
  ![](doc/images/6_Unsolder-2.jpg?raw=true)

5. Get the freshly made Mod PCBs from JLCPCB
  ![](doc/images/7_Mod-PCB.jpg?raw=true)

6. Solder in the spring contacts from one of the previous steps
  ![](doc/images/8_Solder-Spring-Contacts.jpg?raw=true)

7. Insert the blind-plug in the upper shell half. Either use the 3D printed one (see ``Blind-Plug.stl``) or modify the original one by cutting it.
  ![](doc/images/9_Insert-Blind-Plug-3DP.jpg?raw=true)
  ![](doc/images/9_Insert-Blind-Plug.jpg?raw=true)

8. Feed in the spring contacts into their seating. Push down at the USB-C connector side until it is seated
  ![](doc/images/10_Push-In-PCB.jpg?raw=true)

9. Next, also push in the opposite side. Note that you might need to use a flathead screw-driver to help push the hook to the side a bit while pressing down.
  ![](doc/images/11_Insert-PCB.jpg?raw=true)

10. Lastly, put the LED in place and re-solder it.
  ![](doc/images/12_Solder-LED.jpg?raw=true)

11. Done! Test it and put the screws back in
