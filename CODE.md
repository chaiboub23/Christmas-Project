# CODE
## Getting Started
1. Go to [Microbit Code Editor](https://makecode.microbit.org/)
2. Click on the "New Project" button and create a new project.
## Coding work

### Block Code

![Image 1](https://github.com/chaiboub23/Christmas-Project/blob/main/Screen%20Shot%202020-12-11%20at%2012.15.04%20PM.png)

![Image 2](https://github.com/chaiboub23/Christmas-Project/blob/main/Screen%20Shot%202020-12-11%20at%2012.15.49%20PM.png)

![Image 3](https://github.com/chaiboub23/Christmas-Project/blob/main/Screen%20Shot%202020-12-11%20at%2012.15.56%20PM.png)

![Image 4](https://github.com/chaiboub23/Christmas-Project/blob/main/Screen%20Shot%202020-12-11%20at%2012.16.07%20PM.png)

### Python
```python
def on_button_pressed_a():
    for index in range(4):
        for index2 in range(4):
            for index3 in range(4):
                for index4 in range(4):
                    for index5 in range(4):
                        music.ring_tone(494)
                        music.ring_tone(494)
                        music.ring_tone(494)
                        music.stop_all_sounds()
input.on_button_pressed(Button.A, on_button_pressed_a)

def on_button_pressed_b():
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.HALF))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(440, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(440, music.beat(BeatFraction.WHOLE))
    music.play_tone(440, music.beat(BeatFraction.WHOLE))
    music.play_tone(466, music.beat(BeatFraction.WHOLE))
    music.play_tone(440, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(440, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
    music.play_tone(523, music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.rest(music.beat(BeatFraction.WHOLE))
    music.play_tone(262, music.beat(BeatFraction.WHOLE))
    music.play_tone(294, music.beat(BeatFraction.WHOLE))
    music.play_tone(392, music.beat(BeatFraction.WHOLE))
    music.play_tone(330, music.beat(BeatFraction.WHOLE))
    music.play_tone(349, music.beat(BeatFraction.WHOLE))
input.on_button_pressed(Button.B, on_button_pressed_b)

def on_forever():
    basic.show_string("kanye")
basic.forever(on_forever)
```
## Flashing onto Microbit
You want to make sure to click on the download button. It will download a HEX file. You also wan to connect the Microbit using a usb cable. Next, you want to move the file onto the Microbit. Now you can use the Microbit in your design.
