---
title: GetChannelTenderTypesDataRequest.CountingRequired Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CountingRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelTenderTypesDataRequest.CountingRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getchanneltendertypesdatarequest.countingrequired(v=AX.60)
ms:contentKeyID: 65322908
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelTenderTypesDataRequest.CountingRequired
dev_langs:
- CSharp
- C++
- VB
---

# CountingRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets counting required.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountingRequired As Nullable(Of Integer)
    Get
    Private Set
'Usage
Dim instance As GetChannelTenderTypesDataRequest
Dim value As Nullable(Of Integer)

value = instance.CountingRequired
```

``` csharp
[DataMemberAttribute]
public Nullable<int> CountingRequired { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<int> CountingRequired {
    Nullable<int> get ();
    private: void set (Nullable<int> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelTenderTypesDataRequest Class](getchanneltendertypesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

