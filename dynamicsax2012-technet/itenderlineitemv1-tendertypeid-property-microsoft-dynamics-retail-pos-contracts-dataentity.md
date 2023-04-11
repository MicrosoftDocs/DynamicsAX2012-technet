---
title: ITenderLineItemV1.TenderTypeId Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: TenderTypeId Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.TenderTypeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.tendertypeid(v=AX.60)
ms:contentKeyID: 49852808
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.TenderTypeId
dev_langs:
- CSharp
- C++
- VB
---

# TenderTypeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The id for the tendertype

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property TenderTypeId As String
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
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
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

