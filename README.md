### css-session

1. `Useful css selectors` 
    - .class
    - .class1.class2
    - .class1 .class2
    - #id
    - `*`
    - element
    - element.class
    - element,element
    - element element
    - element>element
    - element+element
    - element1~element2
    - :first-child
    - :hover
    - :last-child
    - :not(selector)
    - :nth-child(n)
    - :nth-last-child(n)
    - ::selection
 
2. `pseudo selectors` [reference] (https://www.w3schools.com/css/css_pseudo_classes.asp)

    - Pseudo-classes
        - Style an element when a user mouses over it
        - Style visited and unvisited links differently
        - Style an element when it gets focus
        - e.x (:hover, :first-child, :nth-child, :visited, :not ...)
    - pseudo-elements
        - A CSS pseudo-element is used to style specified parts of an element.
        - Style the first letter, or line, of an element
        - Insert content before, or after, the content of an element
        - pseudo-element can only be applied to block-level elements
        - e.x (::before, ::after, ::first-line, ::first-letter)
        
3. `Css Display property`
    - Inline
    - Inline-block
    - Block
    - Flex
    - Grid
3. `Margin vs Padding`  [source link](https://medium.com/frontendshortcut/margin-vs-padding-c1fc8ea8bfaf)
    - Margin is an element’s personal space — how much distance the element wants to keep with other elements around it.
    - Padding is how much an element is away from itself — how much distance an element wants to keep with the elements inside it.
    - It has testing tool (Developer tools)
    - They both are used to create gaps around elements, but they differ in their method of creating that gap. Margin accommodates the          gap by pushing adjacent elements away from it, while Padding accommodates the gap by either growing its own size or by shrinking        the size of content inside it.
    - Use padding when:
        - Keep your element inside, to control touching the parent border
        - To increase your element size
        - You want the background of the element to be displayed in the produced gap
     - Use margin when:
        - You want to have some space around an element, or you don’t want the element to touch other elements around it:
        - You want to center an element. If you give “margin: auto” to an element with fixed width, it will center that element  
          horizontally (and vertically too if using flexbox)
        - You want the background of the element to be displayed in the produced gap
    
3. `Three Ways to Insert CSS`
    - External CSS
    - Internal CSS
    - Inline CSS

3. `Css units` 
    - Absolute Units
        - px, pt, cm, mm, in
    - Relative Units
       - % - Relative to the parent element’s value for that property
       - em	- Relative to the current font-size of the element
       - rem - Relative to the font-size of the root (e.g. the <html> element). “rem” = “root em”
       - ch	- Number of characters (1 character is equal to the width of the current font’s 0/zero)
       - vh	- Relative to the height of the viewport (window or app size). 1vh = 1/100 of the viewport’s height
       - vw	- Relative to the width of viewport. 1vw = 1/100 of the viewport’s width.
       - vmin - Relative to viewport’s smaller dimension (e.g. for portrait orientation, the width is smaller than the height so it’s            relative to the width). 1vmin = 1/100 of viewport’s smaller dimension.
       - vmax - Relative to viewport’s larger dimension (e.g. height for portrait orientation). 1vmax = 1/100 of viewport’s larger                 dimension.
       - ex - Relative to height of the current font’s lowercase “x”.

4. `Different types of color values`
- RGB (255, 255, 255)
  - 0 to 255
- HEX (#ffffff)
  - 00 to ff 
  - rgb values of hex numbers (ff ff ff)
- HSL 
  - R (0 to 120 deg)
  - G (120 to 240 deg)
  - B (240 to 360)
    - RGBA
    - HSLA
    
5. `Css box model` [ex] (https://www.w3schools.com/css/css_boxmodel.asp)

6. `Shorthand properties in css`
    - 1-value syntax: padding: 10px
    - 2-value syntax: padding: 10px 20px
    - 3-value syntax: padding: 10px 15px 20px
    - 4-value syntax: padding: 10px 15px 20px 25px
    
