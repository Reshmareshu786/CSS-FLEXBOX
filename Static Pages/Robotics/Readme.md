# CSS FLEXBOX
### **Layout**
A Layout is a pattern to structure the information and arrange the elements on the website.

### **Methods to Design a Layout**
Mainly, there are two methods that help design the webpage layout.

- Flexbox (stable)
- CSS Grid (Advanced & Fast growing but not stable)
---
### Flexbox is a layout method that helps to arrange the HTML elements in rows (horizontally) or columns (vertically).
---
## **Flexbox Layout with CSS Properties**
To achieve flexbox layout CSS provides many properties, these are a few among them.

- display
- flex-direction
- justify-content
- align-items
- flex-wrap
- flex-flow
- align-content
- align-self
- flex-grow
- flex-basis
- flex-shrink
- order and many more...
---

### Display
To achieve different Layouts, we can use CSS property display.

Display property can have the following values:

- flex
- inline-flex
- grid
- none and many more...
#### Providing display property with the value flex converts the element into a Flex Container. ***All HTML elements that are direct children of Flex Container are called Flex Items.***
---
## Flex Direction
The Flex Direction specifies the direction of the flex items in the Flexbox Container.

When working with Flexbox layout, we need to think in terms of two axes.

- Main Axis- It is specified by the flex-direction property.
- Cross Axis- It runs perpendicular to the main axis.

### *Flex Direction property can have the following values:*

- row- Direction of the flex items is horizontal.
- column- Direction of the flex items is vertical.
---
## Justify Content
The justify-content property specifies the alignment of flex items along the main axis.

Justify Content property can have the following values:

- flex-start(default) - All the elements will arrange to the start of the container.
- center- All the elements will arrange to the center of the container.
- flex-end- All the elements will arange to the end of the container.
- space-between- Left over space will be arranged in between the flex items.
- space-around- Every flex item will get space around them.

----
## Align Items
The align-items property specifies the alignment of flex items along the cross axis.

Align Items property can have the following values:

- stretch(default)- Will stretch its available height.
- flex-start- Will be at the starting of the flex container.
- center- Will be at the center of the avilable height.
- flex-end- Will be at the ending point of the available height.