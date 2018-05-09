---
title: SearchStoreRequest.QueryCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest.QueryCriteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.searchstorerequest.querycriteria(v=AX.60)
ms:contentKeyID: 62210952
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest.QueryCriteria
dev_langs:
- CSharp
- C++
- VB
---

# QueryCriteria Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property QueryCriteria As SearchStoreCriteria
    Get
    Set
'Usage
Dim instance As SearchStoreRequest
Dim value As SearchStoreCriteria

value = instance.QueryCriteria

instance.QueryCriteria = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public SearchStoreCriteria QueryCriteria { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property SearchStoreCriteria^ QueryCriteria {
    SearchStoreCriteria^ get ();
    void set (SearchStoreCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria](searchstorecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SearchStoreRequest Class](searchstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

