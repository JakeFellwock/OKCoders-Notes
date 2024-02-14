1. CSS Box Model:

The CSS Box Model describes the layout and spacing of elements on a web page. It consists of content, padding, border, and margin.
2. Content:

Represents the actual content area of an element.
Example: <br>

.box {
   width: 200px;
   height: 100px;
   background-color: blue;
}

3. Padding:

Specifies the space between the content area and the border.
Example: <br>

``.box { ``
``    padding: 20px;``
``}``

4. Border:

Surrounds the padding and content areas.
Example: <br>

``.box {``
``    border: 2px solid black;``
``}``


5. Margin:

Specifies the space outside the border, separating the element from other elements.
Example: <br>

``.box {``
``    margin: 10px;``
``}``

6. Positioning:

Allows you to position elements within their containing elements.
Example: <br>

``.color-block {``
``    position: absolute;``
``    top: 0;``
``    left: 0;``
``}``

7. nth-child Selector:

Selects elements based on their position within their parent element.
Example: <br>

``.color-block:nth-child(odd) {``
``    top: 0;``
``}``

``.color-block:nth-child(even) {``
 ``   top: 50%;``
``}``

8. Width Property:

Specifies the width of an element.
Example: <br>

``.color-block {``
``    width: 50%;``
``}``

9. Height Property:

Specifies the height of an element.
Example: <br>

``.color-block {``
``    height: 50%;``
``}``

10. Background-color Property:

Sets the background color of an element.
Example: <br>

``.color-block {``
``    background-color: #ff0000;``
``}``

11. HTML Structure:

Uses HTML elements to create color blocks for the Rothko painting.
Example: <br>

``<div class="color-block" style="background-color: #ff0000;"></div>``








