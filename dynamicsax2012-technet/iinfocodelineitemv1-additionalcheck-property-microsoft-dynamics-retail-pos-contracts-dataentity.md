---
title: IInfoCodeLineItemV1.AdditionalCheck Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AdditionalCheck Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.AdditionalCheck
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iinfocodelineitemv1.additionalcheck(v=AX.60)
ms:contentKeyID: 49839162
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IInfoCodeLineItemV1.AdditionalCheck
dev_langs:
- CSharp
- C++
- VB
---

# AdditionalCheck Property

Can be any value. Only to be used in the Infocode Service

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AdditionalCheck As Integer
    Get
    Set
'Usage
Dim instance As IInfoCodeLineItemV1
Dim value As Integer

value = instance.AdditionalCheck

instance.AdditionalCheck = value
```

``` csharp
int AdditionalCheck { get; set; }
```

``` c++
property int AdditionalCheck {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[IInfoCodeLineItemV1 Interface](iinfocodelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

