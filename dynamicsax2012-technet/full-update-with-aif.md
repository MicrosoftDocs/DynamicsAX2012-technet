---
title: Full Update With AIF
TOCTitle: Full Update With AIF
ms:assetid: 37e523f4-ef04-4ef8-9c5a-dc9cdd3d686c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh582242(v=AX.60)
ms:contentKeyID: 39533578
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Full Update With AIF 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In a full update, all the data in the document submitted to AIF is used and all fields in the database tables are updated with the fields from the submitted document. If there are fields in the table that are not in the submitted data, those table fields are cleared according to the rules for the data type of the field.

The result of a full update is the same as if you deleted the record and then added it from the submitted data with the following exceptions:

  - Primary key fields are not changed.

  - Fields that are allowed by the schema but not included in the submitted data are cleared.

  - Fields that are not allowed by the schema and therefore cannot be sent as part of the update message are defaulted if they have defaulting logic but are not affected otherwise.

For more information about full updates, see [Walkthrough: Updating Data with AIF (Full Update)](walkthrough-updating-data-with-aif-full-update.md).

## Specifying a Full Update

A full update is specified in one of two ways:

  - The presence of the update action in the message header and no other update attributes in any of the records.

  - The presence of the update action in the message header and the top record in the submitted data contains the replace action attribute.

### Child Data

When performing a full update, there are certain rules that AIF follows with regard to child data.

.For example, if a sales order with one sales order line occurs in the database and the message that is submitted for update contains:

  - The sales order data

  - One sales order line that matches an existing sales order line in the database

  - One sales order line that does not match an existing sales order line in the database

In this case, AIF performs the following actions:

  - Update the sales order

  - Update the first sales order line

  - Create the second sales order line in the database

In the previous scenario, the field values for the new sales line that is created come from the fields in the submitted message. For the new sales line, any table fields that are not in the sales order update message are cleared or defaulted according to the rules for the field's data type.


> [!WARNING]
> <P>You should first perform a read operation on the document you want to update to see the fields that are available for update, and to retrieve information for concurrency. For more information, see <A href="concurrency-when-updating-data.md">Concurrency When Updating Data</A>.</P>



In another example, a sales order with three sales order lines occurs in the database and the message that is submitted for update contains:

  - The sales order data

  - Two sales order lines that match existing sales order lines in the database

In this case, AIF performs the following actions.

  - Update the sales order

  - Update the two matching sales order lines

  - Delete the third sales order line from the database

