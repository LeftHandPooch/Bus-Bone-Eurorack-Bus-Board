# PP-02 Bus-Bone
A 14-header Eurorack passive/filtered bus-board

<p>
    <img src="https://hylindevices.com.au/cdn/shop/files/PP02.png?height=157&v=1784184097" width="312.5" height="500" />
</p>

## WHY DID YOU MAKE THIS?
- Easy to build, good for practicing/learning circuit design.
- There is a great need for reliable, cheap busboards.

## WHY SHOULD I MAKE THIS?
- Aaffordable and reliable entry into the incredible world of modular.
- Ribbon cables are sketchy.
- Fully filled out supplier parts sheet so you don't have to spec anything - one-click order through JLCPCB.
- Intermediate friendly layout for those wanting to try SMD soldering.
- Lovely poochy paw prints + all the technical details on the silkscreen print.


## TECHNICAL DETAILS
- 4HP - 128.5mm (H) x 20mm (W) x ~50.5mm (D).
- +12V at 1.5A, -12V at 500mA and 5V at 1A, enough current to supply a small to medium eurorack case, just needs any old external 15-18V DC powerbrick.
- Reverse polarity protection - accidentally using a negative centre powerplug won't do any harm, shorting the supply briefly also fine. 
- Will run fine (hotter) on up to 25V DC but voltage will sag at input lower than ~14.7DC.
- Two 16-pin IDC headers on the board - use flying bus-cables or (ideally) passive busboards to distribute this to your modules.
- ISOLATED AND STIFF 12V RAILS!
- Resettable fuse (for transient spikes + inrush current) in-line with an optional 5V supply (pins 11+12 as per Doepfer standard).
- Pass-thru power jack internally/up the back of the device for power supply options. Allows use of one 15V powerbrick to supply multiple power modules.

## Changelog

### Bus Bone v0.1
- the original!
- drawn using EasyEda and subsequently broke the association between schematic and PCB. Darn. 
### Bus Bone v0.2
- moved components around very slightly to possibly prevent shorting of +5V rail near first header.




### Thanks and credits
My many friends and loved ones for tolerating/encouraging my passion for electronics, music and synths <3


Licensed under MIT license. 

Build and use at your own risk.

For further notes and build advice, see Basic BoM.txt
