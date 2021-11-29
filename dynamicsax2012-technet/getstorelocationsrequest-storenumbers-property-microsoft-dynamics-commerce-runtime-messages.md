---
title: GetStoreLocationsRequest.StoreNumbers Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StoreNumbers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsRequest.StoreNumbers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsrequest.storenumbers(v=AX.60)
ms:contentKeyID: 62215067
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsRequest.StoreNumbers
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumbers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the store numbers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreNumbers As ICollection(Of String)
    Get
    Private Set
'Usage
Dim instance As GetStoreLocationsRequest
Dim value As ICollection(Of String)

value = instance.StoreNumbers
```

``` csharp
[DataMemberAttribute]
public ICollection<string> StoreNumbers { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<String^>^ StoreNumbers {
    ICollection<String^>^ get ();
    private: void set (ICollection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
The search area.  

## See Also

#### Reference

[GetStoreLocationsRequest Class](getstorelocationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

