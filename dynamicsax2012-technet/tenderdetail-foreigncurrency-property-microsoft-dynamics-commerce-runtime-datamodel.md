---
title: TenderDetail.ForeignCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ForeignCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.ForeignCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.foreigncurrency(v=AX.60)
ms:contentKeyID: 65322398
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.ForeignCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ForeignCurrency Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CURRENCY")> _
<DataMemberAttribute> _
Public Property ForeignCurrency As String
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As String

value = instance.ForeignCurrency

instance.ForeignCurrency = value
```

``` csharp
[ColumnAttribute("CURRENCY")]
[DataMemberAttribute]
public string ForeignCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"CURRENCY")]
[DataMemberAttribute]
public:
property String^ ForeignCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

