---
title: ReceiptHeaderTaxInfoIndia.ExciseTaxNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExciseTaxNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ExciseTaxNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptheadertaxinfoindia.excisetaxnumber(v=AX.60)
ms:contentKeyID: 62213175
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ExciseTaxNumber
dev_langs:
- CSharp
- C++
- VB
---

# ExciseTaxNumber Property

Gets or sets ECC number of Excise tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EXCISETAXNUMBER")> _
<DataMemberAttribute> _
Public Property ExciseTaxNumber As String
    Get
    Set
'Usage
Dim instance As ReceiptHeaderTaxInfoIndia
Dim value As String

value = instance.ExciseTaxNumber

instance.ExciseTaxNumber = value
```

``` csharp
[ColumnAttribute("EXCISETAXNUMBER")]
[DataMemberAttribute]
public string ExciseTaxNumber { get; set; }
```

``` c++
[ColumnAttribute(L"EXCISETAXNUMBER")]
[DataMemberAttribute]
public:
property String^ ExciseTaxNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The ECC number.  

## See Also

#### Reference

[ReceiptHeaderTaxInfoIndia Class](receiptheadertaxinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

