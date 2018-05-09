---
title: GetChannelTenderTypesResponse.ChannelTenderTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelTenderTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesResponse.ChannelTenderTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getchanneltendertypesresponse.channeltendertypes(v=AX.60)
ms:contentKeyID: 62209027
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesResponse.ChannelTenderTypes
dev_langs:
- CSharp
- C++
- VB
---

# ChannelTenderTypes Property

Gets the channel tender types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelTenderTypes As ReadOnlyCollection(Of TenderType)
    Get
    Private Set
'Usage
Dim instance As GetChannelTenderTypesResponse
Dim value As ReadOnlyCollection(Of TenderType)

value = instance.ChannelTenderTypes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TenderType> ChannelTenderTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TenderType^>^ ChannelTenderTypes {
    ReadOnlyCollection<TenderType^>^ get ();
    private: void set (ReadOnlyCollection<TenderType^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelTenderTypesResponse Class](getchanneltendertypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

