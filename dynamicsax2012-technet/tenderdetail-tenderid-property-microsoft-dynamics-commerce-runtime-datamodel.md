---
title: TenderDetail.TenderId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.TenderId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderdetail.tenderid(v=AX.60)
ms:contentKeyID: 62215071
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderDetail.TenderId
dev_langs:
- CSharp
- C++
- VB
---

# TenderId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tender id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEID")> _
<DataMemberAttribute> _
Public Property TenderId As String
    Get
    Set
'Usage
Dim instance As TenderDetail
Dim value As String

value = instance.TenderId

instance.TenderId = value
```

``` csharp
[ColumnAttribute("LINEID")]
[DataMemberAttribute]
public string TenderId { get; set; }
```

``` c++
[ColumnAttribute(L"LINEID")]
[DataMemberAttribute]
public:
property String^ TenderId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderDetail Class](tenderdetail-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

