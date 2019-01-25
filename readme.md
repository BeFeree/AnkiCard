# Anki Cards

Template and style of Anki cards.

![Multi Card](https://raw.githubusercontent.com/Ber-Fer/AnkiCard/master/screenshot.gif)

## Fields

1.  Front (Sort by this field in browser)
2.  Back
3.  Picture
4.  Sound
5.  Audio File Name
6.  Story\*
7.  Notes

### Default

Easy-to-read cards with toggle switch fields (show/hide).

| Field           | Comment                                        |
| --------------- | ---------------------------------------------- |
| **Front**       | **expression here; sort by this field**        |
| **Back**        | **expression translation**                     |
| Picture         | optional; `<img src="story_audio_file.jpg" />` |
| Sound           | optional; `[sound:story_audio_file.mp3]`       |
| Audio File Name | optional; `story_audio_file.mp3`               |
| Story\*         | _leave blank!_                                 |
| Notes           | optional;                                      |

The following fields are available to show/hide content:

-   Front (to use the note as a reverse card as well)
-   Front Type  (to check if you are correct)
-   Audio File Name (to replay the audio with **adjustable playback speed** range - set audio to play in slow motion)
-   Notes (show your comments)

**Note:** Playing audio files (this way) are only supported with AnkiDroid.

### Story

Fill out the field of `Story*`, so the carrd is suitable for longer content as well.

| Field           | Comment                                           |
| --------------- | ------------------------------------------------- |
| **Front**       | **title of story; sort by this field**            |
| Back            | optional; eg. the front translation               |
| Picture         | optional; `<img src="story_audio_file.jpg" />`    |
| Sound           | no displayed;                                     |
| Audio File Name | optional; `story_audio_file.mp3`                  |
| **Story\***     | **if it's not empty, the card become story card** |
| Notes           | optional;                                         |
