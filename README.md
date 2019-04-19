# scorm-imsmanifest-java
An library to build Java entity based on [XML Schema Definition Files](https://scorm.com/scorm-explained/technical-scorm/content-packaging/xml-schema-definition-files/]by JAXB

Unfortunately, SCORM official XSD can't be used by JAXD directly. Few modifications have been done to allow JAXB to build Java entities.

The original XSD files in `src/main/resources` folder are copied from following URIs.

The modified XSD files can be found in `src/main/xsd`.  

In `ims_xml.xsd`, `xmlns="http://www.w3.org/XML/1998/namespace"` has been removed from `xsd:schema` tag.
