---
title: TaxParameters.VATIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VATIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.VATIndia
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxparameters.vatindia(v=AX.60)
ms:contentKeyID: 62213785
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.VATIndia
dev_langs:
- CSharp
- C++
- VB
---

# VATIndia Property

Gets or sets a value indicating whether VAT parameter is enable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VAT_IN")> _
<DataMemberAttribute> _
Public Property VATIndia As Boolean
    Get
    Set
'Usage
Dim instance As TaxParameters
Dim value As Boolean

value = instance.VATIndia

instance.VATIndia = value
```

``` csharp
[ColumnAttribute("VAT_IN")]
[DataMemberAttribute]
public bool VATIndia { get; set; }
```

``` c++
[ColumnAttribute(L"VAT_IN")]
[DataMemberAttribute]
public:
property bool VATIndia {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
The value.  

## See Also

#### Reference

[TaxParameters Class](taxparameters-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

