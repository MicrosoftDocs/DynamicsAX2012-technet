---
title: IPosTransactionV1.HeadOfficeCurrencyCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: HeadOfficeCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.HeadOfficeCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.headofficecurrencycode(v=AX.60)
ms:contentKeyID: 47128784
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.HeadOfficeCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# HeadOfficeCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets head office currency code, for example, GBP, USD, or EUR .

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property HeadOfficeCurrencyCode As String
    Get
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.HeadOfficeCurrencyCode
```

``` csharp
string HeadOfficeCurrencyCode { get; }
```

``` c++
property String^ HeadOfficeCurrencyCode {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

