---
title: IPosTransactionV1.FiscalDocumentId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: FiscalDocumentId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.FiscalDocumentId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ipostransactionv1.fiscaldocumentid(v=AX.60)
ms:contentKeyID: 47128266
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransactionV1.FiscalDocumentId
dev_langs:
- CSharp
- C++
- VB
---

# FiscalDocumentId Property

Gets or sets the fiscal document ID. Available for add-in use; limited to 80 characters.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property FiscalDocumentId As String
    Get
    Set
'Usage
Dim instance As IPosTransactionV1
Dim value As String

value = instance.FiscalDocumentId

instance.FiscalDocumentId = value
```

``` csharp
string FiscalDocumentId { get; set; }
```

``` c++
property String^ FiscalDocumentId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[IPosTransactionV1 Interface](ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

