!July2026 just quick, I will add my own photos but I'm chucking up enough right now for others to give this a go. DON'T superglue, just tape, TTP223 modules have some adjustments that can be made, some mods for sensitivity etc - I'll try and document that soon (hint: foil under button, or you can run wire around outside edge of desired touch area and attach one end to pin 3 of the IC... but I'll get in to this some time)


Minimal effort and resources required, I'm not a fan of 3D printing in general but I'm in the middle of several different controllers and thought this might be of a suitable level for some people I know, and some of those only have very small 3d printers. This will fit on the smallest printers available typically sold to kids and schools.
I have PCBs coming in future using touch control IC's, but pre made modules are cheap

Requires: 6x TTP223 touch sensor (10 on AliExpress is £1, but Amazon UK has them next day at £10 for 100!) - 2x tactile switch (4.5x4.5mm - I get a pack of 50 from Ali for around £1, Amazon has boxes with selection of heights for alright prices) - 1x RP2040 Zero (They're knock-offs and not legit Waveshare but when they're up on Ali for £1 each I stock up, if you want next day delivery Amazon has them in packs of 3 for £9)

3D printer and filament (change colours of filament to contrast between case and pads etc). Soldering stuffs. some wire.

Some tape to hold stuff temporarily for testing, superglue when you're ready to commit.

<img width="1600" height="722" alt="drummania_ttp223toy-stl-" src="https://github.com/user-attachments/assets/1e2a8786-0b82-4a8b-a5c6-f08fd396564a" />

on the TTP223 modules you can join all the grounds and connect them to ground on the rp2040, same with voltage. the i/o connection from each TTP223 goes to a GPIO pin on the RP2040, then you can use GP2040-CE firmware to set it up.

