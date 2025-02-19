Color Trigger - C++

Color Trigger - is a simple utility program written in C# that allows you to perform an action when a change in color is detected at the cursor's position. This can be useful for automating tasks or interactions in applications or games where color changes signify specific events.

Usage
Threshold Setting: When you run the program, it will prompt you to enter a threshold value (from 4 to 20). This threshold represents the maximum allowed difference in color values between two consecutive pixel checks for a change to be detected. Higher values allow for more color variation before triggering an action.

Bind Selection: After setting the threshold, you'll be prompted to select a bind (X, F, LALT, Mouse3, Mouse4). This bind determines the key or mouse button that, when pressed, triggers the color change detection.

Running the Program: Once configured, the program will continuously monitor for the specified key or mouse button press. When the trigger key/button is activated, the program will compare the color of the pixel at the cursor's position before and after the key/button press.

Color Change Detection: If the color difference between the two pixels exceeds the threshold, the program will perform an action (left mouse button click). This can be customized to perform other actions as needed.

Threshold Adjustment: You can adjust the threshold during runtime using the "UpArrow" and "DownArrow" keys. Increasing the threshold makes color changes less sensitive, while decreasing it makes them more sensitive.

Example Key Binds
X: Hold down the "X" key to trigger color change detection.
F: Hold down the "F" key to trigger color change detection.
LALT: Hold down the left Alt key (LALT) to trigger color change detection.
Mouse3: Hold down the middle mouse button (Mouse3) to trigger color change detection.
Mouse4: Hold down the fourth mouse button (Mouse4) to trigger color change detection.
Dependencies
The program uses the InputSimulatorStandard library to simulate mouse input.
It relies on Windows API functions for keyboard and mouse input monitoring.
Disclaimer
This program is intended for educational and experimental purposes. Be aware of the legal and ethical considerations when using automation tools in any software or game. Use responsibly and at your own risk.

Example of showing work
 CSGO.mp4 
Author
DesirePro
Discord: desirepro
Feel free to customize this README with your contact information, usage guidelines, and any additional features or improvements you make to the program.
