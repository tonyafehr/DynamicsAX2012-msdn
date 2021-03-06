﻿---
title: ReleaseUpdateDB60_Ledger.updateMainAcctControlTaxCode Upgrade Script
TOCTitle: ReleaseUpdateDB60_Ledger.updateMainAcctControlTaxCode Upgrade Script
ms:assetid: e8506afb-4d3e-35f1-7edf-ffa0c165034e
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ719840(v=AX.60)
ms:contentKeyID: 49711913
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Ledger.updateMainAcctControlTaxCode Upgrade Script 


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
<td><p>updateMainAcctControlTaxCode</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Populates the MainAccountControlTaxCode table.</p></td>
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
<td><p>MainAccountControlTaxCode</p></td>
</tr>
<tr class="even">
<td><p>DEL_LedgerControlTaxCode</p></td>
</tr>
</tbody>
</table>


## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: DEL_LedgerControlTaxCode</p></th>
<th><p>To Table: MainAccountControlTaxCode</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>TaxCode</p></td>
<td><p>TaxCode</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: MainAccount</p></th>
<th><p>To Table: MainAccountControlTaxCode</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RecId</p></td>
<td><p>MainAccount</p></td>
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
<td><p>MainAccountControlTaxCode</p></td>
<td><p></p></td>
<td><p></p></td>
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
<td><p>DEL_LedgerControlTaxCode</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


