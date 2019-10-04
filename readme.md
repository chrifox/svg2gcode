svg2gcode
========
A command line utility for converting SVG to Gcode using 
[canvg](https://code.google.com/p/canvg/) and [Gcanvas](https://github.com/em/gcanvas).

### Installation
First make sure you have [nodejs](http://nodejs.org) installed.
```
npm i -g svg2gcode
```

### Usage
```
  Usage: svg2gcode [options] file > output

  Options:

    -h, --help         |          | output usage information
    -V, --version      |          | output the version number
    -s, --speed        | <number> | spindle speed
    -f, --feed         | <number> | feed rate
    -d, --depth        | <number> | z of final cut depth
    -D, --tooldiameter | <number> | tool diameter (default = 1.75)
    -c, --depthofcut   | <number> | z offset of layered cuts
    -t, --top          | <number> | z of top of work surface
    -a, --above        | <number> | z of safe area above the work

```
