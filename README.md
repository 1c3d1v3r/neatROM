## neatROM
neatROM is a replacement circuit for 24 &amp; 28 pin 8bit ROMs used in retro computers.\
It started as a basic flash based 2364 & 23128 replacement PCB. The idea was to have a neat design like my other projects neapPLA, neat8701 & neatSRAM. All the components are on the bottom side.\
Then I got the idea to add my Switchless JiffyDOS circuit to them. Feature creep kicked in so the current circuit also got features like reprogrammability, jumper selectable banks & VIC-20 character ROM support.  
<img src="/images/neatROM_2364.png" width="350">

### The 24pin version is called neatROM 2364. It supports:
- Use like a generic 2332 or 2364 replacement ROM.
- 16 jumper selectable 4/8kB banks.
- CS signal to pin 20. Also supports CS2 signal to pin 21 in VIC-20 character ROM mode.
- Reprogrammable with an adapter.
- Switchless Kernal Selector for VIC-20 & C64. Switch between two different Kernals with the Restore-key. Third Kernal selectable with a jumper.
- multiROM feature. Use only one neatROM 2364 in a C64 or VIC20 and replace missing ROMs with a connection to the missing ROM CS signal. In a long motherboard C64 one neatROM 2364 can replace all 3 ROMs (Basic, Kernal, Character). In VIC-20 one neatROM 2364 can replace both Kernal & Basic ROMS.
<img src="/images/neatROM_23256.png" width="408">

### The 28pin version is called neatROM 23256. It supports:
- Use like a generic 2764, 23128 or 23256 replacement ROM.
- 8 jumper selectable 16kB banks or 4 jumper selectable 32kB banks.
- CS signal to pin 22.
- Reprogrammable with an adapter.
- Switchless Kernal Selector for C64 & C128. Switch between two different Kernals with the Restore-key.
- multiROM feature. Use only one neatROM 23256 in a short motherboard C64 and replace missing character ROM with a connection to the character ROM CS signal. Usage in C128 is under study.

### See guide for further infomation:
[neatROM guide](docs/neatROM_guide.pdf)

### Licence
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><span property="dct:title">neatROM</span> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/1c3d1v3r/">Pasi Lassila</a> is licensed under <a href="http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>
