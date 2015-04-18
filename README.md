Color Blindness Emulator
========================

This SVG file (`filters.svg`) contains filters that emulate following color
blindness types:

- Protanopia
- Protanomaly
- Deuteranopia
- Deuteranomaly
- Tritanopia
- Tritanomaly
- Achromatopsia
- Achromatomaly


EXAMPLE
-------

![Results of color blindness emulation provided by `filters.svg`][test-results.png]

This preview is the result of applying filters against `test.jpg`.


USAGE
-----

You can use this SVG file from CSS `filter` property:

    .foo {
      filter: url('filters.svg#protanopia');
    }


LICENSE
-------

CC0: http://creativecommons.org/publicdomain/zero/1.0/


[1]: http://caniuse.com/#feat=css-filters
