---
title: Set up global address book translations
TOCTitle: Set up global address book translations
ms:assetid: d6dbb900-16ac-4db6-a352-ab3c3e23be93
ms:mtpsurl: https://technet.microsoft.com/library/Hh227351(v=AX.60)
ms:contentKeyID: 36059538
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up global address book translations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up translations of address information so that you can view the text in your system in your user language, but display the information on documents, such as sales orders, in another language. You can enter translations for country/region names, address purposes, and name sequences.

For example, if your user language is Danish, and you create a sales order for a customer in France, you can view the customer record in Microsoft Dynamics AX in Danish, but display address information in French on the printed sales order.


> [!IMPORTANT]
> <P>When you set up translations, you should enter a translation for each item in the list. Any item that you do not enter a translation for will appear in the system language. For example, your system language is Danish, and you send a document to a customer in Spain. If you have not entered Spanish (ESP) translations for the address information, the information will be displayed in Danish in your system and on printed material.</P>
> <P>The system language is set up in the <STRONG>System parameters</STRONG> form. Click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>System parameters</STRONG>.</P>



The procedure in this topic explains how to enter translations for country/region names. You can follow the same procedure when you add address purposes and name sequences, in those areas of the **Translations** form.

### Enter translations for address book information

1.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Translation**.

2.  In the **Translations** form, click **Country/region**, and then in the **Language** filter, select the language for which you want to enter translations.

3.  Enter a translation for the short name and long name for each country/region.
    
    For example, if you are adding a French translation for the country/region code BOL, you would enter Bolivie in the **Short name** column and République de Bolivie in the **Long name** column.

4.  Repeat steps 2 and 3 for the **Address and contact information purpose** and **Name sequence** areas in the form.

  


