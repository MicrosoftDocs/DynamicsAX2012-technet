---
title: Set up number sequences
TOCTitle: Set up number sequences
ms:assetid: 0c81818d-6d5b-4bba-8d66-28442f9fd023
ms:mtpsurl: https://technet.microsoft.com/library/Hh242127(v=AX.60)
ms:contentKeyID: 36055998
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up number sequences 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Number sequences in Microsoft Dynamics AX are used to generate readable, unique identifiers for master data records and transaction records that require them. A master data or transaction record that requires an identifier is referred to as a reference. Before you can create new records for a reference, you must set up a number sequence and associate it with the reference.

You can set up all required number sequences at the same time by using the **Set up number sequences** wizard, or you can create or modify individual number sequences by using the **Number sequences** form.


> [!NOTE]
> <P>If you are setting up number sequences for a virtual company, you must use the <STRONG>Number sequences</STRONG> form. Number sequences can be set up for virtual companies only if you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2.</P>



## Set up all required number sequences by using the wizard

Use the **Set up number sequences** wizard to automatically create number sequences. The wizard generates number sequences for all references in all organizations for which number sequences are not yet defined. You cannot use the wizard to generate number sequences for a subset of the areas or references that require number sequences. You also cannot use the wizard to modify existing number sequences.


> [!NOTE]
> <P>If you are setting up number sequences for a virtual company, you must use the <STRONG>Number sequences</STRONG> form instead of the wizard. Number sequences can be set up for virtual companies only if you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2.</P>



1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. Then click **Generate**.

2.  On the **Welcome** page, click **Next \>**.

3.  The **Setup** page is displayed. On this page, you can modify the identification code, the lowest value, and the highest value. In addition, you can indicate whether the number sequence must be continuous.
    

    > [!IMPORTANT]
    > <P>Do not select the <STRONG>Continuous</STRONG> option if you must preallocate numbers for the number sequence.</P>

    
    To add a scope segment to the format of a number sequence, select the format in the list, and then click **Include scope in format**. To remove a scope segment from the format of a number sequence, select the format in the list, and then click **Remove scope from format**.
    
    To exclude a number sequence from automatic generation, select the number sequence in the list, and then click **Delete**.
    
    Click **Next \>**.

4.  On the **Completed** page, verify the information, and then click **Finish**.

## Set up individual number sequences

Use the **Number sequences** page to create or modify selected number sequences.


> [!WARNING]
> <P>We recommend that you do not modify the format of a continuous number sequence after numbers from that sequence have been used on documents or transactions. Changing the format when transactions are in process may cause gaps in the number sequence and corrupted number sequence data.</P>



1.  Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**. Click the **Number sequence** button or double-click an existing number sequence.

2.  On the **Identification** FastTab, enter an identification code and a name for the number sequence.

3.  On the **Scope parameters** FastTab, select a scope for the number sequence and select scope values.
    
    The scope defines which organizations use the number sequence. In addition, number sequences that have a scope other than **Shared** can have segments that correspond to their scope. For example, a number sequence with a scope of **Legal entity** can have a legal entity segment.
    
    By default, the following scopes can be used:
    

    > [!IMPORTANT]
    > <P>The available scopes depend on the reference that you are setting up a number sequence for.</P>

    
      - **Shared** – A single number sequence is used for all organizations. The **Shared** scope is available only for some references. For more information about the shared scope, see [Number sequence overview](number-sequence-overview.md).
    
      - **Company** – A separate number sequence is used for each company.
        
        Use the **Company** scope when the underlying table includes the DataAreaId field. For example, use this scope for the number sequence for the customer account number that is in the Customer table, CustTable.
        
        If you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2, the **Company** scope also includes virtual companies. If a number sequence has already been set up for a reference in one of the companies included in the virtual company, you must delete the existing number sequence before you can set up a number sequence for that reference in the virtual company.
    
      - **Legal entity** – A separate number sequence is used for each legal entity.
        
        Use the **Legal entity** scope when the underlying table does not include the DataAreaId field and has a foreign key to the legal entity table, CompanyInfo. For example, use this scope for the number sequence for the expense report number that is in the expense report table, TrvExpTable.
    
      - **Operating unit** – A separate number sequence is used for each operating unit.
    
      - **Company** **and** **Fiscal calendar period** – A separate number sequence is used for each company and fiscal calendar period combination.
    
      - **Legal entity** **and** **Fiscal calendar period** – A separate number sequence is used for each legal entity and fiscal calendar period combination.
    
      - **Operating unit type**– A separate number sequence is used for each type of operating unit. For example, you can set up separate number sequences for cost centers and departments.
        
        This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.

4.  On the **Segments** FastTab, define the format for the number sequence by adding, removing, and rearranging segments.
    
    Number sequences of all scopes can contain **Constant** segments and **Alphanumeric** segments. **Constant** segments contain a set of alphanumeric characters that does not change. Use this segment type to add a hyphen or other separator between number sequence segments. **Alphanumeric** segments contain a combination of number signs (\#) and ampersands (&). These characters represent letters and numbers that increment every time that a number from the sequence is used. Use a number sign (\#) to indicate incrementing numbers and an ampersand (&) to indicate incrementing letters. For example, the format \#\#\#\#\#\_2014 creates the sequence 00001\_2014, 00002\_2014, and so on.
    
    At least one alphanumeric segment must be present. Scope segments, such as company or legal entity, are not mandatory. However, even if you do not include scope segments in the format, numbers for the selected reference are still generated per scope.

5.  On the **References** FastTab, select the document type or record to assign this number sequence to.
    
    This step is optional for sequences that are defined for special application usage patterns. In these scenarios, a new number is generated by using the value of a number sequence code or ID, without using a reference. An example of a special application usage pattern is a voucher series that is used for specific journal names. However, we do not recommend that you use such patterns.

6.  On the **General** FastTab, specify whether the number sequence is manual, and continuous or non-continuous. In addition, enter the lowest and highest numbers that can be used in the number sequence.
    

    > [!WARNING]
    > <P>We do not recommend changing a non-continuous number sequence to a continuous number sequence. The number sequence will not be truly continuous. This change may also cause duplicate key violations in the database. In addition, continuous number sequences have a larger effect on performance.</P>



7.  Save the number sequence and close the form.

## See also

[Number sequence overview](number-sequence-overview.md)

[Number sequences (form)](https://technet.microsoft.com/library/hh209531\(v=ax.60\))

  


