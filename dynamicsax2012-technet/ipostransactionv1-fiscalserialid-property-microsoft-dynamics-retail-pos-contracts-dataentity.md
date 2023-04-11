---
title: IPosTransactionV1.FiscalSerialId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: FiscalSerialId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.FiscalSerialId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.fiscalserialid(v=AX.60)
ms:contentKeyID: 47128219
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.FiscalSerialId
dev_langs:
- CSharp
- C++
- VB
---

# FiscalSerialId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the fiscal serial ID. Available for add-in use; limited to 80 characters

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property FiscalSerialId As String
    Get
    Set
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.FiscalSerialId

instance.FiscalSerialId = value
```

``` csharp
string FiscalSerialId { get; set; }
```

``` c++
property String^ FiscalSerialId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

