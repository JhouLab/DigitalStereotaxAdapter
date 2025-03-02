Ridiculously cheap (and functional) digital stereotax adapter
============================================

---

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_rl.jpg" width="450">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv.jpg" width="160"></div>


_by Tom Jhou_

---

This project will digitize a Stoelting Lab Standard Manipulator Arm like this: https://stoeltingco.com/Neuroscience/Standard-Manipulator-Arms~9758

Cost is about \$50, 98% cheaper than Stoelting's official digital conversion kit.

Accuracy is 0.01mm in the AP axis (same as Stoelting), and 0.1mm in the DV and RL axes, which is less accurate,
but likely still good enough. Remember: the main inaccuracies are from variation in brain size and bregma location
between animals, which is typically larger than the electronic resolution.

We've been using this for about a year in our lab. Feedback from other users is welcome, and helps us improve the design.

Please contact me at tomjhou@gmail.com with questions and comments.


## Requirements:

1. A 3D printer. We have used a Bambu A1 mini, and various Qidi printers. Almost any modern printer should work fine. 
2. About 100 grams of PLA filament (about $3 worth)
3. This 150mm digital readout: ($28.99): https://www.amazon.com/gp/product/B089ZSG84J/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
4. Two 6" calipers (about $8 each): READ STEP 1 INSTRUCTIONS BELOW BEFORE YOU BUY: https://www.amazon.com/Digital-Caliper-Adoric-Calipers-Measuring/dp/B07DFFYCXS
5. Kevlar cutting tool (or equivalent), e.g.: https://www.amazon.com/Xuron-Model-9180-Kevlar-Scissor/dp/B00068P3TY
6. Two 6mm long M3 screws with washers, like this: https://www.amazon.com/HELIFOUNER-Phillips-Screws-Kit-Stainless/dp/B0BV9CF62L
7. Optional (but recommended): #8-32 tap and #8x32-3/8" machine screw for securing digital readout to base clamps.

Note: the 3D printed parts in this project are intended to fit snugly onto the various stereotaxic parts. This is by
design, to eliminate any loose play in the system. But this also means that this project could be affected by small
manufacturing design changes in either the Stoelting components or the digital readouts and calipers used. I am not
currently aware of any such differences, but can't rule this out. If any of the parts here don't fit perfectly on
your system, let me know.


Instructions:
=============

## Step 1: Buy parts

Buy the parts listed above.

IMPORTANT: there are several caliper models at the link above.
You MUST get the 6" model (not 8") BLACK (not red or silver). It will have a black plastic body,
with red/yellow/blue buttons. There is also SILVER model with red/yellow/blue buttons. That one costs more,
but has 10x higher accuracy. In theory, it will work, but since it is made of steel, it will cause trouble in step
6 below when you have to cut the body and jaws down to size. The steel body is MUCH harder to cut, and the higher
accuracy isn't usually necessary, so I don't recommend it.


## Step 2: Print AP axis parts

Print USING SUPPORTS the "Consolidated AP LEFT.stl" or "Consolidated AP RIGHT.stl" file, depending on whether you are
converting a left or right arm. Each file contains the following 4 parts:

1. Spacer (long flat piece with slots at both ends)
2. Y-shaped adapter, which connects the stereotax arm to the spacer.
3. Base clamp-back. Fits over the back corner of the stereotax base.
4. Base clamp-side. Fits over the side of the stereotax base.

OPTIONAL: The base clamps have 3.4mm holes in them. If you know how to use a basic tap tool,
you can cut #8-32 theads into these holes, allowing you to attach a screw for extra stability.

Left and right sides: <div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Consolidated AP left.png" width="400">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Consolidated AP right.png" width="400"></div>


## Step 3: Assemble AP axis parts

First, you have to flip the orientation of the readout bar. Position it with the blue side up, then
loosen the two screws on the black metal bracket by about 1/2 turn, then pull off the bracket. Flip the bar
so the blue side faces down, then put the bracket back on and tighten the screws. There are two brackets, one on
either end of the bar, so you need to do this on both sides.

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip1.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip2.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip3.jpg" width="250">
</div>


Attach the spacer to the digital readout using M3 screws and washers:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_spacer.jpg" width="350">
</div>

Now slide the Y-shaped piece onto the metal bracket around the knob controlling the AP movement:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y_adapter1.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y_adapter2.jpg" width="250">
</div>

Place the back/side base clamps onto the stereotaxic base. One will fit over the back corner, and
the other will slide over the side near the front. Place the readout bar onto the base clamps, snapping the
black metal brackets onto the oval bumps of the base clamps.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/base_clamp_digital_readout_rear.jpg" width="450"></div>

The slider should move freely across the entire range of the readout bar. Align the spacer slot with
the stem of the Y-shaped adapter, and insert the stem into the spacer slot. The fit should
be very tight, and might take some pushing to fit.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Y-adapter_to_spacer_markup.JPG" width="450"></div>

Print the "AP readout panel holder.stl" file, and snap the digital readout panel into the pocket. The cable tucks underneath
the holder.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_readout_crop.jpg" width="450"></div>

## Step 4: Print RL and DV axes parts:

Each of the RL and DV axes has two files (one labeled "caliper body" and one labeled "knob clamp"). Also, the
right and left arms have separate files. This gives 2 x 2 x 2 = 8 files total.

You can print the files in any order, and you should print only the ones you need, e.g. if you are converting a left
arm, you do not need to print the right side parts. Make sure to keep track of which part is which, as they are NOT
interchangeable, despite looking very similar.

Parts for right DV axis:
<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting DV, right arm, part 1 of 2, caliper body.png" width="400">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting DV, right arm, part 2 of 2, knob clamp.png" width="400"></div>


## Step 5: Assemble RL and DV axes parts:

The parts labeled "knob clamp" will snap onto the oval-shaped metal piece just below each knob. The parts labeled
"caliper body" should snap onto the central block of the arm. Without a video, it is hard to describe exactly how
to orient the part. Someday I hope to make a video, but in the meantime, trial and error should eventually get the
parts to snap into place. As usual, the fit will be tight.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_right_arm.jpg" width="450"></div>


## Step 6: Cut the caliper jaws and ruler:

The calipers each come with a long "ruler" that extends about a foot. Cut off the part past
about 140mm. The plastic is soft, and should cut without too much difficulty. If you are a few millimeters
too long or short, it is fine, the exact length is not critical.

There is also a central "spindle" that will protrude as you open/close the caliper. Cut that off too.
Don't worry, the caliper will work fine without it.

Cut off all four jaws of the caliper, while leaving the large outer one half intact, as shown below:

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv_markup.JPG" width="450"></div>

Snap the caliper into the various 3D-printed clamps, as in the photos. I recommend working with one axis at a time, so that
you can learn as you go along. The first one will be rather difficult to assemble, but it will get easier as you go along.


# Example videos:

A video of the stereotax in action is below:

[![Watch the video](https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv.jpg)](https://youtube.com/shorts/_LRqchGYbzQ)
