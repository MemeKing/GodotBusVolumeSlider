# Bus Volume Slider

A very simple extension to HSlider that provides a volume slider which does everything I think you would want it to do.

- Continually updates volume when slider is actively being used.
- Starts with slider value already matching current volume level of bus

It's not a lot but I find this useful to reuse and I couldn't find any addons like this already, except for one which appears to be for educational purposes only. See the following link.

https://godotengine.org/asset-library/asset/1363

 
### Usage

Instantiate a BusVolumeSlider node in your UI tree and set it up like you would with any other slider.

Type the name of a bus into the "Bus Name" exported property. Make sure it's spelled correctly and that your AudioStreamPlayers are outputting to the Buses they should be.

### Example scene audio credits

Vibing Over Venus - Kevin Mcleod incompetech.com

Rain sound - rain_session_27sec_2007.wav by vibe_crc https://freesound.org/people/vibe_crc/sounds/50061/
