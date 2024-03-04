# Documentos XML: Estructura y Validación

## Estructura de Documentos XML

### Declaración o Prólogo
```xml
<?xml version="1.0" encoding="UTF-8" ?>
```

La declaración define la versión de XML utilizada y la codificación de caracteres.

### Elementos
```xml
<elemento>Contenido</elemento>
```

Los elementos son bloques fundamentales que contienen datos o otros elementos.

### Atributos
```xml
<elemento atributo="valor">Contenido</elemento>
```

Los atributos proporcionan información adicional sobre los elementos.

### Comentarios
```xml
<!-- Este es un comentario en XML -->
```

Los comentarios son anotaciones que no afectan la interpretación del documento.

### Espacios de Nombres
```xml
<ns:elemento xmlns:ns="http://ejemplo.com">Contenido</ns:elemento>
```

Los espacios de nombres evitan conflictos de nombres entre elementos.

### Entidades
```xml
&lt;elemento&gt; Contenido &lt;/elemento&gt;
```

Las entidades representan caracteres especiales en XML, como `<` y `>`.

### CDATA
```xml
<![CDATA[ Contenido con caracteres especiales < > ]]> 
```

CDATA permite incluir contenido sin interpretación de entidades XML.

## Validación de Documentos

### DTD (Document Type Definition)

#### Entidades
```xml
<!ENTITY nombre "valor">
```

Definición de entidades para reutilización de valores.

#### Anotaciones
```xml
<!-- DTD: Declaración de Elemento -->
<!ELEMENT elemento (#PCDATA)>
```

Anotaciones describen la estructura y contenido permitido en el documento.

#### Elementos
```xml
<!ELEMENT raiz (elemento1, elemento2)>
```

Define la estructura y relación entre elementos.

#### Atributos
```xml
<!ATTLIST elemento atributo CDATA #IMPLIED>
```

Define atributos permitidos y sus valores.

### XML Schema

#### Definición
```xml
<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
    <!-- Definiciones aquí -->
</xs:schema>
```

Un esquema XML define la estructura y tipos de datos permitidos.

#### Estructura Básica
```xml
<xs:element name="elemento" type="xs:string"/>
```

Define un elemento simple con un tipo de dato string.

#### Elementos Locales y Globales
```xml
<xs:element name="local" type="xs:string"/>
<xs:element name="global" type="xs:string" />
```

Elementos locales y globales con tipos de datos string.

#### Elementos Simples
```xml
<xs:simpleType name="TipoSimple">
    <xs:restriction base="xs:string"/>
</xs:simpleType>
```

Definición de un tipo simple.

#### Elementos Complejos
```xml
<xs:complexType name="TipoComplejo">
    <xs:sequence>
        <xs:element name="subelemento" type="xs:string"/>
    </xs:sequence>
</xs:complexType>
```

Definición de un tipo complejo con una secuencia de elementos.

#### Subelementos
```xml
<xs:element name="padre">
    <xs:complexType>
        <xs:sequence>
            <xs:element name="hijo1" type="xs:string"/>
            <xs:element name="hijo2" type="xs:string"/>
        </xs:sequence>
    </xs:complexType>
</xs:element>
```

Definición de subelementos dentro de un elemento complejo.

#### Atributos
```xml
<xs:element name="elemento" >
    <xs:complexType>
        <xs:attribute name="atributo" type="xs:string"/>
    </xs:complexType>
</xs:element>
```

Definición de atributos para un elemento.

#### Restricciones
```xml
<xs:restriction base="xs:string">
    <xs:minLength value="5"/>
    <xs:maxLength value="10"/>
</xs:restriction>
```

Restricciones en tipos de datos.

#### Tipos de Datos
```xml
<xs:element name="numero" type="xs:integer"/>
```

Definición de un elemento con un tipo de dato entero.

#### Comentarios en XML Schema
```xml
<!-- Comentario en XML Schema -->
```

Los comentarios proporcionan información adicional en el esquema XML.
