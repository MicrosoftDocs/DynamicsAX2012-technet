---
title: GetCommerceListServiceResponse.Clists Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Clists Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceResponse.Clists
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcommercelistserviceresponse.clists(v=AX.60)
ms:contentKeyID: 62211413
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceResponse.Clists
dev_langs:
- CSharp
- C++
- VB
---

# Clists Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of commerce lists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Clists As IEnumerable(Of CommerceList)
    Get
    Private Set
'Usage
Dim instance As GetCommerceListServiceResponse
Dim value As IEnumerable(Of CommerceList)

value = instance.Clists
```

``` csharp
[DataMemberAttribute]
public IEnumerable<CommerceList> Clists { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<CommerceList^>^ Clists {
    IEnumerable<CommerceList^>^ get ();
    private: void set (IEnumerable<CommerceList^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetCommerceListServiceResponse Class](getcommercelistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

