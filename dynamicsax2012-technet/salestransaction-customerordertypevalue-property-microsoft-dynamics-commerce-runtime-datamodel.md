---
title: SalesTransaction.CustomerOrderTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerOrderTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.customerordertypevalue(v=AX.60)
ms:contentKeyID: 62214309
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.CustomerOrderTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer order type value representing the order type in the headquarters.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerOrderTypeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Integer

value = instance.CustomerOrderTypeValue

instance.CustomerOrderTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int CustomerOrderTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int CustomerOrderTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

