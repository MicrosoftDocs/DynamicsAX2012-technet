---
title: CommerceModelFactory.BuildComplexType(TComplexType) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BuildComplexType(TComplexType) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildComplexType``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn716236(v=AX.60)
ms:contentKeyID: 62202501
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildComplexType``1
dev_langs:
- CSharp
- C++
- VB
---

# BuildComplexType(TComplexType) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Builds complex entity type.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function BuildComplexType(Of TComplexType As Class) As ComplexTypeConfiguration(Of TComplexType)
'Usage
Dim returnValue As ComplexTypeConfiguration(Of TComplexType)

returnValue = CommerceModelFactory.BuildComplexType()
```

``` csharp
protected static ComplexTypeConfiguration<TComplexType> BuildComplexType<TComplexType>()
where TComplexType : class
```

``` c++
protected:
generic<typename TComplexType>
where TComplexType : ref class
static ComplexTypeConfiguration<TComplexType>^ BuildComplexType()
```

#### Type Parameters

  - TComplexType

#### Return Value

Type: ComplexTypeConfiguration\<TComplexType\>  
The ComplexTypeConfiguration of complex entity type.  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

