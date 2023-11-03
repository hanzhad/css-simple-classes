# CSS Simple Classes

This library was created to provide a collection of required CSS classes that make it easy to develop markup.

## Installation

You can install this library using npm, yarn, or pnpm:

```shell
npm install css-simple-classes
```

```shell
yarn install css-simple-classes
```

```shell
pnpm install css-simple-classes
```

## Usage

To use this library, you need to import the package in your index file:

```js
import 'css-simple-classes';
```

That's it! You can now start using the CSS classes provided by this library in your project.
Please let me know if you need any further assistance!

## CSS Grid System

### 1. Grid Columns

- **.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12**:
    - Description: These classes define the column widths for a 12-column grid system.
    - CSS Properties:
        - `position`: relative
        - `width`: 100%
        - `padding-right`: 15px
        - `padding-left`: 15px

- **.col, .col-auto, .col-sm, .col-sm-auto, .col-md, .col-md-auto, .col-lg, .col-lg-auto, .col-xl, .col-xl-auto**:
    - Description: General column classes for various responsive breakpoints and auto-sizing.
    - CSS Properties:
        - `position`: relative
        - `width`: 100%
        - `padding-right`: 15px
        - `padding-left`: 15px
        - `-ms-flex-preferred-size`: 0
        - `flex-basis`: 0
        - `-ms-flex-positive`: 1
        - `flex-grow`: 1
        - `max-width`: 100%

- **.col-auto**:
    - Description: Class for creating a column that will automatically adjust its width.
    - CSS Properties:
        - `-ms-flex`: 0 0 auto
        - `flex`: 0 0 auto
        - `width`: auto
        - `max-width`: 100%

### 2. Grid Rows

- **.row-cols-1, .row-cols-2, .row-cols-3, .row-cols-4, .row-cols-5, .row-cols-6**:
    - Description: Classes for creating rows with different numbers of columns.
    - CSS Properties:
        - `-ms-flex`: 0 0 (percentage)
        - `flex`: 0 0 (percentage)
        - `max-width`: (percentage)

### 3. Specific Column Widths

- **.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12**:
    - Description: Classes for specific column widths ranging from 8.33% to 100% of the grid container.
    - CSS Properties:
        - `-ms-flex`: 0 0 (percentage)
        - `flex`: 0 0 (percentage)
        - `max-width`: (percentage)

## Usage

To use this CSS grid system, simply include the relevant classes in your HTML markup and adjust as needed to achieve the
desired layout.

### 4. Margin Classes

#### Margins by Unit Amount:

- **.m-0**:
    - Description: Sets margin to 0.
    - CSS Properties: `margin: 0 !important;`

- **.m-4, .m-n4**:
    - Description: Sets margin to 4px and -4px, respectively.
    - CSS Properties: `margin: 4px !important;` and `margin: -4px !important;`

- **.m-8, .m-n8**:
    - Description: Sets margin to 8px and -8px, respectively.
    - CSS Properties: `margin: 8px !important;` and `margin: -8px !important;`

- **.m-12, .m-n12**:
    - Description: Sets margin to 12px and -12px, respectively.
    - CSS Properties: `margin: 12px !important;` and `margin: -12px !important;`

- **.m-16, .m-n16**:
    - Description: Sets margin to 16px and -16px, respectively.
    - CSS Properties: `margin: 16px !important;` and `margin: -16px !important;`

- **.m-24, .m-n24**:
    - Description: Sets margin to 24px and -24px, respectively.
    - CSS Properties: `margin: 24px !important;` and `margin: -24px !important;`

- **.m-32, .m-n32**:
    - Description: Sets margin to 32px and -32px, respectively.
    - CSS Properties: `margin: 32px !important;` and `margin: -32px !important;`

- **.m-48, .m-n48**:
    - Description: Sets margin to 48px and -48px, respectively.
    - CSS Properties: `margin: 48px !important;` and `margin: -48px !important;`

#### Margins by Position:

- **.mt-**, **.mr-**, **.mb-**, **.ml-**:
    - Description: Sets margin-top, margin-right, margin-bottom, and margin-left to the specified value, respectively.
    - Example: `.mt-8` sets the top margin to 8px.

- **.mx-**, **.my-**:
    - Description: Sets margin-left and margin-right to the specified value for **.mx-** and margin-top and
      margin-bottom to the specified value for **.my-**.
    - Example: `.mx-16` sets both left and right margins to 16px.

#### Centering Elements:

- **.m-auto**, **.mt-auto**, **.mr-auto**, **.mb-auto**, **.ml-auto**, **.mx-auto**, **.my-auto**:
    - Description: Aligns the element at the center with respect to the specified direction.
    - Example: `.mx-auto` horizontally centers the element within its parent container.

### Usage

These margin classes can be applied to HTML elements to manage their spacing within a layout. Use the appropriate class
depending on the desired margin size and position. The `!important` flag is used to ensure that these styles override
any other existing styles.

### 5. Padding Classes

#### Padding by Unit Amount:

- **.p-0**:
    - Description: Sets padding to 0.
    - CSS Properties: `padding: 0 !important;`

- **.p-4**:
    - Description: Sets padding to 4px.
    - CSS Properties: `padding: 4px !important;`

- **.p-8**:
    - Description: Sets padding to 8px.
    - CSS Properties: `padding: 8px !important;`

- **.p-12**:
    - Description: Sets padding to 12px.
    - CSS Properties: `padding: 12px !important;`

- **.p-16**:
    - Description: Sets padding to 16px.
    - CSS Properties: `padding: 16px !important;`

- **.p-24**:
    - Description: Sets padding to 24px.
    - CSS Properties: `padding: 24px !important;`

- **.p-32**:
    - Description: Sets padding to 32px.
    - CSS Properties: `padding: 32px !important;`

- **.p-48**:
    - Description: Sets padding to 48px.
    - CSS Properties: `padding: 48px !important;`

#### Padding by Position:

- **.pt-**, **.pr-**, **.pb-**, **.pl-**:
    - Description: Sets padding-top, padding-right, padding-bottom, and padding-left to the specified value,
      respectively.
    - Example: `.pt-8` sets the top padding to 8px.

- **.px-**, **.py-**:
    - Description: Sets padding-left and padding-right to the specified value for **.px-** and padding-top and
      padding-bottom to the specified value for **.py-**.
    - Example: `.px-16` sets both left and right padding to 16px.

### Usage

These padding classes can be used in HTML elements to adjust the spacing around the content. Select the appropriate
class based on the desired padding size and position. The `!important` flag is used to ensure that these styles override
any other existing styles.

### 6. Display Classes

#### Display Types:

- **.d-none**:
    - Description: Sets the display property to none, making the element invisible.
    - CSS Properties: `display: none !important;`

- **.d-inline**:
    - Description: Sets the display property to inline, allowing the element to generate inline-level box.
    - CSS Properties: `display: inline !important;`

- **.d-inline-block**:
    - Description: Sets the display property to inline-block, allowing the element to generate block-level box in the
      inline flow.
    - CSS Properties: `display: inline-block !important;`

- **.d-block**:
    - Description: Sets the display property to block, allowing the element to generate block-level box.
    - CSS Properties: `display: block !important;`

- **.d-table**:
    - Description: Sets the display property to table, allowing the element to generate table display.
    - CSS Properties: `display: table !important;`

- **.d-table-row**:
    - Description: Sets the display property to table-row, allowing the element to generate a table row.
    - CSS Properties: `display: table-row !important;`

- **.d-table-cell**:
    - Description: Sets the display property to table-cell, allowing the element to generate a table cell.
    - CSS Properties: `display: table-cell !important;`

### Usage

These display classes can be applied to HTML elements to control their visibility and layout behavior. Choose the
appropriate class based on the desired display type for the element. The `!important` flag is used to ensure that these
styles override any other existing styles.

### 7. Flexbox Classes

#### Display and Flex Direction:

- **.d-flex**:
    - Description: Sets the display property to flexbox, allowing the element to use the flexbox layout model.
    - CSS Properties: `display: -ms-flexbox !important; display: flex !important;`

- **.flex-row**, **.flex-column**, **.flex-row-reverse**, **.flex-column-reverse**:
    - Description: Sets the flex direction to row, column, reverse row, and reverse column, respectively.
    - CSS Properties: `-ms-flex-direction`, `flex-direction`

#### Flex Wrap:

- **.flex-wrap**, **.flex-nowrap**, **.flex-wrap-reverse**:
    - Description: Sets the flex wrap to wrap, nowrap, and wrap-reverse, respectively.
    - CSS Properties: `-ms-flex-wrap`, `flex-wrap`

#### Flex Fill, Grow, and Shrink:

- **.flex-fill**:
    - Description: Sets the flex grow and shrink to 1 and flex basis to auto.
    - CSS Properties: `-ms-flex`, `flex`

- **.flex-grow-0**, **.flex-grow-1**, **.flex-shrink-0**, **.flex-shrink-1**:
    - Description: Sets the flex grow and shrink to 0 or 1.
    - CSS Properties: `-ms-flex-positive`, `flex-grow`, `-ms-flex-negative`, `flex-shrink`

#### Justify Content:

- **.justify-content-start**, **.justify-content-end**, **.justify-content-center**, **.justify-content-between**, *
  *.justify-content-around**:
    - Description: Sets the alignment of flex items along the main axis to start, end, center, space-between, and
      space-around, respectively.
    - CSS Properties: `-ms-flex-pack`, `justify-content`

#### Align Items and Content:

- **.align-items-start**, **.align-items-end**, **.align-items-center**, **.align-items-baseline**, *
  *.align-items-stretch**:
    - Description: Sets the alignment of flex items and the cross-axis to start, end, center, baseline, and stretch,
      respectively.
    - CSS Properties: `-ms-flex-align`, `align-items`

- **.align-content-start**, **.align-content-end**, **.align-content-center**, **.align-content-between**, *
  *.align-content-around**, **.align-content-stretch**:
    - Description: Sets the alignment of flex lines within a flex container to start, end, center, space-between,
      space-around, and stretch, respectively.
    - CSS Properties: `-ms-flex-line-pack`, `align-content`

#### Align Self:

- **.align-self-auto**, **.align-self-start**, **.align-self-end**, **.align-self-center**, **.align-self-baseline**, *
  *.align-self-stretch**:
    - Description: Sets the alignment of a flex item within its flex container to auto, start, end, center, baseline,
      and stretch, respectively.
    - CSS Properties: `-ms-flex-item-align`, `align-self`

#### Row:

- **.row**:
    - Description: Creates a row within a flex container, with wrapped elements and adjusted margins.
    - CSS
      Properties: `display: -ms-flexbox; display: flex; -ms-flex-wrap: wrap; flex-wrap: wrap; margin-right: -15px; margin-left: -15px;`

#### Flex Grow:

- **.flex-1**, **.flex-2**, **.flex-3**, **.flex-4**:
    - Description: Sets the flex grow property to 1, 2, 3, or 4, respectively.
    - CSS Properties: `flex: 1;`, `flex: 2;`, `flex: 3;`, `flex: 4;`

### Usage

These flexbox classes can be applied to HTML elements to manage their layout within a flexible container. Choose the
appropriate class based on the desired flex behavior and alignment. The `!important` flag is used to ensure that these
styles override any other existing styles.

### 8. Grid Classes

#### Display Grid:

- **.d-grid**:
    - Description: Sets the display property to grid, allowing the element to use the CSS Grid layout model.
    - CSS Properties: `display: grid;`

#### Grid Gap:

- **.g-4**:
    - Description: Sets the gap between grid items to 4px.
    - CSS Properties: `gap: 4px;`

- **.g-8**:
    - Description: Sets the gap between grid items to 8px.
    - CSS Properties: `gap: 8px;`

- **.g-12**:
    - Description: Sets the gap between grid items to 12px.
    - CSS Properties: `gap: 12px;`

- **.g-16**:
    - Description: Sets the gap between grid items to 16px.
    - CSS Properties: `gap: 16px;`

- **.g-24**:
    - Description: Sets the gap between grid items to 24px.
    - CSS Properties: `gap: 24px;`

- **.g-32**:
    - Description: Sets the gap between grid items to 32px.
    - CSS Properties: `gap: 32px;`

### Usage

These grid classes can be applied to HTML elements to manage their layout using the CSS Grid system. Choose the
appropriate class based on the desired grid behavior and gap size. The `display: grid;` property is used to enable the
CSS Grid layout model, while the `gap` property adjusts the spacing between grid items.

### 9. Gutters Control Classes

- **.no-gutters**:
    - Description: Eliminates the margin and padding on grid columns, ensuring no space between them.
    - CSS Properties:
        ```
        margin-right: 0;
        margin-left: 0;
        ```
- **.no-gutters > .col**, **.no-gutters > [class*="col-"]**:
    - Description: Removes the padding on grid columns within the no-gutters container, ensuring no space between
      columns.
    - CSS Properties:
        ```
        padding-right: 0;
        padding-left: 0;
        ```

### Usage

These gutter control classes can be applied to the grid system to adjust the spacing and gutters between grid columns.
Use the `.no-gutters` class to eliminate the margins between columns and the associated padding classes to control the
padding within the no-gutters container. This allows for more precise control over the layout and spacing of the grid
system.

### 10. Offset Classes

#### Offset Amounts:

- **.offset-1**:
    - Description: Sets the left margin to 8.333333% to create an offset equivalent to one grid column width.
    - CSS Properties: `margin-left: 8.333333%;`

- **.offset-2**:
    - Description: Sets the left margin to 16.666667% to create an offset equivalent to two grid column widths.
    - CSS Properties: `margin-left: 16.666667%;`

- **.offset-3**:
    - Description: Sets the left margin to 25% to create an offset equivalent to three grid column widths.
    - CSS Properties: `margin-left: 25%;`

- **.offset-4**:
    - Description: Sets the left margin to 33.333333% to create an offset equivalent to four grid column widths.
    - CSS Properties: `margin-left: 33.333333%;`

- **.offset-5**:
    - Description: Sets the left margin to 41.666667% to create an offset equivalent to five grid column widths.
    - CSS Properties: `margin-left: 41.666667%;`

- **.offset-6**:
    - Description: Sets the left margin to 50% to create an offset equivalent to six grid column widths.
    - CSS Properties: `margin-left: 50%;`

- **.offset-7**:
    - Description: Sets the left margin to 58.333333% to create an offset equivalent to seven grid column widths.
    - CSS Properties: `margin-left: 58.333333%;`

- **.offset-8**:
    - Description: Sets the left margin to 66.666667% to create an offset equivalent to eight grid column widths.
    - CSS Properties: `margin-left: 66.666667%;`

- **.offset-9**:
    - Description: Sets the left margin to 75% to create an offset equivalent to nine grid column widths.
    - CSS Properties: `margin-left: 75%;`

- **.offset-10**:
    - Description: Sets the left margin to 83.333333% to create an offset equivalent to ten grid column widths.
    - CSS Properties: `margin-left: 83.333333%;`

- **.offset-11**:
    - Description: Sets the left margin to 91.666667% to create an offset equivalent to eleven grid column widths.
    - CSS Properties: `margin-left: 91.666667%;`

### Usage

These offset classes can be applied to grid columns to create space between columns and adjust the layout. Use the
appropriate offset class based on the desired width for the offset. The percentages provided represent the proportion of
the total width of the container.

### 11. Order Classes

#### First and Last Order:

- **.order-first**:
    - Description: Sets the order of the element to -1, making it appear first in the flex container.
    - CSS Properties:
        ```
        -ms-flex-order: -1;
        order: -1;
        ```

- **.order-last**:
    - Description: Sets the order of the element to 13, making it appear last in the flex container.
    - CSS Properties:
        ```
        -ms-flex-order: 13;
        order: 13;
        ```

#### Numeric Order:

- **.order-0** to **.order-12**:
    - Description: Sets the order of the element to the corresponding numeric value, determining its position within the
      flex container.
    - CSS Properties:
        ```
        -ms-flex-order: [value];
        order: [value];
        ```
    - The values range from 0 to 12, allowing for precise control over the order of elements.

### Usage

These order classes can be applied to flex items within a flex container to control the visual order of the elements.
Use the `.order-first` and `.order-last` classes to place elements at the beginning or end of the container,
respectively. Utilize the `.order-[n]` classes to specify the order of elements between 0 and 12, adjusting their
positions within the flex container.

### 12. Overflow Classes

- **.overflow-auto**:
    - Description: Sets the overflow property to auto, enabling scrolling when the content exceeds the container's
      dimensions.
    - CSS Properties: `overflow: auto !important;`

- **.overflow-hidden**:
    - Description: Sets the overflow property to hidden, hiding any content that exceeds the container's dimensions.
    - CSS Properties: `overflow: hidden !important;`

### Usage

These overflow classes can be applied to elements to control the behavior of overflowing content within a container. Use
the `.overflow-auto` class to enable scrolling when the content exceeds the container's dimensions. Use
the `.overflow-hidden` class to hide any content that extends beyond the container's boundaries. These classes are
essential for managing the visibility and scrolling behavior of content within a confined space.

### 13. Position and Display Classes

- **.position-static**:
    - Description: Sets the position property to static, allowing the element to appear in its default position in the
      document flow.
    - CSS Properties: `position: static !important;`

- **.position-relative**:
    - Description: Sets the position property to relative, enabling the use of top, right, bottom, and left properties
      to position the element relative to its normal position.
    - CSS Properties: `position: relative !important;`

- **.position-absolute**:
    - Description: Sets the position property to absolute, allowing the element to be positioned relative to its nearest
      positioned ancestor.
    - CSS Properties: `position: absolute !important;`

- **.position-fixed**:
    - Description: Sets the position property to fixed, fixing the element relative to the viewport, even when the page
      is scrolled.
    - CSS Properties: `position: fixed !important;`

- **.position-sticky**:
    - Description: Sets the position property to sticky, enabling the element to stick to its nearest scrolling ancestor
      or the viewport if no ancestor is scrolling.
    - CSS Properties: `position: -webkit-sticky !important; position: sticky !important;`

- **.fixed-top**:
    - Description: Sets the position to fixed and places the element at the top of the viewport.
    - CSS Properties:
        ```
        position: fixed;
        top: 0;
        right: 0;
        left: 0;
        z-index: 1030;
        ```

- **.fixed-bottom**:
    - Description: Sets the position to fixed and places the element at the bottom of the viewport.
    - CSS Properties:
        ```
        position: fixed;
        right: 0;
        bottom: 0;
        left: 0;
        z-index: 1030;
        ```

- **.sticky-top**:
    - Description: Sets the position to sticky and places the element at the top of the viewport, sticking to its
      nearest scrolling ancestor.
    - CSS Properties:
        ```
        position: -webkit-sticky;
        position: sticky;
        top: 0;
        z-index: 1020;
        ```

### 14. Screen Reader Classes

- **.sr-only**:
    - Description: Hides an element visually while still allowing it to be read by screen readers.
    - CSS Properties:
        ```
        position: absolute;
        width: 1px;
        height: 1px;
        padding: 0;
        margin: -1px;
        overflow: hidden;
        clip: rect(0, 0, 0, 0);
        white-space: nowrap;
        border: 0;
        ```

- **.sr-only-focusable:active, .sr-only-focusable:focus**:
    - Description: Reveals the element when it's in focus or active, ensuring its content is accessible to screen
      readers during interaction.
    - CSS Properties:
        ```
        position: static;
        width: auto;
        height: auto;
        overflow: visible;
        clip: auto;
        white-space: normal;
        ```

### Usage

These position and display classes can be applied to elements to control their positioning and behavior within the
layout. Use the appropriate class based on the desired positioning behavior. Additionally, the screen reader classes
allow for the creation of accessible content that is hidden visually but accessible to screen readers, improving the
overall accessibility of the web page.

### 15. Shadow Classes

- **.shadow-sm**:
    - Description: Applies a small shadow effect to the element, creating a subtle sense of elevation.
    - CSS Properties: `box-shadow: 0 0.125rem 0.25rem rgba(0, 0, 0, 0.075) !important;`

- **.shadow**:
    - Description: Applies a moderate shadow effect to the element, enhancing its sense of elevation and depth.
    - CSS Properties: `box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.15) !important;`

- **.shadow-lg**:
    - Description: Applies a large shadow effect to the element, creating a significant sense of elevation and depth.
    - CSS Properties: `box-shadow: 0 1rem 3rem rgba(0, 0, 0, 0.175) !important;`

- **.shadow-none**:
    - Description: Removes any existing shadow effect from the element, ensuring it has no shadow.
    - CSS Properties: `box-shadow: none !important;`

### Usage

These shadow classes can be applied to elements to add depth and dimension to their appearance. Use the appropriate
class based on the desired shadow effect for the element. The `.shadow-sm` class creates a subtle elevation effect,
while `.shadow` produces a moderate shadow effect. The `.shadow-lg` class creates a significant sense of elevation and
depth. Use the `.shadow-none` class to remove any existing shadow effect from the element. Experiment with these classes
to achieve the desired visual effect for elements on the page.

### 16. Width and Height Classes

- **.w-25**:
    - Description: Sets the width of the element to 25% of its parent container.
    - CSS Properties: `width: 25% !important;`

- **.w-50**:
    - Description: Sets the width of the element to 50% of its parent container.
    - CSS Properties: `width: 50% !important;`

- **.w-75**:
    - Description: Sets the width of the element to 75% of its parent container.
    - CSS Properties: `width: 75% !important;`

- **.w-100**:
    - Description: Sets the width of the element to 100% of its parent container.
    - CSS Properties: `width: 100% !important;`

- **.w-auto**:
    - Description: Sets the width of the element to its automatic value, allowing the browser to determine the width.
    - CSS Properties: `width: auto !important;`

- **.h-25**:
    - Description: Sets the height of the element to 25% of its parent container.
    - CSS Properties: `height: 25% !important;`

- **.h-50**:
    - Description: Sets the height of the element to 50% of its parent container.
    - CSS Properties: `height: 50% !important;`

- **.h-75**:
    - Description: Sets the height of the element to 75% of its parent container.
    - CSS Properties: `height: 75% !important;`

- **.h-100**:
    - Description: Sets the height of the element to 100% of its parent container.
    - CSS Properties: `height: 100% !important;`

- **.h-auto**:
    - Description: Sets the height of the element to its automatic value, allowing the browser to determine the height.
    - CSS Properties: `height: auto !important;`

- **.mw-100**:
    - Description: Sets the maximum width of the element to 100% of its parent container.
    - CSS Properties: `max-width: 100% !important;`

- **.mh-100**:
    - Description: Sets the maximum height of the element to 100% of its parent container.
    - CSS Properties: `max-height: 100% !important;`

- **.min-vw-100**:
    - Description: Sets the minimum width of the element to 100 viewport width.
    - CSS Properties: `min-width: 100vw !important;`

- **.min-vh-100**:
    - Description: Sets the minimum height of the element to 100 viewport height.
    - CSS Properties: `min-height: 100vh !important;`

- **.vw-100**:
    - Description: Sets the width of the element to 100 viewport width.
    - CSS Properties: `width: 100vw !important;`

- **.vh-100**:
    - Description: Sets the height of the element to 100 viewport height.
    - CSS Properties: `height: 100vh !important;`

### Usage

These classes allow for easy manipulation of width and height properties for elements on the page. Use the appropriate
class to set the desired width or height for the element, depending on the layout requirements. The viewport-based
classes allow for control over the dimensions based on the viewport size. Utilize these classes to create responsive and
dynamic layouts for the web application or website.
