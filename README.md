## Generating fatture pojos from xsd
The following items in maven pom.xml needs to change to generate with a different xsd
```xml
        <sources>src/main/resources/MessaggiFatturaTypes_v1.0.xsd</sources>
        <packageName>com.arzamed.fatture.xml.v1</packageName>
```

Then run 
```bash
mvn clean install
```

From :
https://github.com/VLKNKBKSZ/xsdToJavaPojo/tree/master