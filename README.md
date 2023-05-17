## neatROM
neatROM is a replacement circuit for 24 &amp; 28 pin 8bit ROMs used in retro computers.\
It started as a basic flash based 2364 & 23128 replacement PCB. The idea was to have a neat design like my other projects neapPLA, neat8701 & neatSRAM. All the components are on the bottom side.\
Then I got the idea to add my Switchless JiffyDOS circuit to them. Feature creep kicked in so the current circuit got also features like reprogrammability, jumper selectable banks & VIC-20 character ROM support.  
![Image of neatROM2364](/images/neatROM_2364.PNG)

The 24pin version is called neatROM 2364. It supports:
- Use like a generic 2332 or 2364 replacement ROM with 14 jumper selectable 4/8kB banks.
- Reprogrammable with an adapter. Pogo pins interface with missing pins like WE, OE, A13-16.
- Switchless JiffyDOS. Switch between two different kernals with the Restore-key.
- anyROM. Use only one neatROM 2364 in a C64 or VIC20 and replace missing ROMs with a connection to he missing ROM CS signal. In long motherboard C64 you can replace all 3 ROMs (Basic, Kernal, Character) with one neatROM 2364. In VIC-20 you can replace both Kernal & Basic ROMS with one neatROM 2364.
- Replace VIC-20 character ROM. Requires changing a solder short.


The 28pin version is called neatROM 23256. It supports:
- Use like a generic 2764, 23128 or 23256 replacement ROM. 8 jumper selectable 16kB banks or 4 jumper selectable 32kB banks.
- Reprogrammable with an adapter. Pogo pins interface with missing pins like WE, OE, A14-16.
- Switchless JiffyDOS. Switch between two different kernals with the Restore-key.
- anyROM. Use only one neatROM 23256 in a short motherboard C64 and replace missing character ROMs with a connection to the character ROM CS signal.
