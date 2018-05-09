---
title: GetReceiptRequest.QueryBySalesId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryBySalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.QueryBySalesId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getreceiptrequest.querybysalesid(v=AX.60)
ms:contentKeyID: 65321872
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetReceiptRequest.QueryBySalesId
dev_langs:
- CSharp
- C++
- VB
---

# QueryBySalesId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QueryBySalesId As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReceiptRequest
Dim value As Boolean

value = instance.QueryBySalesId
```

``` csharp
[DataMemberAttribute]
public bool QueryBySalesId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool QueryBySalesId {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReceiptRequest Class](getreceiptrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

