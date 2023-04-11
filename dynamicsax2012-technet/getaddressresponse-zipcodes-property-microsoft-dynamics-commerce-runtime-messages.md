---
title: GetAddressResponse.ZipCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ZipCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.ZipCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.zipcodes(v=AX.60)
ms:contentKeyID: 62211909
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.ZipCodes
dev_langs:
- CSharp
- C++
- VB
---

# ZipCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of zipcodes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ZipCodes As ReadOnlyCollection(Of ZipCodeInfo)
    Get
    Private Set
'Usage
Dim instance As GetAddressResponse
Dim value As ReadOnlyCollection(Of ZipCodeInfo)

value = instance.ZipCodes
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ZipCodeInfo> ZipCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ZipCodeInfo^>^ ZipCodes {
    ReadOnlyCollection<ZipCodeInfo^>^ get ();
    private: void set (ReadOnlyCollection<ZipCodeInfo^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ZipCodeInfo](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

