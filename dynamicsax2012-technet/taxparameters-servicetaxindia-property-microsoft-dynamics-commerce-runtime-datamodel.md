---
title: TaxParameters.ServiceTaxIndia Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ServiceTaxIndia Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.ServiceTaxIndia
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxparameters.servicetaxindia(v=AX.60)
ms:contentKeyID: 62212043
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxParameters.ServiceTaxIndia
dev_langs:
- CSharp
- C++
- VB
---

# ServiceTaxIndia Property

Gets or sets a value indicating whether service tax parameter is enable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SERVICETAX_IN")> _
<DataMemberAttribute> _
Public Property ServiceTaxIndia As Boolean
    Get
    Set
'Usage
Dim instance As TaxParameters
Dim value As Boolean

value = instance.ServiceTaxIndia

instance.ServiceTaxIndia = value
```

``` csharp
[ColumnAttribute("SERVICETAX_IN")]
[DataMemberAttribute]
public bool ServiceTaxIndia { get; set; }
```

``` c++
[ColumnAttribute(L"SERVICETAX_IN")]
[DataMemberAttribute]
public:
property bool ServiceTaxIndia {
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

