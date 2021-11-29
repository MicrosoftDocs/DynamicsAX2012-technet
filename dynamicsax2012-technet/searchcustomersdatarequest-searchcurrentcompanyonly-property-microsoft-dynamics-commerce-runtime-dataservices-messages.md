---
title: SearchCustomersDataRequest.SearchCurrentCompanyOnly Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SearchCurrentCompanyOnly Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.SearchCurrentCompanyOnly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.searchcustomersdatarequest.searchcurrentcompanyonly(v=AX.60)
ms:contentKeyID: 65316956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.SearchCurrentCompanyOnly
dev_langs:
- CSharp
- C++
- VB
---

# SearchCurrentCompanyOnly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether only search current company.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchCurrentCompanyOnly As Boolean
    Get
    Private Set
'Usage
Dim instance As SearchCustomersDataRequest
Dim value As Boolean

value = instance.SearchCurrentCompanyOnly
```

``` csharp
[DataMemberAttribute]
public bool SearchCurrentCompanyOnly { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SearchCurrentCompanyOnly {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value indicating whether only to search current company.  

## See Also

#### Reference

[SearchCustomersDataRequest Class](searchcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

