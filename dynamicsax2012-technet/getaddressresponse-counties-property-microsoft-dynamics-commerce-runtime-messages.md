---
title: GetAddressResponse.Counties Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Counties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Counties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.counties(v=AX.60)
ms:contentKeyID: 62213287
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.Counties
dev_langs:
- CSharp
- C++
- VB
---

# Counties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of counties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Counties As ReadOnlyCollection(Of CountyInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of CountyInfo)

value = instance.Counties
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CountyInfo> Counties { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CountyInfo^>^ Counties {
    ReadOnlyCollection<CountyInfo^>^ get ();
    private: void set (ReadOnlyCollection<CountyInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CountyInfo](countyinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

