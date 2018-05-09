---
title: CommerceListManager.AddToCommerceList Method (String, IEnumerable(CommerceListLine)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddToCommerceList Method (String, IEnumerable(CommerceListLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CommerceListManager.AddToCommerceList(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.commercelistmanager.addtocommercelist(v=AX.60)
ms:contentKeyID: 65320497
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddToCommerceList Method (String, IEnumerable(CommerceListLine))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddToCommerceList ( _
    commerceListId As String, _
    commerceListLines As IEnumerable(Of CommerceListLine) _
) As CommerceList
'Usage
Dim instance As CommerceListManager
Dim commerceListId As String
Dim commerceListLines As IEnumerable(Of CommerceListLine)
Dim returnValue As CommerceList

returnValue = instance.AddToCommerceList(commerceListId, _
    commerceListLines)
```

``` csharp
public CommerceList AddToCommerceList(
    string commerceListId,
    IEnumerable<CommerceListLine> commerceListLines
)
```

``` c++
public:
CommerceList^ AddToCommerceList(
    String^ commerceListId, 
    IEnumerable<CommerceListLine^>^ commerceListLines
)
```

#### Parameters

  - commerceListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - commerceListLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CommerceListLine](commercelistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceList](commercelist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceListManager Class](commercelistmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[AddToCommerceList Overload](commercelistmanager-addtocommercelist-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

