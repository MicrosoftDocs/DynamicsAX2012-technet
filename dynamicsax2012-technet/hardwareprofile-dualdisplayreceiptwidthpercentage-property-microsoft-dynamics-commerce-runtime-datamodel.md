---
title: HardwareProfile.DualDisplayReceiptWidthPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DualDisplayReceiptWidthPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayReceiptWidthPercentage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.dualdisplayreceiptwidthpercentage(v=AX.60)
ms:contentKeyID: 62210634
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayReceiptWidthPercentage
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplayReceiptWidthPercentage Property

Gets or sets the dual display receipt width percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DUALDISPLAYRECEIPTPERCENTAGE")> _
Public Property DualDisplayReceiptWidthPercentage As Decimal
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As Decimal

value = instance.DualDisplayReceiptWidthPercentage

instance.DualDisplayReceiptWidthPercentage = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DUALDISPLAYRECEIPTPERCENTAGE")]
public decimal DualDisplayReceiptWidthPercentage { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DUALDISPLAYRECEIPTPERCENTAGE")]
public:
property Decimal DualDisplayReceiptWidthPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The receipt width percentage.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

