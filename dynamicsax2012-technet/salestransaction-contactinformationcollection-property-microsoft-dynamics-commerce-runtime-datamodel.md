---
title: SalesTransaction.ContactInformationCollection Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ContactInformationCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ContactInformationCollection
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.contactinformationcollection(v=AX.60)
ms:contentKeyID: 49822657
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ContactInformationCollection
dev_langs:
- CSharp
- C++
- VB
---

# ContactInformationCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the collection of contact information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ContactInformationCollection As Collection(Of ContactInformation)
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Collection(Of ContactInformation)

value = instance.ContactInformationCollection

instance.ContactInformationCollection = value
```

``` csharp
[DataMemberAttribute]
public Collection<ContactInformation> ContactInformationCollection { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ContactInformation^>^ ContactInformationCollection {
    Collection<ContactInformation^>^ get ();
    void set (Collection<ContactInformation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ContactInformation](contactinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

