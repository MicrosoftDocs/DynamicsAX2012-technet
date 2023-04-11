---
title: TenderType.TakenToSafe Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TakenToSafe Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.TakenToSafe
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.takentosafe(v=AX.60)
ms:contentKeyID: 62209761
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.TakenToSafe
dev_langs:
- CSharp
- C++
- VB
---

# TakenToSafe Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the taken to safe value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAKENTOSAFE")> _
<DataMemberAttribute> _
Public Property TakenToSafe As Integer
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Integer

value = instance.TakenToSafe

instance.TakenToSafe = value
```

``` csharp
[ColumnAttribute("TAKENTOSAFE")]
[DataMemberAttribute]
public int TakenToSafe { get; set; }
```

``` c++
[ColumnAttribute(L"TAKENTOSAFE")]
[DataMemberAttribute]
public:
property int TakenToSafe {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

