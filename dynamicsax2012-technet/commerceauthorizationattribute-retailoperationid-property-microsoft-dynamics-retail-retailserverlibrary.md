---
title: CommerceAuthorizationAttribute.RetailOperationId Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: RetailOperationId Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.RetailOperationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute.retailoperationid(v=AX.60)
ms:contentKeyID: 62201866
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.RetailOperationId
dev_langs:
- CSharp
- C++
- VB
---

# RetailOperationId Property

Gets or sets the retail operation ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Property RetailOperationId As RetailOperation
    Get
    Set
'Usage
Dim instance As CommerceAuthorizationAttribute
Dim value As RetailOperation

value = instance.RetailOperationId

instance.RetailOperationId = value
```

``` csharp
public RetailOperation RetailOperationId { get; set; }
```

``` c++
public:
property RetailOperation RetailOperationId {
    RetailOperation get ();
    void set (RetailOperation value);
}
```

#### Property Value

Type: RetailOperation  
Returns RetailOperation.  

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

