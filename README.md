Creating Web Animation Effects
==============================
This repository contains graphics and animation based on Web Animations, Polymer, and SVG that add animation effects to the Polymer and SVG code samples in the polymer-svg repository.

As you can see, tthis repository contains a massive number of code samples (think "swatches"), with many similar variations, that illustrate how to create animation effects. If you are a developer, you'll learn techniques for creating visual effects. If you are a designer, you can easily update the color values in these code samples in order to create subtler and more aesthetically pleasing visual effects, and I would like to see some of your improvements.

Set-up instructions
===================
1) After downloading the code samples as well as installing bower on your machine, run this command: 
```
bower install
```
The preceding command will install the dependencies for the code samples.
2) Launch a local server (such as: python -m SimpleHTTPServer) in the directory with the code samples, launch a browser and navigate to this URL:
```
http://localhost:8000 
```
Which Web pages do I launch?
============================
The Web pages whose filename contains the string "Poly" contain Polymer-based code for generating SVG-based shapes, and they are always imported into another HTML Web page (containing Web Animation-based code) that you can launch in a browser via a local server described in the previous sentence. Simply launch any of the HTML Web pages with an "Anim" prefix to see animation effects. 

For example, if you click on the Web page AnimArchOvals1.html, you will see animation effects applied to the graphics shapes created in PolyArchOvals1.html that is imported in AnimArchOvals1.html.

In addition, launch any of the other HTML Web pages without an "Anim" or a "Poly" prefix if you want to see the corresponding "static" effects (e.g., ArchOvals1.html).

Note: the Web page AnimArchOvals1.html summarizes the animation-related code variations that are used in the other code samples in this repository, and they might be useful for creating your own variations as well.

The following repository contains gesture-related code samples:
```
https://github.com/ocampesato/web-animations-gestures
```
The filenames with the prefix "Gestures" illustrate how to handle `mouseover` events in order to dynamically update various properties of the SVG-based graphics elements, which you can use as guidelines for handling other gestures.

The following repository contains transforms that are applied to 2D shapes:
```
https://github.com/ocampesato/web-animations-transforms
```
NB: these code samples, as well as those in the two related repositories, are intended for solely for entertainment, which means that they do not necessarily contain "best practices", nor are they intended for a production website.
