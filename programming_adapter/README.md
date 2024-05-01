<img src="/images/neatROM_programming_adapter_in_programmer_no_BG.png" width="408">

## Assembly

Programming adapter part list:
-	neatROM programming adapter PCB
-	J3: DIP socket, 24 position, double leaf spring
-	J4: DIP socket, 28 position, double leaf spring
-	J5, J6: Header SMD, 10 position 2 row, 1.27mm pitch, shrouded
-	J1, J2: Header through hole, 16 position, 2.54mm pitch
-	PR1, PR2, PR3, PR4, PR5: Test probe, R50-3C receptacle, P50-J1 probe
-	Flat cable with female 2x5 IDC connectors, 1.27mm pitch, 8cm

Test probe alignment tool part list:
-	Test probe alignment tool PCB
-	J1, J2, J3, J4: Header through hole, 2 positions, round pin, 2.54mm pitch

First assemble the test probe alignment tool. Use the programming adapter PCB as a jig for assembly. This helps to align the round pin headers.

<img src="/images/test probe alignment tool.PNG" width="408">

Next assemble the programming adapter. Solder the J5 & J6 headers. Notice the slot on the shroud.
Next solder the J3 & J4 IC sockets. If the sockets got a center ridge it need to be cut away.
Pin headers J1 & J2 are assembled from the bottom side.

Lastly solder the test probes. Place the test probe alignment tool into one of the IC sockets. Place the test probes from bottom side of the programming adapter PCB. Align the test probe straight into the alignment tool hole. Solder the test probe so the spring-loaded pin is at the same level as the alignment tool top surface. Repeat for other IC socket. Test probes are inside a receptacle and are replaceable. Just pull out the probe and replace it if needed. The model code is in the part list.

<img src="/images/Programming adapter top.PNG" width="408"><img src="/images/Programming adapter bot.PNG" width="408">
