---
title: GetStoresRequest.StoreNumbers Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StoreNumbers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest.StoreNumbers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getstoresrequest.storenumbers(v=AX.60)
ms:contentKeyID: 62207934
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest.StoreNumbers
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumbers Property

Gets or the collection of store numbers to search for.

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
Dim instance As GetStoresRequest
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

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[GetStoresRequest Class](getstoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

