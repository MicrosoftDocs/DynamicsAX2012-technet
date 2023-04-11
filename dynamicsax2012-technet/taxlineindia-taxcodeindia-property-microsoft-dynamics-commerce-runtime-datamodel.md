---
title: TaxLineIndia.TaxCodeIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCodeIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxCodeIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.taxcodeindia(v=AX.60)
ms:contentKeyID: 62207460
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.TaxCodeIndia
dev_langs:
- CSharp
- C++
- VB
---

# TaxCodeIndia Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets tax code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXCODE")> _
<DataMemberAttribute> _
Public Property TaxCodeIndia As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.TaxCodeIndia

instance.TaxCodeIndia = value
```

``` csharp
[ColumnAttribute("TAXCODE")]
[DataMemberAttribute]
public string TaxCodeIndia { get; set; }
```

``` c++
[ColumnAttribute(L"TAXCODE")]
[DataMemberAttribute]
public:
property String^ TaxCodeIndia {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

