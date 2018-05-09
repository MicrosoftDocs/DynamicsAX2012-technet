---
title: GetItemByIdRequest.ColumnSet Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ColumnSet Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ColumnSet
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitembyidrequest.columnset(v=AX.60)
ms:contentKeyID: 49844476
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdRequest.ColumnSet
dev_langs:
- CSharp
- C++
- VB
---

# ColumnSet Property

Gets or sets the column set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property ColumnSet As ColumnSet
    Get
    Set
'Usage
Dim instance As GetItemByIdRequest
Dim value As ColumnSet

value = instance.ColumnSet

instance.ColumnSet = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ColumnSet ColumnSet { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ColumnSet^ ColumnSet {
    ColumnSet^ get ();
    void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
The column set.  

## See Also

#### Reference

[GetItemByIdRequest Class](getitembyidrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

