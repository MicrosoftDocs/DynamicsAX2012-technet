---
title: TenderLineBase.TenderLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.TenderLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.tenderlineid(v=AX.60)
ms:contentKeyID: 62213644
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.TenderLineId
dev_langs:
- CSharp
- C++
- VB
---

# TenderLineId Property

Gets or sets the tender line identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LINEID")> _
<DataMemberAttribute> _
Public Property TenderLineId As String
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As String

value = instance.TenderLineId

instance.TenderLineId = value
```

``` csharp
[ColumnAttribute("LINEID")]
[DataMemberAttribute]
public string TenderLineId { get; set; }
```

``` c++
[ColumnAttribute(L"LINEID")]
[DataMemberAttribute]
public:
property String^ TenderLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

