# Official Non Secure firmware images for Ledger Nano S 

This directory contains the deterministic hex files and signed image of the non secure (STM32) firmware images for Ledger Nano S 

Unless different instructions are provided for a specific release, you can reflash the images using JTAG or in bootloader mode : 

  - Turn on Ledger Nano S with the left button pressed, until "Bootloader" is displayed
  - Use python -m ledgerblue.loadMCU --target 0x01000001 --fileName token.loadable.signed_perso_11.hex    

