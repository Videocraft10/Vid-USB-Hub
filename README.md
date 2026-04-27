# USB Hub: Videocraft Edition [WIP]
<img width="3840" height="2668" alt="USB Hub Main v2" src="https://github.com/user-attachments/assets/26379795-8718-4870-a766-5db08af34890" />
A custom made USB Hub with some cool little fetures created for Hack Club Fallout.

## Fetures

1. USB-A Input with 4 output USBs (2 A and 2 C)
2. Cool Keychain hole so you can take your hub around you with style :)
3. Easy to open, 3D printed case so you can admire the PCB
4. Red power LED to indicate when power is flowing though (great to make sure it ain't broke)
5. Secured by 4 easy to remove M2 screws if you want to update the case with a diffrent PCB with the same silhouette

## Why??
I created this project to expand my knowlage on how hardware works on a fundemental level and how it is created, through sourcing materials, and designing the PCB. Additionally I wanted to add my own custom spin on the classic USB Hub by adding some cool fetures that I would appreicate and use.

## The PCB
The PCB for this project was created within EasyEDA for easy parts and footprint intagration.


**The Schematic:**
<img width="1452" height="1028" alt="Screenshot 2026-04-26 140159" src="https://github.com/user-attachments/assets/d209de7c-60b7-4f69-8d54-8ca1f9b59b91" />

**The Circuit Borad:**


Front:
<img width="1137" height="579" alt="Screenshot 2026-04-26 140349" src="https://github.com/user-attachments/assets/737d0b10-033c-4cff-91c9-a7c10145c3cc" />



Back:
<img width="1151" height="575" alt="Screenshot 2026-04-26 140403" src="https://github.com/user-attachments/assets/f91e54dd-7763-4123-86fb-5cd0639ded90" />

## The Case
The case was designed using Blender, I choose this over CAD options due to my extensive knowlage and experience in the software.


**Full case**
<img width="1178" height="365" alt="Screenshot 2026-04-26 141623" src="https://github.com/user-attachments/assets/485e5645-3790-4071-86ee-5e94ef2eaa94" />
*This case feautres a key chain hole and a LED Hole*

**Bottom**
<img width="917" height="530" alt="Screenshot 2026-04-26 141639" src="https://github.com/user-attachments/assets/55e8611e-dc0d-425b-886c-4387e3511c02" />


**Top**
<img width="931" height="510" alt="Screenshot 2026-04-26 141649" src="https://github.com/user-attachments/assets/4d8de907-fbb6-4fea-9401-61a633569dd8" />


**Case open with PCB Inside**
<img width="1131" height="328" alt="Screenshot 2026-04-26 141707" src="https://github.com/user-attachments/assets/b97cdd27-b034-4ecf-974a-4afe93b02bf7" />
*This case also features a open swinging design to easily open the case though the 3D printed latch to see inside*

## PCB BOM
*Amount used is for 2 USB Hubs + Price quotes though EasyEDA PCBA*

| Item | JLCPCB # | Single Cost | Amount Used | Fees | Total Price |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 	<ins>USB Hub Chip</ins> | C2684433 | $0.2245 | 2 | Forced to order 5 minimum | $1.1225|
| Resistor 5.1k | C23186 | $0.0016 | 8 | None | $0.0128 |
| Capacitors 1uF | C15849 | $0.0078 | 16 | None | $0.01248 |
| Capacitors 100nF | C14663 | $0.003 | 6 | None | $0.018 |
| Power LED | C2286 | $0.0066 | 2 | None | $0.0132 |
| Resistor 330 | C23138 | $0.0016 | 2 | None | $0.0032 |
| <ins>Type-A USBs</ins> | C668591 | $0.0662 | 6 | Difficult Component Fee + $0.03 per. Plus Order must be a even number, forced to buy 8 (3 for 1 PCB = not even. Forced 4 for one = 8 for both) | $0.5296 |
| <ins>Type-C USBs</ins> | C2765186 | $0.066 | 4 | Forced to buy 5 | $0.33 |
| **PCB Price** | -------- | **PCBA Price + Fees** | **NOTES** | -------- | -------- |
| $2 | -------- | Setup Fee | -------- | -------- | $8.12 |
| -------- | -------- | Stencil | -------- | -------- | $1.52 |
| -------- | -------- | Components | -------- | -------- | $2.15 |
| -------- | -------- | Extended Components Fee | $3.04 per Extended Component (Underlined components are Extended)| -------- | $9.12 |
| -------- | -------- | SMT Assembly | $0.0016 Fee per solder point | -------- | $0.44 |
| -------- | -------- | Special Componet Fee (Type-A USB Difficult fee) | -------- | -------- | $0.24 |
| -------- | -------- | Nitrogen Reflow Soldering | -------- | -------- | $0.85 |
| Total Cost for PCB + 2 PCBA | -------- | -------- | -------- | -------- | $24.44 |
| Shipping Fee | -------- | -------- | -------- | -------- | $9.25 |
| Sales Tax | -------- | -------- | -------- | -------- | $2.23 |
| Grand Total | PCB (5) + PCBA (2) + Shipping + Tax | -------- | -------- | -------- | $35.92 |

## Build BOM

| Item | Discripton | Notes | Cost/Amount Used |
| -------- | -------- | -------- | -------- |
| 3D Printer PLA | Generic 3D printer PLA. Requires a 3D printer to use | Paid $8.34 for 1 kg | Aproxx 14g of filament = $0.12 |
| M2 Screws | -------- | -------- | -------- | 


## How to make one yourself!
*If you have no intention of modifying the case or PCB and you have a 3D printer, here are the steps to follow:*

1. Download your preferred case from the [Ready to Print](https://github.com/Videocraft10/Vid-USB-Hub/tree/main/Development%20Files/Case/Ready%20to%20Print%20Files) folder. Please note that the only case that is 100% polished and updated will always be [Videocraft USB Hub v0 Case Keyhole+LED Hole_Print.stl](https://github.com/Videocraft10/Vid-USB-Hub/blob/main/Development%20Files/Case/Ready%20to%20Print%20Files/Videocraft%20USB%20Hub%20v0%20Case%20Keyhole%2BLED%20Hole_Print.stl). Once downloaded (click the download button on the top right), open it in your 3D printer slicer of choice and export. I will be printing in a generic PLA on an Ender 3 Pro 3D printer, using the Super Quality preset, with tree supports enabled in the Cura Slicer settings.
2. Once you have the 3D print going, download the EasyEDA PCB files from the [PCB](https://github.com/Videocraft10/Vid-USB-Hub/tree/main/Development%20Files/PCB) folder in the GitHub. Please note that EasyEDA files are not supported on KiCad, but you might be able to get them to work with some workarounds if you really want to.
3. Import to EasyEDA and click Order.
4. It is recommended to select the PCB Assembly option to get it pre-assembled. I recommend getting 2 assembled.
6. There you go! Once your PCB arrives, smack it into the case and secure it with M2 screws in the 4 corners.
7. You are now a proud owner of the Videocraft USB Hub :)
P.S. If you dont want to use EasyEDA I have also included the Garber File export too! You can find it [here!](https://github.com/Videocraft10/Vid-USB-Hub/blob/main/Development%20Files/PCB/Gerber_VidUSBHUB.zip)

*If you **DO** have intentions of modifying the case or PCB, here are the steps to follow:*
1. All Blender files, including promotional files, are [here](https://github.com/Videocraft10/Vid-USB-Hub/tree/main/Development%20Files/Case/Blender%20Files).
2. Blender files were created in Blender 5.1.1.
3. NOTE: CAD files are converted from Blender, so they might not be well-organized or modeled correctly!!!
4. Download the EasyEDA files from above in the [PCB](https://github.com/Videocraft10/Vid-USB-Hub/tree/main/Development%20Files/PCB) folder in the GitHub.
5. Import into EasyEDA and modify to your heart's content!
