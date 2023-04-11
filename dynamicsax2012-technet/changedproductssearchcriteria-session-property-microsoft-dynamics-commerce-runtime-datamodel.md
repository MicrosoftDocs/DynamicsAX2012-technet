---
title: ChangedProductsSearchCriteria.Session Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Session Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria.Session
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.changedproductssearchcriteria.session(v=AX.60)
ms:contentKeyID: 62211915
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria.Session
dev_langs:
- CSharp
- C++
- VB
---

# Session Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Session As ReadChangedProductsSession
    Get
    Set
'Usage
Dim instance As ChangedProductsSearchCriteria
Dim value As ReadChangedProductsSession

value = instance.Session

instance.Session = value
```

``` csharp
[DataMemberAttribute]
public ReadChangedProductsSession Session { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadChangedProductsSession^ Session {
    ReadChangedProductsSession^ get ();
    void set (ReadChangedProductsSession^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadChangedProductsSession](readchangedproductssession-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ChangedProductsSearchCriteria Class](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

