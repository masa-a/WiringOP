# WiringOP for OrangePi Zero
This is a modified WiringPi for OrangePi Zero. Since original WiringOP is not fully compatible with OrangePi Zero, GPIO mapping has been modified for OrangePi Zero.
Only use wiringPiSetupPhys() to setup WiringOp because only Pyhs mapping is valid.

Not fully tested but so far ISR on 6 pin(UART2_TX/PA00) doesn't work.

## Installation
    cd WiringOP
    chmod +x ./build
    sudo ./build


