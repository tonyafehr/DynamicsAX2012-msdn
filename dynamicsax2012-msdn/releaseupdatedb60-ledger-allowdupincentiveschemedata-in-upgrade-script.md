﻿---
title: ReleaseUpdateDB60_Ledger.allowDupIncentiveSchemeData_IN Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupIncentiveSchemeData_IN Upgrade Script
ms:assetid: f6c28529-2b09-3daa-9cd2-b655ba6b98ed
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ737596(v=AX.60)
ms:contentKeyID: 49712289
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupIncentiveSchemeData\_IN Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

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
<td><p>allowDupIncentiveSchemeData_IN</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the IncentiveSchemeIdx index in the EximIncentiveSchemeData_IN table to allow for duplicate records.</p></td>
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
<td><p>EximIncentiveSchemeData_IN</p></td>
</tr>
</tbody>
</table>


## Remarks

The Incentive scheme group is replaced with the new Reference and EximIncentiveSchemeGroup surrogate key fields in the IncentiveSchemeIdx unique index. Initially the EximIncentiveSchemeGroup field contains no value. So the index is set to allow for duplicates before the field is updated with the value of the record ID fields in the EximIncentiveSchemeGroup\_IN table.

  


