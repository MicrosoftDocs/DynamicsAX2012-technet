---
title: CommerceAuthorizationAttribute.AllowedRetailRoles Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: AllowedRetailRoles Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.AllowedRetailRoles
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute.allowedretailroles(v=AX.60)
ms:contentKeyID: 62203041
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.AllowedRetailRoles
dev_langs:
- CSharp
- C++
- VB
---

# AllowedRetailRoles Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the allowed retail roles.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Property AllowedRetailRoles As String()
    Get
    Set
'Usage
Dim instance As CommerceAuthorizationAttribute
Dim value As String()

value = instance.AllowedRetailRoles

instance.AllowedRetailRoles = value
```

``` csharp
public string[] AllowedRetailRoles { get; set; }
```

``` c++
public:
property array<String^>^ AllowedRetailRoles {
    array<String^>^ get ();
    void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

