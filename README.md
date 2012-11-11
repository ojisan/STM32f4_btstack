STM32f4_btstack
===============
1)This program is to use a USB BT dongle on STM32f4 discovery.
  also base on bybl/uubt.

2)About sample program of bt_spp.c
  bt_spp.c is sample program, both function of bt_spp_recive_callback() and  bt_spp_send() are important.
  handle SPP receiving and sending communication.
  <Receiving>
  a) Receiving ASCII char '0' from device side(android or PC), LED3(orange colour) on STM32f4 discovery turns on.
  b) Receiving ASCII char except '0' from device side, LED3 turns off.
  <Sending>
  c) Host side(STM32f4 discovery) send "Hellow" in each time.

3)USB BT dongle
   using a PLANEX dongle, but do not know model No. because no marking on dongle.
   purchased a long time ago.

4)Hardware
  No modification on STM32f discovery, only connection to USART2(PA2,PA3) serial line.
  monitoring with PC.

5)Software development
  using gcc-4.6.1 

lastly, I appreciate Mr.Bybl develop basic program and Mr. Nemuisan who is providing software development environment. 
I hope for everyone to use this program.

Best regards.
