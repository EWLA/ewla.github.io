# Audio

We are currently using an Allen & Heath Qu-16 Chrome Edition and Allen & Heath AR2412 Digital Snake. We are currently working on getting a solid base of settings, so please refrain from changing many settings.

## Official Manuals
* [Allen & Heath Qu-16 Manual PDF](http://www.allen-heath.com/media/Qu-Mixer-Reference-Guide-AP9372_8A.pdf)
* [Allen & Heath Qu-16 Getting Started PDF](http://www.allen-heath.com/media/Qu-Mixer-Getting-Started-Guide-AP10025_1.pdf)
* [Allen & Heath AR2412 Digital Snake Manual PDF](http://www.allen-heath.com/media/AR2412-Guide-AP8596_2.pdf)

## Setup

Setup is simple:

1. Place mixer on small folding table in back - plug in power.
1. Place rolling rack behind the center of the stage - plug in power.
1. Plug digital snake into dSnake port on the front of the snake.
1. Run snake cable along with HDMI up to the stage - then underneath the right side of the stage.
1. Plug digital snake into mixer's dSnake port.
1. Plug in all monitors and speakers
1. Power on board (back side - bottom right)
1. Power on snake (back side - bottom right)

**Note:** Leave the coil/reel of the dSnake near the mixer - try not to clutter the space behind the stage.

At this point the connections for the snake are as follows:

* 1-16 on the input (left side) are active input channels
  * 15 is handheld mic (has extra sheath on cord near the XLR plug)
  * 16 is speaker/lapel mic
* The outputs (right side) are:
  * 1 - Left speaker
  * 2 - Right speaker
  * 3 - Front monitor (the XLR from the amp box at the bottom of the rack)
  * 4 - Back monitor (XLR to speaker or IEM box on stage)

## Mixes & Monitors

**Note:** The mixer has motorized faders. Make sure to keep hands/objects off the faders when switching mixes

We have three active mix channels:

* **House:** left/right speakers plugged into output channels 1 & 2 of the snake
* **Lead IEM:** plugged into output channel 3 of the snake
* **Front monitors:** plugged into output channel 4 of the snake
* * **Drum IEM:** plugged into output channel 5 of the snake

### House Mix

To balance the house mix, press the LR button on the right side of the mixer. ([Image](uploads/images/IMG_0900.JPG))

All faders will transition into the current mix for the house. Mute buttons should mute for all mixes.

Make adjustments as normal. Adjustments to gain, pan, and compressor are covered in the [Balancing](pages/audio.md#Balancing) section of the docs.

**Note:** We keep channel 15 and 16 un-muted during service and allow the speaker and MC to mute themselves when they are not talking.

### Monitor Mix

To balance the monitor mix, press the Mix 1 (Lead IEM - [Image](uploads/images/IMG_0901.JPG)) or Mix 2 (Front Monitors - [Image](uploads/images/IMG_0902.JPG)) or Mix 3 (Drum IEM) button on the right side of the mixer.

All faders will transition into the current mix for the selected monitor mix. Mute buttons should mute for all mixes.

Make adjustments (including overall level control with master fader) as the band needs.

## Balancing

Balancing is now done digitally and is simple. Follow the steps below to balance. See the [Channel Memory](pages/audio.md#Channel_Memory) section for restoring defaults!

### Basics

1. Press the select button for the channel you want to balance
1. Press Processing on the screen selection buttons
    * Gain is now able to be adjusted (top left, in the preamp section)
    * You can now adjust the EQ from the Parametric EQ knobs
    * Gate and compression are available to adjust as well (Don't touch if unsure!)
    * You can touch the top graphs and bars to get more adjustments in each section.
1. Basic adjustments can be done by using the bottom row of the Parametric EQ. Left to right:
    * Lows
    * Mid-Lows
    * Mid-Highs
    * Highs

**Note:** The graph representation shows boosting and subracting of balance. If the balance is below the mid-line, you are reducing the gain of that spectrum, above the line is boosting the gain.

### Parametric EQ

We now have 4 adjustable points of balance. You can see the wave representation on the screen as you dial in the knobs. Not only can you adjust the gain, but you can adjust where in the spectrum it affects, and the width of the spectrum to affect. This is very detailed AND very powerful if used correctly.

## Channel Memory

Channel memory is now available! We can recall (and store) tricky balances.

### Recalling

Recalling balances for the wireless setups and Alissa are things we should do weekly!

1. Select the channel you want to recall settings on ([Image](uploads/images/IMG_0910.JPG))
1. Select the library (with the FN button) ([Image](uploads/images/IMG_0912.JPG))
1. Select User ([Image](uploads/images/IMG_0914.JPG))
1. Verify `Recall Preamp` is `On` ([Image](uploads/images/IMG_0916.JPG))
1. Select the preset to recall: ([Image](uploads/images/IMG_0916.JPG))
    * Alissa is Alissa's balance
    * Handheld is for the handheld mic
    * PLawHS is for Lawrence's mic on the lapel (drastically different balance from the church's mic)
1. Select recall ([Image](uploads/images/IMG_0918.JPG))
1. See the new settings reflected ([Image](uploads/images/IMG_0920.JPG))

### Resetting

Resetting is great to get a base for the week and to clear out any balances that are not needed. We will just recall a basic Mic setup:

1. Select the channel you want to recall settings on ([Image](uploads/images/IMG_0910.JPG))
1. Select the library (with the FN button) ([Image](uploads/images/IMG_0912.JPG))
1. Select Factory ([Image](uploads/images/IMG_0922.JPG))
1. Verify `Recall Preamp` is `On` ([Image](uploads/images/IMG_0924.JPG))
1. Select the `:Mic` preset ([Image](uploads/images/IMG_0924.JPG))
1. Select recall ([Image](uploads/images/IMG_0926.JPG))
1. See the new settings reflected ([Image](uploads/images/IMG_0928.JPG))

### Storing

For balances we will have frequently or are incredibly tricky to get, we will store them away for use layer. Typically, this won't be very often.

1. Select the channel you want to save settings of ([Image](uploads/images/IMG_0910.JPG))
1. Select the library (with the FN button) ([Image](uploads/images/IMG_0912.JPG))
1. Select the `Store New` button in the bottom of the channel library ([Image](uploads/images/IMG_0916.JPG))
1. Enter a name for the settings
1. Save

## Recording

Recording is now done with direct USB recording from the mixer. Lawrence will have a 32GB flash drive for use.

1. Plug in flash drive on upper right corner of mixer
1. From the Home Screen choose `Qu-Drive` ([Image](uploads/images/IMG_0930.JPG))
1. Before service starts, press the record button to prime recording ([Image](uploads/images/IMG_0931.JPG))
1. As service starts, press the play/pause button to begin recording ([Image](uploads/images/IMG_0932.JPG))
1. Press the stop button on the same screen after service is complete to save the file.

**Warning!** Make sure to stop AND follow proper shutdown step before unplugging the flash drive

**Note:** The recordings are stored in the `AHQU/USBREC` folder on the USB drive ([Image](uploads/images/IMG_0937.JPG))


## Playback

Playback will eventually be USB directly to the mixer - for now we still use the USB sound card. Plug a 3.5mm male-to-male cord into the headphone slot of the sound card and into the ST3 plug on the top right of the sound board.

To change volume of cimputer audio, press the button on the left, just below the word layers. The faders will move to the balance of each mix. Slide the ST3 fader up.

**Warning:** To get back to the channel levels, press the button below the Layers button, on the same row as the channel names.

## Shutdown

Shutting the mixer down requires a proper power off before pushing the power button.

1. From the home screen, select `Shut Down` ([Image](uploads/images/IMG_0939.JPG))
1. Select `Yes` from the modal dialog ([Image](uploads/images/IMG_0940.JPG))
1. Wait for confirmation screen ([Image](uploads/images/IMG_0941.JPG))
1. Power off board with button on back side of the mixer, bottom right.

## Wireless Mics

Wireless mics should be all setup for use. Check batteries before servicei and change as needed (Handheld will show battery level, lapel will flash the light when low). Do not mess with channel settings, they are currently locked in. If you need to modify channels (or fix them) for any reason, see below:

* **Handheld Mic:** J9 is the receiver channel, 612 is the handset channel. This plugs into input 15 on the snake.
* **Lapel Mic:** This can auto-pair with the reciever. See Lawrence for pairing instructions until we can get them here (need more clarity on steps). This plugs into input 16 on the snake - has a sticky note on it mentioning channel 12 (from old board).
