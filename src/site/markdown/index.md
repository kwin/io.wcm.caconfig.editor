## About Configuration Editor

Context-Aware Configuration Editor Template for AEM.

[![Maven Central](https://img.shields.io/maven-central/v/io.wcm/io.wcm.caconfig.editor)](https://repo1.maven.org/maven2/io/wcm/io.wcm.caconfig.editor/)


### Documentation

* [Usage][usage]
* [Field Validation][validation]
* [API documentation][apidocs]
* [Changelog][changelog]


### Overview

The configuration editor can be used by AEM author users to read and write configuration data mapped to the current context pages.

Features:

* Manage Context-Aware Configuration by creating an editor page in the content context
* Manage singleton configuration, configuration collections and nested configurations
* Display all configuration metadata and default values
* Support all data types and arrays of values
* Control collection and property inheritance and support overridden values
* Allows to define custom widgets for configuration properties like pathbrowser
* Publish configuration

See [Usage][usage] for further details, installation instructions and some screenshots.

There is also a [sample application][sample-app] you can deploy directly in a local AEM 6.1 or 6.2 instance to test the configuration editor.


### Supported AEM versions

Context-Aware Configuration is supported in AEM 6.1, 6.2, 6.3 and upwards. AEM 6.0 is not supported.

When you are using AEM 6.1 or 6.2 you have to additionally deploy the Apache Sling Context-Aware Configuration bundles (API, SPI, Impl) to AEM. In AEM 6.3 you have to update the Apache Sling Context-Aware Configuration SPI and Impl bundles to the latest version to use all features.

See [Deploy and configure Context-Aware Configuration in AEM][deploy-configure-caconfig-in-aem] for details.


### AEM Version Support Matrix

|Context-Aware Configuration Editor version |AEM version supported
|-------------------------------------------|----------------------
|1.12.x or higher                           |AEM 6.5.7+, AEMaaCS
|1.9.x - 1.11.0                             |AEM 6.5+, AEMaaCS
|1.8.x                                      |AEM 6.4+, AEMaaCS
|1.7.x                                      |AEM 6.3+
|1.5.x - 1.6.x                              |AEM 6.2+
|1.0.x - 1.4.x                              |AEM 6.1+


### Dependencies

There are is an **optional** dependency to *wcm.io Sling Commons* which you have to deploy if you want to use the filtering and decorating categories feature (see [Usage][usage]).

|---|---|---|
| [wcm.io Sling Commons](https://repo1.maven.org/maven2/io/wcm/io.wcm.sling.commons/) | [![Maven Central](https://img.shields.io/maven-central/v/io.wcm/io.wcm.sling.commons)](https://repo1.maven.org/maven2/io/wcm/io.wcm.sling.commons/) |


### GitHub Repository

Sources: https://github.com/wcm-io/io.wcm.caconfig.editor


[usage]: usage.html
[validation]: validation.html
[apidocs]: bundle/apidocs/
[changelog]: changes-report.html
[sample-app]: https://github.com/wcm-io/wcm-io-caconfig/tree/develop/sample-app
[deploy-configure-caconfig-in-aem]: https://wcm.io/caconfig/deploy-configure-caconfig-in-aem.html
