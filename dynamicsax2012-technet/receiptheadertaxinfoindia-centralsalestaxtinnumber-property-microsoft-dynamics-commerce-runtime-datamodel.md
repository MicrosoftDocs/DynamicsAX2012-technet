---
title: ReceiptHeaderTaxInfoIndia.CentralSalesTaxTINNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CentralSalesTaxTINNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.CentralSalesTaxTINNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptheadertaxinfoindia.centralsalestaxtinnumber(v=AX.60)
ms:contentKeyID: 62209411
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.CentralSalesTaxTINNumber
dev_langs:
- CSharp
- C++
- VB
---

# CentralSalesTaxTINNumber Property

Gets or sets CST TIN number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CENTRALSALESTAXTINNUMBER")> _
<DataMemberAttribute> _
Public Property CentralSalesTaxTINNumber As String
    Get
    Set
'Usage
Dim instance As ReceiptHeaderTaxInfoIndia
Dim value As String

value = instance.CentralSalesTaxTINNumber

instance.CentralSalesTaxTINNumber = value
```

``` csharp
[ColumnAttribute("CENTRALSALESTAXTINNUMBER")]
[DataMemberAttribute]
public string CentralSalesTaxTINNumber { get; set; }
```

``` c++
[ColumnAttribute(L"CENTRALSALESTAXTINNUMBER")]
[DataMemberAttribute]
public:
property String^ CentralSalesTaxTINNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The CST TIN number.  

## See Also

#### Reference

[ReceiptHeaderTaxInfoIndia Class](receiptheadertaxinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

