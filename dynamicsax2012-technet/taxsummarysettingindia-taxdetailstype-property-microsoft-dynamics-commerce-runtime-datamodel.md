---
title: TaxSummarySettingIndia.TaxDetailsType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxDetailsType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxSummarySettingIndia.TaxDetailsType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxsummarysettingindia.taxdetailstype(v=AX.60)
ms:contentKeyID: 62209172
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxSummarySettingIndia.TaxDetailsType
dev_langs:
- CSharp
- C++
- VB
---

# TaxDetailsType Property

Gets the record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXDETAILSTYPE")> _
Public Property TaxDetailsType As ReceiptTaxDetailsTypeIndia
    Get
    Friend Set
'Usage
Dim instance As TaxSummarySettingIndia
Dim value As ReceiptTaxDetailsTypeIndia

value = instance.TaxDetailsType
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXDETAILSTYPE")]
public ReceiptTaxDetailsTypeIndia TaxDetailsType { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXDETAILSTYPE")]
public:
property ReceiptTaxDetailsTypeIndia TaxDetailsType {
    ReceiptTaxDetailsTypeIndia get ();
    internal: void set (ReceiptTaxDetailsTypeIndia value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTaxDetailsTypeIndia](receipttaxdetailstypeindia-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The record identifier.  

## See Also

#### Reference

[TaxSummarySettingIndia Class](taxsummarysettingindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

