---
title: ReceiptHeaderTaxInfoIndia.ServiceTaxNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServiceTaxNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ServiceTaxNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptheadertaxinfoindia.servicetaxnumber(v=AX.60)
ms:contentKeyID: 62204209
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptHeaderTaxInfoIndia.ServiceTaxNumber
dev_langs:
- CSharp
- C++
- VB
---

# ServiceTaxNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets STC number of Service tax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SERVICETAXNUMBER")> _
<DataMemberAttribute> _
Public Property ServiceTaxNumber As String
    Get
    Set
'Usage
Dim instance As ReceiptHeaderTaxInfoIndia
Dim value As String

value = instance.ServiceTaxNumber

instance.ServiceTaxNumber = value
```

``` csharp
[ColumnAttribute("SERVICETAXNUMBER")]
[DataMemberAttribute]
public string ServiceTaxNumber { get; set; }
```

``` c++
[ColumnAttribute(L"SERVICETAXNUMBER")]
[DataMemberAttribute]
public:
property String^ ServiceTaxNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The STC number.  

## See Also

#### Reference

[ReceiptHeaderTaxInfoIndia Class](receiptheadertaxinfoindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

