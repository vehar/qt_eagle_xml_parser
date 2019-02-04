# EAGLE XML file parser code for Qt (and more useful stuffs)

A Qt based class to parse Autodesk EAGLE Schematics/PCBs/libraries.

Autogenerated from the eagle.dtd* shipped with EAGLE 9.1.3 with [KODE](https://github.com/martonmiklos/kode "KODE")

As of today it is possible to parse and save an EAGLE design without making the EAGLE to claim about missing/malformed stuff.

*[see tools/generate.sh for the tricks](../../blob/master/tools/generate.sh) 


Eventually I might add some EAGLE related classes here. Like dru/.eaglerc loaders/processors, and graphical classes to be able to render EAGLE elements via QPainter.
