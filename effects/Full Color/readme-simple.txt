FullColor Effect
(This is a .txt version of the README.md file)

Contributors: YohananDiamond, EX64 (Shadow Rift)

This effect replaces all the non-transparent pixels of a sprite with a color specified by three values: (R)ed, (G)reen, and (B)lue.

| Parameter | Type  | Range      |
| --------- | ----- | ---------- |
| color_r   | float | 0.0 to 1.0 |
| color_b   | float | 0.0 to 1.0 |
| color_g   | float | 0.0 to 1.0 |

As these values range from 0.0 to 1.0 and not from 0 to 255, you should divide any normal 0-255 value by 255 to get the number to input on the parameters. A more detailed explanation is inside the "example.mfa" file.

INSTALLATION

First of all, if you haven't already, head to the "releases\" folder and download the latest .zip file of the effect.
After that, unpack the .zip and move the files FullColor-float.fx and FullColor-float.xml to your effects folder:
- For who bought Clickteam Fusion via the Clickteam website: "C:\Program Files\Clickteam Fusion\Effects"
- For who bought Clickteam Fusion via Steam: "C:\Program Files\Steam\steamapps\common\Clickteam Fusion\Effects"

Any suggestions and improvements for this effect are greatly appreciated! ~ YohananDiamond