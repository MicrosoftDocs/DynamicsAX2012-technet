---
title: ICustomerV1.SearchName Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SearchName Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.SearchName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv1.searchname(v=AX.60)
ms:contentKeyID: 47128769
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV1.SearchName
dev_langs:
- CSharp
- C++
- VB
---

# SearchName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer's search name.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property SearchName As String
    Get
    Set
'Usage
Dim instance As ICustomerV1
Dim value As String

value = instance.SearchName

instance.SearchName = value
```

``` csharp
string SearchName { get; set; }
```

``` c++
property String^ SearchName {
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

