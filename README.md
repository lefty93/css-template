# CSS-Template 💡

Collection of css ideas during web-surfing 🌊

1) SVG Animation With Text
<p><img src="https://github.com/lefty93/css-template/blob/main/6atciu.gif" alt=""></p>

credit to: https://www.youtube.com/watch?v=vJNVramny9k&t=617s&ab_channel=DevEd

Please take notes that do not remove the fill color as he did. Removing Fill and adding strokes options in Figma, then copying as svg will give results like following: 

Instead, 
1. keep the fill color
2. don't add strokes (we will do it manually)
3. get outline stroke of filled text (no strokes!)
4. copy as svg

And you should get
<svg ...>
<path d="..." fill="..." />
<path d="..." fill="..." />
<path d="..." fill="..." />
<path d="..." fill="..." />
<path d="..." fill="..." />
<path d="..." fill="..." />
<path d="..." fill="..." />
</svg>

remove the fill property and add stroke="white" & stroke-width="5" to the path tags. The paths should look like
<path d="..." stroke="white" stroke-width="5" />

It is important that you remove the fill property or else the fill animation at the end won't work.

