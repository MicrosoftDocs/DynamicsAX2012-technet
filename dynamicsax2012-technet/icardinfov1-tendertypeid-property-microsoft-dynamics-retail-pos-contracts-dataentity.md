---
title: ICardInfoV1.TenderTypeId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.icardinfov1.tendertypeid(v=AX.60)
ms:contentKeyID: 47128215
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfoV1.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender type ID.

The ID of the tender type that the card is associated with.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TenderTypeId As String
    Get
    Set
'Usage
Dim instance As ICardInfoV1
Dim value As String

value = instance.TenderTypeId

instance.TenderTypeId = value
```

``` csharp
string TenderTypeId { get; set; }
```

``` c++
property String^ TenderTypeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)) value.  

## See Also

#### Reference

[ICardInfoV1 Interface](icardinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

