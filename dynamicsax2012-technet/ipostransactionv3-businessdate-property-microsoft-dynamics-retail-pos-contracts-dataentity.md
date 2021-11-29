---
title: IPosTransactionV3.BusinessDate Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: BusinessDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV3.BusinessDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv3.businessdate(v=AX.60)
ms:contentKeyID: 62202025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV3.BusinessDate
dev_langs:
- CSharp
- C++
- VB
---

# BusinessDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the business date.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property BusinessDate As DateTime
    Get
    Set
'Usage
Dim instance As IPosTransactionV3
Dim value As DateTime

value = instance.BusinessDate

instance.BusinessDate = value
```

``` csharp
DateTime BusinessDate { get; set; }
```

``` c++
property DateTime BusinessDate {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[IPosTransactionV3 Interface](ipostransactionv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

