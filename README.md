# Needle Detector

[STILL IN DEVELOPMENT]

Using Top-Hat Transform the shape is highlighted against the background. Otsu Threshold and Canny Edges its possible to segments the needles edges allowing generating the image objects outlines enhacing the probable lines with Hough Transform.

Using these techniques we pretend to find a line correlate to the needle geometry and define an rectangle outlining the needle using the line edges. Through this process it's possible to crop the needle by adding a margin to this detected line.
