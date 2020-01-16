---
title: GetButtonGridsByIdsServiceRequest.ButtonGridIds Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ButtonGridIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceRequest.ButtonGridIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridsbyidsservicerequest.buttongridids(v=AX.60)
ms:contentKeyID: 62211323
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsByIdsServiceRequest.ButtonGridIds
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridIds Property

Gets the buttongrid Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property ButtonGridIds As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As GetButtonGridsByIdsServiceRequest
Dim value As IEnumerable(Of String)

value = instance.ButtonGridIds
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public IEnumerable<string> ButtonGridIds { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
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

[GetButtonGridsByIdsServiceRequest Class](getbuttongridsbyidsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

