﻿---
title: ReleaseUpdateDB60_Ledger.allowDupExciseNumSequenceRef_INExciseNum Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupExciseNumSequenceRef_INExciseNum Upgrade Script
ms:assetid: edf49168-118a-6540-749a-e0bddba2cb10
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719953(v=AX.60)
ms:contentKeyID: 49712025
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupExciseNumSequenceRef\_INExciseNum Upgrade Script 


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
<td><p>allowDupExciseNumSequenceRef_INExciseNum</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the ExciseNumRefIdx index in the ExciseNumSequenceRef_IN table to allow duplicate records.</p></td>
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
<td><p>General ledger</p></td>
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
<td><p>EXCISENUMSEQUENCEREF_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The RegistrationNumber field is replaced with the new Reference and TaxRegistrationNumberTable surrogate key field in the unique ExciseNumRefIdx index. Initially the TaxRegistrationNumberTable field contains no value. So the index is set to allow duplicates before the field is updated with the value of the RecId fields of the TaxRegistrationNumberTable\_IN table.

  


