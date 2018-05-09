---
title: RequiredProductProperties.Items Property  ()
TOCTitle: Items Property
ms:assetid: P:RequiredProductProperties.Items
ms:mtpsurl: https://technet.microsoft.com/en-us/library/requiredproductproperties.items(v=AX.60)
ms:contentKeyID: 65318590
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- RequiredProductProperties.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property

**Namespace:**  [(Default Namespace)](default-namespace-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property Items As RequiredProductPropertiesProperty()
    Get
    Set
'Usage
Dim instance As RequiredProductProperties
Dim value As RequiredProductPropertiesProperty()

value = instance.Items

instance.Items = value
```

``` csharp
public RequiredProductPropertiesProperty[] Items { get; set; }
```

``` c++
public:
property array<RequiredProductPropertiesProperty^>^ Items {
    array<RequiredProductPropertiesProperty^>^ get ();
    void set (array<RequiredProductPropertiesProperty^>^ value);
}
```

#### Property Value

Type: [(Default Namespace).RequiredProductPropertiesProperty](requiredproductpropertiesproperty-class.md)\[\]  

## See Also

#### Reference

[RequiredProductProperties Class](requiredproductproperties-class.md)

[(Default Namespace) Namespace](default-namespace-namespace.md)

