---
title: ICustomerV1.CustomerId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CustomerId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.customerid(v=AX.60)
ms:contentKeyID: 47128787
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer's account number.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CustomerId As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
string CustomerId { get; set; }
```

``` c++
property String^ CustomerId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICustomerV1 Interface](icustomerv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

