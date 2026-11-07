# DJI RC-N3 (or RC-N1) as Xbox Gamepad

This is a program that connects to your DJI Drone Remote Controller (RC-N3 or RC-N1) and emulates a **virtual Xbox 360 Controller** on Windows. 
It reads the stick positions and sends them to Windows via XInput, making it perfectly compatible with any PC flight simulator (FPV.SkyDive, Liftoff, Velocidrone, DRL, etc.) or video game.

<img height="400" src="DJI-RC-N1-Remote-Controller.png" width="400"/>

-----------------------------------------------------------------------------
## Prerequisites & Installation

1. **DJI Drivers:** Install **DJI Assistant 2 (Consumer Drones Series)** to get the correct USB COM drivers for the controller. Open it once, then close it.
   https://www.dji.com/downloads/softwares/dji-assistant-2-consumer-drones-series
2. **ViGEmBus Driver (ESSENTIAL):** You must install the ViGEmBus driver, otherwise the virtual gamepad will not be created. 
   Download and install it from the official releases: https://github.com/nefarius/ViGEmBus/releases (download the `.msi` file and **restart your PC** after installation).
3. **Python 3.9 or 3.x:** Make sure Python is added to your system PATH.

Open your terminal and install the required Python packages:

```bash
pip install vgamepad
pip install pyserial
