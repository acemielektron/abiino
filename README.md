# abiino is a arduino compatible diy board which fits into a breadboard

<img src="/photo4.jpg"></img>
          
<p>abiino is inspired by <a href="https://www.adafruit.com/product/72">DC Boarduino</a> But unlike DC Boarduino abiino is designed as a single sided pcb for easy toner transfer and etching like most diy boards. </p>
<p>And unlike boarduino abiino has a 3.3v linear voltage regulator on board. Unfortunately on board linear voltage regulator S111733PI is not pin compatible with LM78XX so if you want to use abiino with 5v supply with a 7805 you need to change the layout a bit.
<p>Another difference easily seen is abiino does not have an icsp connector. On a single sided pcb making it is as compact as possible is already  challenge enough and i did not want make it any bulkier. Bootloader can be programmed after putting abiino on a breadboard. </p>
<p>I didn't want to make the board any larger than it already is so a 220 ohm resistor connected top 3.3v power supply is shared between green power led and red led connected to D13 so when red led lights green dims a bit.</p>
<p>An important issue to note is soldering breadboard headers in reverse side -although not impossible- is a bit challenging so if you want to build abiino keep that in mind.
<p>And lastly why abiino, abi (short for agabey) in turkish means elder brother. I designed this board for my little brother so it is abiino.


