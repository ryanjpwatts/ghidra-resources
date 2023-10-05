# ghidra-resources
Scripts, guides and other useful resources I use for Ghidra

## Ghidra Launcher
Simple python script to run ghidraRun.bat, simply place into your ghidra folder. I turn this into an executable (to pin to my taskbar) using pyinstaller with the following command:
``pyinstaller ghidra.py -i "C:\Program Files\ghidra_10.3_PUBLIC\support\ghidra.ico" --onefile``
