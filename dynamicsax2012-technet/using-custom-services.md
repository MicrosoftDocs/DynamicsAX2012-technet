---
title: Using Custom Services
TOCTitle: Using Custom Services
ms:assetid: cb5d0f7e-1d47-4d9f-9842-050f42aca224
ms:mtpsurl: https://technet.microsoft.com/library/Hh509052(v=AX.60)
ms:contentKeyID: 37046471
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Using Custom Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

 In Microsoft Dynamics AX, you can create custom services to expose X++ functionality to external clients. Any existing X++ code can be exposed as a custom service simply by adding an attribute. Microsoft Dynamics AX provides standard attributes that can be set on the data contract class and its members to automatically serialize and de-serialize data that is sent and received across a network connection. Many predefined types, such as collections and tables, are also supported.

Use custom services when the schema for the entity can be written as a simple data contract class with relevant data member attributes set. If tables and relationships are used in a data contract, you must write code for any more complex feature, such as dimensions. X++ data contract serialization and deserialization is specified through the [DataContractAttribute](https://technet.microsoft.com/library/gg732039\(v=ax.60\)) and the [DataMemberAttribute](https://technet.microsoft.com/library/gg732046\(v=ax.60\)) attributes. For more information, see [Using Data Contracts in X++](using-data-contracts-in-x.md). Use the [AifCollectionTypeAttribute](https://technet.microsoft.com/library/gg738025\(v=ax.60\)) attribute to define the serialization/deserialization of any X++ collection type that is used as a data member, or as a return value from or parameter to a service operation.

You can use all the functionality of transforms and pipelines for data processing with custom services. For more information, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

You must set the SysEntryPointAttribute attribute to define authorization for all custom service operations. For more information, see [Setting SysEntryPointAttribute for Services](setting-sysentrypointattribute-for-services.md).


> [!WARNING]
> <P>The service operation names <STRONG>Create</STRONG>, <STRONG>Find</STRONG>, <STRONG>Update</STRONG>, and <STRONG>Delete</STRONG> are reserved for use only by AIF Document Services. Use of these service operation names in a custom service will generate an exception and can cause the system to time out when you call the service from an external client.</P>



## Using the AifCollectionTypeAttribute

You must specify the [AifCollectionTypeAttribute](https://technet.microsoft.com/library/gg738025\(v=ax.60\)) attribute if you use an X++ collection as a parameter to or as a return value from a service operation.

The following example shows the X++ collection FMIncCarContract that is used as a return value for a service operation.

    [AifCollectionTypeAttribute(‘return’, Types::Class, classStr(FMIncCarContract)), SysEntryPointAttribute(true)]
       Public List RetrieveAllCars()
       {   
         List result = new List(Types::Class);
         FMIncCarContract car;
         FMIncCars buffer;
    
         While select – from buffer
         {
           car = new FMIncCarContract();
           car.Make(buffer.Make);
           car.Model(buffer,Model);
           car.VIN(buffer.VINF);
    
           result.addEnd(car);
         }
    
         return result;
       }

The following example shows the class FMIncCarContract used in the service operation in the previous example. The [DataContractAttribute](https://technet.microsoft.com/library/gg732039\(v=ax.60\)) attribute is used to define serialization of the class as a data contract.

    [DataContractAttribute]
    Public class FMIncCarContract
    {
       str _VIN;
       str _Make;
       str _Model;
       str _Mileage;
       str _Color;
       str _MPG;
       str _transmission;
       str _AssembledIn;
       str _CarFactsSummry;
       FMVehicleStatus _Status;
    }

The following example shows the data member VIN used in the service operation in the previous example. The [DataMemberAttribute](https://technet.microsoft.com/library/gg732046\(v=ax.60\)) attribute is used to define serialization of the accessor method as a data member.

    [DataMemberAttribute]
    Public str VIN(str vin = _VIN)
    {
       _VIN = vin;
       Return _VIN;
    }

## See also

[Developing with Services and AIF](developing-with-services-and-aif.md)

[Walkthrough: Exposing an X++ Class as a Data Contract](walkthrough-exposing-an-x-class-as-a-data-contract.md)

[Walkthrough: Transforming a document](walkthrough-transforming-a-document.md)

