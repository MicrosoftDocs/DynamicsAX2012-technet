---
title: GetChannelCashDeclarationResponse.ChannelCashDeclarations Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ChannelCashDeclarations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCashDeclarationResponse.ChannelCashDeclarations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcashdeclarationresponse.channelcashdeclarations(v=AX.60)
ms:contentKeyID: 62210332
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCashDeclarationResponse.ChannelCashDeclarations
dev_langs:
- CSharp
- C++
- VB
---

# ChannelCashDeclarations Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel tender types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelCashDeclarations As ReadOnlyCollection(Of CashDeclaration)
    Get
    Private Set
'Usage
Dim instance As GetChannelCashDeclarationResponse
Dim value As ReadOnlyCollection(Of CashDeclaration)

value = instance.ChannelCashDeclarations
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<CashDeclaration> ChannelCashDeclarations { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<CashDeclaration^>^ ChannelCashDeclarations {
    ReadOnlyCollection<CashDeclaration^>^ get ();
    private: void set (ReadOnlyCollection<CashDeclaration^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CashDeclaration](cashdeclaration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelCashDeclarationResponse Class](getchannelcashdeclarationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

