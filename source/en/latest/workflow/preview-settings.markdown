---
Type:            article
Title:           Previewing your settings
Project:         HandBrake
Project_URL:     https://handbrake.fr/
Project_Version: Latest
Language:        English
Language_Code:   en
Text_Encoding:   utf-8
Authors:         Bradley Sepos <bradley@bradleysepos.com>
Copyright:       2016 HandBrake Team
License:         Creative Commons Attribution-ShareAlike 4.0 International
License_Abbr:    CC BY-SA 4.0
License_URL:     https://handbrake.fr/docs/license.html
---

Previewing your settings
========================

Video encoding requires a lot of computer resources and can take awhile to complete. Exactly how long depends on a number of factors, including the duration, resolution, and complexity of your `Source`, and the settings for making your new video.

Luckily, HandBrake has a `Preview` feature that allows you to do a test run on a few seconds or minutes of your `Source`, so you can see what your new video will look like without waiting for a complete encode to finish.

## Opening the Preview window

At the top of HandBrake's main window, you'll see a toolbar with various buttons.

<!-- .system-lin -->

<!-- TODO: Linux figures. -->

<!-- /.system-lin -->
<!-- .system-mac -->

![Main window toolbar](../images/mac/toolbar.png "The Toolbar provides easy access to HandBrake's most common functions.")

<!-- /.system-mac -->
<!-- .system-win -->

<!-- TODO: Windows figures. -->

<!-- /.system-win -->

Select the `Preview` button to open the `Preview` window.

<!-- .system-lin -->

<!-- TODO: Linux figures. -->

<!-- /.system-lin -->
<!-- .system-mac -->


![Preview window](../images/mac/preview-window.png)

<!-- /.system-mac -->
<!-- .system-win -->

<!-- TODO: Windows figures. -->

<!-- /.system-win -->

## Adjusting Preview settings

Move your mouse cursor over the `Preview` window, and some controls will appear.

<!-- .system-lin -->

<!-- TODO: Linux figures. -->

<!-- /.system-lin -->
<!-- .system-mac -->

![Preview controls](../images/mac/preview-controls.png)

<!-- /.system-mac -->

Set the starting position by dragging the `Position` control left or right. Choose how many seconds of video you want to encode using the `Duration` control. Longer durations will take more time to encode.




## Starting a Preview encode on Mac

When you're satisfied with your starting position and duration, select `Live Preview` and be patient. HandBrake will report its progress while it works. When your `Preview` is ready, it will play automatically. You can use the playback controls to pause, rewind, and replay your `Preview`.

<!-- .system-mac -->
![Preview start control](../images/mac/preview-controls-start.png)

![Preview playing](../images/mac/preview-playing.png)

<!-- /.system-mac -->

<!-- .system-mac -->

To create a new `Preview`, select the `×` button to start over. When you're finished previewing your work, you may close the `Preview` window.

![Preview reset control](../images/mac/preview-controls-reset.png)

![Closing the preview window](../images/mac/preview-window-close.png)

<!-- /.system-mac -->

## Next steps

If the `Preview` you created was lacking in quality or otherwise not as expected, you may need to [adjust quality](adjust-quality.html) or select a different [Preset](select-preset.html), after which you can create another `Preview` to see any changes.

Once you are satisfied, continue to [Starting encoding](start-encoding.html).
