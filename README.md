# Piano Doorbell

Project is currently incomplete, [see here for updated to-do list](https://github.com/jkrosby51/piano_doorbell/edit/main/to-do.md).

## Resources

### Hardware & Guides

- https://www.adafruit.com/product/2130
- https://www.adafruit.com/product/2342

- https://learn.adafruit.com/adafruit-audio-fx-sound-board/triggering-audio
- https://www.youtube.com/watch?v=4tAt-0UgqCE
- https://www.youtube.com/watch?v=xEuu4YycDdc

### Audio Files

- https://freesound.org/people/pinkyfinger/sounds/68441/
- https://freesound.org/people/guitarmaster/sounds/56111/

## Using the Sound Card
The sound card is very convenient in that it doesnt require a microcontroller or any code. All programming for this project is built into the card, and in the file names we will give each audio file.

The sound card has a specific file naming system that is necessary for the programming of the board. Audio files must be either .WAV or .OOG (WAV files are preferable as they will load faster when being looped. OOG files may have a noticeable delay inbetween plays while being looped, which we will be doing in this project.), and have file names according to the trigger and trigger type. There are 8 triggers on the board, which we will wire to buttons, named T01-T08. The audio files will be named after the triggers, and will also (if applicable) contain the trigger type. In this case we want our files to loop only when the trigger is held on, therefore all of our file names will be TnnHOLDL.WAV (nn referring to the trigger number). For a full list of trigger types and their necessary file names, [click here](https://learn.adafruit.com/adafruit-audio-fx-sound-board/triggering-audio#trigger-types-2914623). Once all wiring is complete and our files are named accordingly, activating a trigger should automatically play the appropriate file until let go.

## Planning & Design

### Wiring

### Casing Design



