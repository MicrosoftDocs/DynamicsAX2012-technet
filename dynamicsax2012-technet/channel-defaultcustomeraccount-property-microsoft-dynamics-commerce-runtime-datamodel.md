---
title: Channel.DefaultCustomerAccount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultCustomerAccount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.DefaultCustomerAccount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channel.defaultcustomeraccount(v=AX.60)
ms:contentKeyID: 49845741
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.DefaultCustomerAccount
dev_langs:
- CSharp
- C++
- VB
---

# DefaultCustomerAccount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the default customer account of the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DEFAULTCUSTACCOUNT")> _
<IgnoreDataMemberAttribute> _
Public Property DefaultCustomerAccount As String
    Get
    Set
'Usage
Dim instance As Channel
Dim value As String

value = instance.DefaultCustomerAccount

instance.DefaultCustomerAccount = value
```

``` csharp
[ColumnAttribute("DEFAULTCUSTACCOUNT")]
[IgnoreDataMemberAttribute]
public string DefaultCustomerAccount { get; set; }
```

``` c++
[ColumnAttribute(L"DEFAULTCUSTACCOUNT")]
[IgnoreDataMemberAttribute]
public:
property String^ DefaultCustomerAccount {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The channel default customer account.  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

