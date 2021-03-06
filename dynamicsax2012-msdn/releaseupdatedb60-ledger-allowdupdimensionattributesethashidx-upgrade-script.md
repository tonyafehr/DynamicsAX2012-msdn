﻿---
title: ReleaseUpdateDB60_Ledger.allowDupDimensionAttributeSetHashIdx Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.allowDupDimensionAttributeSetHashIdx Upgrade Script
ms:assetid: a316c743-b3ef-c705-8ef6-60456f68a6b9
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736785(v=AX.60)
ms:contentKeyID: 49710216
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.allowDupDimensionAttributeSetHashIdx Upgrade Script 


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
<td><p>allowDupDimensionAttributeSetHashIdx</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the HashIdx index in the DimensionAttributeSet table to allow for duplicate records.</p></td>
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
<td><p>DimensionAttributeSet</p></td>
</tr>
</tbody>
</table>


## Remarks

Initially this field contains no value. So the index is set to allow duplicates before the field is updated with the value of the hash fields in the DimensionAttributeSet table.

  


