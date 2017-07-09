# Leaflet.PolylineMeasure

I have been inspired by [PPete](https://github.com/ppete2) work and his original work https://github.com/ppete2/Leaflet.PolylineMeasure

In this plugin we provide two different mesurement methods to measure the distance between two points.
Those methodes are:

* Great Circle Distance [Wiki](https://en.wikipedia.org/wiki/Great-circle_distance)
* Rhumb Line Distance [Wiki](https://en.wikipedia.org/wiki/Rhumb_line)

As a user you'll have the ability to toggle between the two methodes and each time the distance measurement will be rendered based on your selection, One path .. render twice!!

## Demo
* Please take a look at the following [**Demo**](http://goo.gl/1Q3k75)

![Screenshot](https://github.com/SupervisionT/Leaflet.PolylineMeasure/blob/master/GC.png)

## Usage

Add 2 lines within your **HTML-code** to load the .css and .js files of the plugin:
```html
<link rel="stylesheet" href="https://ppete2.github.io/Leaflet.PolylineMeasure/Leaflet.PolylineMeasure.css" />
<script src="https://ppete2.github.io/Leaflet.PolylineMeasure/Leaflet.PolylineMeasure.js"></script>
```

Add 1 line within your **Javascript-code** to add the plugin's control into your Leaflet map.  
```js
L.control.polylineMeasure(options).addTo(map);
```
