---
title: TaxLineIndia.StoreId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.StoreId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.storeid(v=AX.60)
ms:contentKeyID: 62208605
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.StoreId
dev_langs:
- CSharp
- C++
- VB
---

# StoreId Property

Gets or sets retail store ID.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STOREID")> _
<DataMemberAttribute> _
Public Property StoreId As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.StoreId

instance.StoreId = value
```

``` csharp
[ColumnAttribute("STOREID")]
[DataMemberAttribute]
public string StoreId { get; set; }
```

``` c++
[ColumnAttribute(L"STOREID")]
[DataMemberAttribute]
public:
property String^ StoreId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

