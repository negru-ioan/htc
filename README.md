# How to Use border-radius.htc

To apply rounded corners to elements in Internet Explorer 8 and below, you can use the `border-radius.htc` file. Follow these steps:

1. Include the `border-radius.htc` file in your project.

```css
.rounded {
    border-radius: 11px;
    behavior: url(path/to/border-radius.htc);
}
```

2. Add the `rounded` class to the HTML elements you want to have rounded corners.

```html
<div class="rounded">
    <!-- Your content goes here -->
</div>
```

### Browser Compatibility

The `border-radius.htc` file was specifically built for Internet Explorer versions 8 and below. Here's why:

#### Changes Made

-   **IE8 Standards Mode Compatibility:** Modified for compatibility with IE8 standards mode.
-   **VML Elements Positioning:** VML elements are now positioned behind the original box, reducing the likelihood of breakage.

#### Published Dates

-   Original Author: Remiz Rahnas

    -   [Original Author URL](http://www.htmlremix.com)
    -   Published date: 2008/09/24

-   Changes by Nick Fetchak:
    -   Published date: 2009/11/18

### Important Notes

-   Ensure the `border-radius.htc` file is included and accessible in your project.
-   The `rounded` class should be applied to elements requiring rounded corners.
-   If you encounter any issues or have questions, refer to the original author's [website](http://www.htmlremix.com) for additional information.

Feel free to reach out if you need further assistance or have any questions related to the usage of `border-radius.htc`.
