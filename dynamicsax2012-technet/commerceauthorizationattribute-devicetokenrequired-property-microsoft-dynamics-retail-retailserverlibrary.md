---
title: CommerceAuthorizationAttribute.DeviceTokenRequired Property  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: DeviceTokenRequired Property
ms:assetid: P:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.DeviceTokenRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute.devicetokenrequired(v=AX.60)
ms:contentKeyID: 62202337
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute.DeviceTokenRequired
dev_langs:
- CSharp
- C++
- VB
---

# DeviceTokenRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether device token required.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Property DeviceTokenRequired As Boolean
    Get
    Set
'Usage
Dim instance As CommerceAuthorizationAttribute
Dim value As Boolean

value = instance.DeviceTokenRequired

instance.DeviceTokenRequired = value
```

``` csharp
public bool DeviceTokenRequired { get; set; }
```

``` c++
public:
property bool DeviceTokenRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

