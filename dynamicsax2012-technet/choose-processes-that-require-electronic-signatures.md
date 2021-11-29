---
title: Choose processes that require electronic signatures
TOCTitle: Choose processes that require electronic signatures
ms:assetid: 3b807a83-69db-49d6-bff1-2ac6715be360
ms:mtpsurl: https://technet.microsoft.com/library/Dd309646(v=AX.60)
ms:contentKeyID: 36056648
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- compliance
- e-signatures
audience: Application User
ms.search.region: Global
---

# Choose processes that require electronic signatures 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you require electronic signatures for a process, the process cannot continue until the signature is provided. By default, the electronic signature functionality is available for the following manufacturing processes:

  - Approve route

  - Approve route version

  - Activate route version

  - Approve bill of materials (BOM)

  - Approve BOM version

  - Activate BOM version

  - Release production order

  - Report production order as finished

You can also set up a custom electronic signature requirement for a table or field in Microsoft Dynamics AX.


> [!WARNING]
> <P>Custom requirements for electronic signatures can cause application errors. Make sure that you test the effects of a custom requirement for electronic signatures before you implement the requirement in a production environment.</P>



Follow these recommendations when you set up custom requirements for electronic signatures:

  - We recommend that you do not set up signature requirements for the following actions on the following tables.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Table</p></th>
    <th><p>Action</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>LedgerJournalTable</p></td>
    <td><ul>
    <li><p>Insert</p></li>
    <li><p>Update</p></li>
    <li><p>Delete</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p>VendTable</p></td>
    <td><ul>
    <li><p>Insert</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p>CustTable</p></td>
    <td><ul>
    <li><p>Insert</p></li>
    <li><p>Delete</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p>SalesTable</p></td>
    <td><ul>
    <li><p>Insert</p></li>
    <li><p>Delete</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>
    
    If one of the tables in the previous list has a signature requirement and a user makes changes in the corresponding form, the message "Transaction does not contain a required signature" is displayed, and changes are not saved.

  - We recommend that you do not set up signature requirements on the tables in an inheritance hierarchy. If some tables in the hierarchy have a signature requirement but others do not, and a user tries to insert a record, the record is not inserted. For example, the DirPerson and DirOrganizationBase tables inherit from the DirPartyTable table. If the DirPartyTable table has a signature requirement, but the DirPerson table does not, a new record cannot be created in the DirPerson table.

  - We recommend that you do not set up a custom requirement for an electronic signature on a table that contains date-effective records.

  - Custom signature requirements are not supported on tables or fields that are updated through Enterprise Portal for Microsoft Dynamics AX or Application Integration Framework (AIF). Requirements for electronic signatures on these tables and fields cause errors.

## Require electronic signatures for an existing process

Use this procedure to require electronic signatures for built-in processes or processes that you previously created.

1.  Click **Organization administration** \> **Setup** \> **Electronic signature** \> **Electronic signature requirements**.

2.  Select the check box next to each process that requires electronic signatures.

3.  For signature requirements that you created, you can click the **Properties** button to modify the signature requirement. You can change the table, field, or action that requires a signature.
    

    > [!NOTE]
    > <P>You cannot change the properties for built-in processes.</P>



4.  Close the form.

## Set up a custom requirement for electronic signatures

Electronic signatures help guarantee compliance and accountability, and may be either mandated by law or required by company policy for critical business processes. The following examples show potential uses for electronic signatures:

  - In financials, accountability is important. Electronic signatures can be required when purchase orders are approved or tax documents are submitted to government entities.

  - In human resources, electronic signatures can be used for offer letters, compliance forms, handbook and policy acknowledgements, position approvals, new hires, transfers, or promotions.

  - In the public sector, signatures can be required when purchase orders, budgets, budget revisions, or journals are approved.

Use this procedure to create a requirement for electronic signatures for a process.

1.  Click **Organization administration** \> **Setup** \> **Electronic signature** \> **Electronic signature requirements**.

2.  Press CTRL+N or click **New** to create a new record.

3.  Enter a name for the signature requirement.

4.  Click **Properties** to open the **Signature requirement details** form.

5.  Select the table where the data that must be signed is stored.

6.  Select the field in the table that you want to monitor.

7.  Specify when a signature is required. Select **Always** if a signature is required whenever the data in the field changes. Select **Only** if a signature is required only under certain conditions. If you select **Only**, you must also select one of the following options:
    
      - **When a record is inserted** – A signature is required only when a new record is created.
    
      - **When a record is updated** – A signature is required only when a record is changed.
    
      - **When a record is deleted** – A signature is required only when a record is removed from the table.
    

    > [!NOTE]
    > <P>To require a signature any time that a record is inserted into or deleted from a table, we recommend that you select only that table. To require a signature any time that a record is changed, you must select both a table and a field.</P>



8.  Click **OK** in the **Signature requirement details** form to save your changes and close the form.

9.  Close the **Electronic signature requirements** form.

10. Restart any Microsoft Dynamics AX clients that were open when the new requirement was set up. If a client has not been restarted, and the user attempts to change a field that now requires a signature, the user will get an error.

  


