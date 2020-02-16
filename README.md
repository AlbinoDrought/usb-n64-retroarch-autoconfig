# Knockoff N64 Controller Retroarch Autoconfig

I bought a two pack of unbranded neon-seethrough USB N64 controllers.

One controller is orange and shows up to my computer as `DragonRise Inc. Generic USB Joystick`. 
The other is green and shows up to my computer as `SWITCH CO.,LTD. Controller (Dinput)`.
Neither of them worked in Retroarch off-the-bat.

## Using these configs

Copy the [`Sean_Orange_N64.cfg`](./autoconfig/udev/Sean_Orange_N64.cfg) and [`Sean_Green_N64.cfg`](./autoconfig/udev/Sean_Green_N64.cfg) files from this repository into your Retroarch udev autoconfig folder. 
On my machine this is located at `~/.config/retroarch/autoconfig/udev`.

## Unbreaking your old controller binds

If you're like me and have tried binding controls but just made it worse, remember to:

- remove any leftover autoconfigs. Mine were named after the device (`SWITCH CO.,LTD. Controller (Dinput).cfg`, `DragonRise Inc. Generic USB Joystick.cfg`) and were in my Retroarch autoconfig folder (`~/.config/retroarch/autoconfig/udev`)
- remove all manual binds for your knockoff controller (`Settings` -> `Input` -> `Port (whatever port) Binds` -> `Bind Default All`) and then **save the Retroarch config**. I saved my Retroarch config by performing a clean exit (System Menu -> Exit Retroarch)

## Rebinding the controller yourself

| Retroarch Buttons     | N64 Controller Buttons      |
|-----------------------|-----------------------------|
| B button \(down\)     | A                           |
| Y button \(left\)     | B                           |
| Start button          | Start                       |
| D\-Pad                | D\-Pad                      |
| A button \(right\)    | B \(might not be required\) |
| L button \(shoulder\) | L                           |
| R button \(shoulder\) | R                           |
| L2 button \(trigger\) | Z                           |
| Left Analog           | Joystick                    |
| Right Analog          | C buttons                   |
