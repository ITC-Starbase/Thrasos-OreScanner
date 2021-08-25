# Thrasos-OreScanner
Modified Version of the Marmot MN Ore Scanner that stays on until results are displayed.

Configure Your Ore scanner with the following variable/property names:
```Scanner
I
R
M
V
Scan
Reset
```
[Scanner Properties](./images/ScannerConfig.png)

Put a button on your dash and set its name to "ScanBtn" and set ButtonStyle to 1  
Put a TextPanel on your Dash and name it: "LastScan"  
Paste the Script in a basic Yolol Chip and put the chip in a reader.  
Now when you press your ScanBtn the scanner will come on and remain on until you either turn it off or it successfully scans something!
Results will apprear like this:
```
LastScan:
Valkite
 10678 kv Ore
Bastium
 3456 kv Ore
```
[Scanner Properties](./images/ScanResults.png)

If you scan an asteroid it will add "Ore" or "Crystals" to the result text. If you scan an object it will omit these words