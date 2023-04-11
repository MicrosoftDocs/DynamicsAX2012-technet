---
title: CommerceListManager.GetCommerceList Method (String, String) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetCommerceList Method (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.GetCommerceList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.getcommercelist(v=AX.60)
ms:contentKeyID: 62213918
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceList Method (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a single commerce list by id.

Customer account number must also be provided to ensure that customers can only access their own commerce lists.

Because it retrieves an entire, single commerce list entity, this method is most applicable for use by the online channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetCommerceList ( _
    commerceListId As String, _
    customerId As String _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceListId As String
Dim customerId As String
Dim returnValue As CommerceList

returnValue = instance.GetCommerceList(commerceListId, _
    customerId)
```

``` csharp
public CommerceList GetCommerceList(
    string commerceListId,
    string customerId
)
```

``` c++
public:
CommerceList^ GetCommerceList(
    String^ commerceListId, 
    String^ customerId
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The commerce list or NULL if no matching commerce list was found.  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetCommerceList Overload](commercelistmanager-getcommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

