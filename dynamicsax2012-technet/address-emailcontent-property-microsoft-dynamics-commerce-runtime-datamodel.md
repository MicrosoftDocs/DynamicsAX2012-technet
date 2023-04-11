---
title: Address.EmailContent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailContent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailContent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.emailcontent(v=AX.60)
ms:contentKeyID: 62207418
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.EmailContent
dev_langs:
- CSharp
- C++
- VB
---

# EmailContent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the EmailContent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EMAILCONTENT")> _
Public Property EmailContent As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.EmailContent

instance.EmailContent = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EMAILCONTENT")]
public string EmailContent { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EMAILCONTENT")]
public:
property String^ EmailContent {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

