---
title: GetButtonGridsByIdsRequest.ButtonGridIds Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ButtonGridIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest.ButtonGridIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsbyidsrequest.buttongridids(v=AX.60)
ms:contentKeyID: 62213322
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsRequest.ButtonGridIds
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifiers of the buttongrids to retrieve.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ButtonGridIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsByIdsRequest
Dim value As IEnumerable(Of String)

value = instance.ButtonGridIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<string> ButtonGridIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<String^>^ ButtonGridIds {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridsByIdsRequest Class](getbuttongridsbyidsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

