﻿---
title: ReleaseUpdateTransformDB40_Prod2.prodRouteTransDeltaPreUpgradeProcess Upgrade Script
TOCTitle: ReleaseUpdateTransformDB40_Prod2.prodRouteTransDeltaPreUpgradeProcess Upgrade Script
ms:assetid: 34283cc7-f8a7-2862-9d1a-f0489cd78c6f
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685121(v=AX.60)
ms:contentKeyID: 49707574
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB40\_Prod2.prodRouteTransDeltaPreUpgradeProcess Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB40_Prod2</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>prodRouteTransDeltaPreUpgradeProcess</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Transforms data from the old account and dimension fields to the new account and dimension fields in the ProdRouteTrans table.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Delta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX Source</strong></p></td>
<td><p>Microsoft Dynamics AX 4.0</p></td>
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
<td><p>Manufacture</p></td>
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
<td><p>ProdRouteTrans</p></td>
</tr>
</tbody>
</table>


## Remarks

This upgrade is required in order to convert account and dimension data to the new accounts and dimension model for Microsoft Dynamics AX 2012.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: ProdRouteTrans</p></th>
<th><p>To Table: ProdRouteTrans</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AccountCalcIssue</p></td>
<td><p>IssueLedgerDimension</p></td>
</tr>
<tr class="even">
<td><p>AccountCalcIssueOffset</p></td>
<td><p>IssueOffsetLedgerDimension</p></td>
</tr>
<tr class="odd">
<td><p>AccountWIPIssue</p></td>
<td><p>WIPIssueLedgerDimension</p></td>
</tr>
<tr class="even">
<td><p>AccountWIPValuation</p></td>
<td><p>WIPValuationLedgerDimension</p></td>
</tr>
<tr class="odd">
<td><p>Dimension</p></td>
<td><p>DefaultDimension</p></td>
</tr>
</tbody>
</table>


## New Tables or Fields

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
<th><p>Extended Data Type</p>
<p>-or- Base Enum</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>IssueLedgerDimension</p></td>
<td><p>LedgerDimensionDefaultAccount</p></td>
</tr>
<tr class="even">
<td><p>ProdRouteTrans</p></td>
<td><p>IssueOffsetLedgerDimension</p></td>
<td><p>LedgerDimensionDefaultAccount</p></td>
</tr>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>WIPIssueLedgerDimension</p></td>
<td><p>LedgerDimensionDefaultAccount</p></td>
</tr>
<tr class="even">
<td><p>ProdRouteTrans</p></td>
<td><p>WIPValuationLedgerDimension</p></td>
<td><p>LedgerDimensionDefaultAccount</p></td>
</tr>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>DefaultDimension</p></td>
<td><p>DimensionDefault</p></td>
</tr>
</tbody>
</table>


## Deleted Tables or Fields

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table</p></th>
<th><p>Field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>AccountCalcIssue</p></td>
</tr>
<tr class="even">
<td><p>ProdRouteTrans</p></td>
<td><p>AccountCalcIssueOffset</p></td>
</tr>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>AccountWIPIssue</p></td>
</tr>
<tr class="even">
<td><p>ProdRouteTrans</p></td>
<td><p>AccountWIPValuation</p></td>
</tr>
<tr class="odd">
<td><p>ProdRouteTrans</p></td>
<td><p>Dimension</p></td>
</tr>
</tbody>
</table>

  


