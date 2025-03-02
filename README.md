Ridiculously cheap (and functional) digital stereotax adapter
============================================

---

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_rl.jpg" width="450"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv.jpg" width="300"></div>


_by Tom Jhou_

---

This project will digitize a Stoelting Lab Standard Manipulator Arm like this one:

https://stoeltingco.com/Neuroscience/Standard-Manipulator-Arms~9758?navigate_from_document=960&navigated_from_object=3778

Cost is about \$50, 98% cheaper than Stoelting's official digital conversion kit.

Accuracy is 0.01mm in the AP axis (same as Stoelting), and 0.1mm in the DV and RL axes,
which is less accurate, but still good enough. Remember: the main source of inaccuracy is inter-animal
variation in brain size and bregma location, which is typically on the order of a few hundred microns.

## Requirements:

1. A standard 3D printer. Our lab uses QIDI and Bambu A1 mini printers. Both work fine.
2. About 100 grams of PLA filament, any color.
3. This 140mm digital readout: ($28.99): https://www.amazon.com/gp/product/B089ZSG84J/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
4. Two calipers (about $8 each): READ STEP 1 INSTRUCTIONS BELOW BEFORE YOU BUY: https://www.amazon.com/Digital-Caliper-Adoric-Calipers-Measuring/dp/B07DFFYCXS
5. Kevlar cutting tool (or equivalent), e.g.: https://www.amazon.com/Xuron-Model-9180-Kevlar-Scissor/dp/B00068P3TY
6. 6mm long M3 screw with washer, like this: https://www.amazon.com/HELIFOUNER-Phillips-Screws-Kit-Stainless/dp/B0BV9CF62L
7. Optional: #8-32 tap and #8x32-3/8" machine screw for securing digital readout to base clamps.

This project has been in use for about a year in my lab. It works well for us, but feedback from other labs would be
welcome, and may help me to improve the design.

Please contact me at tomjhou@gmail.com if you run into trouble.


Instructions:
=============

## Step 1: Buy parts

Buy the parts listed above.

IMPORTANT: there are several caliper models at the link above.
You MUST get the 6" model (not 8") BLACK (not red or silver). It will have a black plastic body,
with red/yellow/blue buttons.

There is also SILVER model with red/yellow/blue buttons. That one costs more, but has 10x higher accuracy.
In theory, it will work, but I don't recommend it, since it is made of steel, and will cause trouble in step
6 below when you have to cut the body and jaws down to size. The steel body is MUCH harder to cut, and the higher
accuracy isn't usually necessary.


## Step 2: Print AP axis parts

Print USING SUPPORTS the "Consolidated AP LEFT.stl" or "Consolidated AP RIGHT.stl" file, depending on whether you are
converting a left or right arm. Each file contains the following 4 parts:

1. Spacer (long flat piece with slots at both ends)
2. Y-shaped adapter, which connects the stereotax arm to the spacer.
3. Base clamp-back. Fits over the back corner of the stereotax base.
4. Base clamp-side. Fits over the side of the stereotax base.

OPTIONAL: The base clamps have 3.4mm holes in them. If you know how to use a basic tap tool,
you can cut #8-32 theads into these holes, allowing you to attach a screw for extra stability.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Consolidated AP left.png" width="450"></div>
<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Consolidated AP right.png" width="450"></div>


## Step 3: Assemble AP axis parts

Attach the spacer to the digital readout using the M3 screw. The photo below shows a right-arm conversion. The left arm
would be the mirror image:

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_spacer.jpg" width="450"></div>

Don't tighten the screw all the way - leave just enough play so you can slide the spacer in the end to keep the spacer
parallel with the AP axis.

Slide the Y-shaped piece onto the metal bracket around the knob controlling the AP movement. The fit will likely be
very snug.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Y-adapter.jpg" width="450"></div>

Place the back/side base clamps onto the stereotaxic base. One will fit over the back corner, and
the other will slide over the side near the front. Place the readout bar onto the base clamps, snapping the
black metal brackets onto the oval bumps of the base clamps. 

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/base_clamp_digital_readout_rear.jpg" width="450"></div>

The slider should move freely across the entire range of the readout bar. Slide it until the spacer slot aligns with
the vertical stem of the Y-shaped adapter. Place the stem of the Y-shaped adapter into the spacer slot. The fit should
be very tight. It might not go in right away, but if you push on it, it should eventually slide in place.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Y-adapter_to_spacer_markup.JPG" width="450"></div>

Print the "AP readout panel holder_dual.stl" file. It has space for two panels, since it was intended for use with
a dual stereotax. 

Snap the digital readout panel into the pocket.

## Step 4: Print RL and DV axes parts:

Each of the RL and DV axes has two files (one labeled "caliper body" and one labeled "knob clamp"). Also, the
right and left arms have separate files. This gives 2 x 2 x 2 = 8 files total.

You can print the files in any order, and you should print only the ones you need, e.g. if you are converting a left
arm, you do not need to print the right side parts. Make sure to keep track of which part is which, as they are NOT
interchangeable, despite looking very similar.

## Step 5: Assemble RL and DV axes parts:

The parts labeled "knob clamp" will snap onto the oval-shaped metal piece just below each knob. The parts labeled
"capliper body" should snap onto the central block of the arm. Without a video, it is hard to describe exactly how
to orient the part. Someday when I have a few extra hours I might try to make a video, but in the meantime, the best
way I can think of to explain this is to look at the various photos, and know that there is only one way that each part
works.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_right_arm.jpg" width="450"></div>

As with the other pieces, the fit will be tight. This is all by design, to prevent play in the system.

## Step 6: Cut the caliper jaws and ruler:

The calipers each come with a long "ruler" that extends about a foot. Use a cutting tool to cut off the part past
about 140mm. The plastic is fairly soft, and should cut without too much difficulty. If you are a few millimeters
too long or short, it is fine, the exact length is not critical, as the end does not get used anyway.

There is also a central "spindle" that will protrude as you open/close the caliper. Cut that off too.
Don't worry, the caliper will work fine without it.

Cut off all four jaws of the caliper, as shown in the various photos.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv_markup.JPG" width="450"></div>

Snap the caliper into the various 3D-printed clamps, as in the photos. I recommend working with one axis at a time, so that
you can learn as you go along. The first one will be rather difficult to assemble, but it will get easier as you go along.


# Example videos:

A video of the stereotax in action is below:

[![Watch the video](https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv.jpg)](https://youtube.com/shorts/_LRqchGYbzQ)
