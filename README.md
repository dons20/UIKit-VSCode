UIKit 3.0 Snippets for Visual Studio Code
===

![Demo Image](https://zippy.gfycat.com/AmusingGiftedJumpingbean.gif)

[Gfycat Link](https://gfycat.com/AmusingGiftedJumpingbean)

This extension adds all the snippets from [UIKit 3.0](https://getuikit.com/docs/introduction) into Visual Studio Code for easy access and usage.

Suggestions are welcome in order to improve the quality of the snippets, as well as keeping it up to date.
Head over to the [issues](https://github.com/dons20/UIKit-VSCode/issues) page to submit those.

Setup
---
#### Method 1

1. Go to Extensions by pressing Ctrl-Shift-X (Windows/Linux) or Cmd-Shift-X (Mac)
2. Search for UIKit 3.0 Snippets
3. Click on Install
4. Reload your editor and you're good to go!

#### Method 2

1. With Visual Studio Code opened, press `Ctrl+P`.
2. Type in `ext install uikit-3-snippets` and press `Enter`.


Table of Contents
---
* [UIKit 3.0 Snippets](#uikit-30-snippets-for-visual-studio-code)
  * [Setup](#setup)
    * [Method 1](#method-1)
    * [Method 2](#method-2)
  * [Table of Contents](#table-of-contents)
  * [Usage](#usage)
  * [Contribution Guidelines](#contribution-guidelines)
    * [Snippet Template](#snippet-template)
  * [Snippet Modification Tips](#snippet-modification-tips)
    * [Official Documention](#official-documentation)
    * [Keeping Snippets Well Formatted](#keeping-snippets-well-formatted)
    * [Testing Changes](#testing-changes)
    * [Tab Locations](#tab-locations)
  * [Changelog](#changelog)
  * [License](#license)
  * [Disclaimer](#disclaimer)
  * [List of Commands (HTML/PHP/HTML Eex)](#list-of-commands-htmlphp)
    * [UIKit Master Template](#uikit-master-template)
    * [Accordion](#accordion)
    * [Alert](#alert)
    * [Alignment](#alignment)
    * [Animation](#animation)
    * [Article](#article)
    * [Background](#background)
    * [Badge](#badge)
    * [Breadcrumb](#breadcrumb)
    * [Button](#button)
    * [Card](#card)
    * [Close](#close)
    * [Column](#column)
    * [Comment](#comment)
    * [Container](#container)
    * [Countdown](#countdown)
    * [Cover](#cover)
    * [Description List](#description-list)
    * [Disabled](#disabled)
    * [Divider](#divider)
    * [Dotnav](#dotnav)
    * [Drop](#drop)
    * [Dropdown](#dropdown)
    * [Flex](#flex)
    * [Form](#form)
    * [Grid](#grid)
    * [Grid Parallax](#grid-parallax)
    * [Heading](#heading)
    * [Icon](#icon)
    * [Iconnav](#iconnav)
    * [Inverse](#inverse)
    * [Label](#label)
    * [Lightbox](#lightbox)
    * [Link](#link)
    * [List](#list)
    * [Margin](#margin)
    * [Marker](#marker)
    * [Modal](#modal)
    * [Nav](#nav)
    * [Navbar](#navbar)
    * [Notification](#notification)
    * [Offcanvas](#offcanvas)
    * [Overlay](#overlay)
    * [Padding](#padding)
    * [Pagination](#pagination)
    * [Parallax](#parallax)
    * [Placeholder](#placeholder)
    * [Position](#position)
    * [Progress](#progress)
    * [Scroll](#scroll)
    * [Scrollspy](#scrollspy)
    * [Search](#search)
    * [Section](#section)
    * [Slidenav](#slidenav)
    * [Sortable](#sortable)
    * [Spinner](#spinner)
    * [Sticky](#sticky)
    * [Subnav](#subnav)
    * [Switcher](#switcher)
    * [Tab](#tab)
    * [Table](#table)
    * [Text](#text)
    * [Toggle](#toggle)
    * [Tooltip](#tooltip)
    * [Totop](#totop)
    * [Transition](#transition)
    * [Upload](#upload)
    * [Utility](#utility)
    * [Visibility](#visibility)
    * [Width](#width)
  * [List of Commands (Javascript)](#list-of-commands-javascript)
    * [Accordion JS](#accordion-js)
    * [Alert JS](#alert-js)
    * [Countdown JS](#countdown-js)
    * [Cover JS](#cover-js)
    * [Drop JS](#drop-js)
    * [Dropdown JS](#dropdown-js)
    * [Form JS](#form-js)
    * [Grid JS](#grid-js)
    * [Grid Parallax JS](#grid-parallax-js)
    * [Icon JS](#icon-js)
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
    * [Sortable JS](#sortable-js)
    * [Sticky JS](#sticky-js)
    * [Switcher JS](#switcher-js)
    * [Tab JS](#tab-js)
    * [Toggle JS](#toggle-js)
    * [Tooltip JS](#tooltip-js)
    * [Upload JS](#upload-js)

Usage
---
To use the snippets, open a HTML file, and start typing `uk-` (optionally followed by `Ctrl+Space` depending on user settings). A list of UIKit snippets will show up.
Each snippet has a short and simple description to aid with understanding its use. 
For more details and eve better examples and possible options, [head to the UIKit Documentation](https://getuikit.com/docs/introduction)

A detailed list of supported commands are listed below in the **List of Commands** section.

Contribution Guidelines
---
[Read the contribution guidelines](./CONTRIBUTING.md)

Changelog
---
[View the changelog](./CHANGELOG.md)

License
---
UIKit 3.0 Snippets - Visual Studio Code plugin is licensed under the [MIT License](http://opensource.org/licenses/MIT)

Disclaimer
---
[Readme layout inspiration](https://github.com/thekalinga/bootstrap4-vscode)

[UIKit Snippets Original Source](https://getuikit.com/docs/introduction)

List of Commands (HTML/PHP)
---

### UIKit Master Template
| Trigger | Description |
| :-------: | :-----------: |
| uk-$ | Creates a basic UIKit template |
| uk-$-rtl | Creates a basic UIKit template with RTL support |
| uk-$-css-import | Imports the default minified css file for UIKit |
| uk-$-css-rtl-import | Imports the RTL minified css file for UIKit |
| uk-$-js-import | Imports the minified scripts for UIKit |

### Accordion
| Trigger | Description |
| :-------: | :-----------: |
| uk-accordion | [Attribute] Used to create an accordion element in a parent container |
| uk-accordion-sample | Creates a sample Accordion component |
| uk-accordion-no-collapse | Accordion that always keeps one item open |
| uk-accordion-multiple-open | Accordion that allows multiple items to be opened at once |
| uk-accordion-open-index | Accordion that opens an item by default |

### Alert
| Trigger | Description |
| :-------: | :-----------: |
| uk-alert | [Attribute] Used to create an alert element in a block element |
| uk-alert-default | A default alert applied to a div |
| uk-alert-close | An alert with a close button |
| uk-alert-primary | An alert with a primary style applied |
| uk-alert-success | An alert with a success style applied |
| uk-alert-warning | An alert with a warning style applied |
| uk-alert-danger | An alert with a danger style applied |

### Alignment
| Trigger | Description |
| :-------: | :-----------: |
| uk-align-default | [Class] Floats the element to a selected position |
| uk-align-left | [Class] Floats the element to the left |
| uk-align-center | [Class] Floats the element to the center |
| uk-align-right | [Class] Floats the element to the right |
| uk-align-responsive | [Class] Floats the element on specific widths |

### Animation
| Trigger | Description |
| :-------: | :-----------: |
| uk-animation-fade | [Class] The element fades in |
| uk-animation-scale-up | [Class] The element fades in and scales up |
| uk-animation-scale-down | [Class] The element fades in and scales down |
| uk-animation-slide-top | [Class] The element fades in and slides in from the top |
| uk-animation-slide-bottom | [Class] The element fades in and slides in from the bottom |
| uk-animation-slide-left | [Class] The element fades in and slides in from the left |
| uk-animation-slide-right | [Class] The element fades in and slides in from the right |
| uk-animation-slide-custom | [Class] The element slides in with a specific distance |
| uk-animation-kenburns | [Class] The element scales slowly up without fading in |
| uk-animation-shake | [Class] The element shakes |
| uk-animation-reverse | [Class] The element's animation plays in reverse |
| uk-animation-fast | [Class] The element's animation plays at a faster speed |
| uk-animation-transform-origin | [Class] The element scales in from a different direction |

### Article
| Trigger | Description |
| :-------: | :-----------: |
| uk-article-basic | A basic article layout |
| uk-article-sample | A complete sample article with placeholders |

### Background
| Trigger | Description |
| :-------: | :-----------: |
| uk-background-default | [Class] Applies the default background color |
| uk-background-muted | [Class] Applies a muted background color |
| uk-background-primary | [Class] Applies the primary background color |
| uk-background-secondary | [Class] Applies the secondary background color |
| uk-background-cover | [Class] Scales the background image to cover the containing area |
| uk-background-contain | [Class] Scales the background image to fit within the containing area |
| uk-background-position | [Class] Alters the initial position of the background iamge |
| uk-background-norepeat | [Class] Prevents the background image from being repeated |
| uk-background-fixed | [Class] Locks the image in place while scrolling |
| uk-background-image-responsive | [Class] Shows the background image on widths of chosen size upwards |
| uk-background-blend | [Class] Applies a chosen blend mode to the background image |

### Badge
| Trigger | Description |
| :-------: | :-----------: |
| uk-badge | [Class] Used to create a notification badge in an inline element |
| uk-badge-span | Creates a simple notification badge span |
| uk-badge-link | Creates a simple notification badge link |

### Breadcrumb
| Trigger | Description |
| :-------: | :-----------: |
| uk-breadcrumb | [Class] Used to create a breadcrumb list |
| uk-breadcrumb-list | Creates a default breadcrumb list |

### Button
| Trigger | Description |
| :-------: | :-----------: |
| uk-button-default | Creates a button with a default style |
| uk-button-primary | Creates a button with a primary style |
| uk-button-secondary | Creates a button with a secondary style |
| uk-button-danger | Creates a button with a danger style |
| uk-button-text | Creates a button with a alternative, typographic style |
| uk-button-link | Creates a button that looks like a link |
| uk-button-disabled | Creates a disabled button |
| uk-button-small | Creates a small button |
| uk-button-large | Creates a large button |
| uk-button-full-width | Creates a button that takes up the full width of its container |
| uk-button-dropdown | Creates a button that toggles a dropdown menu |
| uk-button-group | Creates a group of buttons |
| uk-button-group-dropdown | Creates a button group with a dropdown toggle on the right |

### Card
| Trigger | Description |
| :-------: | :-----------: |
| uk-card-default | Creates a card with a default style |
| uk-card-primary | Creates a card with a primary style |
| uk-card-secondary | Creates a card with a secondary style |
| uk-card-hover | Creates a card with a hover effect |
| uk-card-small | Creates a card with reduced padding |
| uk-card-large | Creates a card with increased padding |
| uk-card-header-footer | Creates a card divided into three sections |
| uk-card-media | Displays an image inside a card without any spacing |
| uk-card-horizontal | Creates a card with a horizontal layout (Ideal for media-left & media-right) |
| uk-card-badge | Creates a card with a styled badge inside |

### Close
| Trigger | Description |
| :-------: | :-----------: |
| uk-close | [Attribute] Used to create a close button |
| uk-close-button | Creates a close button |
| uk-close-button-large | Creates a larger close button |

### Column
| Trigger | Description |
| :-------: | :-----------: |
| uk-column | [Class] Displays the inline content in multiple columns |
| uk-column-responsive | [Class] Displays the inline content in multiple columns on specific width breakpoints |
| uk-column-divider | [Class] Displays the inline content in multiple columns seperated by dividers |
| uk-column-span | Creates a column with an inline element that spans each column |

### Comment
| Trigger | Description |
| :-------: | :-----------: |
| uk-comment-default | Creates a standard comment layout |
| uk-comment-primary | Creates a highlighted comment with a standard layout |
| uk-comment-list | Creates a nestable list of comments | 

### Container
| Trigger | Description |
| :-------: | :-----------: |
| uk-container | [Class] Used to create a centered container |
| uk-container-default | Creates a centered container |
| uk-container-small | Creates a narrower, centered container | 
| uk-container-large | Creates a wider, centered container |
| uk-container-expand | Creates a max-width container |

### Countdown
| Trigger | Description |
| :-------: | :-----------: |
| uk-countdown | [Attribute] Used to create a countdown timer |
| uk-countdown-sample | Creates a countdown timer. Date is in the format: YYYY-MM-DDThh:mm:ssTZD |
| uk-countdown-separator | Creates a countdown timer with each number separated by a colon |
| uk-countdown-label | Used to add a label to each number on the countdown timer |

### Cover
| Trigger | Description |
| :-------: | :-----------: |
| uk-cover-container | Creates an image that covers its parent element |
| uk-cover-container-video | Creates a video that covers its parent element |
| uk-cover-container-iframe | Creates an iframe that covers its parent element |
| uk-cover-container-responsive | Creates an element that scales responsively with its parent |

### Description List
| Trigger | Description |
| :-------: | :-----------: |
| uk-description-list | [Class] Used to create a description list |
| uk-description-list-sample | Creates a sample list to display terms and descriptions below each other |
| uk-description-list-divider | Creates a divided description list |

### Disabled
| Trigger | Description |
| :-------: | :-----------: |
| uk-disabled | [Class] Disables an item within a list |

### Divider
| Trigger | Description |
| :-------: | :-----------: |
| uk-divider-icon | Creates a divider with a decoration |
| uk-divider-small | Creates a smaller divider |

### Dotnav
| Trigger | Description |
| :-------: | :-----------: |
| uk-dotnav | Creates a navigation list with dots |
| uk-dotnav-vertical | Creates a vertical navigation list with dots |
| uk-dotnav-centered-viewport | Creates a dotnav centered vertically and aligned right |

### Drop
| Trigger | Description |
| :-------: | :-----------: |
| uk-drop | [Attribute] Used to create a drop component |
| uk-drop-basic | Creates a basic drop component |
| uk-drop-example | Creates two example drops with different modes |
| uk-drop-grid | Creates a drop with a grid inside |
| uk-drop-position | Creates a drop with its alignment adjusted |
| uk-drop-boundary | Creates a drop with a predetermined element as its boundary |
| uk-drop-boundary-aligned | Creates a drop aligned to its boundary |
| uk-drop-offset | Creates a drop with an offset |
| uk-drop-animated | Creates a drop with an offset |

### Dropdown
| Trigger | Description |
| :-------: | :-----------: |
| uk-dropdown | [Attribute] Used to create a dropdown in a block element such as a div |
| uk-dropdown-basic | Creates a basic dropdown underneath a button toggle |
| uk-dropdown-basic-inline | Creates a basic dropdown grouped with its toggle |
| uk-dropdown-nav | Creates a dropdown containing a nav element |
| uk-dropdown-grid | Creates a dropdown containing a grid |
| uk-dropdown-position | Creates a dropdown with its alignment adjusted |
| uk-dropdown-boundary | Determines a parent element as the dropdown's boundary |
| uk-dropdown-boundary-aligned | Aligns the dropdown to the parent's boundary |
| uk-dropdown-offset | Defines a custom offset for the dropdown |
| uk-dropdown-animated | Applies one or more animations to the dropdown |

### Flex
| Trigger | Description |
| :-------: | :-----------: |
| uk-flex | [Class] Used to apply a flexbox layout model to an element |
| uk-flex-block | Creates a flex container and behaves like a block element |
| uk-flex-inline | Creates a flex container and behaves like an inline element |
| uk-flex-horizontal-alignment | Defines the horizontal alignment of flex items and distributes space between them |
| uk-flex-horizontal-alignment-responsive | Defines the horizontal alignment of flex items on specific device widths |
| uk-flex-vertical-alignment | Defines the vertical alignment of flex items and distributes space between them |
| uk-flex-direction | Defines the axis that flex items are placed on and their direction |
| uk-flex-wrap-modifier | Defines the axis that flex items are placed on and their direction |
| uk-flex-item-order | [Class] Displays an item as the first or last one (Add to item) |
| uk-flex-item-dimensions | [Class] Determines how much space a flex item should take up (Add to item) |
| uk-flex-grid-example | Creates a sample flex with a grid inside |

### Form
| Trigger | Description |
| :-------: | :-----------: |
| uk-form-sample | Creates a sample form with all elements as reference |
| uk-form-fieldset | Creates a fieldset for a form |
| uk-form-legend | Creates a legend for a form |
| uk-form-states | [Class] Applies a custom state to a form control |
| uk-form-disabled | Disables a form control |
| uk-form-sizes | Modifies the size of an input, select or textarea |
| uk-form-width-modifiers | Modifies the width of an input, select or textarea |
| uk-form-blank | Minimizes the styling of form controls |
| uk-form-stacked | Stacks labels and controls on top of each other |
| uk-form-horizontal | Aligns labels and controls horizontally (use uk-form-controls-text to better align checkboxes and radio buttons) |
| uk-form-icon | Creates a form control with an icon inside to the left (or right with flip class) |
| uk-form-icon-click | Creates a form icon that can be clicked |
| uk-form-grid-example | Creates a form defined by a grid layout |
| uk-form-custom-control | Replaces a file input or select form with your own HTML content |

### Grid
| Trigger | Description |
| :-------: | :-----------: |
| uk-grid | [Attribute] Used to create a grid container inside a div |
| uk-grid-stacked | Creates a basic stacked grid container |
| uk-grid-expanded | Creates an expanded grid container with elements side by side |
| uk-grid-gutter-modifier | Modifies the spacing between grid items |
| uk-grid-nested-sample | Creates a sample nested grid |
| uk-grid-divided | Seperates each grid cell with lines |
| uk-grid-match-height | Matches the height of all grid cells |
| uk-grid-match-cell | [Class] Matches the height of a grid cell |
| uk-grid-width | Manually determines the column widths |
| uk-grid-flex | Combines a grid element with flex |

### Grid Parallax
| Trigger | Description |
| :-------: | :-----------: |
| uk-grid-parallax | [Attribute] Used to add a scrolling effect to columns within a grid |

### Heading
| Trigger | Description |
| :-------: | :-----------: |
| uk-heading-primary | [Class] Used to create an emphasized heading |
| uk-heading-primary-sample | Creates an emphasized heading |
| uk-heading-divider | [Class] Used to create a heading with a divider underneath |
| uk-heading-divider-sample | Creates a heading with a divider underneath |
| uk-heading-bullet | [Class] Used to create a heading used in a list |
| uk-heading-bullet-sample | Creates a heading as part of a list |
| uk-heading-line | [Class] Used to create a heading with a vertically centered line |
| uk-heading-line-sample | Creates a heading with a vertically centered line |

### Icon
| Trigger | Description |
| :-------: | :-----------: |
| uk-icon-span | Creates an icon within a span. (List of Icons Here: https://getuikit.com/docs/icon) |
| uk-icon-link | Creates an icon within a link. (List of Icons Here: https://getuikit.com/docs/icon) |
| uk-icon-ratio | Modifies the size of the icon by the ratio |
| uk-icon-link-modifier | Resets the default link styling to a more muted color when using an icon inside an anchor |
| uk-icon-button-modifier | Creates an icon button |
| uk-icon-image-modifier | Scales a background image to the size of an icon |

### Iconnav
| Trigger | Description |
| :-------: | :-----------: |
| uk-iconnav | [Class] Used to create a navigation consisting of icons |
| uk-iconnav-horizontal | Creates a navigation consisting of icons |
| uk-iconnav-vertical | Creates a vertical navigation consisting of icons |

### Inverse
| Trigger | Description |
| :-------: | :-----------: |
| uk-light | [Class] Used to improve the visibility of objects on light backgrounds in a light style |
| uk-inverse-light | Improves the visibility of objects on dark backgrounds in a light style |
| uk-dark | [Class] Used to improve the visibility of objects on light backgrounds in a dark style |
| uk-inverse-dark | Improves the visibility of objects on light backgrounds in a dark style |

### Label
| Trigger | Description |
| :-------: | :-----------: |
| uk-label | [Class] Used to create a label in a span element |
| uk-label-default | Creates a label with a default style |
| uk-label-success | Creates a label with a success style |
| uk-label-warning | Creates a label with a warning style |
| uk-label-danger | Creates a label with a danger style |

### Lightbox
| Trigger | Description |
| :-------: | :-----------: |
| uk-lightbox | [Attribute] Turns all the anchors inside a container into lightbox links |
| uk-lightbox-basic | Creates a lightbox container with an anchor inside |
| uk-lightbox-caption | Creates a lightbox container with a caption at the bottom |
| uk-lightbox-animation | Creates a lightbox container with a modified transition animation |
| uk-lightbox-alternate-content | Creates a lightbox container with multiple content types |

### Link
| Trigger | Description |
| :-------: | :-----------: |
| uk-link-muted | Creates a link with a muted style |
| uk-link-text | Creates a link with a body text style |
| uk-link-reset | Creates a link that inherits its color from its parent |

### List
| Trigger | Description |
| :-------: | :-----------: |
| uk-list | [Class] Used to create a basic ordered or unordered list |
| uk-list-basic | Creates a basic ordered or unordered list |
| uk-list-bullet-modifier | Creates a bulleted list |
| uk-list-divider-modifier | Creates a divided list |
| uk-list-striped-modifier | Creates a striped list |
| uk-list-large-modifier | Creates a list with increased spacing between items. Can be combined with other list styles |

### Margin
| Trigger | Description |
| :-------: | :-----------: |
| uk-margin | [Class] Adds top margin, if it is preceded by another element, and always bottom margin |
| uk-margin-position | [Class] Adds the selected margin to that side |
| uk-margin-size | [Class] Adds a margin of chosen size |
| uk-margin-size-position | [Class] Adds a margin of chosen size to the chosen side |
| uk-margin-remove | [Class] Removes all margins |
| uk-margin-remove-position | [Class] Removes the margin the chosen side(s) |
| uk-margin-auto | [Class] Sets left and right margins to auto, centering block and flex elements |
| uk-margin-auto-position | [Class] Sets the selected margin to auto, pushing block and flex elements to the opposite end |
| uk-margin-dynamic-sample | Automatically adds spacing to stacking elements with the uk-margin attribute |

### Marker
| Trigger | Description |
| :-------: | :-----------: |
| uk-marker | [Attribute] Used to create a marker icon that can be displayed on top of images |

### Modal
| Trigger | Description |
| :-------: | :-----------: |
| uk-modal | [Attribute] Used to create a modal |
| uk-modal-sample | Creates a modal with a button toggle |
| uk-modal-close-default | Creates a modal with close button inside |
| uk-modal-close-outside | Creates a modal with close button outside |
| uk-modal-center | Creates a centered modal using the parameter 'center' |
| uk-modal-header-footer | Creates a modal divided into different content sections |
| uk-modal-caption | Creates a modal with a caption outside of it |
| uk-modal-container-modifier | Creates a modal that expands to the default container width |
| uk-modal-full-modifier | Creates a modal that fills the entire page |

### Nav
| Trigger | Description |
| :-------: | :-----------: |
| uk-nav | [Class] Used to create a nav with optional styling |
| uk-nav-default | Creates a nav with default styling |
| uk-nav-nested | Creates a nested nav with default styling |
| uk-nav-accordion | Creates an accordion-styled nav with icons for parents |
| uk-nav-accordion-multiple-open | Creates an accordion nav that can have multiple sub-navs open at once |
| uk-nav-header | Creates a nav header |
| uk-nav-divider | Creates a nav divider |
| uk-nav-primary | Creates a nav with emphasized styling |
| uk-nav-center | Creates a centered nav |
| uk-nav-dropdown | Creates a nav in a dropdown |
| uk-nav-navbar | Creates a nav in a navbar |

### Navbar
| Trigger | Description |
| :-------: | :-----------: |
| uk-navbar | [Attribute] Used to create a navigation bar |
| uk-navbar-sample | Creates a primary navigation bar |
| uk-navbar-multiple | Creates multiple navigations inside the navbar container |
| uk-navbar-click | Creates a primary navigation bar that is toggled with a click |
| uk-navbar-transparent | Creates a transparent navigation bar |
| uk-navbar-subtitle | Creates a subtitle for a navbar item |
| uk-navbar-custom-content | Creates a navbar which can hold custom items (text, icons, buttons, forms) |
| uk-navbar-centered-logo | Creates a navbar with a centered logo |
| uk-navbar-toggle-item | Creates a navbar with an icon as a toggle |
| uk-navbar-dropdown | Creates a navbar with a dropdown component |
| uk-navbar-dropdown-multiple-columns | Creates a navbar dropdown with multiple columns |
| uk-navbar-dropdown-boundary-align | Creates a navbar with dropdowns aligned to the navbar boundary |
| uk-navbar-dropdown-justify | Creates a navbar with dropdowns justified |
| uk-navbar-dropbar | Creates a navbar with dropdowns justified |
| uk-navbar-dropbar-push | Creates a navbar with a dropdown that pushes page content down to fit the space |

### Notification
| Trigger | Description |
| :-------: | :-----------: |
| uk-notification-example | Creates a notification example using javascript |
| uk-notification-html-message | Creates a notification with html content |
| uk-notification-position | Creates a notification with an adjusted position |
| uk-notification-style | Creates a styled notification |
| uk-notification-close-all | Closes all notifications |

### Offcanvas
| Trigger | Description |
| :-------: | :-----------: |
| uk-offcanvas | [Attribute] Used to create an off-canvas |
| uk-offcanvas-sample | Creates a basic off-canvas |
| uk-offcanvas-overlay | Creates an off-canvas that adds an overlay to the page |
| uk-offcanvas-flip-modifier | Creates an off-canvas that slides in from the right |
| uk-offcanvas-animation-mode | Creates an off-canvas with a modified animation mode for its entrance |
| uk-offcanvas-nav | Creates an off-canvas containing a nav component |

### Overlay
| Trigger | Description |
| :-------: | :-----------: |
| uk-overlay | [Class] Used to create a basic image overlay |
| uk-overlay-basic | Creates a basic image overlay at a modifiable position |
| uk-overlay-style-default | Creates an image overlay with a default style |
| uk-overlay-style-primary | Creates an image overlay with a primary style |
| uk-overlay-icon | Creates an image overlay icon |

### Padding
| Trigger | Description |
| :-------: | :-----------: |
| uk-padding | [Class] Adds default padding to the element |
| uk-padding-size | [Class] Adds a smaller or larger padding to the element |
| uk-padding-remove | [Class] Removes all padding from an element |
| uk-padding-remove-position | [Class] Removes padding from the chosen side(s) of an element |

### Pagination
| Trigger | Description |
| :-------: | :-----------: |
| uk-pagination | [Class] Used to create a simple pagination for navigation through pages |
| uk-pagination-basic | Creates a simple pagination for navigation through pages |
| uk-pagination-alignment | Creates a simple pagination aligned with flex |
| uk-pagination-previous-next | Creates a previous and next button inside of a pagination |

### Parallax
| Trigger | Description |
| :-------: | :-----------: |
| uk-parallax | [Attribute] Used to animate CSS properties depending on the scroll position of the document |
| uk-parallax-properties | [Attribute] Inserts the parallax attribute with a list of animatable properties |
| uk-parallax-start-end | [Attribute] Sets the start and end values of a property by seperating them with a comma |
| uk-parallax-viewport | [Attribute] Defines how far inside the viewport the element is scrolled until the animation is completed |
| uk-parallax-sample | Creates a sample div with parallax enabled |
| uk-parallax-nested-sample | Showcases nested parallax elements |
| uk-parallax-target-sample | Creates a parallax animation based on the viewport visibility of another element |
| uk-parallax-easing-sample | Creates a parallax element with a modifiable easing value |
| uk-parallax-color-sample | Creates a parallax element with a color transition |
| uk-parallax-filter-sample | Creates a parallax element with css filters |

### Placeholder
| Trigger | Description |
| :-------: | :-----------: |
| uk-placeholder | [Class] Used to create a placeholder space |
| uk-placeholder-sample | Creates a placeholder space |

### Position
| Trigger | Description |
| :-------: | :-----------: |
| uk-position | [Class] Positions the element at the chosen location |
| uk-position-extended | [Class] Positions the element at specific locations without it being spread over its parent container |
| uk-position-cover | [Class] Positions the element to cover its container |
| uk-position-small | [Class] Positions the element at specific locations with a small margin |
| uk-position-medium | [Class] Positions the element at specific locations with a medium margin |
| uk-position-relative | [Class] Positions the element at a relative position |
| uk-position-absolute | [Class] Positions the element at an absolute position |
| uk-position-fixed | [Class] Positions the element at a fixed position |
| uk-position-z-index | [Class] Positions the element at a z-index position of 1 |

### Progress
| Trigger | Description |
| :-------: | :-----------: |
| uk-progress | [Class] Used to create a progress bar |
| uk-progress-sample | Creates a progress bar |

### Scroll
| Trigger | Description |
| :-------: | :-----------: |
| uk-scroll | [Attribute] Used to create a link that smooth scrolls to the targeted element with a matching id |
| uk-scroll-anchor | Creates a link that smooth scrolls to the targetted element with matching id |

### Scrollspy
| Trigger | Description |
| :-------: | :-----------: |
| uk-scrollspy | [Attribute] Used to add a scrollspy to an element |
| uk-scrollspy-sample | Adds the scrollspy attribute to an element and animates it when in view |
| uk-scrollspy-group | Adds the scrollspy attribute to an element and animates it when in view |

### Search
| Trigger | Description |
| :-------: | :-----------: |
| uk-search | [Class] Used to create a search bar |
| uk-search-default | Creates a search bar with default styling |
| uk-search-icon | Creates a search bar with a search icon to the left |
| uk-search-icon-flip | Creates a search bar with a search icon to the right |
| uk-search-icon-button | Creates a search bar with a clickable search icon |
| uk-search-large | Creates a larger search bar |
| uk-search-navbar | Creates a search bar that can be used within a navbar |
| uk-search-toggle | Creates a toggle using a search icon |
| uk-search-navbar-toggle | Creates a search icon toggle inside of a navbar |

### Section
| Trigger | Description |
| :-------: | :-----------: |
| uk-section | [Class] Used to create a section with optional styling |
| uk-section-default | Creates a section with a default style |
| uk-section-muted | Creates a section with a muted style |
| uk-section-primary | Creates a section with a primary style |
| uk-section-secondary | Creates a section with a secondary style |
| uk-section-media | Creates a section used for custom background images |
| uk-section-preserve-color | Creates a section that preserves the font colours of child elements |
| uk-section-size-modifier | Creates a section with modified padding applied |
| uk-section-overlap-modifier | Creates a section that applies a border image and a negative offset |

### Slidenav
| Trigger | Description |
| :-------: | :-----------: |
| uk-slidenav | Creates a previous and next button for flipping through slideshows |
| uk-slidenav-large | Creates a larger slidenav |
| uk-slidenav-position-image | Creates a slidenav appropriately positioned to the sides of an image |
| uk-slidenav-container | Displays a cojoint slidenav |

### Sortable
| Trigger | Description |
| :-------: | :-----------: |
| uk-sortable | [Attribute] Used to create a sortable, re-arrangable grid of elements |
| uk-sortable-sample | Creates a sortable, re-arrangable grid of elements |
| uk-sortable-handle | Creates a sortable list using a special handle button instead of the entire element |
| uk-sortable-group | Creates a sortable group that can interchange elements |
| uk-sortable-custom-class | Creates sortable that can apply multiple classes to items while being dragged |

### Spinner
| Trigger | Description |
| :-------: | :-----------: |
| uk-spinner | [Attribute] Used to create an animated loading spinner |
| uk-spinner-sample | Creates an animated loading spinner |

### Sticky
| Trigger | Description |
| :-------: | :-----------: |
| uk-sticky | [Attribute] Used to create an element that remains at the top of the viewport while scrolling down |
| uk-sticky-sample | Creates an element that remains at the top of the viewport while scrolling down |
| uk-sticky-offset | Creates a sticky element with a pixel offset from the top |
| uk-sticky-top | Creates a sticky element with a delay |
| uk-sticky-animation | Creates a sticky element with an animation when it reappears |
| uk-sticky-scroll-up | Creates a sticky element that shows only when scrolling up |
| uk-sticky-bottom | Creates a sticky element that is bound to a specific element |
| uk-sticky-responsive | Creates a sticky element that is only enabled on specified device widths and above |

### Subnav
| Trigger | Description |
| :-------: | :-----------: |
| uk-subnav | [Class] Used to create a basic sub-navigation |
| uk-subnav-basic | Creates a basic sub-navigation with items wrapping into the next line |
| uk-subnav-divider | Creates a sub-navigation seperated with lines |
| uk-subnav-pill | Creates a sub-navigation that highlights the active item with a background |
| uk-subnav-dropdown | Creates a sub-navigation that contains a dropdown |

### Switcher
| Trigger | Description |
| :-------: | :-----------: |
| uk-switcher | [Attribute] Used to create a switcher component |
| uk-switcher-basic | Creates a switcher that dynamically transitions through different content panes |
| uk-switcher-navigation | Creates a switcher with navigation controls within the content pane |
| uk-switcher-connect-containers | Creates a switcher that connects multiple content containers |
| uk-switcher-animation | Creates a switcher animates its transitions |
| uk-switcher-multiple-animations | Creates a switcher with multiple animations |
| uk-switcher-subnav | Creates a switcher combined with a subnav |
| uk-switcher-tab | Creates a switcher combined with a tab |
| uk-switcher-tab-vertical | Creates a switcher combined with a vertical tab |
| uk-switcher-button | Creates a switcher combined with a vertical tab |
| uk-switcher-nav | Creates a switcher combined with a vertical tab |

### Tab
| Trigger | Description |
| :-------: | :-----------: |
| uk-tab | [Attribute] Used to create a basic tabbed navigation |
| uk-tab-basic | Creates a basic tabbed navigation |
| uk-tab-bottom | Creates a tab with items flipped to the bottom |
| uk-tab-vertical | Creates a tab with items aligned left or right |
| uk-tab-alignment | Creates a tab with items aligned left or right |
| uk-tab-dropdown | Creates a tab with a dropdown |

### Table
| Trigger | Description |
| :-------: | :-----------: |
| uk-table | [Class] Used to create a table |
| uk-table-sample | Creates a table without any styling |
| uk-table-divider | Creates a table with each row seperated by a divider |
| uk-table-hover | Creates a table with a hover state on table rows |
| uk-table-striped | Creates a table with zebra-striping on table rows |
| uk-table-small | Creates a smaller, more compact table |
| uk-table-justify | Creates a table with the outer padding of the first and last columns removed |
| uk-table-middle | Creates a table with center aligned elements |
| uk-table-responsive | Creates a table that provides a horizontal scrollbar on smaller device screens when needed |
| uk-table-column-width | Modifies the width of a table column |

### Text
| Trigger | Description |
| :-------: | :-----------: |
| uk-text-lead | [Class] Highlights text for subheadings and article subtitles |
| uk-text-meta | [Class] Text class for paragraphs with meta data about an article or similar |
| uk-text-size | [Class] Modifies the font size of text |
| uk-text-bold | [Class] Creates bold text |
| uk-text-transform | [Class] Transforms text characters into the chosen case |
| uk-text-color | [Class] Modifies the color of text into the chosen color scheme |
| uk-text-alignment | [Class] Aligns text to a chosen position |
| uk-text-alignment-responsive | [Class] Aligns text to a chosen position on specific screen widths |
| uk-text-vertical-alignment | [Class] Aligns text vertically |
| uk-text-wrapping | [Class] Wraps text according to your choice |

### Tile
| Trigger | Description |
| :-------: | :-----------: |
| uk-tile | [Class] Used to create a tile with optional styling |
| uk-tile-size-modifier | [Class] Used to create a tile with modified sizing |
| uk-tile-default | Creates a tile with a default style |
| uk-tile-muted | Creates a tile with a muted style |
| uk-tile-primary | Creates a tile with a primary style |
| uk-tile-secondary | Creates a tile with a secondary style |
| uk-tile-padding | Creates a tile with modified padding from the padding component |

### Toggle
| Trigger | Description |
| :-------: | :-----------: |
| uk-toggle | [Attribute] Used to create a toggle that shows/hides an element |
| uk-toggle-example | Creates a toggle that shows/hides an element |
| uk-toggle-multiple | Creates a toggle that shows/hides multiple elements |
| uk-toggle-custom-class | Creates a toggle that applies a custom class to the target element |
| uk-toggle-animation | Creates a toggle that animates when toggling between items |
| uk-toggle-multiple-animations | Creates a toggle with multiple animations |
| uk-toggle-queued-animation | Creates a toggle with queued animations |
| uk-toggle-modes | Changes the trigger mode for the toggle |
| uk-toggle-media | Toggles an element based on the screen width |

### Tooltip
| Trigger | Description |
| :-------: | :-----------: |
| uk-tooltip | [Attribute] Used to create an element with a tooltip |
| uk-tooltip-sample | Creates an element with a tooltip |
| uk-tooltip-alignment | Creates a tooltip with a modified alignment |
| uk-tooltip-delay | Creates a tooltip with a specified delay in milliseconds |

### Totop
| Trigger | Description |
| :-------: | :-----------: |
| uk-totop | [Attribute] Used to create an icon used for scrolling to the top of the page |
| uk-totop-sample | Creates an icon used for scrolling to the top of the page |
| uk-totop-smooth | Creates a totop component with smooth scrolling |

### Transition
| Trigger | Description |
| :-------: | :-----------: |
| uk-transition-fade | Creates a smooth transition between two states when hovering an element |
| uk-transition-scale | Creates a smooth transition between two states when hovering an element |
| uk-transition-slide | Creates a smooth transition between two states when hovering an element |
| uk-transition-slide-size | Creates a smooth transition between two states when hovering an element |

### Upload
| Trigger | Description |
| :-------: | :-----------: |
| uk-upload-select | Creates a button which opens a file select window |
| uk-upload-drop-area | Creates an area for files to be dropped and uploaded |
| uk-upload-script | Creates the upload script |

### Utility
| Trigger | Description |
| :-------: | :-----------: |
| uk-utility-panel | Creates a panel used to outline a section of content |
| uk-utility-panel-scrollable | Creates a scrollable panel |
| uk-utility-float | [Class] Floats an element left or right |
| uk-utility-clearfix | [Class] Removes floats from this element and its children |
| uk-utility-overflow | [Class] Modifies an element's overflow behaviour |
| uk-utility-resize | [Class] Allows an element to be resized |
| uk-utility-display | [Class] Changes the display properties of an element |
| uk-utility-inline | [Class] Applies inline-block behaviour to an element, adds a max-width of 100% and creates a position context. Optionally clips overflowing child elements. |
| uk-utility-height | [Class] Modifies the height of an element to 100%/150px/300px/450px respectively. |
| uk-utility-max-height | [Class] Modifies the max-height of an element to 150px/300px/450px respectively. |
| uk-utility-viewport-height | Modifies the height of an element to fill the entire viewport. Height behaviour can be changed with an option. |
| uk-utility-match-height | Expands all children of a container to the same height. |
| uk-utility-match-height-specific | Matches the height of specific child elements |
| uk-utility-match-height-all | Matches the height of all child elements even in other rows |
| uk-utility-responsive | [Class] Applies a responsive behaviour to any element |
| uk-utility-preserve-width | [Class] Avoids responsive behaviour and preserves original dimensions |
| uk-utility-border-radius | [Class] Modifies the border radius of an element |
| uk-utility-box-shadow | [Class] Adds a box shadow to an element |
| uk-utility-box-shadow-bottom | [Class] Adds a box shadow to the bottom of an element |
| uk-utility-box-shadow-hover | [Class] Adds a box shadow to an element on hover |
| uk-utility-dropcap | Applies a drop cap on a paragraph |
| uk-utility-leader | Visually connects horizontal items with a line of dots |
| uk-utility-logo-text | Creates a text logo |
| uk-utility-logo-image | Creates an image logo |
| uk-utility-inline-svg | Adds an inline SVG |
| uk-utility-gif | Adds a GIF that plays when it comes into view |
| uk-utility-video | Adds a video that can automatically play when it comes into view |
| uk-utility-blend | [Class] Applies a modified blend mode to a background |
| uk-utility-transform-center | [Class] Centers an element to itself |
| uk-utility-transform-origin | [Class] Modifies the origin of an animation |
| uk-utility-disabled | [Class] Disables the click behaviour of any element |
| uk-utility-drag | [Class] Applies a move cursor to an element |
| uk-utility-dragover | [Class] Creates a box shadow used for upload areas when dragging a file over it |

### Visibility
| Trigger | Description |
| :-------: | :-----------: |
| uk-hidden | [Attribute] Used for hiding an element |
| uk-hidden-class | [Class] Legacy class used for hiding an element. Recommended: Use 'hidden' attribute instead. |
| uk-hidden-responsive | [Class] Hides an element from screens larger than the specified width (640/960/1200/1600 px respectively) |
| uk-hidden-hover | Hides the content until the parent container is hovered |
| uk-visible | [Class] Shows an element on screens larger than the specified width (640/960/1200/1600 px respectively) |
| uk-invisible | [Class] Hides the element without removing it from the document flow. |
| uk-invisible-hover | Hides the content (without removing it from the document flow) until the parent container is hovered |
| uk-hidden-touch | Hides the content on touch devices |
| uk-hidden-notouch | Hides the content on devices without a touch screen |

### Width
| Trigger | Description |
| :-------: | :-----------: |
| uk-width | [Class] Modifies the width of an element to take up a portion of its parent container, or the entire width. Usually used with 'uk-grid'. |
| uk-width-responsive | [Class] Modifies the width of an element to take up a portion of its parent container on specified device widths and higher. Columns stack on smaller sizes. |
| uk-width-auto | [Class] The item expands to the width of its own content. Usually used with 'uk-grid'. |
| uk-width-expand | [Class] The item expands to fill up the remaining space of the grid container. Usually used with 'uk-grid'. |
| uk-child-width | [Class] Evenly divides the width of all child elements in a 'uk-grid' |
| uk-child-width-responsive | [Class] Evenly divides the width of all child elements in a 'uk-grid' on specified device widths and higher. Columns stack on smaller sizes. |
| uk-fixed-width | [Class] Applies a fixed width to an element of 150/300/450/600/750 px respectively. | 

List of Commands (Javascript)
---

### Accordion JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-accordion | Initializes an accordion element with various options |
| uk-accordion-events | Triggers a function when a specified accordion event is triggered |

### Alert JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-alert | Initializes an alert element with various options |
| uk-alert-events | Triggers a function when a specified alert event is triggered |
| uk-alert-methods | Showcases the methods available to the alert component |

### Countdown JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-countdown | Initializes a countdown element with various options |

### Cover JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-cover | Initializes a cover element with various options |

### Drop JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-drop | Initializes a drop element with various options |
| uk-drop-events | Triggers a function when a specified drop event is triggered |

### Dropdown JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-dropdown | Initializes a dropdown element with various options |
| uk-dropdown-events | Triggers a function when a specified dropdown event is triggered |

### Form JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-form | Initializes a form element with various options |

### Grid JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-grid | Initializes a grid element with various options |

### Grid Parallax JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-grid-parallax | Initializes a grid parallax element with various options |

### Icon JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-icon | Initializes an icon element with various options |

### Lightbox JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-lightbox | Initializes a lightbox element with various options |
| uk-lightbox-events | Triggers a function when a specified lightbox event is triggered |
| uk-lightbox-methods | Showcases the methods available to the lightbox component |
| uk-lightbox-panel | Initializes a lightbox panel element with various options |
| uk-lightbox-panel-methods | Showcases the methods available to the lightbox panel component |

### Margin JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-margin | Initializes a margin element with various options |

### Modal JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-modal | Initializes a modal element with various options |
| uk-modal-events | Triggers a function when a specified modal event is triggered |
| uk-modal-alert | Creates an alert box with one button |
| uk-modal-confirm | Creates a confirm dialog with your message and two buttons |
| uk-modal-prompt | Creates a dialog asking for a text input |
| uk-modal-dialog | Creates a dialog with any HTML content |
| uk-modal-dialog-sample | Creates a sample dialog which processes user input |

### Nav JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-nav | Initializes a nav element with various options |

### Navbar JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-navbar | Initializes a navbar element with various options |
| uk-navbar-events | Triggers a function when a specified navbar event is triggered |

### Notification JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-notification | Creates a notification with various options |
| uk-notification-events | Triggers a function when a specified notification event is triggered |

### Offcanvas JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-offcanvas | Initializes a offcanvas element with various options |
| uk-offcanvas-events | Triggers a function when a specified offcanvas event is triggered |

### Parallax JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-parallax | Initializes a parallax element with various options |

### Scroll JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-scroll | Initializes a scroll element with various options |

### Scrollspy JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-scrollspy | Initializes a scrollspy with various options |
| uk-scrollspy-events | Triggers a function when a specified scrollspy event is triggered |
| uk-scrollspy-nav | Initializes a scrollspy nav with various options |
| uk-scrollspy-nav-events | Triggers a function when a specified scrollspy nav event is triggered |

### Sortable JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-sortable | Initializes a sortable with various options |
| uk-sortable-events | Triggers a function when a specified sortable event is triggered |

### Sticky JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-sticky | Initializes a sticky with various options |
| uk-sticky-events | Triggers a function when a specified sticky event is triggered |

### Switcher JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-switcher | Initializes a switcher with various options |
| uk-switcher-events | Triggers a function when a specified switcher event is triggered |

### Tab JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-tab | Initializes a tab with various options |
| uk-tab-events | Triggers a function when a specified tab event is triggered |

### Toggle JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-toggle | Initializes a toggle with various options |
| uk-toggle-events | Triggers a function when a specified toggle event is triggered |

### Tooltip JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-tooltip | Initializes a tooltip with various options |
| uk-tooltip-events | Triggers a function when a specified tooltip event is triggered |

### Upload JS
| Trigger | Description |
| :-------: | :-----------: |
| uk-upload | Initializes a upload with various options |
| uk-upload-events | Triggers a function when a specified upload event is triggered |
| uk-upload-sample | Creates a sample upload script based on official docs |
