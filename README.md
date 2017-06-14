# HTML5 canvas-svg


### canvas

The HTML ``` <canvas> ``` element is used to draw graphics on a web page.

points to be noted down while creating canvas elements
 * The HTML ``` <canvas> ``` element is used to draw graphics on a web page.
 * The ``` <canvas> ``` element is only a container for graphics.
 * You must use JavaScript to actually draw the graphics.
 * A canvas is a rectangular area on an HTML page.
 * By default, a canvas has no border and no content.

The markup looks like this:

```html
<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000;">
</canvas>
```
![ScreenShot](https://user-images.githubusercontent.com/6780840/27128831-c6c06534-511d-11e7-8ab1-91c546319d10.png)

### Example
```javascript
var canvasId = document.getElementById("myCanvas");
var context = canvasId.getContext("2d");
context.moveTo(0,0);
context.lineTo(200,100);
context.stroke();
```



### SVG

points to be noted down while creating SVG elements

* SVG stands for Scalable Vector Graphics
* SVG is used to define graphics for the Web
* SVG is a W3C recommendation
* The HTML ``` <svg> ``` element is a container for SVG graphics.


### Example

```html
<!DOCTYPE html>
<html>
<body>

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

</body>
</html>
```

### differences between Canvas and SVG

Canvas						  | SVG
------------------------------|---------------------------
No support for event handlers | Support for event handlers
You can save the resulting image as .png or .jpg | 
Resolution dependent | Resolution independent
