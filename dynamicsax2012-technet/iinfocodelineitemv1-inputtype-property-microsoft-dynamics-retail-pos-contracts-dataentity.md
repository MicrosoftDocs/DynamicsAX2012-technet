---
title: IInfoCodeLineItemV1.InputType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InputType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.inputtype(v=AX.60)
ms:contentKeyID: 49821292
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputType
dev_langs:
- CSharp
- C++
- VB
---

# InputType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The infocode input type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InputType As InfoCodeInputType
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As InfoCodeInputType

value = instance.InputType

instance.InputType = value
```

``` csharp
InfoCodeInputType InputType { get; set; }
```

``` c++
property InfoCodeInputType InputType {
    InfoCodeInputType get ();
    void set (InfoCodeInputType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputType](infocodeinputtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [InfoCodeInputType](infocodeinputtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

