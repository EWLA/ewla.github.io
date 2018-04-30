# Audio

We are currently using an Allen & Heath Qu-16 Chrome Edition and Allen & Heath AR2412 Digital Snake. We are currently working on getting a solid base of settings, so please refrain from changing many settings.

## Official Manuals
* [Allen & Heath Qu-16 Manual PDF](http://www.allen-heath.com/media/Qu-Mixer-Reference-Guide-AP9372_8A.pdf)
* [Allen & Heath Qu-16 Getting Started PDF](http://www.allen-heath.com/media/Qu-Mixer-Getting-Started-Guide-AP10025_1.pdf)
* [Allen & Heath AR2412 Digital Snake Manual PDF](http://www.allen-heath.com/media/AR2412-Guide-AP8596_2.pdf)

## Setup Basics

1. Place mixer on small folding table in back - plug in power
1. Place rolling rack behind the stage - plug in power
1. Plug digital snake into dSnake port on the front of the rolling rack snake
1. Run snake cable along with HDMI up to the stage - then underneath the right side of the stage
1. Plug digital snake into mixer's dSnake port
1. Plug in all monitors and speakers
1. Power on board (back side - bottom right)
1. Power on snake (back side - bottom right)

**Note:** Leave the coil/reel of the dSnake near the mixer - try not to clutter the space behind the stage.

At this point the connections for the snake are as follows:

* 1-16 on the input (left side) are active input channels
  * 15 is handheld mic (has extra sheath on cord near the XLR plug)
  * 16 is speaker/lapel mic
* The outputs (right side) are:
  * 1 - 8 IEMs (Channels 5-6 and 7-8 are stereo pairs, resulting in 6 true unique IEM channels)
  * 9-10 - Subs (Only need to plug in a singe channel to the amp)
  * 11-12 - House speakers

## Mixes & Monitors

**Note:** The mixer has motorized faders. Make sure to keep hands/objects off the faders when switching mixes

We have multiple active mix channels:

* **House:** LR is the main mix, controls the outputs on outs 11-12
* **IEMs:** Ouputs 1, 2, 3, 4, 5-6, 7-8 are IEM mixes, the band will generally control their own mix via [Qu-You App](https://www.allen-heath.com/ahproducts/qu-you/)
* **Subs:** Outputs on 9-10 are to the subs. This mix shouldn't be touched. It is set up in such a way to only send the channels we want in the subs, the channels then follow the main mix. **Example:** If the channel is turned all the way down in the main mix, the subs will also turn all the way down.

### House Mix

To balance the house mix, press the LR button on the right side of the mixer. ([Image](uploads/images/IMG_0900.JPG))

All faders will transition into the current mix for the house. Mute buttons should mute for all mixes.

Make adjustments as normal. Adjustments to gain, pan, and compressor are covered in the [Balancing](audio.md#Balancing) section of the docs.

**Note:** We keep channel 15 and 16 un-muted during service and allow the speaker and MC to mute themselves when they are not talking.

### Monitor Mix

To balance the monitor mix, press the Mix 1 (Lead IEM - [Image](uploads/images/IMG_0901.JPG)) or Mix 2 (Front Monitors - [Image](uploads/images/IMG_0902.JPG)) or Mix 3 (Drum IEM) button on the right side of the mixer.

All faders will transition into the current mix for the selected monitor mix. Mute buttons should mute for all mixes.

Make adjustments (including overall level control with master fader) as the band needs.
## Recording

Recording is now done with direct USB recording from the mixer. Lawrence will have a 32GB flash drive for use.

1. Plug in flash drive on upper right corner of mixer
1. From the Home Screen choose `Qu-Drive` ([Image](uploads/images/IMG_0930.JPG))
1. Before service starts, press the record button to prime recording ([Image](uploads/images/IMG_0931.JPG))
1. As service starts, press the play/pause button to begin recording ([Image](uploads/images/IMG_0932.JPG))
1. Press the stop button on the same screen after service is complete to save the file.

**Warning!** Make sure to stop AND follow proper shutdown step before unplugging the flash drive

**Note:** The recordings are stored in the `AHQU/USBREC` folder on the USB drive ([Image](uploads/images/IMG_0937.JPG))

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

--------------------------------

**Warning:** The notes below are generally locked off. Our PEQ and Compression settings are locked down to keep the same tone from week to week. If you need to make changes to these settings, please contact Jared, Austin, or Ian for help.

--------------------------------

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

