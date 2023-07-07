# BLE_LED_AtomMatrix
BLE sample program for M5 Atom Matrix

The program makes M5 Atom Matris as BLE pheripheral.
It works two BLE characterestics:
* LED display
* Button Count
  
LED display characteristics is write port. Written 3byte are transferred to 25 LEDs in Atom Matrix.
Button count simply returns the counts of push button.


