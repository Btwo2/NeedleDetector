# Needle Detector

[STILL IN DEVELOPMENT]

Using Top-Hat Transform the shape is highlighted against the background. Otsu Threshold and Canny Edges its possible to segments the needles edges allowing generating the image objects outlines enhacing the probable lines with Hough Transform.

Using these techniques we pretend to find a line correlate to the needle geometry and define an rectangle outlining the needle using the line edges. Through this process it's possible to crop the needle by adding a margin to this detected line.

# Current Result
## Before

![Antes](https://github.com/Btwo2/NeedleDetector/assets/110456965/5b2212a1-9942-4adc-a55f-fb8e9260addf)

## After

![Depois](https://github.com/Btwo2/NeedleDetector/assets/110456965/2eb3715a-34fb-4c19-868c-ce5a14504081)
