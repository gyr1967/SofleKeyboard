# SofleKeyboard
My own build of the Sofle Rev1 Split Keyboard
Original creator/repo https://josefadamcik.github.io/SofleKeyboard/

I bought the barebones kit from mechboards.co.uk/products/sofle-kit#, which comes with the 2 pcbs, top and bottom plates,
65 SMD diodes, MX hotswap sockets, 2 OLED screens, 2 TRRS jacks, 2 rotary encoders, 2 reset buttons and some accessories.
I used 2 pro-micro microcontrollers
I deliberately left out the rotary encoders on both sides as I wouldn't use them for anything.
My Build Process:
  Soldered SMD diodes 
  Soldered MX hotswap sockets
  Soldered reset switches
  Bridged OLED jumper pads
  Soldered pro-micros (this was quite tricky as this was my first time using a soldering iron, and I bridged some pins the first time round ;-;)
  Soldered OLEDs to cover pro-micros - this is all the soldering done
  
  Fitted Gateron Red switches
  Screw plates together, applying rubber feet to stop it slipping on my desk
  Fitted blank keycaps, to show off my touch typing ability :P
  
  I used QMK toolbox to flash VIA compatible firmware onto the pro-micros,
  which means I can use the wonderful VIA interface to remap the keyboard and set up macros etc
