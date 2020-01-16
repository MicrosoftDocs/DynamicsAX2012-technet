---
title: GetProductPartsDataServiceRequest.IsOnline Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: IsOnline Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.IsOnline
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataservicerequest.isonline(v=AX.60)
ms:contentKeyID: 65319133
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.IsOnline
dev_langs:
- CSharp
- C++
- VB
---

# IsOnline Property

Gets a value indicating whether the current search is online or offline.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property IsOnline As Boolean
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceRequest
Dim value As Boolean

value = instance.IsOnline
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool IsOnline { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool IsOnline {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceRequest Class](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

