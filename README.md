3DVisualizer
============

Google Calendar visualizer extended from Tilt by Victor Porof

https://github.com/victorporof/Tilt

3D Visualizer: Google Calendar visualization based on Naïve Bayes classifier

Motivation:

Calendar is an integral part of our daily schedules and for a long time not much change has been
observed in their presentation.
The world we see around is 3D which makes depth a natural cue for any visualization we see
around us. So, we want to introduce cue of “depth” different from other cues (color, font, highlighting)
generally used in calendar user interfaces.

Implementation:

Our implementation is developed over Tilt Mozilla extension by Victor Porof. It extends it to
customize the UI for Google Calendar and introduces machine learning Naïve Bayes classification for
identifying event importance.

Design:

A Mozilla extension which visualizes your calendar page. It present an interface to interact with
visualization in a 3D perspective.

Running Instruction:

Step 1: Install Mozilla browser

Step 2: Drag and drop 3DVisualizer.xpi file to any window in the browser. Restart browser
https://github.com/haruitk/3DVisualizer/raw/master/bin/3DVisualizer.xpi

Step 3: Login to Google Calendar and navigate to the weekly page you want to visualize

Step 4: Click on Menu->Web Developer-> 3DVisualizer: Google Calendar. Enjoy!
