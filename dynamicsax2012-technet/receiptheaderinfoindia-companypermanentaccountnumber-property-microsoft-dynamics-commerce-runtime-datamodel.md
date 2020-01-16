---
title: ReceiptHeaderInfoIndia.CompanyPermanentAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyPermanentAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderInfoIndia.CompanyPermanentAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptheaderinfoindia.companypermanentaccountnumber(v=AX.60)
ms:contentKeyID: 62210301
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderInfoIndia.CompanyPermanentAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# CompanyPermanentAccountNumber Property

Gets or sets the Permanent Account Number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COMPANYPERMANENTACCOUNTNUMBER")> _
Public Property CompanyPermanentAccountNumber As String
    Get
    Set
'Usage
Dim instance As ReceiptHeaderInfoIndia
Dim value As String

value = instance.CompanyPermanentAccountNumber

instance.CompanyPermanentAccountNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COMPANYPERMANENTACCOUNTNUMBER")]
public string CompanyPermanentAccountNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COMPANYPERMANENTACCOUNTNUMBER")]
public:
property String^ CompanyPermanentAccountNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptHeaderInfoIndia Class](receiptheaderinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

