---
title: ReceiptProfile.ProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptprofile.profileid(v=AX.60)
ms:contentKeyID: 62209128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ProfileId
dev_langs:
- CSharp
- C++
- VB
---

# ProfileId Property

Gets or sets the profileId of a receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PROFILEID")> _
<DataMemberAttribute> _
Public Property ProfileId As String
    Get
    Set
'Usage
Dim instance As ReceiptProfile
Dim value As String

value = instance.ProfileId

instance.ProfileId = value
```

``` csharp
[ColumnAttribute("PROFILEID")]
[DataMemberAttribute]
public string ProfileId { get; set; }
```

``` c++
[ColumnAttribute(L"PROFILEID")]
[DataMemberAttribute]
public:
property String^ ProfileId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptProfile Class](receiptprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

