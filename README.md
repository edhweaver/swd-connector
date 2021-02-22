

SWD Connector Circuit Board
--------------------------------------------------------------------------------

  This circuit board was designed to provide a standard SWD Connection for a
Proffie board installed inside a Light Saber chassis.  This board has the
following features incorporated into the design:
  * The SWD connector connects to a standard 2x5 IDC with 1.27 mm pitch
  * Circuits added to protect against signal noise on IDC cable
    * Decoupling capacitor on power
    * Reset Circuit to prevent unexpected reset
    * SWD Circuit added to keep initial signal levels for STM32 family
  * Mounting Holes added for easy installation onto Light Saber chassis

  PCB Revision is on the bottom of the PCB in silkscreen.  PCA Revision has a
silkscreen box to track BOM polulation.
