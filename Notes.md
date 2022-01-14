# Colors:
Light: #d3cdc3ff
Mid:   #71624cff
Dark:  #453824ff

# Colors (Old):
Light: #bbb4a1ff
Mid:   #7f7059ff
Dark:  #453824ff

# New Sizes:
* Gear: 600x600
* Card: 800x1240
* Settlement Event: 1200x2000
* Settlement Location: 1024x2048

** Gear: 600x600
* Card: 800x1240
* Settlement Event: 1200x2000
    1230x2048
* Settlement Location: 747x1513
    1024x2048
* Rules: 1500x1159


2.0254350736278447121820615796519
1275x2475
1.9411764705882352941176470588235


# Scan Crop Sizes
*** BOOKMARK: -> 1783x3383 -> 1054x2000 ***
*** SETTLEMENT EVENT: 2030x3383 -> 1200x2000 ***
*** SETTLEMENT LOCATION: 2350x4760 -> 1400x2836 ***
*** CARD: 1310X2030 -> 800x1240 ***
*** GEAR: 1170x1170 -> 600x600
1 mm = 14.285714285714285714285714285714

2500x1818 -> 113.63636363636363636363636363636 x 113.625

Banner: 4mm from left, 7mm wide, 11mm tall = 57/100/157
Title: 6mm from top = 88
Subtitle: 11mm from top = 157
FA Art: 17mm from top, 32mm high = 243/457
Disorder Head: 15mm from top, 28.5mm tall = 214/407
Disorder Text = 4mm from bottom of head = 57
FA Text: 5mm from bottom of art
Margin: 5mm = 71


# Deck Sheet Dimensions
Card: 800 x 1240, 5x3 = 4000 x 3720 -> 4096 x 3809.28 (+2.4%)
Gear: 600x600, 7x7 = 4200x4200 -> 4096x4096 (-2.5%)
Settlement Event: 1200x2000, 3x2 = 3600x4000 -> 3686.4 x 4096 (+2.4%)
Settlement Location: 1400x2836 - 3x1 = 4200x2836 -> 4096 x 2765.7752380952380952380952380952 (-2.4%)
4096    
    3 = 1365.333...
    4 = 1024
    5 = 819.2
    6 = 682.666...
    7 = 585.14285714285714285714285714286
    8 = 512

sloc: 4.814575 x 9.751407
	332x672
	338 x 672
sevent: 3.548889 x 5.914705
	244x408
card: 2.697159 x 4.18051
	186x286
68.961451660803089473034403978408

# Scanning, Importing, and Filtering
- Raw scan
- Gimp: G'MIC-Qt -> PhotoComiX Smoothing Filter -> 0.25 Sharpness, all other settings default
    I can do up to 3 images in parallel before overloading my system
- Gimp: Adjust color levels: black to just before first black, white to the "valley" between the two "white spikes" (the actual scanned white and the background white)
- Gimp: Cut individual card and paste into separate pre-sized window
- Gimp: Rotate to correct orientation
- Gimp: Center image
- Gimp: Scale down image
- Gimp: Sharpen filter: Amount = 0.3
- Gimp: Fix any blemishes (hair, dust) using Blur tool
- Export to png
- Undo actions up to the Scale Down to reset canvas size, move to next scanned image
