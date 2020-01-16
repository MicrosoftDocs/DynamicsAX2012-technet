---
title: ResponseError.ShowDebugInfo Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: ShowDebugInfo Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.ShowDebugInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.responseerror.showdebuginfo(v=AX.60)
ms:contentKeyID: 65318079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ResponseError.ShowDebugInfo
dev_langs:
- CSharp
- C++
- VB
---

# ShowDebugInfo Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShowDebugInfo As Boolean
    Get
    Set
'Usage
Dim instance As ResponseError
Dim value As Boolean

value = instance.ShowDebugInfo

instance.ShowDebugInfo = value
```

``` csharp
[DataMemberAttribute]
public bool ShowDebugInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool ShowDebugInfo {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ResponseError Class](responseerror-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

