---
title: SearchStoreResponse.Stores Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Stores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreResponse.Stores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.searchstoreresponse.stores(v=AX.60)
ms:contentKeyID: 62209378
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreResponse.Stores
dev_langs:
- CSharp
- C++
- VB
---

# Stores Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Stores As ReadOnlyCollection(Of OrgUnit)
    Get
    Private Set
'Usage
Dim instance As SearchStoreResponse
Dim value As ReadOnlyCollection(Of OrgUnit)

value = instance.Stores
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<OrgUnit> Stores { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<OrgUnit^>^ Stores {
    ReadOnlyCollection<OrgUnit^>^ get ();
    private: void set (ReadOnlyCollection<OrgUnit^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[SearchStoreResponse Class](searchstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

