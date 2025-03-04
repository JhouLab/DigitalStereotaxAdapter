Ridiculously cheap (and functional) 3-axis digital stereotax adapter
============================================


<div align="center">
<video src="https://github.com/user-attachments/assets/23dbc953-8d90-421e-99c2-d5927db93f00" />
</div>


_by Tom Jhou_

---

## Overview:

This project will digitize all three axes of a Stoelting Lab Standard Manipulator Arm, like this one: https://stoeltingco.com/Neuroscience/Standard-Manipulator-Arms~9758

Cost is about \$30 for the AP axis, and $10 for each of the DV and RL axes. These are NOT typos, it really is that
cheap, about 98% less than Stoelting's digital conversion kit. You will also need about \$50-ish in hand tools,
along with a 3D printer and basic familiarity with its use.

Accuracy is 0.01mm in the AP axis (same as Stoelting), and 0.1mm in the DV and RL axes, which is less accurate,
but likely still good enough, as the anatomical variation between animals will exceed this anyway. We've been using
this in our lab since 2024, and it works quite well.

If you have problems, ideas, or comments, contact me at tomjhou@gmail.com or tjhou@som.umaryland.edu.


## Requirements:

1. A 3D printer. Almost any model works, including small tabletop ones like the Bambu A1 mini.
2. About 100 grams of PLA filament (about $3 worth)
3. This 150mm digital readout: ($28.99): https://www.amazon.com/gp/product/B089ZSG84J/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
4. Two 6" calipers (<$10 each): READ STEP 1 INSTRUCTIONS BELOW BEFORE YOU BUY: https://www.amazon.com/Digital-Caliper-Adoric-Calipers-Measuring/dp/B07DFFYCXS
5. Any cutting tool, like this one: https://www.amazon.com/Xuron-Model-9180-Kevlar-Scissor/dp/B00068P3TY
6. 6mm long M3 screws + washers, like this (pack of 500, but you only need 2): https://www.amazon.com/HELIFOUNER-Phillips-Screws-Kit-Stainless/dp/B0BV9CF62L
7. Optional (but highly recommended) #8x32-1/4" stainless steel machine screws.<br>
    Pack of 100 screws (but you only need 2): https://www.mcmaster.com/91772A190/<br>
    Tap tool for cutting threads: https://www.amazon.com/Drill-America-DWT54279-High-Speed-Threading/dp/B00DL7COVW<br>
    Manual holder for tap tool: https://www.amazon.com/AUTOTOOLHOME-Drilling-Capacity-0-315-Screwdriver/dp/B01M4FY99G<br>
8. Waterproof glue (e.g. "Amazing Goop", shoe goo, etc) for base clamps. https://www.amazon.com/Amazing-GOOP-140231-Purpose-Clear/dp/B006NTE01M

All links are accurate as of March 2025, but parts on Amazon are subject to change. If any links are broken,
please email me.

Note: the 3D printed parts will fit snugly together. This is by design, to eliminate loose play in the system.
However, this means the tight fits can be disrupted by small differences in 3D printer settings, or by
small manufacturing design changes in Stoelting's components or the digital readouts and calipers.
If any parts don't fit perfectly on your system, please let me know.


Instructions:
=============

## Step 1: Buy the parts listed above.

IMPORTANT: the 6" caliper linked above comes in several varieties.
You MUST get the 6" model (not 8") in BLACK (not red or silver). It has a black plastic body,
with red/yellow/blue buttons. Do NOT buy any of the steel models, as the caliper body/jaws need to be cut
later (see step 3.6 below), and the metal ones are vastly harder to cut.


## Step 2: Print AP axis parts

Print the following two files in the "STL files" folder:

1. "Stoelting AP, parts 1-2 of 4, USE SUPPORTS.stl"
2. One of the following, depending on whether you are converting a left or right arm:<br>
    "Stoelting AP, parts 3-4 of 4, LEFT, NO SUPPORTS.stl"<br>
	"Stoelting AP, parts 3-4 of 4, RIGHT, NO SUPPORTS.stl"

The first file should be printed with supports _enabled_ in your 3D printer settings,
while the second file should be printed _without_ supports enabled (otherwise the holes will fill with PLA, and you will
have to drill them out). This gives you four total parts:

1. Spacer (long flat piece with rectangular slots at both ends)
2. Y-shaped adapter.
3. Base clamp (back corner).
4. Base clamp (side).

OPTIONAL BUT HIGHLY RECOMMENDED: The base clamps have 3.4mm holes in them. You can tap #8-32 theads into these holes,
allowing you to attach a screw for extra stability in step 3.4below. Tapping threads should take only about 60
seconds using cheap hand tools.

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting AP, parts 1-2 of 4.png" width="400">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting AP, parts 3-4 of 4, RIGHT.png" width="400">
</div>

---

When you print the spacer and Y-shaped adapter, make sure you can fit the stem of the Y-adapter into
the spacer slot. It will likely be hard to insert at first, but with a little pressure it should go in. Once
you verify that they fit, please separate the pieces again and go onto the next step.

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/parts1-2_separate.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/parts1-2_joined.jpg" width="250">
</div>



## Step 3: Assemble AP axis parts

3.1: The 150mm digital readout has a blue metal bar with two black metal brackets on each end. You first
need to flip their orientation, as shown below:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip1.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip2.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_flip3.jpg" width="250">
</div>


---
3.2: Attach the spacer to the digital readout using M3 screws and washers:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Readout_spacer.jpg" width="350">
</div>

---
3.3: Slide the Y-shaped piece onto the metal bracket around the knob controlling the AP movement:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y_adapter1.jpg" width="250">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y_adapter2.jpg" width="250">
</div>

---

3.4: Place the two base clamps onto the stereotaxic base. One will fit over the back corner, and
the other will slide over the side near the front. Place the digital readout bar on the clamps, aligning the
oval bracket holes with the oval bumps on the clamps.

At this point, the base clamps will be loose, as the metal stereotax base has nothing to lock onto.
To stabilize them, add a couple of drops of glue underneath each clamp to keep it from slipping. I use
"Amazing Goop", a silicone-based glue with stiffening additives, but aquarium glue (which is also silicone-based)
or even krazy glue will work.

If you tapped threads into the holes in the oval bumps, you can now add a 1/4" long #8-32 machine screw to lock
the digital readout bar onto the base clamps. Otherwise, you can use krazy glue or silicone glue to keep the bar
secured to the base clamps.

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Base_clamp_back.jpg" width="300">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Base_clamp_front.jpg" width="300">
</div>

---
3.5: Make sure the digital readout slider can slide freely, and then flex the end down slightly and slide it under
the stem of the Y-adapter. Push the spacer end up to lock it to the Y-adapter stem. The fit should be tight:

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y-adapter_to_spacer.jpg" width="450"></div>

---
3.6: OPTIONAL: print the "AP readout panel holder.stl" file, and snap the digital readout panel into the pocket.
The cable tucks underneath the holder.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_readout_crop.jpg" width="450"></div>

## Step 4: Print RL and DV axes parts:

Each of the RL and DV axes has two files (one labeled "caliper body" and one labeled "knob clamp"). There are separate
arms for the right and left arms, hence 2 x 2 x 2 = 8 files total.

You can print the files in any order, and you should print only the ones you need, e.g. if you are converting a left
arm, you do not need to print the right side parts.

Supports should be ENABLED in your 3D printer for these parts. Make sure to track which part is which, as
they are NOT interchangeable, despite looking very similar.

Drawings of parts for right DV axis:
<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting DV, right arm, part 1 of 2, caliper body.png" width="400">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/PNG images/Stoelting DV, right arm, part 2 of 2, knob clamp.png" width="400"></div>


## Step 5: Snap RL and DV axes clamps onto arm:

The parts labeled "knob clamp" will snap onto the oval-shaped metal piece just below each knob. The parts labeled
"caliper body" should snap onto the central block of the arm. Without a video, it is hard to describe exactly how
to orient these parts. But you should be able to see their orientation from the photo below. As usual, the fit will be snug.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_right_arm_annotated.jpg" width="450"></div>


## Step 6: Cut the caliper jaws and ruler, and snap it onto arm:

The calipers each come with a long "ruler" that extends about a foot. Cut off the part past
about 140mm. The plastic is soft, and should cut without too much difficulty. If you are a few millimeters
too long or short, it is fine, the exact length is not critical.

There is also a central "spindle" that will protrude as you open/close the caliper. Cut that off too as far as you can.
You might have to slide the body almost to the end to fully remove the spindle. There are some small plastic pieces
inside the body that might fall out when you do this. Don't worry, they aren't necessary to keep.

Finally, completely remove 3 of the caliper jaws, while removing half of the  one half intact, as shown below:

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_dv_markup.jpg" width="400">
</div>
<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_rl_markup.jpg" width="500">
</div>

Snap the caliper into the 3D-printed clamps, as in the photos. This might take some trial and error, and patience.

That should be it. As you can see, this is not an easy project, I myself had to print and assemble these parts
several times before I got everything right.

