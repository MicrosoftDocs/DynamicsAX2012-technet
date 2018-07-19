---
title: (AUS) Set up a method of payment to pay vendors through Australian banks
TOCTitle: (AUS) Set up a method of payment to pay vendors through Australian banks
ms:assetid: ff6b1e28-f0d5-4a92-95d4-ac3a1e31a6d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ944963(v=AX.60)
ms:contentKeyID: 51412457
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Australia
---

# (AUS) Set up a method of payment to pay vendors through Australian banks 


_**Applies To:** Microsoft Dynamics AX 2012_

You can pay vendors electronically through banks. The names of the banks and the file formats that they accept for the electronic payments are listed in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Bank name</p></th>
<th><p>Bank interface</p></th>
<th><p>File format</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Australia and New Zealand Bank</p></td>
<td><p>ANZ TransActive</p>
<p>Banking for Business</p></td>
<td><p><strong>ANZ Direct Credit Service (AU)</strong></p></td>
</tr>
<tr class="even">
<td><p>Commonwealth Bank of Australia</p></td>
<td><p>CommBiz</p></td>
<td><p><strong>CBA Direct Credit Service (AU)</strong></p></td>
</tr>
<tr class="odd">
<td><p>Westpac Banking Corporation</p></td>
<td><p>Corporate Online</p>
<p>Business Online</p></td>
<td><p><strong>WBC Direct Entry System (AU)</strong></p></td>
</tr>
<tr class="even">
<td><p>St. George Bank</p></td>
<td><p>Business banking online</p></td>
<td><p><strong>STG Direct credit Service (AU)</strong></p></td>
</tr>
<tr class="odd">
<td><p>National Australia Bank</p></td>
<td><p>Internet Banking</p>
<p>NAB Connect</p>
<p>NAB Online</p></td>
<td><p><strong>NAB Direct Credit Service (AU)</strong></p></td>
</tr>
</tbody>
</table>


Use the **Methods of payment - vendors** form to set up a method of payment that uses one of the file formats mentioned in the preceding table to make electronic payments.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a method of payment.

3.  In the **Method of payment** field, enter a unique identification code for the payment format.

4.  In the **Payment type** field, select **Electronic payment**.

5.  On the **File formats** FastTab, in the **Export format** field, select a file format.
    

    > [!NOTE]
    > <P>If the file formats are not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move the file format to use with the method of payment from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list, and then close the form.</P>



## See also

[Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\))

  


