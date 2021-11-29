---
title: Global address books and address reference data
TOCTitle: Global address books and address reference data
ms:assetid: 11e4bc19-6a3e-4066-8682-0dd43cfd0db1
ms:mtpsurl: https://technet.microsoft.com/library/Gg751354(v=AX.60)
ms:contentKeyID: 35132552
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Global address books and address reference data 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 includes a global address book that is shared among all companies in your environment. You do not have to create virtual companies for the global address book, as in past releases of Microsoft Dynamics AX. The global address book stores party record information for each organization or person that your organization has contact with, such as customers, vendors, competitors, and workers. A party is a person or organization that is either internal or external to your organization. Each party has its own record.

Before you begin to work with address books, you can set the defaults, enable the parameters, and, if you choose, grant security privileges so that workers can access your organization's address books or party records. You can also enable the parameters for each party record individually in the global address book. For more information about the parameters for the global address book, see [Set up global address book parameters](set-up-global-address-book-parameters.md). For more information about global address book security and granting privileges, see [About security in the global address book](about-security-in-the-global-address-book.md).

## Plan address books

You can create additional address books as needed, such as for each company in your organization or each line of business. This section contains an example of how a company might organize its address books.

Fabrikam is an international organization that has multiple companies and multiple lines of business. Fabrikam plans to create an address book for each line of business. For lines of business that occur in more than one location, such as its pneumatic tools business, Fabrikam will create an address book for each location. Chris, the IT manager for Fabrikam, has created the following list of address books that must be created, which also describes the party records to include in each address book:

  - Public Sector Contracts (PubSC) – Party records for all parties that are involved in the public sector contracts that are held by Fabrikam.

  - Private Sector Contracts (PriSC) – Party records for all parties that are involved in the private sector contracts that are held by Fabrikam.

  - Electronic Tools (ET) – Party records for all parties that are involved in the purchase or sale of electronic tools, or that otherwise interact with the electronic tools that are provided by or purchased for Fabrikam in the Fabrikam-Japan company.

  - Pneumatic Tools (PTJPN) – Party records for all parties that are involved in the purchase or sale of pneumatic tools, or that otherwise interact with the pneumatic tools that are provided by or purchased for Fabrikam in the Fabrikam-Japan company.

  - Pneumatic Tools (PTUSA) – Party records for all parties that are involved in the purchase or sale of pneumatic tools, or that otherwise interact with the pneumatic tools that are provided by or purchased for Fabrikam in the Fabrikam-US company.

For more information about how to create address books, see [Create address books](create-address-books.md).

## Work with address reference data and party record information

In addition to creating address books, you can work with address reference data, such as countries/regions, states, and ZIP/postal codes, and more detailed elements of party records, such as address and contact information purposes.

An address and contact information purpose describes the reason or use of a particular address or telephone number. For example, if a customer record contains an address for each of the customer's four locations; you can assign an address purpose to each address. This can help you track where deliveries should be sent, where services are needed, or where mail is sent by using the postal service. For more information about how to create address purposes, see [Set up address and contact information purposes](set-up-address-and-contact-information-purposes.md).

Because numerous distinct address formats are used world-wide, your organization might need to adjust an address format when displaying a postal address. You can use the **Address setup** form to set up information about postal addresses for your organization. For more information about how to set up address formats, see [Key tasks: Set up address formats](key-tasks-set-up-address-formats.md).

You can set up translations of country/region information. You can view the country/region information in your user language, but the printed country/region information appears in the translated language that you select. For example, if your user language is Danish, and you have a customer in Japan, in Microsoft Dynamics AX, you can view the customer record in Danish, but when the address is printed for a sales order, the country/region information appears in Japanese. For more information about translations, see [Set up global address book translations](set-up-global-address-book-translations.md).

## See also

[Merge global address book records](merge-global-address-book-records.md)

[Convert party types](convert-party-types.md)

  


