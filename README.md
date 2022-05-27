# Leaflet.Rainviewer

- [Demo](https://mwasil.github.io/Leaflet.Rainviewer/demo/)
- [Demo JSFiddle](https://jsfiddle.net/hwmz670c/)

# Installation

````html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/mwasil/Leaflet.Rainviewer/leaflet.rainviewer.css"/>
<script src="https://cdn.jsdelivr.net/gh/mwasil/Leaflet.Rainviewer/leaflet.rainviewer.js"></script>
````

# Setup

````js
    // Change default options
    L.control.rainviewer({ 
        position: 'bottomleft',
        nextButtonText: '>',
        playStopButtonText: 'Play/Stop',
        prevButtonText: '<',
        positionSliderLabelText: "Hour:",
        opacitySliderLabelText: "Opacity:",
        animationInterval: 500,
        opacity: 0.5
    }).addTo(map);
````
