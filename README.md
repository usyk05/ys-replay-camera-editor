# YS REPLAY CAMERA EDITOR

YS REPLAY CAMERA EDITOR is a browser-based replay file editor for YSFlight, inspired by the original YS CAMERA.
https://usyk05.github.io/ys-replay-camera-editor/

It allows you to add and configure camera aircraft in YSFlight replay (`.yfs`) files to create custom camera shots for screenshots and video capture.

The editor runs entirely in your browser and is platform-independent. Your replay files are processed locally and are not uploaded anywhere.

## Requirements

YS REPLAY CAMERA EDITOR requires the camera aircraft add-ons included with YS CAMERA:
https://forum.ysfhq.com/viewtopic.php?t=7147

It should also work with custom builds of YSFlight, although some compatibility issues may remain.

## How to Use

1. Save a flight record in YSFlight.
2. Drag and drop the `.yfs` file into YS REPLAY CAMERA EDITOR.
3. Configure the camera settings.
4. Export the edited `.yfs` file. The original file will not be overwritten.
5. Load the edited replay in YSFlight.
6. Press F5 to switch viewpoints.

## Known Issue

- A stall warning may sound when switching to a camera aircraft during replay. This may be resolved by modifying the `.dat` file for `<<CAMERA>>`.

## Tips

YS REPLAY CAMERA EDITOR is intended as a tool for creating individual shots rather than automatically producing a complete video. Adjust the camera settings for each shot, capture the footage you need, and assemble the resulting clips in a video editor.

A close camera and a distant camera with zoom can produce very different results even when the aircraft appears at a similar size on screen. This works much like changing the focal length of a real camera lens. Neither approach is inherently better; use whichever suits the shot.

## Development

Further updates and improvements are planned.
In parallel with this project, I'm also experimenting with visual improvements to YSFlight itself.
