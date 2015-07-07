# config-astyle
Just a configuration file for Artistic Style Automatic Formatter (http://astyle.sourceforge.net/)

How to use the file:
1) cp codestyle.cfg $HOME/.astylerc
or
2) export ARTISTIC_STYLE_OPTIONS="$(pwd -P)/codestyle.cfg"
or
3) atyle --options="$(pwd -P)/codestyle.cfg" ...

