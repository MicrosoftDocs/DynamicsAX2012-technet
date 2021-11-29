---
title: ICustomerDiscountItemV1.CustomerDiscountGroup Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CustomerDiscountGroup Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItemV1.CustomerDiscountGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerdiscountitemv1.customerdiscountgroup(v=AX.60)
ms:contentKeyID: 49829188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerDiscountItemV1.CustomerDiscountGroup
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscountGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The discount group of the customer

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CustomerDiscountGroup As String
    Get
    Set
'Usage
Dim instance As ICustomerDiscountItemV1
Dim value As String

value = instance.CustomerDiscountGroup

instance.CustomerDiscountGroup = value
```

``` csharp
string CustomerDiscountGroup { get; set; }
```

``` c++
property String^ CustomerDiscountGroup {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ICustomerDiscountItemV1 Interface](icustomerdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

