---
title: PickingList.TotalReceived Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TotalReceived Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.TotalReceived
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglist.totalreceived(v=AX.60)
ms:contentKeyID: 62208070
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList.TotalReceived
dev_langs:
- CSharp
- C++
- VB
---

# TotalReceived Property

Gets or sets the total items received.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TotalReceived As Decimal
    Get
    Set
'Usage
Dim instance As PickingList
Dim value As Decimal

value = instance.TotalReceived

instance.TotalReceived = value
```

``` csharp
[DataMemberAttribute]
public decimal TotalReceived { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TotalReceived {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PickingList Class](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

