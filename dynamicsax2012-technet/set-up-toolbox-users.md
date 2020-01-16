---
title: Set up toolbox users
TOCTitle: Set up toolbox users
ms:assetid: 2f0988fa-a861-43d0-a91e-cc8e79b136ad
ms:mtpsurl: https://technet.microsoft.com/library/JJ730403(v=AX.60)
ms:contentKeyID: 49636322
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up toolbox users 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Some features of Retail use a Microsoft ActiveX control that requires direct access to the Microsoft Dynamics AX database. Only users who have specific database permissions can access the following features:

  - Till layouts

  - Form layout

  - Button grids

  - Item images

  - Item bar codes

  - Language-specific item descriptions

  - Retail point of sale (POS) operations

  - Sales tax overrides

  - Payment types

This topic assumes that you have installed Microsoft SQL Server Reporting Services on the Microsoft Dynamics AX database server, and that the SQL Server settings comply with Payment Card Industry (PCI) standards. For more information about PCI compliance, see [Implementation Guide for PCI Compliance](https://go.microsoft.com/fwlink/?linkid=237283).

For each user of Microsoft Dynamics AX who should have access to these features, follow these steps in SQL Server Management Studio.

1.  Create a new SQL Server logon in the Microsoft Dynamics AX database by using Windows authentication and the user’s Windows logon ID.

2.  On the **Securables** page, grant the user **Delete**, **Insert**, **Select**, and **Update** permissions to the following tables:
    
      - RETAILBUTTONGRID
    
      - RETAILBUTTONGRIDBUTTONS
    
      - RETAILFORMLAYOUT
    
      - RETAILIMAGES
    
      - RETAILTILLLAYOUT

3.  Grant the user **Select** permission to the following tables:
    
      - INVENTTABLE
    
      - INVENTTXT
    
      - INVENTITEMBARCODE
    
      - RETAILOPERATIONS
    
      - RETAILSALESTAXOVERRIDE
    
      - RETAILSALESTAXOVERRIDEGROUPMEMBER
    
      - RETAILSTORETABLE
    
      - RETAILSTORETENDERTYPETABLE
    
      - RETAILTERMINALCUSTOMFIELD

## See also

[Set up buttons](set-up-buttons.md)

[Design a screen layout](design-a-screen-layout.md)

[Set up a button grid](set-up-a-button-grid.md)

  


