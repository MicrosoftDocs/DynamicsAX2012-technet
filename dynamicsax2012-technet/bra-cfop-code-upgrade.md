---
title: (BRA) CFOP code (upgrade)
TOCTitle: (BRA) CFOP code (upgrade)
ms:assetid: 81bb969d-d11d-4421-bec1-1581ad227339
ms:mtpsurl: https://technet.microsoft.com/library/JJ714194(v=AX.60)
ms:contentKeyID: 49651303
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (BRA) CFOP code (upgrade) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In releases prior to Microsoft Dynamics AX 2012 R2, you could create multiple records for the same Código Fiscal de Operações e Prestações (CFOP) code by specifying different locations or types of transaction. In Microsoft Dynamics AX 2012 R2 and R3, you must create unique CFOP codes based on the location and direction of movement of the items. During upgrade preprocessing, if multiple records are available with the same CFOP code for different locations and types of transaction on the source system, you must select a unique CFOP code to add to the target system. The default location and direction for the CFOP code are updated in the **Location** and **Direction** fields in the **CFOP codes** form, based on the first digit of the CFOP code. The following table contains the first digits of CFOP codes and the default locations and directions they signify.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 First digit of CFOP code
  </p> </th>
    <th> <p>
   
	 Location
  </p> </th>
    <th> <p>
   
	 Direction
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 1
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Same state</strong> – The customer or vendor is located in the same state as the fiscal establishment.
  </p> </td>
    <td rowspan="3"> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Incoming</strong> – Items are entering the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 2
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Other state</strong> – The customer or vendor is located in the same country as the fiscal establishment but in another state.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 3
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Outside country</strong> – The customer or vendor is located in a different country from the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 5
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Same state</strong> – The customer or vendor is located in the same state as the fiscal establishment.
  </p> </td>
    <td rowspan="3"> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Outgoing</strong> – Items are leaving the fiscal establishment.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 6
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Other state</strong> – The customer or vendor is located in the same country as the fiscal establishment but in another state.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 7
  </p> </td>
    <td> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Outside country</strong> – The customer or vendor is located in a different country from the fiscal establishment.
  </p> </td>
  </tr>
</table>



> [!NOTE]
> <P>If the CFOP code starts with 0, 4, 8, 9, or any alphanumeric character other than 1, 2, 3, 5, 6, or 7, the default location is updated as <STRONG>Same state</STRONG>. However, you can enter a different location in the <STRONG>Location</STRONG> field in the <STRONG>CFOP codes</STRONG> form. You can also select the direction of the movement of items as <STRONG>Incoming</STRONG> or <STRONG>Outgoing</STRONG> in the <STRONG>Direction</STRONG> field .</P>



Use the following procedure to select unique CFOP codes to upgrade when multiple legacy CFOP code records are available with the same CFOP code.

1.  In the **Preprocessing upgrade checklist**, expand **Prepare application data for preprocessing**, and then click **CFOP code** to open the **CFOP code** form.

2.  Select the **Remains in AX 2012** check box to select one CFOP code from multiple records with the same CFOP code, to add to the target system.

3.  Repeat step 2 for each group of multiple records with the same CFOP code.

4.  After you have selected unique CFOP codes for all multiple records with the same CFOP code, click **Set to ready for upgrade** to mark the checklist task as complete.

## See also

[(BRA) CFOP code (upgrade) (form)](https://technet.microsoft.com/library/jj713620\(v=ax.60\))

  


