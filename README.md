# Sequencer App Prototype
## What is it?
Starting point for a 4 bar 16th note resolution sequencer
application. This app was created as a reference for a student of the
StackUp Full Stack Foundation course. Feel free to copy and distribute
this project for your own purposes within the limitations of the
included LICENSE.

If you do use this project as a baseline for you own work, I would love
to see the derived works! Not required but certainly appreciated.

See a live demo at http://nat.io/sequencer/

## Installation
No installation needed, its a purely client-side app, you may need to
run it from a local web-server though as it does use XHR requests and
your browser may block locally depending on what browser you are using
and how you have it configured.

## How to build it and run the tests
Uhmm... oops I forgot to write unit tests. To build just compile the
.scss files and you are good to go, I have included the compiled .css
output just in case you don't have the compiler available.

## Licensing
Please refer to LICENSE

## Authors
Please refer to AUTHORS

## How to use it
This is a pretty bare-bones, and incomplete shell, the goal was to
demonstrate one approach to achieving this type of interaction and
display in native ES5 JS and HTML5, no third-party libs or frameworks
were used.

### Playing the sequence
Hit 'spacebar' or 'right-arrow', spacebar doesn't work in Firefox (scrolls
the page)

### Creating a new note

Click on an empty note position to insert a new note.

### Selecting and editing a note

Double click a note to select it. Double Click the same note to unselect
a note. Selecting a new note by double click action will also deselect
the previous note.

### Setting a notes length

Double click on a note to select it and then click an empty note slot
further ahead in the time line to set the notes length

### Deleting a note

While a note is selected, press the 'delete' key or the 'left-arrow'. The
delete key does not work in Firefox (navigates to previous page)

### Setting the Pitch of a note

While a note is selected use keyboard entry for z-/ to set the notes
pitch in 100 cent (1 semitone) intervals

### Editor in use
<video src="demo.mp4"></video>