# design.automation-java-simple.sample

[![odata](https://img.shields.io/badge/odata-4.0-yellow.svg)](http://www.odata.org/documentation/)
[![ver](https://img.shields.io/badge/AutoCAD.io-2.0.0-blue.svg)](https://developer.autodesk.com/api/autocadio/v2/)
[![License](http://img.shields.io/:license-mit-red.svg)](http://opensource.org/licenses/MIT)

## Description

This is a simple Java client that exercises the predefined `PlotToPDF` activity.

It issues direct HTTP requests to call the [Autodesk Forge Design Automation API](https://developer.autodesk.com/en/docs/design-automation/v2/overview/).

## Dependencies

- [IntelliJ 14](http://www.jetbrains.com/idea/).

## Setup/Usage Instructions

Please refer to the [Design Automation API tutorials](https://developer.autodesk.com/en/docs/design-automation/v2/tutorials/)
and how to [convert a DWG to a PDF file](https://developer.autodesk.com/en/docs/design-automation/v2/tutorials/convert-dwg-to-pdf/).

Create your Forge app first of all, as described there.

Store your credentials in the environement variables `FORGE_CLIENT_ID` and `FORGE_CLIENT_SECRET`.
 
The Java client will pick them up from there.

## Questions

Please post your questions to [StackOverflow using the `autodesk-designautomation` tag](http://stackoverflow.com/questions/tagged/autodesk-designautomation).

## License

These samples are licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT).
Please see the [LICENSE](LICENSE) file for full details.

## Authors

- Jonathan Miao
- Version 2.0.0 by Jeremy Tammik,
[The Building Coder](http://thebuildingcoder.typepad.com),
[ADN](http://www.autodesk.com/adn)
[Open](http://www.autodesk.com/adnopen),
[Autodesk Inc.](http://www.autodesk.com)
&mdash; migrated to Design Automation API on November 7-8, 2016.
