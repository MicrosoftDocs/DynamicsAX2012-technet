---
title: ISaleLineItemV4.ReturnLocationText Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: ReturnLocationText Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.ReturnLocationText
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv4.returnlocationtext(v=AX.60)
ms:contentKeyID: 62202330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV4.ReturnLocationText
dev_langs:
- CSharp
- C++
- VB
---

# ReturnLocationText Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets location text for printing

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property ReturnLocationText As String
    Get
    Set
'Usage
Dim instance As ISaleLineItemV4
Dim value As String

value = instance.ReturnLocationText

instance.ReturnLocationText = value
```

``` csharp
string ReturnLocationText { get; set; }
```

``` c++
property String^ ReturnLocationText {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ISaleLineItemV4 Interface](isalelineitemv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

