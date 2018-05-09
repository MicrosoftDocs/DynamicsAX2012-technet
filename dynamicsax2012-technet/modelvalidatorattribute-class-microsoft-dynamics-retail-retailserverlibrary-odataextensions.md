---
title: ModelValidatorAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: ModelValidatorAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.ModelValidatorAttribute
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.modelvalidatorattribute(v=AX.60)
ms:contentKeyID: 62202647
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.ModelValidatorAttribute
dev_langs:
- CSharp
- C++
- VB
---

# ModelValidatorAttribute Class

OData model validation filter attribute class.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Class Or AttributeTargets.Method, AllowMultiple := True,  _
    Inherited := True)> _
<ComVisibleAttribute(False)> _
Public NotInheritable Class ModelValidatorAttribute _
    Inherits ActionFilterAttribute
'Usage
Dim instance As ModelValidatorAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = true, 
    Inherited = true)]
[ComVisibleAttribute(false)]
public sealed class ModelValidatorAttribute : ActionFilterAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Class|AttributeTargets::Method, AllowMultiple = true, 
    Inherited = true)]
[ComVisibleAttribute(false)]
public ref class ModelValidatorAttribute sealed : public ActionFilterAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/en-us/library/e8kc3626\(v=ax.60\))  
    FilterAttribute  
      ActionFilterAttribute  
        Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.ModelValidatorAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

