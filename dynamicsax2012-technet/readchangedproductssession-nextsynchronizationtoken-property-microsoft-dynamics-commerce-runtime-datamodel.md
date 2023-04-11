---
title: ReadChangedProductsSession.NextSynchronizationToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NextSynchronizationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NextSynchronizationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.nextsynchronizationtoken(v=AX.60)
ms:contentKeyID: 62210063
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.NextSynchronizationToken
dev_langs:
- CSharp
- C++
- VB
---

# NextSynchronizationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets next synchronization token which should be used to check for changes beyond this session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property NextSynchronizationToken As Char()
    Get
    Private Set
'Usage
Dim instance As ReadChangedProductsSession
Dim value As Char()

value = instance.NextSynchronizationToken
```

``` csharp
public char[] NextSynchronizationToken { get; private set; }
```

``` c++
public:
property array<wchar_t>^ NextSynchronizationToken {
    array<wchar_t>^ get ();
    private: void set (array<wchar_t>^ value);
}
```

#### Property Value

Type: [System.Char](https://technet.microsoft.com/library/k493b04s\(v=ax.60\))\[\]  
The synchronization token.  

## See Also

#### Reference

[ReadChangedProductsSession Class](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

