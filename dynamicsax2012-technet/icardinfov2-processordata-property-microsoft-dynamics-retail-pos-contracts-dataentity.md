---
title: ICardInfoV2.ProcessorData Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ProcessorData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.ProcessorData
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov2.processordata(v=AX.60)
ms:contentKeyID: 49822261
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV2.ProcessorData
dev_langs:
- CSharp
- C++
- VB
---

# ProcessorData Property

Gets or sets the processor specific data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ProcessorData As IDictionary(Of String, Object)
    Get
    Set
'Usage
Dim instance As ICardInfoV2
Dim value As IDictionary(Of String, Object)

value = instance.ProcessorData

instance.ProcessorData = value
```

``` csharp
IDictionary<string, Object> ProcessorData { get; set; }
```

``` c++
property IDictionary<String^, Object^>^ ProcessorData {
    IDictionary<String^, Object^>^ get ();
    void set (IDictionary<String^, Object^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\>  
The processor data.  

## See Also

#### Reference

[ICardInfoV2 Interface](icardinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

