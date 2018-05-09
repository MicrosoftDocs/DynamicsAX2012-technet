---
title: DeviceConfiguration.RequireAmountDeclaration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RequireAmountDeclaration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RequireAmountDeclaration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.requireamountdeclaration(v=AX.60)
ms:contentKeyID: 62211422
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.RequireAmountDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# RequireAmountDeclaration Property

Gets or sets a value indicating whether starting amount and tender declarations are required before closing a shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REQUIREAMOUNTDECLARATION")> _
<DataMemberAttribute> _
Public Property RequireAmountDeclaration As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.RequireAmountDeclaration

instance.RequireAmountDeclaration = value
```

``` csharp
[ColumnAttribute("REQUIREAMOUNTDECLARATION")]
[DataMemberAttribute]
public bool RequireAmountDeclaration { get; set; }
```

``` c++
[ColumnAttribute(L"REQUIREAMOUNTDECLARATION")]
[DataMemberAttribute]
public:
property bool RequireAmountDeclaration {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value true if starting amount and tender declarations are required; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

