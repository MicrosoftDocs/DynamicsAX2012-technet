---
title: IInfoCodeLineItemV1.InputRequiredType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: InputRequiredType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputRequiredType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.inputrequiredtype(v=AX.60)
ms:contentKeyID: 49855251
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.InputRequiredType
dev_langs:
- CSharp
- C++
- VB
---

# InputRequiredType Property

When is the input required

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property InputRequiredType As InfoCodeInputRequiredType
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As InfoCodeInputRequiredType

value = instance.InputRequiredType

instance.InputRequiredType = value
```

``` csharp
InfoCodeInputRequiredType InputRequiredType { get; set; }
```

``` c++
property InfoCodeInputRequiredType InputRequiredType {
    InfoCodeInputRequiredType get ();
    void set (InfoCodeInputRequiredType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeInputRequiredType](infocodeinputrequiredtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [InfoCodeInputRequiredType](infocodeinputrequiredtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

