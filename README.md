# UltraBoyColor
 A modernized, feature-packed Gameboy Color replacement board!

---

## Purpose of this repository
As of creating this, I am currently in the process of finishing the fifth revision of the Ultra Boy Color board, which hopefully will be the final revision. I am not ready to make the files public, so for now the purpose of this repository is to serve as a comprehensive feature list and guide to building a unit with a fully assembled board provided by me. I will eventually update this to include tips on how to assemble a DIY Ultra Boy Color kit, and possibly even the files so you can order your own boards and modify the circuit if you want!

---

### Features
- Louder amplifier with cleaner output (less interference) and better frequency response (more bass than the original GBC). Demo audio can be found on my YouTube channel on [this playlist](https://www.youtube.com/playlist?list=PLDhmFPH88AsarVaGamZC6ayKIjXoZndGF). You may want to turn your volume down; there are also flashing images (they are oscilloscope views.)
- Ability to switch between using AAs and a LiPo on the fly by using a switch in the battery bay (left for LiPo, right for AA)
- USB-C safe charge and play with a LiPo battery (blue charging light turns off when finished charging- takes 3-4 hours to recharge a 1200mAh battery)
- USB-C powers system with power switch in "off" position when in AA mode
- 2-stage battery indicator with independently adjustable thresholds for both battery types
- Compatible with clone CPU from a GB Boy Colour, which can run at the correct speed and utilize infrared with new replacement parts
- Tactile buttons
- Easily-accessible button and audio test pads for easier installation of aftermarket backlit screen kits

---

### Caveats
- Requires a decent amount of shell trimming and filing
- Requires a 103040 size LiPo battery with a JST PH 2.0mm connector to fit in the battery bay without removing the battery terminals (1200mAh battery of that size provides a good average of 6 hours of battery life with a 2.45" TN screen kit though)
- JST battery connector must be trimmed so the connector doesn't get stuck (may look ugly but vastly improves ease of use)
- Revision 3 and 4 boards with clone hardware require the crystal to be attached to somewhat long wires to be able to fit in the shell due to component placement miscalculation
- OEM screw for metal cartridge port shield is required above the volume wheel due to aftermarket ones usually being too large and causing the wheel to be hard to turn when the shell is put together

---

### Notes on screens from my experience
- The 2.2" TFT (no cut/no solder) kit produces an audible low-ish pitch drone when the brightness is not full or off.
- The Q5 IPS kit with HDMI output (and possibly the Q5 OSD kit) may produce a high pitched whine ONLY when using a LiPo battery.
- Most screens will generally produce some kind of headphone interference, but it shouldn't be noticeable at listening levels that won't damage your hearing.

---

### How to prep your system
The folder "Shell trimming" contains a guide on how to trim the shell in order to fit the board properly. Read that first!!! After you have finished trimming the shell, read the following to familiarize yourself with the test points so you can install your screen kit properly:

- UP, DN, L, R, STA, SEL, B, and A are all for the up, down, left, right, start, select, B and A buttons.
- BATT connects directly to the output of the battery mode switch. Solder to this test point if the screen kit you are installing requires soldering to the top pin of the power switch or requires wrapping a wire around the AA battery terminal.
- SWBATT connects to the center pin of the power switch. Solder to this test point if the screen kit you are installing requires soldering to the center pin of the power switch.
- 3.3V and 5V are connected to the 3.3V and 5V power rails respectively. I recommend soldering the power wire for the 2.45" TN kit to the 3.3V test pad so the backlight doesn't start crapping out when the batteries get low. I advise only using the 5V test pad if you absolutely know what you're doing.
- On the other side of the board, there are 4 audio test points: 2 take the left and right signals before they go through the volume wheel (labeled "pre-pot"), and the other 2 take the left and right signals after they go through the volume wheel. These test points are only necessary if you are installing the Q5 IPS kit with HDMI output.

---

### Revision change summary
The first two revisions of the board were rather crude compared to revisions 3 and 4. Revision 1 did not have the right footprint for the LiPo charging IC, and revision 2 had the MOSFET used to charge the battery in backwards. They shared the same janky, basically non-functional low battery indicator circuit, with fixed thresholds for both battery types.

Revision 3 improved this by fixing the MOSFET orientation and introducing potentiometers to separately adjust the AA and LiPo low battery thresholds. However, due to another oversight of mine, the LiPo side of the low battery indicator didn't work properly. I was able to fix it by creating a small bodge board, though. Since I also changed the crystal footprint from revision 2 to accommodate a different crystal that can be found on CGB-CPU-05 boards, I managed to goof up the placement of the through hole crystal used for clone boards. It does not impact units with real GBC CPUs though. This did carry over to revision 4, unfortunately.

Revision 4 is currently the latest board revision, which fixes the major issues with revision 3. I made 2 variants with slightly different low battery indicator circuits in case one didn't work, but both do work, thus I am selling both variants.

Revision 5 is on the way!
