---
title: OrgUnit.EmailReceiptProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailReceiptProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.EmailReceiptProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.emailreceiptprofileid(v=AX.60)
ms:contentKeyID: 62212254
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.EmailReceiptProfileId
dev_langs:
- CSharp
- C++
- VB
---

# EmailReceiptProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the receipt profile identifier used for emailing the receipt for this store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMAILRECEIPTPROFILEID")> _
<DataMemberAttribute> _
Public Property EmailReceiptProfileId As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.EmailReceiptProfileId

instance.EmailReceiptProfileId = value
```

``` csharp
[ColumnAttribute("EMAILRECEIPTPROFILEID")]
[DataMemberAttribute]
public string EmailReceiptProfileId { get; set; }
```

``` c++
[ColumnAttribute(L"EMAILRECEIPTPROFILEID")]
[DataMemberAttribute]
public:
property String^ EmailReceiptProfileId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

