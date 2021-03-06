﻿---
title: ReleaseUpdateDB60_Ledger.allowDupLedgerGDPdUFieldFieldNameIdx
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupLedgerGDPdUFieldFieldNameIdx
ms:assetid: 3708c3b8-4ab8-e8e6-15b1-97953a26a1dc
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685180(v=AX.60)
ms:contentKeyID: 49707632
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupLedgerGDPdUFieldFieldNameIdx 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Ledger</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>allowDupLedgerGDPdUFieldFieldNameIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the index &lt;c&gt;FieldNameIdx&lt;/c&gt; in the table &lt;c&gt;LedgerGDPdUField&lt;/c&gt; to allow duplicate records.</p></td>
</tr>
</tbody>
</table>


## Affected Modules and Tables

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Modules</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Ledger</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Affected Tables</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>LedgerGDPdUField</p></td>
</tr>
</tbody>
</table>


## Remarks

The GDPdUGroupId field is replaced with the new surrogate key field LedgerGDPdUTable in the unique index FieldNameIdx. Initially this field contains no value. So the index is set to allow duplicates before the field is updated with the value of the RecId field of the table LedgerGDPdUTable.

  


