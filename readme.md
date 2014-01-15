**THIS IS A WORK IN PROGRESS!!**

# GGSX - Golden Grid System Extended

**TODO**
- Explain differences with original GGS
- Better example layout
- Figure out how 16 col grid units work when 16 not active

## How to install

`git clone --recursive https://github.com/aripalo/GGSX.git`


## Golden Grid System

Originally Developed by [Joni Korpi](http://jonikorpi.com/) / [@jonikorpi](http://twitter.com/jonikorpi/). Licensed under [MIT](http://opensource.org/licenses/mit-license.php).

A fluid-width grid system composed out of 18 even columns, two of which are used as outer margins, leaving 16 columns for use in design, which in turn can be combined into 8 columns or 4 columns as needed. They could also be doubled into 32 columns, but I don't think anyone needs a grid for 5000 CSS-px wide sites.

See http://goldengridsystem.com/ for more details.

## File list

- **GGSX.html** contains the required markup (namely the meta viewport tag) and a simple demo.
- **GGSX.scss** contains all the required CSS and Sass mixins + sample grid for GGSX use.
- **GGS.js** contains Golden Gridlet, a script that overlays the GGS grid and a baseline grid of 1.5em onto the page. Can be customized around the top of the file. Powered by the [Ender library](http://ender.no.de/).

## Credits


Original Golden Grid System Developed by [Joni Korpi](http://jonikorpi.com/) / [@jonikorpi](http://twitter.com/jonikorpi/). Licensed under [MIT](http://opensource.org/licenses/mit-license.php).

Golden Grid System Extended by [Ari Palo](http://aripalo.fi/) / [@aripalo](http://twitter.com/aripalo/).
