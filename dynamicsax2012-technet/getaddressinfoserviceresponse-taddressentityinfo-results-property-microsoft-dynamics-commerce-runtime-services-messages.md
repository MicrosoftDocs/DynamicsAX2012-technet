---
title: GetAddressInfoServiceResponse(TAddressEntityInfo).Results Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Results Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1.Results
ms:mtpsurl: https://technet.microsoft.com/library/Dn696951(v=AX.60)
ms:contentKeyID: 62208592
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceResponse`1.Results
dev_langs:
- CSharp
- C++
- VB
---

# Results Property

Gets the collection of results.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Results As ReadOnlyCollection(Of TAddressEntityInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressInfoServiceResponse
Dim value As ReadOnlyCollection(Of TAddressEntityInfo)

value = instance.Results
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TAddressEntityInfo> Results { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TAddressEntityInfo>^ Results {
    ReadOnlyCollection<TAddressEntityInfo>^ get ();
    private: void set (ReadOnlyCollection<TAddressEntityInfo>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TAddressEntityInfo](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressInfoServiceResponse\<TAddressEntityInfo\> Class](getaddressinfoserviceresponse-taddressentityinfo-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

