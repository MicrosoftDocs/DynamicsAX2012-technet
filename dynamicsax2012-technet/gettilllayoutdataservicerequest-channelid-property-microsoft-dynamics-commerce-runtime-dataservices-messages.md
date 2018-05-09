---
title: GetTillLayoutDataServiceRequest.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.ChannelId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.gettilllayoutdataservicerequest.channelid(v=AX.60)
ms:contentKeyID: 65315537
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetTillLayoutDataServiceRequest.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property

Gets the channel identifier (surrogate key) if specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelId As Nullable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetTillLayoutDataServiceRequest
Dim value As Nullable(Of Long)

value = instance.ChannelId
```

``` csharp
[DataMemberAttribute]
public Nullable<long> ChannelId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> ChannelId {
    Nullable<long long> get ();
    private: void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[GetTillLayoutDataServiceRequest Class](gettilllayoutdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

