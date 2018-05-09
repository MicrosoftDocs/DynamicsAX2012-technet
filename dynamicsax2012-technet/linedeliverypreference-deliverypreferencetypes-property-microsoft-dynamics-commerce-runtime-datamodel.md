---
title: LineDeliveryPreference.DeliveryPreferenceTypes Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryPreferenceTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.DeliveryPreferenceTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreference.deliverypreferencetypes(v=AX.60)
ms:contentKeyID: 65318868
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreference.DeliveryPreferenceTypes
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryPreferenceTypes Property

Gets the collection of delivery preferences available for this sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeliveryPreferenceTypes As ICollection(Of DeliveryPreferenceType)
    Get
    Private Set
'Usage
Dim instance As LineDeliveryPreference
Dim value As ICollection(Of DeliveryPreferenceType)

value = instance.DeliveryPreferenceTypes
```

``` csharp
[DataMemberAttribute]
public ICollection<DeliveryPreferenceType> DeliveryPreferenceTypes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<DeliveryPreferenceType>^ DeliveryPreferenceTypes {
    ICollection<DeliveryPreferenceType>^ get ();
    private: void set (ICollection<DeliveryPreferenceType>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The delivery preferences.  

## See Also

#### Reference

[LineDeliveryPreference Class](linedeliverypreference-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

