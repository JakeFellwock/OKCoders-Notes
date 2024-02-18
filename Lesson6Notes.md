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
``}`<br>


<hr>

3. Flex Items: <br>

The child elements of the flex container that are laid out using flexbox. <br>
Example:

``Copy code``<br>
``.gallery-item {``<br>
 ``   flex: 1 1 300px;``<br>
``    margin-bottom: 20px;``<br>
``}``<br>

<hr>

4. Flex Property: <br>

A shorthand property for the flex-grow, flex-shrink, and flex-basis properties. <br>
Example:

``.gallery-item {``<br>
 ``   flex: 1 1 300px;``<br>
``}``<br>

<hr>

5. Flex-grow Property: <br>

Specifies how much a flex item should grow relative to the other flex items. <br>
Example:

``.gallery-item {``<br>
``    flex-grow: 1;``<br>
``}``<br>

<hr>

6. Flex-shrink Property: <br>

Specifies how much a flex item should shrink relative to the other flex items. <br>
Example:

``.gallery-item {``<br>
``    flex-shrink: 1;``<br>
``}``<br>

<hr>

7. Flex-basis Property: <br>

Specifies the initial main size of a flex item. <br>
Example:

``.gallery-item {``<br>
``    flex-basis: 300px;``<br>
``}``<br>

<hr>

8. Flex-direction Property: <br>

Specifies the direction in which flex items are laid out in the flex container. <br>
Example:

``.gallery-container {``<br>
 ``   flex-direction: row;``<br>
``}``<br>

<hr>

9. Justify-content Property: <br>

Aligns flex items along the main axis of the flex container. <br>
Example:

``.gallery-container {``<br>
``    justify-content: space-between;``<br>
``}``<br>

<hr>

10. Align-items Property: <br>

Aligns flex items along the cross axis of the flex container. <br>
Example:

``.gallery-container {``<br>
``    align-items: flex-start;``<br>
``}``<br>

<hr>

11. Align-self Property: <br>

Allows individual flex items to override the alignment set by the align-items property. <br>
Example:

``.gallery-item:nth-child(3) {``<br>
``    align-self: flex-end;``<br>
``}``<br>

<hr>

12. Flex-wrap Property: <br>

Specifies whether flex items are forced onto a single line or can wrap onto multiple lines. <br>
Example:

``.gallery-container {``<br>
``    flex-wrap: wrap;``<br>
``}``<br>

<hr>

13. HTML Structure: <br>

Uses HTML elements to create a photo gallery layout. <br>
Example:

``<div class="gallery-container">``<br>
``    <div class="gallery-item"></div>``<br>
``    <div class="gallery-item"></div>``<br>
``    <!-- More gallery items -->``<br>
``</div>``<br>

By understanding and applying these concepts, you can create flexible and responsive layouts using CSS Flexbox, such as the photo gallery demonstrated in this module. Experimenting with different properties and values will help you customize your layouts according to your design requirements.




