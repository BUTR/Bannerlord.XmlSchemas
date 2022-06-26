# Bannerlord.XmlSchemas
Contains the following XML schemas:
* [SubModule.xsd](https://raw.githubusercontent.com/BUTR/Bannerlord.XmlSchemas/master/SubModule.xsd) - for SubModule.xml
* [ModuleLanguage.xsd](https://raw.githubusercontent.com/BUTR/Bannerlord.XmlSchemas/master/ModuleLanguage.xsd) - for the language translation file
* [ModuleLanguageData.xsd](https://raw.githubusercontent.com/BUTR/Bannerlord.XmlSchemas/master/ModuleLanguageData.xsd) - for the language translation descriptors
* [MCMExternalSettings.xsd](https://raw.githubusercontent.com/BUTR/Bannerlord.XmlSchemas/master/MCMExternalSettings.xsd) - for MCMv5 External Settings

## How to use
Just add the following attributes to the root node - `xmlns:xsi='http://www.w3.org/2001/XMLSchema-instance xsi:noNamespaceSchemaLocation="%URL%"`  
Example:
```xml
<ROOT xmlns:xsi='http://www.w3.org/2001/XMLSchema-instance'
      xsi:noNamespaceSchemaLocation="%URL%">
```
