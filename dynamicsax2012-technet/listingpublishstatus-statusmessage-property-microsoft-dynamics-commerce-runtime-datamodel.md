---
title: ListingPublishStatus.StatusMessage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StatusMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.StatusMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.listingpublishstatus.statusmessage(v=AX.60)
ms:contentKeyID: 49848184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ListingPublishStatus.StatusMessage
dev_langs:
- CSharp
- C++
- VB
---

# StatusMessage Property

Gets or sets the status message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STATUSMESSAGE")> _
Public Property StatusMessage As String
    Get
    Set
'Usage
Dim instance As ListingPublishStatus
Dim value As String

value = instance.StatusMessage

instance.StatusMessage = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STATUSMESSAGE")]
public string StatusMessage { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STATUSMESSAGE")]
public:
property String^ StatusMessage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ListingPublishStatus Class](listingpublishstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

