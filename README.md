Z-Ray Extension API
==========

This document will describe the Z-Ray extensions API concepts, how to use and supply code samples.

## Extension Structure
A Z-Ray extension is comprised of two main components:
1. A `zray.php` file - the zray extension include file, which is expected to be located in the root of the extension directory.
2. Other files, such as view scripts, JavaScript and PHP components.

The extension implements a tracing functionality for collecting and storing data into the custom data zray database table. This information is available for use using the zrayGetCustomData Web API action, and is utilized by Z-Ray for display purposes.

Unless specified otherwise, any data type stored using the ZrayExtension class will be used to automatically generate a data table based on the information saved in the data type.

A view script may be added to the extension to create a custom display.

## Code Examples
You can find code examples for all the content in this document (and more!) in our GitHub account http://github.com/zend-server-extensions. You can find an example Z-Ray extension here: http://github.com/zend-server-extensions/Z-Ray-Samples. 

<br/><br/><br/><br/>


## Main Subjects
### [Data Collection](DataCollection.md)
### [Data Display](DataDisplay.md)
### [Z-Ray Widgets](Widgets.md)
