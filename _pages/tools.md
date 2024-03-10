---
permalink: /tools/
title: "My tools"
---

[Draw points to create polygon coordinates](https://jye9.github.io/assets/tools.html)
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>PolygonZone by Roboflow</title>
    <meta name="title" content="PolygonZone by Roboflow">
    <meta name="description" content="Draw polygons on an image and retrieve the coordinates for use in your computer vision projects.">
    <link rel="stylesheet" href="/assets/css/tools.css">
</head>
<body>
    <main>
        <div class="flex">
            <div class="left">
                <h1>Draw points to create polygon coordinates</h1>
                <p class="show_normalized" id="coords" style="display: none;">x: <span id="x"></span> | y: <span id="y"></span></p>
                <canvas id="canvas"></canvas>
                <div style="margin-top: 20px;">
                    <a href="" id="clear" class="widgetButton">Clear Polygons</a>
                    <a href="" id="saveImage" class="widgetButton">Save Image</a>
                    <br>
                    <p id="mode">Mode: Polygon (Press <kbd>L</kbd> to switch to Line drawing mode)</p>
                </div>
            </div>
            <div class="right">
                <h2>NumPy Points</h2>
                <p>Copy the points below into your Python code.</p>
                <a href="" id="clipboard" class="widgetButton">Copy Python to Clipboard</a>
                <pre id="python">
                    <code>
                    </code>
                </pre>
                <div class="show_normalized" style="margin-bottom: 25px;">
                    <label for="normalize_checkbox">Show Normalized Points from 0-1</label>
                    <input type="checkbox" id="normalize_checkbox" name="normalize_checkbox" value="normalize_checkbox">
                </div>
                <details>
                    <summary>View JSON Points</summary>
                    <h2>JSON Points</h2>
                    <a href="" id="clipboardJSON" class="widgetButton">Copy JSON to Clipboard</a>
                    <pre id="json">
                        <code>
                        </code>
                    </pre>
                </details>
            </div>
        </div>
    </main>
    <script src="/assets/js/script.js"></script>
</body>
</html>