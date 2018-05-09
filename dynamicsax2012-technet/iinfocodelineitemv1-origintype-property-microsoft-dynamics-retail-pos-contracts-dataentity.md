---
title: IInfoCodeLineItemV1.OriginType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: OriginType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.OriginType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.origintype(v=AX.60)
ms:contentKeyID: 49825252
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.OriginType
dev_langs:
- CSharp
- C++
- VB
---

# OriginType Property

Where does the infocode originate from (sales, payment, etc)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property OriginType As InfoCodeType
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As InfoCodeType

value = instance.OriginType

instance.OriginType = value
```

``` csharp
InfoCodeType OriginType { get; set; }
```

``` c++
property InfoCodeType OriginType {
    InfoCodeType get ();
    void set (InfoCodeType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.InfoCodeType](infocodetype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [InfoCodeType](infocodetype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

