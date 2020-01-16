---
title: ReceiptHeaderTaxInfoIndia.ValueAddedTaxTINNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValueAddedTaxTINNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ValueAddedTaxTINNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptheadertaxinfoindia.valueaddedtaxtinnumber(v=AX.60)
ms:contentKeyID: 62208335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ValueAddedTaxTINNumber
dev_langs:
- CSharp
- C++
- VB
---

# ValueAddedTaxTINNumber Property

Gets or sets the VAT TIN number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALUEADDEDTAXTINNUMBER")> _
<DataMemberAttribute> _
Public Property ValueAddedTaxTINNumber As String
    Get
    Set
'Usage
Dim instance As ReceiptHeaderTaxInfoIndia
Dim value As String

value = instance.ValueAddedTaxTINNumber

instance.ValueAddedTaxTINNumber = value
```

``` csharp
[ColumnAttribute("VALUEADDEDTAXTINNUMBER")]
[DataMemberAttribute]
public string ValueAddedTaxTINNumber { get; set; }
```

``` c++
[ColumnAttribute(L"VALUEADDEDTAXTINNUMBER")]
[DataMemberAttribute]
public:
property String^ ValueAddedTaxTINNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
VAT TIN number.  

## See Also

#### Reference

[ReceiptHeaderTaxInfoIndia Class](receiptheadertaxinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

