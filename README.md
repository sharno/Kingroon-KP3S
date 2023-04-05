I got a Kingroon KP3S 3.0 printer, still trying to figure things out but here's the resources that I found

# Official videos:
- Assembly for version 3.0 (The video I got to from google was outdated): https://www.youtube.com/watch?v=XR0hI4pVvlY
- Bed leveling tutorial: https://www.youtube.com/watch?v=cpsmau0TnVo
- How to add filament sensor: https://www.youtube.com/watch?v=mHwWJhEbGF4
- How to replace main board: https://www.youtube.com/watch?v=LBa8X6U1Y_w
- How to replace the heating tube and the thermistors sensors: https://www.youtube.com/watch?v=W7K4EUnCy6E
- How to replace the cooling fan: https://www.youtube.com/watch?v=w-5YFIYymcE
- How to replace Titan extruder: https://www.youtube.com/watch?v=_Ob6vjfb7UQ
- Stepper motor installation:
  - https://www.youtube.com/watch?v=Xf40ofJEuYg
  - https://www.youtube.com/watch?v=_jZ-SE-kS0g
  - https://www.youtube.com/watch?v=Zo79jQX6qJA
- Nozzle installation:
  - https://www.youtube.com/watch?v=w-NXUCSCNlg
  - https://www.youtube.com/watch?v=kBYjaQFhSSA
- Nozzle clogging troubleshooting: https://www.youtube.com/watch?v=e6X0Mhzdudc
- Belt installation:
  - https://www.youtube.com/watch?v=WN9NfEslSPI
  - https://www.youtube.com/watch?v=D2j-rojJPbw
  - https://www.youtube.com/watch?v=COBy9IvdeTE
- How to prepare Klipper firmware: https://www.youtube.com/watch?v=AXshlSearbs
- How to setup octopi: https://www.youtube.com/watch?v=Q2hflwNQiSI
- How to add 3d touch (auto leveling): https://www.youtube.com/watch?v=s2ZiibBKVKI
- How to add laser engraving: https://www.youtube.com/watch?v=nqGEDbwFWtI
- How to make a timelapse video with DSLR: https://www.youtube.com/watch?v=quforfN6YSM
- 3D printable upgrades:
  - https://www.youtube.com/watch?v=rxJvDy2HzDw
  - https://www.youtube.com/watch?v=t6ASPpqH1zM

# Slicers:
## PrusaSlicer profiles:
- Official from Kingroon: https://drive.google.com/drive/folders/17OpJVyVZrWrf6uncm1H41P58TKElGBk0
- Official video from Kingroon:
  - https://www.youtube.com/watch?v=pAzWunhUIUQ
  - https://www.youtube.com/watch?v=x8BLwpfhZ0g
- It seems that there are tiny differences between the config from the video and from the files on google drive. But given that the files are a bit more recent, I think they should be the closest to perfect.
- I tried the video settings and I get some stringing in my prints (I might play with retraction settings and see if I can make it disappear)
- I'll update it here if I find that either is better than the other

## Cura profile:
- It has a default profile inside, when I tried it out, I got good prints but a visible Z scar most of the time
- PrusaSlicer made the Z scar disappear but got the stringing issue to deal with
- I'll try to see what are the differences between the official PrusaSlicer config and what Cura has by default and hopefully file some tickets to fix the Z scar.

# Mods:
- Y belt tensioner: https://www.printables.com/model/199016-kingroon-kp3s-y-belt-tensioner
- Z linear rails (extend the Z axis): https://www.printables.com/model/204470-kingroon-kp3s-z-axis-linear-rails
- Spool holder:
  - https://www.thingiverse.com/thing:4890598
  - https://www.thingiverse.com/thing:4600120
- Power Supply stand:
  - https://www.thingiverse.com/thing:4766628
  - https://www.thingiverse.com/thing:4671163
- Thumbwheel lock: https://www.thingiverse.com/thing:4893883
- Base:
  - https://www.thingiverse.com/thing:4893306
  - https://www.thingiverse.com/thing:5173303
  
more:
- https://www.thingiverse.com/search?q=KP3S+&page=1&type=things&sort=relevant
- https://www.printables.com/search/models?o=popular&q=kp3s
- https://thangs.com/search/kp3s?scope=all

From reddit:
- For the KP3S not PRO you can do the following:
- bed level locks https://www.thingiverse.com/thing:4893883
- bed cable https://www.thingiverse.com/thing:4942388
- z wire strap https://www.thingiverse.com/thing:4942374
- PSU stand https://www.thingiverse.com/thing:4766628
- spool holder https://www.thingiverse.com/thing:3969208
- fan duct https://www.thingiverse.com/thing:4942470
- 3d touch mount https://www.thingiverse.com/thing:5197271
- changed to latest marlin firmware and used this screen case https://www.thingiverse.com/thing:5319887
- replaced fans with Noctua 40x20 with some extra airflow
- removed the bed leveling knob and only use the 3D touch. And I can freely change from metal PEI to glass to other bed surfaces without changing the Z-offset.

