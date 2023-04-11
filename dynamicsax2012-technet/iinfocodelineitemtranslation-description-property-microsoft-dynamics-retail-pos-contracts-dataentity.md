---
title: IInfocodeLineItemTranslation.Description Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemtranslation.description(v=AX.60)
ms:contentKeyID: 62202036
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfocodeLineItemTranslation.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

A description of the line item

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Description As String
    Get
    Set
'Usage
Dim instance As IInfocodeLineItemTranslation
Dim value As String

value = instance.Description

instance.Description = value
```

``` csharp
string Description { get; set; }
```

``` c++
property String^ Description {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[IInfocodeLineItemTranslation Interface](iinfocodelineitemtranslation-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

