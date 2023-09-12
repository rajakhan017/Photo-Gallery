# Photo-Gallery


## [Live Website Link!]https://rajakhan017.github.io/Photo-Gallery/

### Structure of the web page

img src="./public/webpage.jpg" width="700px" alt="structure of the webpage"  />
![image](https://github.com/rajakhan017/Photo-Gallery/assets/135150598/2c90c4e4-a63f-4070-89d0-1ae071cb3ce6)


### Universal Selector `*`

| CSS Property | Value      | Explanation                                                                                                 |
| ------------ | ---------- | ----------------------------------------------------------------------------------------------------------- |
| box-sizing   | border-box | Makes sure that the element's total width and height include padding and border, not just the content area. |

**Selector Explanation**: The universal selector `*` targets all elements on the page and applies the `box-sizing` property to ensure consistent box model behavior for all elements.

### `body`

| CSS Property | Value      | Explanation                                                              |
| ------------ | ---------- | ------------------------------------------------------------------------ |
| margin       | 0          | Sets margin on all sides to 0.                                           |
| font-family  | sans-serif | Sets the font family for the entire page to a sans-serif typeface.       |
| background   | #f5f6f7    | Sets the background color of the body to a light grayish-blue (#f5f6f7). |

**Selector Explanation**: The `body` selector targets the entire document's body, setting its margin, font family, and background color for styling purposes.

### `.header`

| CSS Property     | Value             | Explanation                                                                                  |
| ---------------- | ----------------- | -------------------------------------------------------------------------------------------- |
| text-align       | center            | Centers the text within the header.                                                          |
| text-transform   | uppercase         | Transforms text to uppercase.                                                                |
| padding          | 32px              | Adds 32 pixels of padding inside the header.                                                 |
| background-color | #0a0a23           | Sets the background color of the header to a dark blue (#0a0a23).                            |
| color            | #fff              | Sets the text color to white (#fff).                                                         |
| border-bottom    | 4px solid #fdb347 | Adds a 4-pixel solid border at the bottom of the header with a light orange color (#fdb347). |

**Selector Explanation**: The `.header` selector targets elements with the class `.header`, styling them to create a header section with centered text, uppercase letters, padding, background color, text color, and a bottom border.
![image](https://github.com/rajakhan017/Photo-Gallery/assets/135150598/b08bd573-712d-4ae9-86a9-42704be02fe3)

### `.gallery`

| CSS Property    | Value     | Explanation                                                                            |
| --------------- | --------- | -------------------------------------------------------------------------------------- |
| display         | flex      | Configures the gallery as a flex container.                                            |
| flex-flow       | row wrap  | Defines a row-based layout with wrapping items.                                        |
| justify-content | center    | Centers content horizontally within the gallery.                                       |
| align-items     | center    | Centers content vertically within the gallery.                                         |
| gap             | 16px      | Adds a 16-pixel gap between gallery items.                                             |
| max-width       | 1400px    | Sets the maximum width of the gallery to 1400 pixels.                                  |
| margin          | 0 auto    | Centers the gallery horizontally with no vertical margin.                              |
| padding         | 20px 10px | Adds 20 pixels of padding on top and bottom and 10 pixels on the sides of the gallery. |

**Selector Explanation**: The `.gallery` selector targets elements with the class `.gallery`, transforming them into a flex container with row-based layout, centered content, spacing between items, and specific width and padding.

### `.gallery img`

| CSS Property  | Value | Explanation                                                                        |
| ------------- | ----- | ---------------------------------------------------------------------------------- |
| width         | 100%  | Sets the width of gallery images to 100% of their parent's width.                  |
| max-width     | 350px | Sets the maximum width of gallery images to 350 pixels.                            |
| height        | 300px | Sets the height of gallery images to 300 pixels.                                   |
| object-fit    | cover | Ensures that the image covers the entire container while maintaining aspect ratio. |
| border-radius | 10px  | Rounds the corners of gallery images with a radius of 10 pixels.                   |

**Selector Explanation**: The `.gallery img` selector targets all `img` elements within elements with the class `.gallery`, resizing and styling them for consistent presentation.
![image](https://github.com/rajakhan017/Photo-Gallery/assets/135150598/b96ee36a-e4b7-41ed-92ba-0ad05beb8e27)

### `.gallery::after`

| CSS Property | Value | Explanation                                         |
| ------------ | ----- | --------------------------------------------------- |
| content      | ''    | Generates an empty content box.                     |
| width        | 350px | Sets the width of the pseudo-element to 350 pixels. |

**Selector Explanation**: The `.gallery::after` selector generates a pseudo-element to the right of the gallery container, creating additional spacing.
