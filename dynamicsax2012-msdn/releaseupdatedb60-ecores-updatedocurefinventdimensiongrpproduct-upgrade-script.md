﻿---
title: ReleaseUpdateDB60_EcoRes.updateDocuRefInventDimensionGrpProduct Upgrade Script
TOCTitle: ReleaseUpdateDB60_EcoRes.updateDocuRefInventDimensionGrpProduct Upgrade Script
ms:assetid: 30782f1b-2471-13d9-9743-506e7c7df9f5
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736063(v=AX.60)
ms:contentKeyID: 49707477
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_EcoRes.updateDocuRefInventDimensionGrpProduct Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_EcoRes</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateDocuRefInventDimensionGrpProduct</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates records in the DocuRef table that are related to the InventDimGroup and InventDimSetup tables. The records will be updated to relate to the EcoResProductDimensionGroup and EcoResProductDimensionGroupFldSetup records.</p></td>
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
<td><p>Product management</p></td>
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
<td><p>DocuRef</p></td>
</tr>
<tr class="even">
<td><p>DEL_InventDimSetup</p></td>
</tr>
<tr class="odd">
<td><p>DEL_EcoResDimGroupUpgrade</p></td>
</tr>
<tr class="even">
<td><p>EcoResProductDimensionGroup</p></td>
</tr>
<tr class="odd">
<td><p>EcoResProductDimensionGroupFldSetup</p></td>
</tr>
</tbody>
</table>

  


