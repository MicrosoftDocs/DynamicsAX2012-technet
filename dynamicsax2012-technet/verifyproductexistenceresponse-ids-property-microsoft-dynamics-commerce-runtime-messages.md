---
title: VerifyProductExistenceResponse.Ids Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Ids Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceResponse.Ids
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.verifyproductexistenceresponse.ids(v=AX.60)
ms:contentKeyID: 62215154
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.VerifyProductExistenceResponse.Ids
dev_langs:
- CSharp
- C++
- VB
---

# Ids Property

Gets product IDs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Ids As ReadOnlyCollection(Of ProductExistenceId)
    Get
    Private Set
'Usage
Dim instance As VerifyProductExistenceResponse
Dim value As ReadOnlyCollection(Of ProductExistenceId)

value = instance.Ids
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductExistenceId> Ids { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductExistenceId^>^ Ids {
    ReadOnlyCollection<ProductExistenceId^>^ get ();
    private: void set (ReadOnlyCollection<ProductExistenceId^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductExistenceId](productexistenceid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[VerifyProductExistenceResponse Class](verifyproductexistenceresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

