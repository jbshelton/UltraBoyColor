## Shell trimming guide
This page is to help with doing the necessary shell trimming in order to prepare it for an Ultra Boy Color board. For best results... follow this guide, and measure twice, cut once! Or do a bunch of small cuts until it's enough.

These steps are in no particular order. Just make sure to follow them closely to get a good result!

Filing the shell will result in some whisps of plastic hanging onto the edges, which can be scraped or cut off using a craft knife.

If you have any suggestions on how to improve this guide, don't hesitate to open an issue!

---

## Tools required
In order to trim the shell, you will need the following:

- Side/flush cutters (I recommend using a separate pair from what you use to trim component pins)
- A small drill bit (and preferably a small hand drill)
- A small set of files
- Sandpaper
- Craft knife(s)
- Thin masking tape (for outlining the USB-C port)

![Necessary tools](images/tools_1.jpg)
![More tools](images/tools_2.jpg)

---

### Remove the sticker in the battery bay
The first thing you want to do is remove the battery cover. There is a sticker where the cover tab goes like so:
![Sticker](images/batterybay_uncut.jpg)

Remove the sticker.
![Removed](images/batterybay_nosticker.jpg)

---

### Trim the front of the shell
The front half of the shell needs to be trimmed slightly to accommodate the headphone pins being in a different location. Here is a before and after of the required cut.
![Uncut](images/shell_front_uncut.jpg)
![Cut](images/shell_front_cut.jpg)

---

### Make a hole for the charge indicator light pipe
This step is required if you're using a shell that is opaque, or if the translucent shell color may make the blue charge indicator LED too dim.
I like to trim the part of the front of the shell that sits above the USB port completely- 
![Charge pipe preinstall](images/chargepipe_predrill.jpg)

and then drill a hole in it (approximately in the middle) with a 3mm drill. You may need to circle the drill around a few times to widen the hole a bit more so the pipe can fit.
![Charge pipe drill](images/chargepipe_drill.jpg)

I recommend that you use a pair of tweezers to insert the light pipe initially, and needlenose pliers to push it all the way into the shell. It's a pretty small part!
![Charge pipe installed](images/chargepipe_install.jpg)
![Charge pipe installed outside view](images/chargepipe_install_out.jpg)

---

### Cut the back of the shell for headphone jack
Next, you want to want to get the rear half of the shell, and cut the plastic away from where I circled. This is after I made the cuts- there is a small divider in the middle that needs to be cut, and a small portion of plastic on the left of the headphone jack needs to be trimmed.
![Headphone cuts](images/headphone_cuts.jpg)

---

### Create space for the USB C port
This step requires precision and care to get a clean result. The first sub-step is to have the two halves of the shell aligned vertically so the USB port and the 3D printed spacer can be seen like so:
![USB pre-alignment](images/usb_cut_prealign.jpg)

Then, with the shell in that position, use the masking tape to mark the sides of where the USB port and spacer reach. A third piece of tape can be placed just slightly above the DC jack port- the height can be reduced later.
![USB align tape](images/usb_cut_align_tape.jpg)

I like to start by cutting from the edge of the shell to the hole to remove some plastic so I can then use a small file to file away the rest of the plastic. Take note that the space between the headphone jack and the edge of the USB-C hole must be about 3mm.
![USB headphone space](images/shell_measure.jpg)

The result should look something like this. I added the 3D printed spacer so that the DC jack hole wouldn't show like it did in some of my earlier trim experiments. I'd say it looks great! If it doesn't fit the first time, take note of which side isn't filed enough and file just a bit of plastic off.
![USB port cutting result](images/ports_result.jpg)

---

### Create hole in the battery bay for LiPo connector
If you have an opaque shell, then a bit of eyeballing is required. With the shell oriented such that the headphone jack and power port are facing AWAY from you, drill a hole in between the side of the battery bay and the screw post. Here is where the hole(s) should roughly be:
![Hole position](images/lipoconnector_holes.jpg)

Using a flashlight to see where the port is is helpful. One side of the hole should be flush with the screw post (a small bit of it should be filed away.) The top of the port can just be eyeballed and filed until the connector fits through the hole- it's on the back behind the batteries so its appearance shouldn't matter a ton. This is what it should look like after you finish cutting/filing.
![LiPo cut result](images/lipoconnector_result.jpg)

---

### Create space for battery mode switch
This step isn't as important as cutting the USB-C port, but still important to get a functional result. Cut the shell so it looks like this- the opening for the battery mode switch needs to be at least this large, but more plastic can be filed/cut away to make it look cleaner. This is applicable to only rev 4 boards:
![What to cut](images/back_cuts_no_lipo.jpg)

And this is applicable to rev 5 boards. A small amount still needs to be cut to accommodate for the ceramic capacitors near the battery mode switch.
![Rev 5 battery switch](images/rev5_switchcut.jpg)

It should look like this inside the battery bay.
![Battery switch](images/batteryswitch_cut.jpg)

---

### Create space for 5V decoupling capacitor (REV 5 ONLY)
While revision 5 doesn't require mangling the shell as much near the battery mode switch, it does require the back half to be trimmed to accommodate for a capacitor.
![Rev 5 capacitor cut](images/rev5_capcut.jpg)

---

### Hollow out the battery compartment
This step does not apply to Funnyplaying laminated IPS-ready shells, as they do not have the divider that needs to be removed. The divider needs to be cut until it is a few millimeters below the bottom of the tab part of the positive battery terminals. I use flush cutters to cut most of the plastic, a craft knife to clean it up a bit and then sandpaper to smooth it out.
![Side](images/batterybay_cut_side.jpg)
![Top](images/batterybay_cut_top.jpg)

---

### Install the light pipe
Finally, after doing any other necessary cuts for your particular screen kit, drop the 3D printed light pipe into the shell!
![Pipe](images/light_pipe.jpg)

---

## You can now proceed with the rest of the installation process.
