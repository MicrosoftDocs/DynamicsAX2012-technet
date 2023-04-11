---
title: ReasonCodeSettings.Item Property (String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Item Property (String)
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.Item(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodesettings.item(v=AX.60)
ms:contentKeyID: 65321836
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Item Property (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Item ( _
    key As String _
) As Object
    Get
'Usage
Dim instance As ReasonCodeSettings
Dim key As String
Dim value As Object

value = instance.Item(key)
```

``` csharp
public Object this[
    string key
] { get; }
```

``` c++
public:
property Object^ Item[String^ key] {
    Object^ get (String^ key);
}
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Property Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[ReasonCodeSettings Class](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Item Overload](reasoncodesettings-item-property-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

