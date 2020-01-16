---
title: ReasonCodeSettings.Item Property (ReasonCodeSourceType) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Item Property (ReasonCodeSourceType)
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings.Item(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodesettings.item(v=AX.60)
ms:contentKeyID: 62208849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Item Property (ReasonCodeSourceType)

Gets the reason code id [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) associated with the specified key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Item ( _
    reasonCodeSourceType As ReasonCodeSourceType _
) As String
    Get
'Usage
Dim instance As ReasonCodeSettings
Dim reasonCodeSourceType As ReasonCodeSourceType
Dim value As String

value = instance.Item(reasonCodeSourceType)
```

``` csharp
public string this[
    ReasonCodeSourceType reasonCodeSourceType
] { get; }
```

``` c++
public:
property String^ Item[ReasonCodeSourceType reasonCodeSourceType] {
    String^ get (ReasonCodeSourceType reasonCodeSourceType);
}
```

#### Parameters

  - reasonCodeSourceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The reason code id. String.Empty if not specified.  

## See Also

#### Reference

[ReasonCodeSettings Class](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Item Overload](reasoncodesettings-item-property-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

