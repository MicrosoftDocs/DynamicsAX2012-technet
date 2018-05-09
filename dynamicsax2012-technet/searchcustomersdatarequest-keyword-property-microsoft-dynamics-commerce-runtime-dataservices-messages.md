---
title: SearchCustomersDataRequest.Keyword Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Keyword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.Keyword
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.searchcustomersdatarequest.keyword(v=AX.60)
ms:contentKeyID: 65323094
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SearchCustomersDataRequest.Keyword
dev_langs:
- CSharp
- C++
- VB
---

# Keyword Property

Gets the search keyword.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Keyword As String
    Get
    Private Set
'Usage
Dim instance As SearchCustomersDataRequest
Dim value As String

value = instance.Keyword
```

``` csharp
[DataMemberAttribute]
public string Keyword { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Keyword {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The keyword.  

## See Also

#### Reference

[SearchCustomersDataRequest Class](searchcustomersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

