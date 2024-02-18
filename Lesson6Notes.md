CSS FLEX BOX

1. CSS Flexbox: <br>
Flexbox is a layout model that allows you to design more flexible and efficient layouts in CSS.

<hr>

2. Flex Container: <br>

The container element that holds the flex items and defines the main and cross axes. <br>
Example: 

``.gallery-container {`` <br>
``    display: flex;``<br>
``    flex-direction: row;``<br>
``    flex-wrap: wrap;``<br>
 ``   justify-content: space-between;``<br>
 ``   align-items: flex-start;``<br>
``}`
`

<hr>

3. Flex Items: <br>

The child elements of the flex container that are laid out using flexbox. <br>
Example:

``Copy code``
``.gallery-item {``
 ``   flex: 1 1 300px;``
``    margin-bottom: 20px;``
``}``

<hr>

4. Flex Property: <br>

A shorthand property for the flex-grow, flex-shrink, and flex-basis properties. <br>
Example:

``.gallery-item {``
 ``   flex: 1 1 300px;``
``}``

<hr>

5. Flex-grow Property: <br>

Specifies how much a flex item should grow relative to the other flex items. <br>
Example:

``.gallery-item {``
``    flex-grow: 1;``
``}``

<hr>

6. Flex-shrink Property: <br>

Specifies how much a flex item should shrink relative to the other flex items. <br>
Example:

``.gallery-item {``
``    flex-shrink: 1;``
``}``

<hr>

7. Flex-basis Property: <br>

Specifies the initial main size of a flex item. <br>
Example:

``.gallery-item {``
``    flex-basis: 300px;``
``}``

<hr>

8. Flex-direction Property: <br>

Specifies the direction in which flex items are laid out in the flex container. <br>
Example:

``.gallery-container {``
 ``   flex-direction: row;``
``}``

<hr>

9. Justify-content Property: <br>

Aligns flex items along the main axis of the flex container. <br>
Example:

``.gallery-container {``
``    justify-content: space-between;``
``}``

<hr>

10. Align-items Property: <br>

Aligns flex items along the cross axis of the flex container. <br>
Example:

``.gallery-container {``
``    align-items: flex-start;``
``}``

<hr>

11. Align-self Property: <br>

Allows individual flex items to override the alignment set by the align-items property. <br>
Example:

``.gallery-item:nth-child(3) {``
``    align-self: flex-end;``
``}``

<hr>

12. Flex-wrap Property: <br>

Specifies whether flex items are forced onto a single line or can wrap onto multiple lines. <br>
Example:

``.gallery-container {``
``    flex-wrap: wrap;``
``}``

<hr>

13. HTML Structure: <br>

Uses HTML elements to create a photo gallery layout. <br>
Example:

``<div class="gallery-container">``
``    <div class="gallery-item"></div>``
``    <div class="gallery-item"></div>``
``    <!-- More gallery items -->``
``</div>``

By understanding and applying these concepts, you can create flexible and responsive layouts using CSS Flexbox, such as the photo gallery demonstrated in this module. Experimenting with different properties and values will help you customize your layouts according to your design requirements.




