e-flash
=======

e-flashcards for Vidyasagar. These should include


    Animals and Birds
    Numbers and counting
    Shapes
    Vehicles
    Math concepts like Size, position, quantity, serialization, etc.,
    Matching and sorting
    Paint software with stamps of animals, people, etc.,
    Games - make a face with different sets of hairs, spectacles etc, having funny expressions.
    Bowling
    1-4 piece jigsaw puzzle (numbered pieces)
    
Basic Requirements
-----------------
    
The main requirement is that all operations which are done via keyboard and mouse should be converted to a single mouse click. This conversion can then be translated to a sensor based device (eg., ADITI used by Vidyasagar), so that the user can operate computer with the help of his finger. Here are some basic requirements that should be kept in mind, regardless of any module. For sample application, check out MathAssistant 1.0.

Scan mode
-----------
To convert the keyboard strokes or certain application specific information into left mouse click, we incorporate a method called scanning. In this method, the keyboard strokes or application specific information are placed as buttons in the screen and the focus is varied from one button to the next with a time interval of 9 seconds. This scan mode should operate in all the screens.

Initial screen
---------------
The first screen for all the software should hold two buttons for modes Normal mode and High contrast mode. Normal mode is for children with normal vision and high contrast for children with low vision, as shown below.


Normal vision mode
-------------------
In the normal vision mode, all the pictures should be in the natural color.

High contrast mode
------------------
In the high contrast mode:
1. Background should be black.
2. The cursor should be clearly visible as an yellow cursor with a clear thick black/red outline.
3. There should not be details within the picture. In other words, the edges should be clearly marked.
4. Should not use more than two solid colors.
5. Should use only red, yellow or white colors in pictures.

Text to speech
--------------
Text to speech should be provided in both languages - English and Tamil.

Executable
-----------
The developed software should run as an executable in both windows and linux platforms.
