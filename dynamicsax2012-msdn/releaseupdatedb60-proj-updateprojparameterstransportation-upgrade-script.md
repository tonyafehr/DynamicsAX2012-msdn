﻿---
title: ReleaseUpdateDB60_Proj.updateProjParametersTransportation Upgrade Script
TOCTitle: ReleaseUpdateDB60_Proj.updateProjParametersTransportation Upgrade Script
ms:assetid: 5d381b2d-5b02-25de-b6b8-c222be1ac4ec
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ736347(v=AX.60)
ms:contentKeyID: 49708522
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Proj.updateProjParametersTransportation Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>updateProjParametersTransportation</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Updates the TransportationProperties_LT field in the ProjParameters table to the DoPrintTransportationDocument field.</p></td>
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
<td><p>Accounts receivable</p></td>
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
<td><p>ProjParameters</p></td>
</tr>
</tbody>
</table>


## Remarks

The update is handled by the upgrade framework and no upgrade script has been produced.

## Name Changes for Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Old Table Name: ProjParameters</p></th>
<th><p>New Table Name: ProjParameters</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Old Field Name:</p></td>
<td><p>New Field Name:</p></td>
</tr>
<tr class="even">
<td><p>TransportationProperties_LT</p></td>
<td><p>DoPrintTransportationDocument</p></td>
</tr>
</tbody>
</table>

  


