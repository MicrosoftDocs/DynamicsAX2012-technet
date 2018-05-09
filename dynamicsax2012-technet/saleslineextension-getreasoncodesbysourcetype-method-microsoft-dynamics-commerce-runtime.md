---
title: SalesLineExtension.GetReasonCodesBySourceType Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetReasonCodesBySourceType Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetReasonCodesBySourceType(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.saleslineextension.getreasoncodesbysourcetype(v=AX.60)
ms:contentKeyID: 65318932
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.SalesLineExtension.GetReasonCodesBySourceType
dev_langs:
- CSharp
- C++
- VB
---

# GetReasonCodesBySourceType Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetReasonCodesBySourceType ( _
    salesLine As SalesLine, _
    reasonCodeSettings As ReasonCodeSettings, _
    reasonCodeSourceType As ReasonCodeSourceType, _
    context As RequestContext _
) As IEnumerable(Of ReasonCodeLine)
'Usage
Dim salesLine As SalesLine
Dim reasonCodeSettings As ReasonCodeSettings
Dim reasonCodeSourceType As ReasonCodeSourceType
Dim context As RequestContext
Dim returnValue As IEnumerable(Of ReasonCodeLine)

returnValue = salesLine.GetReasonCodesBySourceType(reasonCodeSettings, _
    reasonCodeSourceType, context)
```

``` csharp
public static IEnumerable<ReasonCodeLine> GetReasonCodesBySourceType(
    this SalesLine salesLine,
    ReasonCodeSettings reasonCodeSettings,
    ReasonCodeSourceType reasonCodeSourceType,
    RequestContext context
)
```

``` c++
[ExtensionAttribute]
public:
static IEnumerable<ReasonCodeLine^>^ GetReasonCodesBySourceType(
    SalesLine^ salesLine, 
    ReasonCodeSettings^ reasonCodeSettings, 
    ReasonCodeSourceType reasonCodeSourceType, 
    RequestContext^ context
)
```

#### Parameters

  - salesLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - reasonCodeSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSettings](reasoncodesettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - reasonCodeSourceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[SalesLineExtension Class](saleslineextension-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

