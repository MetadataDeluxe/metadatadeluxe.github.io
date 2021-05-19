## vra.config for ExifTool

This is a config file to read and write VRA Core Essentials XMP embedded metadata using [ExifTool by Phil Harvey.](https://exiftool.org/)

[VRA Core schema](http://www.loc.gov/standards/vracore/) is a data standard for the description of works of visual culture as well as the images that document them. 

VRA Essentials is made up select VRA Core properties adapted to the Adobe XMP embedded metadata specification. 

The prefered XMP prefix is "vrae" and the namespace is http://www.vraweb.org/vracore/4.0/essential/

Properties are defined as either Work or Image (Collection is not supported at this time)
 - Work: describes the creative artwork, object or performance shown in the image/photo.
 - - All Work display and indexed properties and sub-properties are supported, but only selected attributes are supported.
 - Image: describes the photo as a visual surrogate of the Artwork/Object.
 - - When possible, VRA Image properties use IPTC XMP properties in order to maximize interoperability in image processing/editing/database applications.

Properties have a set of indexed values, e.g., WorkAgentIndexed and a corresponding display element, e.g., WorkAgent
 - Indexed values are repeatable, i.e., you can have multiple Agents (architect, landscape architect, etc.). An indexed set is an XMP sequential array or structures.
 - Display values concatenate Indexed values into a single text string that can be modified for readability. A display element is a simple XMP text property.

## [See full documentation and downloads](https://github.com/MetadataDeluxe/VRA-Core-Essentials-ExifTool-config)
