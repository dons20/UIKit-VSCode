# UIKit 3.0 Snippets for Visual Studio Code

[![Version](https://vsmarketplacebadge.apphb.com/version/Keno.uikit-3-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Keno.uikit-3-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/Keno.uikit-3-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Keno.uikit-3-snippets)
[![Rating](https://vsmarketplacebadge.apphb.com/rating/Keno.uikit-3-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=Keno.uikit-3-snippets)

[![Demo Image](https://thumbs.gfycat.com/WeakRemorsefulHornshark-size_restricted.gif)](https://gfycat.com/weakremorsefulhornshark)

## [🌞 View the Changelog](https://github.com/dons20/UIKit-VSCode/blob/master/CHANGELOG.md) to see what's new!

---

This extension adds all the snippets from [UIKit 3.0](https://getuikit.com/docs/introduction) into Visual Studio Code for easy access and usage.

To show support for the project, you can do any of the following:

-   [Rate the extension on the marketplace](https://marketplace.visualstudio.com/items?itemName=Keno.uikit-3-snippets)
-   [Star the repository](https://github.com/dons20/UIKit-VSCode)
-   [Follow me on Twitter](https://twitter.com/KCInnovations)

> Please remember to direct your issues, queries and suggestions to the [issues page](https://github.com/dons20/UIKit-VSCode/issues) of the repository.

_Please note: While effort is made to make the snippets easy to use without documentation, some components are too complex to provide comprehensive descriptions/snippets so be sure to check the [official documentation](https://getuikit.com/docs/)!_

Thank You!

## Setup

#### Method 1

1. Go to Extensions by pressing Ctrl-Shift-X (Windows/Linux) or Cmd-Shift-X (Mac)
2. Search for UIKit 3.0 Snippets
3. Click on Install
4. Reload your editor and you're good to go!

#### Method 2

1. With Visual Studio Code opened, press `Ctrl+P`.
2. Type in `ext install uikit-3-snippets` and press `Enter`.

## Table of Contents

<details>
  <summary><strong>Reveal Table of Contents</strong></summary>
  <p>

-   [UIKit 3.0 Snippets](#uikit-30-snippets-for-visual-studio-code)
-   [Setup](#setup)
    -   [Method 1](#method-1)
    -   [Method 2](#method-2)
-   [Table of Contents](#table-of-contents)
-   [Usage](#usage)
-   [Contribution Guidelines](#contribution-guidelines)
    -   [Snippet Template](#snippet-template)
-   [Changelog](#changelog)
-   [License](#license)
-   [References](#references)
-   [List of Commands (HTML5/PHP)](#list-of-commands-htmlphp)

    <details>
    <summary><strong>Reveal List of Commands (HTML5/PHP)</strong></summary>
    <p>

    -   [UIKit Master Template](#uikit-master-template)
    -   [Accordion](#accordion)
    -   [Alert](#alert)
    -   [Alignment](#alignment)
    -   [Animation](#animation)
    -   [Article](#article)
    -   [Background](#background)
    -   [Badge](#badge)
    -   [Breadcrumb](#breadcrumb)
    -   [Button](#button)
    -   [Card](#card)
    -   [Close](#close)
    -   [Column](#column)
    -   [Comment](#comment)
    -   [Container](#container)
    -   [Countdown](#countdown)
    -   [Cover](#cover)
    -   [Description List](#description-list)
    -   [Disabled](#disabled)
    -   [Divider](#divider)
    -   [Dotnav](#dotnav)
    -   [Drop](#drop)
    -   [Dropdown](#dropdown)
    -   [Filter](#filter)
    -   [Flex](#flex)
    -   [Form](#form)
    -   [Grid](#grid)
    -   [Grid Parallax](#grid-parallax)
    -   [Heading](#heading)
    -   [Height](#height)
    -   [Icon](#icon)
    -   [Iconnav](#iconnav)
    -   [Image](#image)
    -   [Inverse](#inverse)
    -   [Label](#label)
    -   [Leader](#leader)
    -   [Lightbox](#lightbox)
    -   [Link](#link)
    -   [List](#list)
    -   [Margin](#margin)
    -   [Marker](#marker)
    -   [Modal](#modal)
    -   [Nav](#nav)
    -   [Navbar](#navbar)
    -   [Notification](#notification)
    -   [Offcanvas](#offcanvas)
    -   [Overlay](#overlay)
    -   [Padding](#padding)
    -   [Pagination](#pagination)
    -   [Parallax](#parallax)
    -   [Placeholder](#placeholder)
    -   [Position](#position)
    -   [Progress](#progress)
    -   [Scroll](#scroll)
    -   [Scrollspy](#scrollspy)
    -   [Search](#search)
    -   [Section](#section)
    -   [Slidenav](#slidenav)
    -   [Slider](#slider)
    -   [Slideshow](#slideshow)
    -   [Sortable](#sortable)
    -   [Spinner](#spinner)
    -   [Sticky](#sticky)
    -   [Subnav](#subnav)
    -   [SVG](#svg)
    -   [Switcher](#switcher)
    -   [Tab](#tab)
    -   [Table](#table)
    -   [Text](#text)
    -   [Thumbnav](#thumbnav)
    -   [Tile](#tile)
    -   [Toggle](#toggle)
    -   [Tooltip](#tooltip)
    -   [Totop](#totop)
    -   [Transition](#transition)
    -   [Upload](#upload)
    -   [Utility](#utility)
    -   [Video](#video)
    -   [Visibility](#visibility)
    -   [Width](#width)

        </p>
        </details>

    -   [List of Commands (Javascript)](#list-of-commands-javascript)

            <details>
            <summary><strong>Reveal List of Commands (Javascript)</strong></summary>
            <p>

            * [Accordion JS](#accordion-js)
            * [Alert JS](#alert-js)
            * [Countdown JS](#countdown-js)
            * [Cover JS](#cover-js)
            * [Drop JS](#drop-js)
            * [Dropdown JS](#dropdown-js)
            * [Filter JS](#filter-js)
            * [Form JS](#form-js)
            * [Grid JS](#grid-js)
            * [Grid Parallax JS](#grid-parallax-js)
            * [Icon JS](#icon-js)
            * [Image JS](#image-js)
            * [Lightbox JS](#lightbox-js)
            * [Margin JS](#margin-js)
            * [Modal JS](#modal-js)
            * [Nav JS](#nav-js)
            * [Navbar JS](#navbar-js)
            * [Notification JS](#notification-js)
            * [Offcanvas JS](#offcanvas-js)
            * [Parallax JS](#parallax-js)
            * [Scroll JS](#scroll-js)
            * [Scrollspy JS](#scrollspy-js)
            * [Slider JS](#slider-js)
            * [Slideshow JS](#slideshow-js)
            * [Sortable JS](#sortable-js)
            * [Sticky JS](#sticky-js)
            * [SVG JS](#svg-js)
            * [Switcher JS](#switcher-js)
            * [Tab JS](#tab-js)
            * [Toggle JS](#toggle-js)
            * [Tooltip JS](#tooltip-js)
            * [Upload JS](#upload-js)
            * [Video JS](#video-js)
            </p>
            </details>

          </p>
        </details>

## Usage

To use the snippets, open a HTML file, and start typing `uk-` (optionally followed by `Ctrl+Space` depending on user settings). A list of UIKit snippets will show up.
Each snippet has a short and simple description to aid with understanding its use.
For more details and even better examples and possible options, [head to the UIKit Documentation](https://getuikit.com/docs/introduction)

A detailed list of supported commands are listed below in the [**List of Commands**](#list-of-commands-htmlphp) section.

## Contribution Guidelines

[Read the contribution guidelines](/CONTRIBUTING.md)

## Changelog

[View the changelog](/CHANGELOG.md)

## License

UIKit 3.0 Snippets - Visual Studio Code plugin is licensed under the [MIT License](http://opensource.org/licenses/MIT)

## References

[Readme layout inspiration](https://github.com/1tontech/bootstrap4-snippets/tree/master/vscode)

[UIKit Snippets Original Source](https://getuikit.com/docs/introduction)

## List of Commands (HTML/PHP)

<details>
  <summary><strong>Click to Reveal List of Commands (HTML/PHP)</strong></summary>
  <p>
  
### UIKit Master Template
<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                    |
|---------------------------|------------------------------------------------|
| uk-\$                     | Creates a basic UIKit template                 |
| uk-\$-css-import          | Imports a chosen minified css file for UIKit   |
| uk-\$-js-import           | Imports the default minified scripts for UIKit |
| uk-\$-js-component-import | Imports a selected js component file for UIKit |

</p>
</details>

### Accordion

<details><summary>Reveal Content</summary>
<p>

| Trigger                    | Description                                                           |
|----------------------------|-----------------------------------------------------------------------|
| uk-accordion               | [Attribute] Used to create an accordion element in a parent container |
| uk-accordion-sample        | Creates a sample Accordion component                                  |
| uk-accordion-no-collapse   | Accordion that always keeps one item open                             |
| uk-accordion-multiple-open | Accordion that allows multiple items to be opened at once             |
| uk-accordion-open-index    | Accordion that opens an item by default                               |

</p>
</details>

### Alert

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                    |
|------------------|----------------------------------------------------------------|
| uk-alert         | [Attribute] Used to create an alert element in a block element |
| uk-alert-default | A default alert applied to a div                               |
| uk-alert-close   | An alert with a close button                                   |
| uk-alert-styled  | An alert with a chosen style applied                           |

</p>
</details>

### Alignment

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                                       |
|---------------------|---------------------------------------------------|
| uk-align            | [Class] Floats the element to a selected position |
| uk-align-responsive | [Class] Floats the element on specific widths     |

</p>
</details>

### Animation

<details><summary>Reveal Content</summary>
<p>

| Trigger                       | Description                                                              |
|-------------------------------|--------------------------------------------------------------------------|
| uk-animation-fade             | [Class] The element fades in                                             |
| uk-animation-scale            | [Class] The element fades in and scales up or down                       |
| uk-animation-slide            | [Class] The element fades in and slides in from a chosen direction       |
| uk-animation-slide-custom     | [Class] The element slides in with a specific distance                   |
| uk-animation-kenburns         | [Class] The element scales slowly up without fading in                   |
| uk-animation-shake            | [Class] The element shakes                                               |
| uk-animation-stroke           | [Class] The SVG element strokes are drawn                                |
| uk-animation-stroke-svg       | Easier usage of svg stroke animations                                    |
| uk-animation-reverse          | [Class] The element's animation plays in reverse                         |
| uk-animation-fast             | [Class] The element's animation plays at a faster speed                  |
| uk-animation-transform-origin | [Class] The element scales in from a different direction                 |
| uk-animation-toggle           | [Class] Added to a parent element to toggle animations on hover or focus |

</p>
</details>

### Article

<details><summary>Reveal Content</summary>
<p>

| Trigger           | Description                                 |
|-------------------|---------------------------------------------|
| uk-article-basic  | A basic article layout                      |
| uk-article-sample | A complete sample article with placeholders |

</p>
</details>

### Background

<details><summary>Reveal Content</summary>
<p>

| Trigger                        | Description                                                         |
|--------------------------------|---------------------------------------------------------------------|
| uk-background-color            | [Class] Applies the selected background color                       |
| uk-background-size             | [Class] Scales the background image to a selected size              |
| uk-background-position         | [Class] Alters the initial position of the background iamge         |
| uk-background-norepeat         | [Class] Prevents the background image from being repeated           |
| uk-background-fixed            | [Class] Locks the image in place while scrolling                    |
| uk-background-image-responsive | [Class] Shows the background image on widths of chosen size upwards |
| uk-background-blend            | [Class] Applies a chosen blend mode to the background image         |

</p>
</details>

### Badge

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                                      |
|-----------------|------------------------------------------------------------------|
| uk-badge        | [Class] Used to create a notification badge in an inline element |
| uk-badge-span   | Creates a simple notification badge span                         |
| uk-badge-anchor | Creates a simple notification badge anchor                       |

</p>
</details>

### Breadcrumb

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                              |
|--------------------|------------------------------------------|
| uk-breadcrumb      | [Class] Used to create a breadcrumb list |
| uk-breadcrumb-list | Creates a default breadcrumb list        |

</p>
</details>

### Button

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                |
|--------------------------|------------------------------------------------------------|
| uk-button-anchor         | Creates an anchor with a button style                      |
| uk-button-styled         | Creates a button with a chosen style                       |
| uk-button-disabled       | Creates a disabled button                                  |
| uk-button-size           | Creates a button with a selected size                      |
| uk-button-dropdown       | Creates a button that toggles a dropdown menu              |
| uk-button-group          | Creates a group of buttons                                 |
| uk-button-group-dropdown | Creates a button group with a dropdown toggle on the right |

</p>
</details>

### Card

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                                                                  |
|-----------------------|------------------------------------------------------------------------------|
| uk-card-styled        | Creates a card with a chosen style                                           |
| uk-card-secondary     | Creates a card with a secondary style                                        |
| uk-card-hover         | Creates a card with a hover effect                                           |
| uk-card-small         | Creates a card with reduced padding                                          |
| uk-card-large         | Creates a card with increased padding                                        |
| uk-card-header-footer | Creates a card divided into three sections                                   |
| uk-card-media         | Displays an image inside a card without any spacing                          |
| uk-card-horizontal    | Creates a card with a horizontal layout (Ideal for media-left & media-right) |
| uk-card-badge         | Creates a card with a styled badge inside                                    |

</p>
</details>

### Close

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                               |
|-----------------------|-------------------------------------------|
| uk-close              | [Attribute] Used to create a close button |
| uk-close-button       | Creates a close button                    |
| uk-close-button-large | Creates a larger close button             |

</p>
</details>

### Column

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                                           |
|----------------------|---------------------------------------------------------------------------------------|
| uk-column            | [Class] Displays the inline content in multiple columns                               |
| uk-column-responsive | [Class] Displays the inline content in multiple columns on specific width breakpoints |
| uk-column-divider    | [Class] Displays the inline content in multiple columns seperated by dividers         |
| uk-column-span       | Creates a column with an inline element that spans each column                        |

</p>
</details>

### Comment

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                                          |
|--------------------|------------------------------------------------------|
| uk-comment-default | Creates a standard comment layout                    |
| uk-comment-primary | Creates a highlighted comment with a standard layout |
| uk-comment-list    | Creates a nestable list of comments                  |

</p> 
</details>

### Container

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                 |
|----------------------|---------------------------------------------|
| uk-container         | [Class] Used to create a centered container |
| uk-container-default | Creates a centered container                |
| uk-container-size    | Creates a container with varying size       |

</p>
</details>

### Countdown

<details><summary>Reveal Content</summary>
<p>

| Trigger                | Description                                                              |
|------------------------|--------------------------------------------------------------------------|
| uk-countdown           | [Attribute] Used to create a countdown timer                             |
| uk-countdown-sample    | Creates a countdown timer. Date is in the format: YYYY-MM-DDThh:mm:ssTZD |
| uk-countdown-separator | Creates a countdown timer with each number separated by a colon          |
| uk-countdown-label     | Used to add a label to each number on the countdown timer                |

</p>
</details>

### Cover

<details><summary>Reveal Content</summary>
<p>

| Trigger                       | Description                                                 |
|-------------------------------|-------------------------------------------------------------|
| uk-cover-container            | Creates an image that covers its parent element             |
| uk-cover-container-video      | Creates a video that covers its parent element              |
| uk-cover-container-iframe     | Creates an iframe that covers its parent element            |
| uk-cover-container-responsive | Creates an element that scales responsively with its parent |

</p>
</details>

### Description List

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                                              |
|-----------------------------|--------------------------------------------------------------------------|
| uk-description-list         | [Class] Used to create a description list                                |
| uk-description-list-sample  | Creates a sample list to display terms and descriptions below each other |
| uk-description-list-divider | Creates a divided description list                                       |

</p>
</details>

### Disabled

<details><summary>Reveal Content</summary>
<p>

| Trigger     | Description                            |
|-------------|----------------------------------------|
| uk-disabled | [Class] Disables an item within a list |

</p>
</details>

### Divider

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                         |
|---------------------|-------------------------------------|
| uk-divider-icon     | Creates a divider with a decoration |
| uk-divider-small    | Creates a smaller divider           |
| uk-divider-vertical | Creates a vertical divider          |

</p>
</details>

### Dotnav

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                            |
|-----------------------------|--------------------------------------------------------|
| uk-dotnav                   | Creates a navigation list with dots                    |
| uk-dotnav-vertical          | Creates a vertical navigation list with dots           |
| uk-dotnav-overlay           | Creates a dotnav as an overlay for an element          |
| uk-dotnav-centered-viewport | Creates a dotnav centered vertically and aligned right |

</p>
</details>

### Drop

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                 |
|--------------------------|-------------------------------------------------------------|
| uk-drop                  | [Attribute] Used to create a drop component                 |
| uk-drop-basic            | Creates a basic drop component                              |
| uk-drop-example          | Creates two example drops with different modes              |
| uk-drop-grid             | Creates a drop with a grid inside                           |
| uk-drop-position         | Creates a drop with its alignment adjusted                  |
| uk-drop-boundary         | Creates a drop with a predetermined element as its boundary |
| uk-drop-boundary-aligned | Creates a drop aligned to its boundary                      |
| uk-drop-offset           | Creates a drop with an offset                               |
| uk-drop-animated         | Creates a drop with an offset                               |

</p>
</details>

### Dropdown

<details><summary>Reveal Content</summary>
<p>

| Trigger                      | Description                                                            |
|------------------------------|------------------------------------------------------------------------|
| uk-dropdown                  | [Attribute] Used to create a dropdown in a block element such as a div |
| uk-dropdown-basic            | Creates a basic dropdown underneath a button toggle                    |
| uk-dropdown-basic-inline     | Creates a basic dropdown grouped with its toggle                       |
| uk-dropdown-nav              | Creates a dropdown containing a nav element                            |
| uk-dropdown-grid             | Creates a dropdown containing a grid                                   |
| uk-dropdown-position         | Creates a dropdown with its alignment adjusted                         |
| uk-dropdown-boundary         | Determines a parent element as the dropdown's boundary                 |
| uk-dropdown-boundary-aligned | Aligns the dropdown to the parent's boundary                           |
| uk-dropdown-offset           | Defines a custom offset for the dropdown                               |
| uk-dropdown-animated         | Applies one or more animations to the dropdown                         |

</p>
</details>

### Filter

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                      |
|------------------|--------------------------------------------------|
| uk-filter        | [Attribute] Used to create a filter component    |
| uk-filter-sample | Used to filter or sort items in any given layout |

</p>
</details>

### Flex

<details><summary>Reveal Content</summary>
<p>

| Trigger                                 | Description                                                                       |
|-----------------------------------------|-----------------------------------------------------------------------------------|
| uk-flex                                 | [Class] Used to apply a flexbox layout model to an element                        |
| uk-flex-block                           | Creates a flex container and behaves like a block element                         |
| uk-flex-inline                          | Creates a flex container and behaves like an inline element                       |
| uk-flex-horizontal-alignment            | Defines the horizontal alignment of flex items and distributes space between them |
| uk-flex-horizontal-alignment-responsive | Defines the horizontal alignment of flex items on specific device widths          |
| uk-flex-vertical-alignment              | Defines the vertical alignment of flex items and distributes space between them   |
| uk-flex-direction                       | Defines the axis that flex items are placed on and their direction                |
| uk-flex-wrap-modifier                   | Defines the axis that flex items are placed on and their direction                |
| uk-flex-item-order                      | [Class] Displays an item as the first or last one (Add to item)                   |
| uk-flex-item-dimensions                 | [Class] Determines how much space a flex item should take up (Add to item)        |
| uk-flex-grid-example                    | Creates a sample flex with a grid inside                                          |

</p>
</details>

### Form

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                                                                                      |
|-------------------------|------------------------------------------------------------------------------------------------------------------|
| uk-form-sample          | Creates a sample form with all elements as reference                                                             |
| uk-form-fieldset        | Creates a fieldset for a form                                                                                    |
| uk-form-legend          | Creates a legend for a form                                                                                      |
| uk-form-states          | [Class] Applies a custom state to a form control                                                                 |
| uk-form-disabled        | Disables a form control                                                                                          |
| uk-form-sizes           | Modifies the size of an input, select or textarea                                                                |
| uk-form-width-modifiers | Modifies the width of an input, select or textarea                                                               |
| uk-form-blank           | Minimizes the styling of form controls                                                                           |
| uk-form-stacked         | Stacks labels and controls on top of each other                                                                  |
| uk-form-horizontal      | Aligns labels and controls horizontally (use uk-form-controls-text to better align checkboxes and radio buttons) |
| uk-form-icon            | Creates a form control with an icon inside to the left (or right with flip class)                                |
| uk-form-icon-click      | Creates a form icon that can be clicked                                                                          |
| uk-form-grid-example    | Creates a form defined by a grid layout                                                                          |
| uk-form-custom-control  | Replaces a file input or select form with your own HTML content                                                  |

</p>
</details>

### Grid

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                                   |
|-------------------------|---------------------------------------------------------------|
| uk-grid                 | [Attribute] Used to create a grid container inside a div      |
| uk-grid-stacked         | Creates a basic stacked grid container                        |
| uk-grid-expanded        | Creates an expanded grid container with elements side by side |
| uk-grid-gutter-modifier | Modifies the spacing between grid items                       |
| uk-grid-nested-sample   | Creates a sample nested grid                                  |
| uk-grid-divided         | Seperates each grid cell with lines                           |
| uk-grid-match-height    | Matches the height of all grid cells                          |
| uk-grid-match-cell      | [Class] Matches the height of a grid cell                     |
| uk-grid-width           | Manually determines the column widths                         |
| uk-grid-flex            | Combines a grid element with flex                             |
| uk-grid-masonry         | Allows grid items of different heights to fit seamlessly      |
| uk-grid-parallax        | Used to add a scrolling effect to columns within a grid       |

</p>
</details>

### Heading

<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| uk-heading-primary        | [Class] Used to create a heading with a specified size           |
| uk-heading-primary-sample | Creates a heading with a specified size                          |
| uk-heading-divider        | [Class] Used to create a heading with a divider underneath       |
| uk-heading-divider-sample | Creates a heading with a divider underneath                      |
| uk-heading-bullet         | [Class] Used to create a heading used in a list                  |
| uk-heading-bullet-sample  | Creates a heading as part of a list                              |
| uk-heading-line           | [Class] Used to create a heading with a vertically centered line |
| uk-heading-line-sample    | Creates a heading with a vertically centered line                |

</p>
</details>

### Height

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                                       |
|--------------------------|-----------------------------------------------------------------------------------|
| uk-height                | [Class] Modifies the height of an element to 100%/150px/300px/450px respectively. |
| uk-max-height            | [Class] Modifies the max-height of an element to 150px/300px/450px respectively.  |
| uk-viewport-height       | [Attribute] Modifies the height of an element to fill the entire viewport.        |
| uk-match-height          | [Attribute] Expands all children of a container to the same height.               |
| uk-match-height-specific | [Attribute] Matches the height of specific child elements                         |
| uk-match-height-all      | [Attribute] Matches the height of all child elements even in other rows           |

</p>
</details>

### Icon

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                                                               |
|-------------------------|-------------------------------------------------------------------------------------------|
| uk-icon-span            | Creates an icon within a span. (List of Icons Here: https://getuikit.com/docs/icon)       |
| uk-icon-link            | Creates an icon within a link. (List of Icons Here: https://getuikit.com/docs/icon)       |
| uk-icon-ratio           | Modifies the size of the icon by the ratio                                                |
| uk-icon-link-modifier   | Resets the default link styling to a more muted color when using an icon inside an anchor |
| uk-icon-button-modifier | Creates an icon button                                                                    |
| uk-icon-image-modifier  | Scales a background image to the size of an icon                                          |

</p>
</details>

### Iconnav

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                                             |
|-----------------------|---------------------------------------------------------|
| uk-iconnav            | [Class] Used to create a navigation consisting of icons |
| uk-iconnav-horizontal | Creates a navigation consisting of icons                |
| uk-iconnav-vertical   | Creates a vertical navigation consisting of icons       |

</p>
</details>

### Image

<details><summary>Reveal Content</summary>
<p>

| Trigger       | Description                                                               |
|---------------|---------------------------------------------------------------------------|
| uk-img        | [Attribute] Lazy-load images on any element with ease                     |
| uk-img-sample | Creates a basic lazy-loaded image component                               |
| uk-img-custom | Creates an element with lazy-load applied                                 |
| uk-img-target | Creates an image component which triggers on another element's visibility |

</p>
</details>

### Inverse

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                                             |
|------------------|-----------------------------------------------------------------------------------------|
| uk-light         | [Class] Used to improve the visibility of objects on light backgrounds in a light style |
| uk-inverse-light | Improves the visibility of objects on dark backgrounds in a light style                 |
| uk-dark          | [Class] Used to improve the visibility of objects on light backgrounds in a dark style  |
| uk-inverse-dark  | Improves the visibility of objects on light backgrounds in a dark style                 |

</p>
</details>

### Label

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                      |
|------------------|--------------------------------------------------|
| uk-label         | [Class] Used to create a label in a span element |
| uk-label-default | Creates a label with a default style             |
| uk-label-success | Creates a label with a success style             |
| uk-label-warning | Creates a label with a warning style             |
| uk-label-danger  | Creates a label with a danger style              |

</p>
</details>

### Leader

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                        |
|------------------|--------------------------------------------------------------------|
| uk-leader        | [Attribute] Visually connects horizontal items with a line of dots |
| uk-leader-sample | Creates a sample leader component                                  |

</p>
</details>

### Lightbox

<details><summary>Reveal Content</summary>
<p>

| Trigger                       | Description                                                              |
|-------------------------------|--------------------------------------------------------------------------|
| uk-lightbox                   | [Attribute] Turns all the anchors inside a container into lightbox links |
| uk-lightbox-basic             | Creates a lightbox container with an anchor inside                       |
| uk-lightbox-caption           | Creates a lightbox container with a caption at the bottom                |
| uk-lightbox-animation         | Creates a lightbox container with a modified transition animation        |
| uk-lightbox-alternate-content | Creates a lightbox container with multiple content types                 |

</p>
</details>

### Link

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                                                             |
|-----------------|-----------------------------------------------------------------------------------------|
| uk-link-muted   | Creates a link with a muted style                                                       |
| uk-link-text    | Creates a link with a body text style                                                   |
| uk-link-heading | Creates a link with a heading style                                                     |
| uk-link-reset   | Creates a link that inherits its color from its parent                                  |
| uk-link-toggle  | Creates a link on the parent element and applies a link style to one of its child nodes |

</p>
</details>

### List

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                                                 |
|--------------------------|---------------------------------------------------------------------------------------------|
| uk-list                  | [Class] Used to create a basic ordered or unordered list                                    |
| uk-list-basic            | Creates a basic ordered or unordered list                                                   |
| uk-list-bullet-modifier  | Creates a bulleted list                                                                     |
| uk-list-divider-modifier | Creates a divided list                                                                      |
| uk-list-striped-modifier | Creates a striped list                                                                      |
| uk-list-large-modifier   | Creates a list with increased spacing between items. Can be combined with other list styles |

</p>
</details>

### Margin

<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                                                                   |
|---------------------------|-----------------------------------------------------------------------------------------------|
| uk-margin                 | [Class] Adds top margin, if it is preceded by another element, and always bottom margin       |
| uk-margin-position        | [Class] Adds the selected margin to that side                                                 |
| uk-margin-size            | [Class] Adds a margin of chosen size                                                          |
| uk-margin-size-position   | [Class] Adds a margin of chosen size to the chosen side                                       |
| uk-margin-remove          | [Class] Removes all margins                                                                   |
| uk-margin-remove-position | [Class] Removes the margin the chosen side(s)                                                 |
| uk-margin-auto            | [Class] Sets left and right margins to auto, centering block and flex elements                |
| uk-margin-auto-position   | [Class] Sets the selected margin to auto, pushing block and flex elements to the opposite end |
| uk-margin-dynamic-sample  | Automatically adds spacing to stacking elements with the uk-margin attribute                  |

</p>
</details>

### Marker

<details><summary>Reveal Content</summary>
<p>

| Trigger   | Description                                                                     |
|-----------|---------------------------------------------------------------------------------|
| uk-marker | [Attribute] Used to create a marker icon that can be displayed on top of images |

</p>
</details>

### Modal

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                                 |
|-----------------------------|-------------------------------------------------------------|
| uk-modal                    | [Attribute] Used to create a modal                          |
| uk-modal-sample             | Creates a modal with a button toggle                        |
| uk-modal-close-default      | Creates a modal with close button inside                    |
| uk-modal-close-outside      | Creates a modal with close button outside                   |
| uk-modal-center             | Creates a centered modal using the parameter 'center'       |
| uk-modal-header-footer      | Creates a modal divided into different content sections     |
| uk-modal-caption            | Creates a modal with a caption outside of it                |
| uk-modal-container-modifier | Creates a modal that expands to the default container width |
| uk-modal-full-modifier      | Creates a modal that fills the entire page                  |

</p>
</details>

### Nav

<details><summary>Reveal Content</summary>
<p>

| Trigger                        | Description                                                           |
|--------------------------------|-----------------------------------------------------------------------|
| uk-nav                         | [Class] Used to create a nav with optional styling                    |
| uk-nav-default                 | Creates a nav with default styling                                    |
| uk-nav-nested                  | Creates a nested nav with default styling                             |
| uk-nav-accordion               | Creates an accordion-styled nav with icons for parents                |
| uk-nav-accordion-multiple-open | Creates an accordion nav that can have multiple sub-navs open at once |
| uk-nav-header                  | Creates a nav header                                                  |
| uk-nav-divider                 | Creates a nav divider                                                 |
| uk-nav-primary                 | Creates a nav with emphasized styling                                 |
| uk-nav-center                  | Creates a centered nav                                                |
| uk-nav-dropdown                | Creates a nav in a dropdown                                           |
| uk-nav-navbar                  | Creates a nav in a navbar                                             |

</p>
</details>

### Navbar

<details><summary>Reveal Content</summary>
<p>

| Trigger                             | Description                                                                     |
|-------------------------------------|---------------------------------------------------------------------------------|
| uk-navbar                           | [Attribute] Used to create a navigation bar                                     |
| uk-navbar-sample                    | Creates a primary navigation bar                                                |
| uk-navbar-multiple                  | Creates multiple navigations inside the navbar container                        |
| uk-navbar-click                     | Creates a primary navigation bar that is toggled with a click                   |
| uk-navbar-transparent               | Creates a transparent navigation bar                                            |
| uk-navbar-subtitle                  | Creates a subtitle for a navbar item                                            |
| uk-navbar-custom-content            | Creates a navbar which can hold custom items (text, icons, buttons, forms)      |
| uk-navbar-centered-logo             | Creates a navbar with a centered logo                                           |
| uk-navbar-toggle-item               | Creates a navbar with an icon as a toggle                                       |
| uk-navbar-dropdown                  | Creates a navbar with a dropdown component                                      |
| uk-navbar-dropdown-multiple-columns | Creates a navbar dropdown with multiple columns                                 |
| uk-navbar-dropdown-boundary-align   | Creates a navbar with dropdowns aligned to the navbar boundary                  |
| uk-navbar-dropdown-justify          | Creates a navbar with dropdowns justified                                       |
| uk-navbar-dropbar                   | Creates a navbar with dropdowns justified                                       |
| uk-navbar-dropbar-push              | Creates a navbar with a dropdown that pushes page content down to fit the space |

</p>
</details>

### Notification

<details><summary>Reveal Content</summary>
<p>

| Trigger                      | Description                                      |
|------------------------------|--------------------------------------------------|
| uk-notification-example      | Creates a notification example using javascript  |
| uk-notification-html-message | Creates a notification with html content         |
| uk-notification-position     | Creates a notification with an adjusted position |
| uk-notification-style        | Creates a styled notification                    |
| uk-notification-close-all    | Closes all notifications                         |

</p>
</details>

### Offcanvas

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                                           |
|-----------------------------|-----------------------------------------------------------------------|
| uk-offcanvas                | [Attribute] Used to create an off-canvas                              |
| uk-offcanvas-sample         | Creates a basic off-canvas                                            |
| uk-offcanvas-overlay        | Creates an off-canvas that adds an overlay to the page                |
| uk-offcanvas-flip-modifier  | Creates an off-canvas that slides in from the right                   |
| uk-offcanvas-animation-mode | Creates an off-canvas with a modified animation mode for its entrance |
| uk-offcanvas-nav            | Creates an off-canvas containing a nav component                      |

</p>
</details>

### Overlay

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                            |
|--------------------------|--------------------------------------------------------|
| uk-overlay               | [Class] Used to create a basic image overlay           |
| uk-overlay-basic         | Creates a basic image overlay at a modifiable position |
| uk-overlay-style-default | Creates an image overlay with a default style          |
| uk-overlay-style-primary | Creates an image overlay with a primary style          |
| uk-overlay-icon          | Creates an image overlay icon                          |

</p>
</details>

### Padding

<details><summary>Reveal Content</summary>
<p>

| Trigger                    | Description                                                   |
|----------------------------|---------------------------------------------------------------|
| uk-padding                 | [Class] Adds default padding to the element                   |
| uk-padding-size            | [Class] Adds a smaller or larger padding to the element       |
| uk-padding-remove          | [Class] Removes all padding from an element                   |
| uk-padding-remove-position | [Class] Removes padding from the chosen side(s) of an element |

</p>
</details>

### Pagination

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                                             |
|-----------------------------|-------------------------------------------------------------------------|
| uk-pagination               | [Class] Used to create a simple pagination for navigation through pages |
| uk-pagination-basic         | Creates a simple pagination for navigation through pages                |
| uk-pagination-alignment     | Creates a simple pagination aligned with flex                           |
| uk-pagination-previous-next | Creates a previous and next button inside of a pagination               |

</p>
</details>

### Parallax

<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                                                                              |
|---------------------------|----------------------------------------------------------------------------------------------------------|
| uk-parallax               | [Attribute] Used to animate CSS properties depending on the scroll position of the document              |
| uk-parallax-properties    | [Attribute] Inserts the parallax attribute with a list of animatable properties                          |
| uk-parallax-start-end     | [Attribute] Sets the start and end values of a property by seperating them with a comma                  |
| uk-parallax-viewport      | [Attribute] Defines how far inside the viewport the element is scrolled until the animation is completed |
| uk-parallax-sample        | Creates a sample div with parallax enabled                                                               |
| uk-parallax-nested-sample | Showcases nested parallax elements                                                                       |
| uk-parallax-target-sample | Creates a parallax animation based on the viewport visibility of another element                         |
| uk-parallax-easing-sample | Creates a parallax element with a modifiable easing value                                                |
| uk-parallax-color-sample  | Creates a parallax element with a color transition                                                       |
| uk-parallax-filter-sample | Creates a parallax element with css filters                                                              |

</p>
</details>

### Placeholder

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                                |
|-----------------------|--------------------------------------------|
| uk-placeholder        | [Class] Used to create a placeholder space |
| uk-placeholder-sample | Creates a placeholder space                |

</p>
</details>

### Position

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                                                           |
|----------------------|-------------------------------------------------------------------------------------------------------|
| uk-position          | [Class] Positions the element at the chosen location                                                  |
| uk-position-extended | [Class] Positions the element at specific locations without it being spread over its parent container |
| uk-position-cover    | [Class] Positions the element to cover its container                                                  |
| uk-position-small    | [Class] Positions the element at specific locations with a small margin                               |
| uk-position-medium   | [Class] Positions the element at specific locations with a medium margin                              |
| uk-position-large    | [Class] Positions the element at specific locations with a large margin                               |
| uk-position-relative | [Class] Positions the element at a relative position                                                  |
| uk-position-absolute | [Class] Positions the element at an absolute position                                                 |
| uk-position-fixed    | [Class] Positions the element at a fixed position                                                     |
| uk-position-z-index  | [Class] Positions the element at a z-index position of 1                                              |

</p>
</details>

### Progress

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                           |
|--------------------|---------------------------------------|
| uk-progress        | [Class] Used to create a progress bar |
| uk-progress-sample | Creates a progress bar                |

</p>
</details>

### Scroll

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                                                      |
|------------------|--------------------------------------------------------------------------------------------------|
| uk-scroll        | [Attribute] Used to create a link that smooth scrolls to the targeted element with a matching id |
| uk-scroll-anchor | Creates a link that smooth scrolls to the targetted element with matching id                     |

</p>
</details>

### Scrollspy

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                                                             |
|---------------------|-------------------------------------------------------------------------|
| uk-scrollspy        | [Attribute] Used to add a scrollspy to an element                       |
| uk-scrollspy-sample | Adds the scrollspy attribute to an element and animates it when in view |
| uk-scrollspy-group  | Adds the scrollspy attribute to an element and animates it when in view |

</p>
</details>

### Search

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                           |
|-------------------------|-------------------------------------------------------|
| uk-search               | [Class] Used to create a search bar                   |
| uk-search-default       | Creates a search bar with default styling             |
| uk-search-icon          | Creates a search bar with a search icon to the left   |
| uk-search-icon-flip     | Creates a search bar with a search icon to the right  |
| uk-search-icon-button   | Creates a search bar with a clickable search icon     |
| uk-search-large         | Creates a larger search bar                           |
| uk-search-navbar        | Creates a search bar that can be used within a navbar |
| uk-search-toggle        | Creates a toggle using a search icon                  |
| uk-search-navbar-toggle | Creates a search icon toggle inside of a navbar       |

</p>
</details>

### Section

<details><summary>Reveal Content</summary>
<p>

| Trigger                     | Description                                                         |
|-----------------------------|---------------------------------------------------------------------|
| uk-section                  | [Class] Used to create a section with optional styling              |
| uk-section-default          | Creates a section with a default style                              |
| uk-section-muted            | Creates a section with a muted style                                |
| uk-section-primary          | Creates a section with a primary style                              |
| uk-section-secondary        | Creates a section with a secondary style                            |
| uk-section-preserve-color   | Creates a section that preserves the font colours of child elements |
| uk-section-size-modifier    | Creates a section with modified padding applied                     |
| uk-section-overlap-modifier | Creates a section that applies a border image and a negative offset |

</p>
</details>

### Slidenav

<details><summary>Reveal Content</summary>
<p>

| Trigger                      | Description                                                        |
|------------------------------|--------------------------------------------------------------------|
| uk-slidenav                  | Creates a previous and next button for flipping through slideshows |
| uk-slidenav-large            | Creates a larger slidenav                                          |
| uk-slidenav-position-overlay | Creates a slidenav positioned on top of an element                 |
| uk-slidenav-container        | Displays a cojoint slidenav                                        |

</p>
</details>

### Slider

<details><summary>Reveal Content</summary>
<p>

| Trigger                             | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| uk-slider                           | [Attribute] Used to create a responsive carousel                            |
| uk-slider-sample                    | Creates a responsive carousel slider                                        |
| uk-slider-container                 | [Class] Creates a responsive carousel slider                                |
| uk-slider-gutter                    | Creates a carousel slider with a gutter between items                       |
| uk-slider-center                    | Creates a carousel slider with centered items                               |
| uk-slider-autoplay                  | Creates a carousel slider with autoplay activated                           |
| uk-slider-finite                    | Creates a carousel slider with infinite scrolling disabled                  |
| uk-slider-sets                      | Creates a carousel slider which loops through a set of slides               |
| uk-slider-navigation                | Creates a carousel slider with navigation controls                          |
| uk-slider-navigation-outside        | Creates a carousel slider with outer navigation controls                    |
| uk-slider-viewport-height           | Creates a carousel slider which expands to fill the height of its container |
| uk-slider-content-overlay           | Creates a carousel slider with content overlays added                       |
| uk-slider-content-parallax          | Creates a carousel slider with a parallax effect on the content             |
| uk-slider-content-transitions       | Creates a carousel slider with transition effects added                     |
| uk-slider-content-transitions-hover | Creates a carousel slider with transition effects on mouse hover            |

</p>
</details>

### Slideshow

<details><summary>Reveal Content</summary>
<p>

| Trigger                         | Description                                                                         |
|---------------------------------|-------------------------------------------------------------------------------------|
| uk-slideshow                    | [Attribute] Used to create a responsive slideshow with images and videos            |
| uk-slideshow-sample             | Creates a responsive slideshow with images and videos                               |
| uk-slideshow-animations         | Creates a responsive slideshow with a modified transition animation                 |
| uk-slideshow-autoplay           | Creates a responsive slideshow with autoplay enabled                                |
| uk-slideshow-infinite-scrolling | Creates a responsive slideshow with endless scrolling enabled (default) or disabled |
| uk-slideshow-ratio              | Creates a responsive slideshow with a modified ratio                                |
| uk-slideshow-min-max-height     | Creates a responsive slideshow with a minimum and/or maximum height                 |

</p>
</details>

### Sortable

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                                         |
|--------------------------|-------------------------------------------------------------------------------------|
| uk-sortable              | [Attribute] Used to create a sortable, re-arrangable grid of elements               |
| uk-sortable-sample       | Creates a sortable, re-arrangable grid of elements                                  |
| uk-sortable-handle       | Creates a sortable list using a special handle button instead of the entire element |
| uk-sortable-group        | Creates a sortable group that can interchange elements                              |
| uk-sortable-custom-class | Creates sortable that can apply multiple classes to items while being dragged       |

</p>
</details>

### Spinner

<details><summary>Reveal Content</summary>
<p>

| Trigger           | Description                                            |
|-------------------|--------------------------------------------------------|
| uk-spinner        | [Attribute] Used to create an animated loading spinner |
| uk-spinner-sample | Creates an animated loading spinner                    |

</p>
</details>

### Sticky

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                                                        |
|----------------------|----------------------------------------------------------------------------------------------------|
| uk-sticky            | [Attribute] Used to create an element that remains at the top of the viewport while scrolling down |
| uk-sticky-sample     | Creates an element that remains at the top of the viewport while scrolling down                    |
| uk-sticky-offset     | Creates a sticky element with a pixel offset from the top                                          |
| uk-sticky-top        | Creates a sticky element with a delay                                                              |
| uk-sticky-animation  | Creates a sticky element with an animation when it reappears                                       |
| uk-sticky-scroll-up  | Creates a sticky element that shows only when scrolling up                                         |
| uk-sticky-bottom     | Creates a sticky element that is bound to a specific element                                       |
| uk-sticky-responsive | Creates a sticky element that is only enabled on specified device widths and above                 |

</p>
</details>

### Subnav

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                                                                |
|--------------------|----------------------------------------------------------------------------|
| uk-subnav          | [Class] Used to create a basic sub-navigation                              |
| uk-subnav-basic    | Creates a basic sub-navigation with items wrapping into the next line      |
| uk-subnav-divider  | Creates a sub-navigation seperated with lines                              |
| uk-subnav-pill     | Creates a sub-navigation that highlights the active item with a background |
| uk-subnav-dropdown | Creates a sub-navigation that contains a dropdown                          |

</p>
</details>

### SVG

<details><summary>Reveal Content</summary>
<p>

| Trigger       | Description                                        |
|---------------|----------------------------------------------------|
| uk-svg        | [Attribute] Used to apply svg formatting to images |
| uk-svg-sample | Adds an inline SVG element                         |

</p>
</details>

### Switcher

<details><summary>Reveal Content</summary>
<p>

| Trigger                         | Description                                                                     |
|---------------------------------|---------------------------------------------------------------------------------|
| uk-switcher                     | [Attribute] Used to create a switcher component                                 |
| uk-switcher-basic               | Creates a switcher that dynamically transitions through different content panes |
| uk-switcher-navigation          | Creates a switcher with navigation controls within the content pane             |
| uk-switcher-connect-containers  | Creates a switcher that connects multiple content containers                    |
| uk-switcher-animation           | Creates a switcher animates its transitions                                     |
| uk-switcher-multiple-animations | Creates a switcher with multiple animations                                     |
| uk-switcher-subnav              | Creates a switcher combined with a subnav                                       |
| uk-switcher-tab                 | Creates a switcher combined with a tab                                          |
| uk-switcher-tab-vertical        | Creates a switcher combined with a vertical tab                                 |
| uk-switcher-button              | Creates a switcher combined with a vertical tab                                 |
| uk-switcher-nav                 | Creates a switcher combined with a vertical tab                                 |

</p>
</details>

### Tab

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                          |
|------------------|------------------------------------------------------|
| uk-tab           | [Attribute] Used to create a basic tabbed navigation |
| uk-tab-basic     | Creates a basic tabbed navigation                    |
| uk-tab-bottom    | Creates a tab with items flipped to the bottom       |
| uk-tab-vertical  | Creates a tab with items aligned left or right       |
| uk-tab-alignment | Creates a tab with items aligned left or right       |
| uk-tab-dropdown  | Creates a tab with a dropdown                        |

</p>
</details>

### Table

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                                                                                |
|-----------------------|--------------------------------------------------------------------------------------------|
| uk-table              | [Class] Used to create a table                                                             |
| uk-table-sample       | Creates a table without any styling                                                        |
| uk-table-divider      | Creates a table with each row seperated by a divider                                       |
| uk-table-hover        | Creates a table with a hover state on table rows                                           |
| uk-table-sizing       | Creates a table of a selected size                                                         |
| uk-table-striped      | Creates a table with zebra-striping on table rows                                          |
| uk-table-justify      | Creates a table with the outer padding of the first and last columns removed               |
| uk-table-middle       | Creates a table with center aligned elements                                               |
| uk-table-responsive   | Creates a table that provides a horizontal scrollbar on smaller device screens when needed |
| uk-table-column-width | Modifies the width of a table column                                                       |

</p>
</details>

### Text

<details><summary>Reveal Content</summary>
<p>

| Trigger                      | Description                                                                  |
|------------------------------|------------------------------------------------------------------------------|
| uk-text-default              | [Class] Applies a default text style                                         |
| uk-text-lead                 | [Class] Highlights text for subheadings and article subtitles                |
| uk-text-meta                 | [Class] Text class for paragraphs with meta data about an article or similar |
| uk-text-size                 | [Class] Modifies the font size of text                                       |
| uk-text-bold                 | [Class] Creates bold text                                                    |
| uk-text-transform            | [Class] Transforms text characters into the chosen case                      |
| uk-text-color                | [Class] Modifies the color of text into the chosen color scheme              |
| uk-text-alignment            | [Class] Aligns text to a chosen position                                     |
| uk-text-alignment-responsive | [Class] Aligns text to a chosen position on specific screen widths           |
| uk-text-vertical-alignment   | [Class] Aligns text vertically                                               |
| uk-text-wrapping             | [Class] Wraps text according to your choice                                  |

</p>
</details>

### Thumbnav

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                     |
|----------------------|-------------------------------------------------|
| uk-thumbnav          | [Class] Used to create a thumbnail navigation   |
| uk-thumbnav-sample   | Creates a flexible thumbnail navigation         |
| uk-thumbnav-vertical | Creates a vertical thumbnav                     |
| uk-thumbnav-overlay  | Creates a thumbnav as an overlay for an element |

</p>
</details>

### Tile

<details><summary>Reveal Content</summary>
<p>

| Trigger               | Description                                                     |
|-----------------------|-----------------------------------------------------------------|
| uk-tile               | [Class] Used to create a tile with optional styling             |
| uk-tile-size-modifier | [Class] Used to create a tile with modified sizing              |
| uk-tile-default       | Creates a tile with a default style                             |
| uk-tile-muted         | Creates a tile with a muted style                               |
| uk-tile-primary       | Creates a tile with a primary style                             |
| uk-tile-secondary     | Creates a tile with a secondary style                           |
| uk-tile-padding       | Creates a tile with modified padding from the padding component |

</p>
</details>

### Toggle

<details><summary>Reveal Content</summary>
<p>

| Trigger                       | Description                                                        |
|-------------------------------|--------------------------------------------------------------------|
| uk-toggle                     | [Attribute] Used to create a toggle that shows/hides an element    |
| uk-toggle-example             | Creates a toggle that shows/hides an element                       |
| uk-toggle-multiple            | Creates a toggle that shows/hides multiple elements                |
| uk-toggle-custom-class        | Creates a toggle that applies a custom class to the target element |
| uk-toggle-animation           | Creates a toggle that animates when toggling between items         |
| uk-toggle-multiple-animations | Creates a toggle with multiple animations                          |
| uk-toggle-queued-animation    | Creates a toggle with queued animations                            |
| uk-toggle-modes               | Changes the trigger mode for the toggle                            |
| uk-toggle-media               | Toggles an element based on the screen width                       |

</p>
</details>

### Tooltip

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                              |
|----------------------|----------------------------------------------------------|
| uk-tooltip           | [Attribute] Used to create an element with a tooltip     |
| uk-tooltip-sample    | Creates an element with a tooltip                        |
| uk-tooltip-alignment | Creates a tooltip with a modified alignment              |
| uk-tooltip-delay     | Creates a tooltip with a specified delay in milliseconds |

</p>
</details>

### Totop

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                                                  |
|-----------------|------------------------------------------------------------------------------|
| uk-totop        | [Attribute] Used to create an icon used for scrolling to the top of the page |
| uk-totop-sample | Creates an icon used for scrolling to the top of the page                    |
| uk-totop-smooth | Creates a totop component with smooth scrolling                              |

</p>
</details>

### Transition

<details><summary>Reveal Content</summary>
<p>

| Trigger                  | Description                                                             |
|--------------------------|-------------------------------------------------------------------------|
| uk-transition-fade       | Creates a smooth transition between two states when hovering an element |
| uk-transition-scale      | Creates a smooth transition between two states when hovering an element |
| uk-transition-slide      | Creates a smooth transition between two states when hovering an element |
| uk-transition-slide-size | Creates a smooth transition between two states when hovering an element |

</p>
</details>

### Upload

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                                          |
|---------------------|------------------------------------------------------|
| uk-upload-select    | Creates a button which opens a file select window    |
| uk-upload-drop-area | Creates an area for files to be dropped and uploaded |
| uk-upload-script    | Creates the upload script                            |

</p>
</details>

### Utility

<details><summary>Reveal Content</summary>
<p>

| Trigger                      | Description                                                                                                                                                 |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| uk-utility-panel             | Creates a panel used to outline a section of content                                                                                                        |
| uk-utility-panel-scrollable  | Creates a scrollable panel                                                                                                                                  |
| uk-utility-float             | [Class] Floats an element left or right                                                                                                                     |
| uk-utility-clearfix          | [Class] Removes floats from this element and its children                                                                                                   |
| uk-utility-overflow          | [Class] Modifies an element's overflow behaviour                                                                                                            |
| uk-utility-resize            | [Class] Allows an element to be resized                                                                                                                     |
| uk-utility-display           | [Class] Changes the display properties of an element                                                                                                        |
| uk-utility-inline            | [Class] Applies inline-block behaviour to an element, adds a max-width of 100% and creates a position context. Optionally clips overflowing child elements. |
| uk-utility-responsive        | [Class] Applies a responsive behaviour to any element                                                                                                       |
| uk-utility-preserve-width    | [Class] Avoids responsive behaviour and preserves original dimensions                                                                                       |
| uk-utility-border-radius     | [Class] Modifies the border radius of an element                                                                                                            |
| uk-utility-box-shadow        | [Class] Adds a box shadow to an element                                                                                                                     |
| uk-utility-box-shadow-bottom | [Class] Adds a box shadow to the bottom of an element                                                                                                       |
| uk-utility-box-shadow-hover  | [Class] Adds a box shadow to an element on hover                                                                                                            |
| uk-utility-dropcap           | Applies a drop cap on a paragraph                                                                                                                           |
| uk-utility-leader            | Visually connects horizontal items with a line of dots                                                                                                      |
| uk-utility-logo-text         | Creates a text logo                                                                                                                                         |
| uk-utility-logo-image        | Creates an image logo                                                                                                                                       |
| uk-utility-inline-svg        | Adds an inline SVG                                                                                                                                          |
| uk-utility-video             | Adds a video that can automatically play when it comes into view                                                                                            |
| uk-utility-blend             | [Class] Applies a modified blend mode to a background                                                                                                       |
| uk-utility-transform-center  | [Class] Centers an element to itself                                                                                                                        |
| uk-utility-transform-origin  | [Class] Modifies the origin of an animation                                                                                                                 |
| uk-utility-disabled          | [Class] Disables the click behaviour of any element                                                                                                         |
| uk-utility-drag              | [Class] Applies a move cursor to an element                                                                                                                 |
| uk-utility-dragover          | [Class] Creates a box shadow used for upload areas when dragging a file over it                                                                             |

</p>
</details>

### Video

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                          |
|-----------------|------------------------------------------------------|
| uk-video        | [Attribute] Used to add lazy-load to a video element |
| uk-video-sample | Creates a video element that loads once in view      |

</p>
</details>

### Visibility

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                                                               |
|----------------------|-----------------------------------------------------------------------------------------------------------|
| uk-hidden            | [Attribute] Used for hiding an element                                                                    |
| uk-hidden-class      | [Class] Legacy class used for hiding an element. Recommended: Use 'hidden' attribute instead.             |
| uk-hidden-responsive | [Class] Hides an element from screens larger than the specified width (640/960/1200/1600 px respectively) |
| uk-hidden-hover      | Hides the content until the parent container is hovered                                                   |
| uk-visible           | [Class] Shows an element on screens larger than the specified width (640/960/1200/1600 px respectively)   |
| uk-invisible         | [Class] Hides the element without removing it from the document flow.                                     |
| uk-invisible-hover   | Hides the content (without removing it from the document flow) until the parent container is hovered      |
| uk-hidden-touch      | Hides the content on touch devices                                                                        |
| uk-hidden-notouch    | Hides the content on devices without a touch screen                                                       |

</p>
</details>

### Width

<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                                                                                                                                  |
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| uk-width                  | [Class] Modifies the width of an element to take up a portion of its parent container, or the entire width. Usually used with 'uk-grid'.                     |
| uk-width-responsive       | [Class] Modifies the width of an element to take up a portion of its parent container on specified device widths and higher. Columns stack on smaller sizes. |
| uk-width-auto             | [Class] The item expands to the width of its own content. Usually used with 'uk-grid'.                                                                       |
| uk-width-expand           | [Class] The item expands to fill up the remaining space of the grid container. Usually used with 'uk-grid'.                                                  |
| uk-child-width            | [Class] Evenly divides the width of all child elements in a 'uk-grid'                                                                                        |
| uk-child-width-responsive | [Class] Evenly divides the width of all child elements in a 'uk-grid' on specified device widths and higher. Columns stack on smaller sizes.                 |
| uk-fixed-width            | [Class] Applies a fixed width to an element of 150/300/450/600/750 px respectively.                                                                          |

</p> 
</details>

</p>
</details>

## List of Commands (Javascript)

<details>
  <summary><strong>Click to Reveal List of Commands (Javascript)</strong></summary>
  <p>

### Accordion JS

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                       |
|----------------------|-------------------------------------------------------------------|
| uk-accordion         | Initializes an accordion component with various options           |
| uk-accordion-events  | Triggers a function when a specified accordion event is triggered |
| uk-accordion-methods | Showcases the methods available to the accordion component        |

</p>
</details>

### Alert JS

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                   |
|------------------|---------------------------------------------------------------|
| uk-alert         | Initializes an alert component with various options           |
| uk-alert-events  | Triggers a function when a specified alert event is triggered |
| uk-alert-methods | Showcases the methods available to the alert component        |

</p>
</details>

### Countdown JS

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                |
|----------------------|------------------------------------------------------------|
| uk-countdown         | Initializes a countdown component with various options     |
| uk-countdown-methods | Showcases the methods available to the countdown component |

</p>
</details>

### Cover JS

<details><summary>Reveal Content</summary>
<p>

| Trigger  | Description                                        |
|----------|----------------------------------------------------|
| uk-cover | Initializes a cover component with various options |

</p>
</details>

### Drop JS

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                                  |
|-----------------|--------------------------------------------------------------|
| uk-drop         | Initializes a drop component with various options            |
| uk-drop-events  | Triggers a function when a specified drop event is triggered |
| uk-drop-methods | Showcases the methods available to the drop component        |

</p>
</details>

### Dropdown JS

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                                                      |
|---------------------|------------------------------------------------------------------|
| uk-dropdown         | Initializes a dropdown component with various options            |
| uk-dropdown-events  | Triggers a function when a specified dropdown event is triggered |
| uk-dropdown-methods | Showcases the methods available to the dropdown component        |

</p>
</details>

### Filter JS

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                    |
|------------------|----------------------------------------------------------------|
| uk-filter        | Initializes a filter component with various options            |
| uk-filter-events | Triggers a function when a specified filter event is triggered |

</p>
</details>

### Form JS

<details><summary>Reveal Content</summary>
<p>

| Trigger | Description                                       |
|---------|---------------------------------------------------|
| uk-form | Initializes a form component with various options |

</p>
</details>

### Grid JS

<details><summary>Reveal Content</summary>
<p>

| Trigger | Description                                       |
|---------|---------------------------------------------------|
| uk-grid | Initializes a grid component with various options |

</p>
</details>

### Height Match JS

<details><summary>Reveal Content</summary>
<p>

| Trigger         | Description                                               |
|-----------------|-----------------------------------------------------------|
| uk-height-match | Initializes a height match component with various options |

</p>
</details>

### Icon JS

<details><summary>Reveal Content</summary>
<p>

| Trigger | Description                                        |
|---------|----------------------------------------------------|
| uk-icon | Initializes an icon component with various options |

</p>
</details>

### Image JS

<details><summary>Reveal Content</summary>
<p>

| Trigger | Description                                         |
|---------|-----------------------------------------------------|
| uk-img  | Initializes an image component with various options |

</p>
</details>

### Lightbox JS

<details><summary>Reveal Content</summary>
<p>

| Trigger                   | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| uk-lightbox               | Initializes a lightbox component with various options            |
| uk-lightbox-events        | Triggers a function when a specified lightbox event is triggered |
| uk-lightbox-methods       | Showcases the methods available to the lightbox component        |
| uk-lightbox-panel         | Initializes a lightbox panel component with various options      |
| uk-lightbox-panel-methods | Showcases the methods available to the lightbox panel component  |

</p>
</details>

### Margin JS

<details><summary>Reveal Content</summary>
<p>

| Trigger   | Description                                         |
|-----------|-----------------------------------------------------|
| uk-margin | Initializes a margin component with various options |

</p>
</details>

### Modal JS

<details><summary>Reveal Content</summary>
<p>

| Trigger                | Description                                                   |
|------------------------|---------------------------------------------------------------|
| uk-modal               | Initializes a modal component with various options            |
| uk-modal-events        | Triggers a function when a specified modal event is triggered |
| uk-modal-methods       | Showcases the methods available to the modal component        |
| uk-modal-alert         | Creates an alert box with one button                          |
| uk-modal-confirm       | Creates a confirm dialog with your message and two buttons    |
| uk-modal-prompt        | Creates a dialog asking for a text input                      |
| uk-modal-dialog        | Creates a dialog with any HTML content                        |
| uk-modal-dialog-sample | Creates a sample dialog which processes user input            |

</p>
</details>

### Nav JS

<details><summary>Reveal Content</summary>
<p>

| Trigger        | Description                                          |
|----------------|------------------------------------------------------|
| uk-nav         | Initializes a nav component with various options     |
| uk-nav-methods | Showcases the methods available to the nav component |

</p>
</details>

### Navbar JS

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                    |
|------------------|----------------------------------------------------------------|
| uk-navbar        | Initializes a navbar component with various options            |
| uk-navbar-events | Triggers a function when a specified navbar event is triggered |

</p>
</details>

### Notification JS

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                                          |
|-------------------------|----------------------------------------------------------------------|
| uk-notification         | Creates a notification with various options                          |
| uk-notification-events  | Triggers a function when a specified notification event is triggered |
| uk-notification-methods | Showcases the methods available to the notification component        |

</p>
</details>

### Offcanvas JS

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                       |
|----------------------|-------------------------------------------------------------------|
| uk-offcanvas         | Initializes a offcanvas component with various options            |
| uk-offcanvas-events  | Triggers a function when a specified offcanvas event is triggered |
| uk-offcanvas-methods | Showcases the methods available to the offcanvas component        |

</p>
</details>

### Parallax JS

<details><summary>Reveal Content</summary>
<p>

| Trigger     | Description                                           |
|-------------|-------------------------------------------------------|
| uk-parallax | Initializes a parallax component with various options |

</p>
</details>

### Scroll JS

<details><summary>Reveal Content</summary>
<p>

| Trigger   | Description                                         |
|-----------|-----------------------------------------------------|
| uk-scroll | Initializes a scroll component with various options |

</p>
</details>

### Scrollspy JS

<details><summary>Reveal Content</summary>
<p>

| Trigger                 | Description                                                           |
|-------------------------|-----------------------------------------------------------------------|
| uk-scrollspy            | Initializes a scrollspy component with various options                |
| uk-scrollspy-events     | Triggers a function when a specified scrollspy event is triggered     |
| uk-scrollspy-nav        | Initializes a scrollspy nav component with various options            |
| uk-scrollspy-nav-events | Triggers a function when a specified scrollspy nav event is triggered |

</p>
</details>

### Slider JS

<details><summary>Reveal Content</summary>
<p>

| Trigger           | Description                                                    |
|-------------------|----------------------------------------------------------------|
| uk-slider         | Initializes a slider component with various options            |
| uk-slider-events  | Triggers a function when a specified slider event is triggered |
| uk-slider-methods | Showcases the methods available to the slider component        |

</p>
</details>

### Slideshow JS

<details><summary>Reveal Content</summary>
<p>

| Trigger              | Description                                                       |
|----------------------|-------------------------------------------------------------------|
| uk-slideshow         | Initializes a slideshow component with various options            |
| uk-slideshow-events  | Triggers a function when a specified slideshow event is triggered |
| uk-slideshow-methods | Showcases the methods available to the slideshow component        |

</p>
</details>

### Sortable JS

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                                                      |
|--------------------|------------------------------------------------------------------|
| uk-sortable        | Initializes a sortable component with various options            |
| uk-sortable-events | Triggers a function when a specified sortable event is triggered |

</p>
</details>

### Sticky JS

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                    |
|------------------|----------------------------------------------------------------|
| uk-sticky        | Initializes a sticky component with various options            |
| uk-sticky-events | Triggers a function when a specified sticky event is triggered |

</p>
</details>

### SVG JS

<details><summary>Reveal Content</summary>
<p>

| Trigger           | Description                                                    |
|-------------------|----------------------------------------------------------------|
| uk-svg            | Initializes a svg component with various options               |
| uk-svg-properties | A JavaScript Promise that will resolve with the added SVG Node |

</p>
</details>

### Switcher JS

<details><summary>Reveal Content</summary>
<p>

| Trigger             | Description                                                      |
|---------------------|------------------------------------------------------------------|
| uk-switcher         | Initializes a switcher with various options                      |
| uk-switcher-events  | Triggers a function when a specified switcher event is triggered |
| uk-switcher-methods | Showcases the methods available to the switcher component        |

</p>
</details>

### Tab JS

<details><summary>Reveal Content</summary>
<p>

| Trigger        | Description                                                 |
|----------------|-------------------------------------------------------------|
| uk-tab         | Initializes a tab with various options                      |
| uk-tab-events  | Triggers a function when a specified tab event is triggered |
| uk-tab-methods | Showcases the methods available to the tab component        |

</p>
</details>

### Toggle JS

<details><summary>Reveal Content</summary>
<p>

| Trigger           | Description                                                    |
|-------------------|----------------------------------------------------------------|
| uk-toggle         | Initializes a toggle with various options                      |
| uk-toggle-events  | Triggers a function when a specified toggle event is triggered |
| uk-toggle-methods | Showcases the methods available to the toggle component        |

</p>
</details>

### Tooltip JS

<details><summary>Reveal Content</summary>
<p>

| Trigger            | Description                                                     |
|--------------------|-----------------------------------------------------------------|
| uk-tooltip         | Initializes a tooltip component with various options            |
| uk-tooltip-events  | Triggers a function when a specified tooltip event is triggered |
| uk-tooltip-methods | Showcases the methods available to the tooltip component        |

</p>
</details>

### Upload JS

<details><summary>Reveal Content</summary>
<p>

| Trigger          | Description                                                    |
|------------------|----------------------------------------------------------------|
| uk-upload        | Initializes an upload component with various options           |
| uk-upload-events | Triggers a function when a specified upload event is triggered |
| uk-upload-sample | Creates a sample upload script based on official docs          |

</p>
</details>

### Video JS

<details><summary>Reveal Content</summary>
<p>

| Trigger  | Description                                        |
|----------|----------------------------------------------------|
| uk-video | Initializes a video component with various options |

</p>
</details>

</p>
</details>
