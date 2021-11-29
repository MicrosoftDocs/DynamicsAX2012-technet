---
title: ReadChangedProductsSession.Id Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Id Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.Id
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.readchangedproductssession.id(v=AX.60)
ms:contentKeyID: 62209075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession.Id
dev_langs:
- CSharp
- C++
- VB
---

# Id Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets session Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Id As Guid
    Get
    Private Set
'Usage
Dim instance As ReadChangedProductsSession
Dim value As Guid

value = instance.Id
```

``` csharp
[DataMemberAttribute]
public Guid Id { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Guid Id {
    Guid get ();
    private: void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
Returns [Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\)).  

## See Also

#### Reference

[ReadChangedProductsSession Class](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

