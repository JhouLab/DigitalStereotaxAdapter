Ridiculously cheap (and functional) digital stereotax adapter
============================================

---

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_rl.jpg" width="450">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_dv.jpg" width="160"></div>


_by Tom Jhou_

---

## Overview:

This project will digitize a Stoelting Lab Standard Manipulator Arm like this: https://stoeltingco.com/Neuroscience/Standard-Manipulator-Arms~9758

Cost is about \$50, which is 98% cheaper than Stoelting's official digital conversion kit. You might need
\$50-ish or so in hand tools also.

Accuracy is 0.01mm in the AP axis (same as Stoelting), and 0.1mm in the DV and RL axes, which is less accurate,
but likely still good enough, as the anatomical variation between animals will exceed this anyway. We've been using
this for about a year in our lab, and it works quite well.

Assembly requires familiarity with 3D printing as well as mechanical skill. If you run into trouble,
or have ideas/comments, feel free to contact me at tomjhou@gmail.com or tjhou@som.umaryland.edu.


## Requirements:

1. A 3D printer. Almost any model will suffice, including small ones like the Bambu A1 mini.
2. About 100 grams of PLA filament (about $3 worth)
3. This 150mm digital readout: ($28.99): https://www.amazon.com/gp/product/B089ZSG84J/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&th=1
4. Two 6" calipers (about $8 each): READ STEP 1 INSTRUCTIONS BELOW BEFORE YOU BUY: https://www.amazon.com/Digital-Caliper-Adoric-Calipers-Measuring/dp/B07DFFYCXS
5. Any cutting tool, like this one: https://www.amazon.com/Xuron-Model-9180-Kevlar-Scissor/dp/B00068P3TY
6. Two 6mm long M3 screws with washers, like this: https://www.amazon.com/HELIFOUNER-Phillips-Screws-Kit-Stainless/dp/B0BV9CF62L
7. Optional (but highly recommended): #8-32 tap and two #8x32-1/4" machine screws for securing digital readout to base clamps.<br>
    Tap: https://www.amazon.com/Drill-America-DWT54279-High-Speed-Threading/dp/B00DL7COVW<br>
    Manual tool for holding tap: https://www.amazon.com/AUTOTOOLHOME-Drilling-Capacity-0-315-Screwdriver/dp/B01M4FY99G<br>
    Machine screw (pack of 100 but you only need 2): https://www.mcmaster.com/91772A190/<br>
8. Silicone glue (e.g. "Amazong Goop" or equivalent) for base clamps.

Note: the 3D printed parts should fit snugly together. This is by
design, to eliminate loose play in the system. But this also means the fit could be affected by small
differences in 3D printer settings, or by small manufacturing design changes in Stoelting's components
or the digital readouts and calipers. If any parts don't fit perfectly on your system, please let me know,
and I'll see if I can help.


Instructions:
=============

## Step 1: Buy the parts listed above.

IMPORTANT: the 6" caliper linked above comes in several varieties.
You MUST get the 6" model (not 8") in BLACK (not red or silver). It has a black plastic body,
with red/yellow/blue buttons. Do NOT buy any of the steel models, as the caliper body/jaws need to be cut in step
3.6 below, and the metal ones are vastly harder to cut.


## Step 2: Print AP axis parts

Print the following two files in the "STL files" folder:

1. "Stoelting AP, parts 1-2 of 4, USE SUPPORTS.stl"
2. One of the following, depending on whether you are converting a left or right arm:<br>
    "Stoelting AP, parts 3-4 of 4, LEFT, NO SUPPORTS.stl"<br>
	"Stoelting AP, parts 3-4 of 4, RIGHT, NO SUPPORTS.stl"

The first file should be printed with supports _enabled_ in your 3D printer settings,
while the second file should be printed _without_ supports enabled (otherwise the holes will fill with PLA, and you will
have to drill them out). This gives you four total parts:

1. Spacer (long flat piece with slots at both ends)
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
the other will slide over the side near the front. Each base clamp has an oval protrusion on top with a central hole.
The digital readout's two metal brackets have corresponding oval holes that snap snugly onto the protrusion.

At this point, the base clamps will be loose, as the metal stereotax base has nothing to lock onto.
To stabilize them, I add a couple of drops of glue underneath each clamp to keep it from slipping. I use
"Amazing Goop", a silicone-based glue with stiffening additives, but aquarium glue (which is also silicone-based)
or even krazy glue will also work.

If you tapped threads into the central hole, use a 1/4" long #8-32 machine screw to lock the digital readout bar
onto the base clamps. Otherwise, you can use krazy glue or silicone glue to keep the bar in place.

<div align="center">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Base_clamp_back.jpg" width="300">
<img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Base_clamp_front.jpg" width="300">
</div>

---
3.5: Make sure the digital readout slider can slide freely, and then flex the end down slightly and slide it under
the stem of the Y-adapter. Push the spacer end up to lock it to the Y-adapter stem. The fit should be tight:

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/Y-adapter_to_spacer.jpg" width="450"></div>

---
3.6: Print the "AP readout panel holder.stl" file, and snap the digital readout panel into the pocket. The cable tucks underneath
the holder.

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


## Step 5: Assemble RL and DV axes parts:

The parts labeled "knob clamp" will snap onto the oval-shaped metal piece just below each knob. The parts labeled
"caliper body" should snap onto the central block of the arm. Without a video, it is hard to describe exactly how
to orient these parts. But you should be able to see their orientation from the photo below. As usual, the fit will be snug.

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_right_arm_annotated.jpg" width="450"></div>


## Step 6: Cut the caliper jaws and ruler:

The calipers each come with a long "ruler" that extends about a foot. Cut off the part past
about 140mm. The plastic is soft, and should cut without too much difficulty. If you are a few millimeters
too long or short, it is fine, the exact length is not critical.

There is also a central "spindle" that will protrude as you open/close the caliper. Cut that off too.

Cut off all four jaws of the caliper, while leaving the large outer one half intact, as shown below:

<div align="center"><img src="https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/Assembly/photo_dv_markup.jpg" width="450"></div>

Snap the caliper into the 3D-printed clamps, as in the photos. This might take some trial and error, and patience.


# Example videos:

A video of the stereotax in action is below:

[![Watch the video](https://github.com/JhouLab/DigitalStereotaxAdapter/blob/main/photo_dv.jpg)](https://youtube.com/shorts/_LRqchGYbzQ)
