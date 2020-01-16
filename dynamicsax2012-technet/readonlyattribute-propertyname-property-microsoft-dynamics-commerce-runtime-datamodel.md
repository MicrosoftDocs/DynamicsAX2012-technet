---
title: ReadOnlyAttribute.PropertyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PropertyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.PropertyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readonlyattribute.propertyname(v=AX.60)
ms:contentKeyID: 62210487
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute.PropertyName
dev_langs:
- CSharp
- C++
- VB
---

# PropertyName Property

Gets the readonly property name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property PropertyName As String
    Get
    Private Set
'Usage
Dim instance As ReadOnlyAttribute
Dim value As String

value = instance.PropertyName
```

``` csharp
public string PropertyName { get; private set; }
```

``` c++
public:
property String^ PropertyName {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReadOnlyAttribute Class](readonlyattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

