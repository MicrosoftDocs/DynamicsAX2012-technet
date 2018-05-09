---
title: IEFTInfoV2.ProcessorTenderId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ProcessorTenderId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV2.ProcessorTenderId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfov2.processortenderid(v=AX.60)
ms:contentKeyID: 49850336
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfoV2.ProcessorTenderId
dev_langs:
- CSharp
- C++
- VB
---

# ProcessorTenderId Property

Indicates the processor provided Tender ID for processor specific tenders (typically reprsented as a Guid)Null or empty when does not apply

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ProcessorTenderId As String
    Get
    Set
'Usage
Dim instance As IEFTInfoV2
Dim value As String

value = instance.ProcessorTenderId

instance.ProcessorTenderId = value
```

``` csharp
string ProcessorTenderId { get; set; }
```

``` c++
property String^ ProcessorTenderId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IEFTInfoV2 Interface](ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

