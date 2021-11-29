---
title: SalesLine.Clone(TClone) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Clone(TClone) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Clone``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn969206(v=AX.60)
ms:contentKeyID: 65322821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Clone``1
dev_langs:
- CSharp
- C++
- VB
---

# Clone(TClone) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

This member overrides [CommerceEntity.Clone\<T\>()](commerceentity-clone-t-method-microsoft-dynamics-commerce-runtime-datamodel.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Clone(Of TClone As {New, CommerceEntity}) As TClone
'Usage
Dim instance As SalesLine
Dim returnValue As TClone

returnValue = instance.Clone()
```

``` csharp
public override TClone Clone<TClone>()
where TClone : new(), CommerceEntity
```

``` c++
public:
generic<typename TClone>
where TClone : gcnew(), CommerceEntity
virtual TClone Clone() override
```

#### Type Parameters

  - TClone

#### Return Value

Type: TClone  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

