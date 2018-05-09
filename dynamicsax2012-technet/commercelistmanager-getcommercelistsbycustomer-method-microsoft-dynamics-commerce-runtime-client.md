---
title: CommerceListManager.GetCommerceListsByCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCommerceListsByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.GetCommerceListsByCustomer(System.String,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.getcommercelistsbycustomer(v=AX.60)
ms:contentKeyID: 62211840
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.GetCommerceListsByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetCommerceListsByCustomer Method

Gets all commerce lists associated with the specified customer account number.

Because it retrieves entire commerce list entities, this method is most applicable for use by the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCommerceListsByCustomer ( _
    customerId As String, _
    favoriteFilter As Boolean, _
    publicFilter As Boolean _
) As ReadOnlyCollection(Of CommerceList)
'Usage
Dim instance As CommerceListManager
Dim customerId As String
Dim favoriteFilter As Boolean
Dim publicFilter As Boolean
Dim returnValue As ReadOnlyCollection(Of CommerceList)

returnValue = instance.GetCommerceListsByCustomer(customerId, _
    favoriteFilter, publicFilter)
```

``` csharp
public ReadOnlyCollection<CommerceList> GetCommerceListsByCustomer(
    string customerId,
    bool favoriteFilter,
    bool publicFilter
)
```

``` c++
public:
ReadOnlyCollection<CommerceList^>^ GetCommerceListsByCustomer(
    String^ customerId, 
    bool favoriteFilter, 
    bool publicFilter
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - favoriteFilter  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - publicFilter  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
A collection of [CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

