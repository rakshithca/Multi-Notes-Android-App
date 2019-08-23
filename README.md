# Multi-Notes-Android-App
This app allows the creation and maintenance of multiple notes. Any number of notes are allowed (including no notes at all). Notes are made up of a Title and Note Text
There is no need to use a different layout for landscape orientation in this application. One layout should work fine in either orientation.
Notes should be saved to (and loaded from) the internal file system in JSON format. If no file is found upon loading, the application should start with no existing notes and no errors. (A new JSON file would then be created when new notes are saved).
JSON file loading must happen in an AsyncTask that is started in the onCreate method. Saving should happen in the onPause method.
A simple java Note class (with last save date, title, and note text) should be created to represent each individual note in the application.
The application is made up of 3 activities. These are described below:

1) Main Activity:
The Main Activity allows the user to create a new note via an Add options-menu item . Pressing this button will open the Edit Activity with empty Title and Note Text areas.

2) Edit Activity:
The Edit Activity contains editable fields for the note title and note text.

3) About Activity:
The About Activity contains a full-screen image background.
