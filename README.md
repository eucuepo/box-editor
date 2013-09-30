box-editor
==========

This is a custom component designed with jqueryUI and Kinetic.js. See a working demo here: http://eucuepo.github.io/box/box.html

See me explaining it here: http://www.youtube.com/watch?v=RWviGE16zcQ

Technical details
=================

The widget have been designed as a jQuery widget. As external libraries I have used KinectJS for the graphic part and jQuery UI for the draggable components. 

#Highlights of my app:

1. Rich UI using jQueryUI and KineticJS
2. Pure HTML5 design using canvas (compatible with mobile devices and tablets)
3. Customizable width, height and colors, along with the css.
4. Array normalization by linear interpolation

Why KineticJS?
==============
KineticJS (http://kineticjs.com/) is a Javascript framework that enables graphics, animations, and event handling, all performed using HTML5 canvas element. It is compatible with desktop and mobile devices.
After reviewing some libraries like RaphaelJS or D3JS, I thought Kinetic will be a perfect match for this challenge, because is very event-intensive (drags, transformations, hover events) and in their webpage they have benchmarks that proves itself very fast (see http://www.html5canvastutorials.com/labs/html5-canvas-kineticjs-drag-and-drop-stress-test-with-1000-shapes/, more than 10.000 shapes at once).

#Some goals achieved thanks to Kinetic:

1. Vector-based markers, with dynamic shadowing. The markers look gorgeous!
2. Fancy and smooth animations, even managing more than 200 values per array.
3. Mobile and tablet compatible, thanks to the use of the HTML5 canvas element.
4. Allows different sized arrays to be visualized, calculating the values with linear interpolation. 

