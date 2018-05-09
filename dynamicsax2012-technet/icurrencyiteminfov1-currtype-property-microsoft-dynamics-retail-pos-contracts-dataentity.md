---
title: ICurrencyItemInfoV1.CurrType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CurrType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfoV1.CurrType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icurrencyiteminfov1.currtype(v=AX.60)
ms:contentKeyID: 47129063
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICurrencyItemInfoV1.CurrType
dev_langs:
- CSharp
- C++
- VB
---

# CurrType Property

Gets or sets the type of the currency (banknotes or coins).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CurrType As CurrType
    Get
    Set
'Usage
Dim instance As ICurrencyItemInfoV1
Dim value As CurrType

value = instance.CurrType

instance.CurrType = value
```

``` csharp
CurrType CurrType { get; set; }
```

``` c++
property CurrType CurrType {
    CurrType get ();
    void set (CurrType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CurrType](currtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.Services.CurrType](currtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md) value.  

## See Also

#### Reference

[ICurrencyItemInfoV1 Interface](icurrencyiteminfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

