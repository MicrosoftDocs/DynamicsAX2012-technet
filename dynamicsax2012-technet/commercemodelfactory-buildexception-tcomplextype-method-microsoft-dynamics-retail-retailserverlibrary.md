---
title: CommerceModelFactory.BuildException(TComplexType) Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BuildException(TComplexType) Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildException``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn737433(v=AX.60)
ms:contentKeyID: 62202146
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceModelFactory.BuildException``1
dev_langs:
- CSharp
- C++
- VB
---

# BuildException(TComplexType) Method

Builds exception for the complex type.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function BuildException(Of TComplexType As CommerceRuntimeException) As ComplexTypeConfiguration(Of TComplexType)
'Usage
Dim returnValue As ComplexTypeConfiguration(Of TComplexType)

returnValue = CommerceModelFactory.BuildException()
```

``` csharp
protected static ComplexTypeConfiguration<TComplexType> BuildException<TComplexType>()
where TComplexType : CommerceRuntimeException
```

``` c++
protected:
generic<typename TComplexType>
where TComplexType : CommerceRuntimeException
static ComplexTypeConfiguration<TComplexType>^ BuildException()
```

#### Type Parameters

  - TComplexType

#### Return Value

Type: ComplexTypeConfiguration\<TComplexType\>  
The ComplexTypeConfiguration configuration.  

## See Also

#### Reference

[CommerceModelFactory Class](commercemodelfactory-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

