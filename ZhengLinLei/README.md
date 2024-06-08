# Business Card PCB
A personal <b>Business Card</b> designed as a <b>PCB</b>. It contains an integrated <b>NFC</b> tag to share contact information wirelessly, and uses energy harvesting from NFC field to light up the LED circuitry!! 

<img width="1024" alt="pcb" src="https://github.com/ZhengLinLei/pcb-project-kicad/assets/77938581/861f89fe-74ba-472b-a12b-d38f5bae3e1b">
<img width="677" alt="3d" src="https://github.com/ZhengLinLei/pcb-project-kicad/assets/77938581/b81c75f5-6c18-49a0-9bae-9f78a673d548">


The heart of this PCB is the <b>NFC</b> controller IC, the <b>NT3H1101</b> from <b>NXP Semiconductors</b>.


<b>NFC (Near Field Communication)</b> is a short-range radio technology that enables communication between devices that are held in close proximity (< 10 cm). NFC systems are based on traditional High Frequency (HF) RFID, operating at 13.56 MHz

You can store your contact information, link to your portfolio, social media, and so on, the choice is Yours!!

The form factor is maintained as a standard credit/debit card, so you can carry it around normally in your wallet.

The Schematics and PCB design is done with <b>KiCAD</b>, the Vector graphics is done with <b>Inkscape</b>.

I used the "Bitmap to Component Convertor" tool built in <b>KiCAD</b> to import my custom font text, Logo, QR code, etc. I imported them as Soldermask and Copper layer so that they'll be visible with nice HASL/ENIG finish. 
My suggestion would be to minimize the use of silkscreen, as the silkscreen print might not be of good quality for complex graphics.

The NFC tag programming was done with Tagwriter app from <b>NXP</b>. This app has multiple options to write Website Links, Phone number, Email, etc into the NTAG IC which you can customize as per your requirement.

While doing the PCB layout, please make sure you import the <b>NFC antenna</b> correctly. NXP semiconductors have a detailed guide on different types of NFC antennas and their layout template. The rest of the circuit can be done as per your design. 
<br><br>
<i>Note : Please make sure there is no Copper under the Antenna region, Best option is to define a custom keepout area so that you won't mess up the Antenna performance.</i>
<br>

![pcball](https://github.com/ZhengLinLei/pcb-project-kicad/assets/77938581/f63c8e26-fc27-4cf9-92ad-c6797fa5b4da)

Feel free to use this as a reference and design your own Business Card PCBs!! Good Luck!! :)
 
