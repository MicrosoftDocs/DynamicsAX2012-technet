---
title: IInfoCodeLineItemV1.InputRequired Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InputRequired Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.inputrequired(v=AX.60)
ms:contentKeyID: 49852414
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputRequired
dev_langs:
- CSharp
- C++
- VB
---

# InputRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is the the input required or can it be skipped

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InputRequired As Boolean
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As Boolean

value = instance.InputRequired

instance.InputRequired = value
```

``` csharp
bool InputRequired { get; set; }
```

``` c++
property bool InputRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

