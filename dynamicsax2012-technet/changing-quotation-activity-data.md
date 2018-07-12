---
title: Changing quotation activity data
TOCTitle: Changing quotation activity data
ms:assetid: 2c538513-73c0-4b3a-a790-a91035bf2f2c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496868(v=AX.60)
ms:contentKeyID: 36056258
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Changing quotation activity data 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you change quotation data, do so carefully because changes can affect the data for the related quotation activity. This topic describes the changes that you can make to quotations, and the effects that the changes have on the data for quotation activities.

## Changing the status

If you change the status of a sales quotation to **Canceled** or **Lost**, or if you convert the sales quotation to a sales order, the follow-up activity for the sales quotation is automatically closed.

## Deleting a sales quotation

If you delete a sales quotation, the attached follow-up activity is also deleted.

## Changing the follow-up date

If you change the follow-up date of a sales quotation, the start date of the follow-up activity is also changed.

## Changing the responsibility for the sales quotation

If you change the worker who is responsible for a sales quotation, the follow-up activity is changed to reflect the new worker.

If the follow-up activity was previously synchronized by using Microsoft Outlook, the follow-up activity is deleted. The synchronization log is set to delete the old follow-up activity during the next synchronization, and a new follow-up activity is created for the new worker.

If you remove the worker who is responsible for a quotation, the follow-up activity is deleted.

## Changing the contact person

If a contact person is associated with a sales quotation, the contact is registered in the follow-up activity for the sales quotation.

If you remove the contact, the follow-up activity is automatically updated, and the contact is removed from the data for the follow-up activity.

## Changing activity data

Changes to the data for the follow-up activity for a sales quotation do not affect the sales quotation on which the data is based.

  


