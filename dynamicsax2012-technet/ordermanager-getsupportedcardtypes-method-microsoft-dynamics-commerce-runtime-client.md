---
title: OrderManager.GetSupportedCardTypes Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetSupportedCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetSupportedCardTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getsupportedcardtypes(v=AX.60)
ms:contentKeyID: 49849384
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetSupportedCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetSupportedCardTypes Method

Get a collection of support card types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetSupportedCardTypes As ReadOnlyCollection(Of String)
'Usage
Dim instance As OrderManager
Dim returnValue As ReadOnlyCollection(Of String)

returnValue = instance.GetSupportedCardTypes()
```

``` csharp
public ReadOnlyCollection<string> GetSupportedCardTypes()
```

``` c++
public:
ReadOnlyCollection<String^>^ GetSupportedCardTypes()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  
A collection of card types.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

