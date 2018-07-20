# responsive.js
A simple library for making websites responsive.

### All this library does is hide or show HTML in this set of tags:
```html
<horizontal>
    <!-- Content for horizontal screen orientation -->
</horizontal>

<vertical>
    <!-- Content for vertical screen orientation -->
</vertical>

<mobile>
    <!-- Content for mobile -->
</mobile>

<desktop>
    <!-- Content for desktop -->
</desktop>
```

> In addition to the tags, you can use the constant booleans `isMobile` and `isDesktop`. I think those are fairly self-explanatory.

### Thats it.
> The "horizontal" and "vertical" conditions are updated on window resize.<br />
> The "mobile" and "desktop" conditions are only checked upon load of the library.<br />
> Tags are hidden using css `display: none` and unhidden using `display: block`.<br />
> The library is tiny and can be easily modified to fit your needs.<br />
<br />
### Happy coding!