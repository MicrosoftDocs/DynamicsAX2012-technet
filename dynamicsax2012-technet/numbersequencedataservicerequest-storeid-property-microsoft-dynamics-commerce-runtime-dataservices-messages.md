---
title: NumberSequenceDataServiceRequest.StoreId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: StoreId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.StoreId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.numbersequencedataservicerequest.storeid(v=AX.60)
ms:contentKeyID: 65315609
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.NumberSequenceDataServiceRequest.StoreId
dev_langs:
- CSharp
- C++
- VB
---

# StoreId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the store identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StoreId As String
    Get
    Private Set
'Usage
Dim instance As NumberSequenceDataServiceRequest
Dim value As String

value = instance.StoreId
```

``` csharp
[DataMemberAttribute]
public string StoreId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StoreId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[NumberSequenceDataServiceRequest Class](numbersequencedataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

