---
title: ExtendedControllerAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ExtendedControllerAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.extendedcontrollerattribute(v=AX.60)
ms:contentKeyID: 62203424
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerAttribute
dev_langs:
- CSharp
- C++
- VB
---

# ExtendedControllerAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents an extended controller for Retail Server.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<MetadataAttributeAttribute> _
<AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple := False)> _
Public NotInheritable Class ExtendedControllerAttribute _
    Inherits ExportAttribute _
    Implements IExtendedControllerMetadata
'Usage
Dim instance As ExtendedControllerAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[MetadataAttributeAttribute]
[AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple = false)]
public sealed class ExtendedControllerAttribute : ExportAttribute, 
    IExtendedControllerMetadata
```

``` c++
[ComVisibleAttribute(false)]
[MetadataAttributeAttribute]
[AttributeUsageAttribute(AttributeTargets::Class, AllowMultiple = false)]
public ref class ExtendedControllerAttribute sealed : public ExportAttribute, 
    IExtendedControllerMetadata
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    ExportAttribute  
      Microsoft.Dynamics.Retail.RetailServerLibrary.ExtendedControllerAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

