# LEGO® Spike Hub and the Speaker

A Python snippet utilizing the LEGO Spike speaker, [MicroPython](https://lego.github.io/MINDSTORMS-Robot-Inventor-hub-API/), and the `beep()`, `start_beep()`, `stop()`, `play_sound()`, and `set_volume()` commands.

## Sample Code

```py
from mindstorms import MSHub
from mindstorms.control import wait_for_seconds

hub = MSHub()

hub.speaker.beep()
hub.speaker.beep(44, 2, 50)
hub.speaker.beep(123, 4, 100)

hub.speaker.start_beep(60, 100)
wait_for_seconds(2)
hub.speaker.stop()

hub.speaker.play_sound('Celebrate', 50)

hub.speaker.start_sound('Shut Down')
wait_for_seconds(2)

hub.speaker.beep()
```

***

## Repo Resources

* [Visual Studio Code](https://code.visualstudio.com/)
* [MicroPython for LEGO Robot Inventor](https://www.lego.com/en-ca/themes/mindstorms/downloads)
* [LEGO Mindstorms](https://www.lego.com/en-ca/themes/mindstorms)
* [LEGO Mindstorms App for Mac](https://apps.apple.com/us/app/lego-mindstorms-inventor/id1515448947)
* [LEGO Mindstorms App for Android](https://play.google.com/store/apps/details?id=com.lego.retail.mindstorms)
* [LEGO Mindstorms App for Windows](https://www.microsoft.com/store/apps/9N7GN3KC2GK6)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>

