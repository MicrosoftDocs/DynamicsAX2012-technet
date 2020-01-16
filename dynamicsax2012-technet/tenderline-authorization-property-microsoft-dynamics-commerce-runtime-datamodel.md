---
title: TenderLine.Authorization Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Authorization Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.Authorization
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderline.authorization(v=AX.60)
ms:contentKeyID: 49832741
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLine.Authorization
dev_langs:
- CSharp
- C++
- VB
---

# Authorization Property

Gets or sets the authorization.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PAYMENTAUTHORIZATION")> _
<ReadOnlyAttribute("PAYMENTAUTHORIZATION")> _
Public Property Authorization As String
    Get
    Set
'Usage
Dim instance As TenderLine
Dim value As String

value = instance.Authorization

instance.Authorization = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PAYMENTAUTHORIZATION")]
[ReadOnlyAttribute("PAYMENTAUTHORIZATION")]
public string Authorization { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PAYMENTAUTHORIZATION")]
[ReadOnlyAttribute(L"PAYMENTAUTHORIZATION")]
public:
property String^ Authorization {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The authorization.  

## See Also

#### Reference

[TenderLine Class](tenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

