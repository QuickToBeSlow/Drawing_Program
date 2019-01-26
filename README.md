# Drawing_Program
INFORMATION:
Made in pure HTML and javascript.
Although this tool isn't pretty, it allows for the user to create Images and Animations from scratch in base64.
TIPS:
1. Use inspect element to copy the base64 data if you want to use the drawn image(s) elsewhere.
2. Using the Alpha tool allows for a nice color gradient and/or shading (0.01 works really well).
3. Use the TAB key to go to the textboxes to edit them. You may use your mouse, but this might accidentally draw a circle depending on the circle's size.
TOOLS:
A: Enable/Disable drawing loop (good for touchpad users).
L: Write ImageData over current frame.
C: Set the image to a transparent background.
<- and -> keys: Switch between frames to save/override ImageData.
MOUSEDOWN: Draw a circle at the current mouseposition or not if the A key is enabled.
MOUSEDRAG: Same thing as MOUSEDOWN but this will continuously draw circles where the mouse is.
TEXTBOXES:
1. Size of the circle to draw. 1-Infinity.
2. Red value of the RGBA circle. 0-255.
3. Green value of the RGBA circle. 0-255.
4. Blue value of the RGBA circle. 0-255.
5. Alpha value of the RGBA circle. 0-1 (1 = 100% visibility, 0 = 0% visibility).
