﻿---
title: ReleaseUpdateTransformDB50_Proj.ProjInvoiceJourPIJPrintDeltaPreUpgrade Upgrade Script
TOCTitle: ReleaseUpdateTransformDB50_Proj.ProjInvoiceJourPIJPrintDeltaPreUpgrade Upgrade Script
ms:assetid: 05645e7e-2be3-1005-ffc8-073ed2dade39
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ684717(v=AX.60)
ms:contentKeyID: 49706413
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransformDB50\_Proj.ProjInvoiceJourPIJPrintDeltaPreUpgrade Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransformDB50_Proj</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>ProjInvoiceJourPIJPrintDeltaPreUpgrade</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>This script is used for saving information about project invoice printing in the &lt;c&gt;ProjInvoiceJourPrint&lt;/c&gt; table. This feature is specific to Hungary.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Preprocessing 60: Delta</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ax Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2009</p></td>
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
<td><p>Project</p></td>
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
<td><p>ProjInvoiceJourPrint</p></td>
</tr>
</tbody>
</table>


## Remarks

This script creates new \<c\>ProjInvoiceJourPrint\</c\> records for every \<c\>ProjInvoiceJour\</c\> record. It copies the value of the \<c\>CopiesPrinted\_HU\</c\> and \<c\>Printed\_HU\</c\> fields from the \<c\>ProjInvoiceJour\</c\> table to \<c\>ProjInvoiceJourPrint\</c\> table.

## Data Migration Section

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>From Table: ProjInvoiceJour</p></th>
<th><p>To Table: ProjInvoiceJourPrint</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CopiesPrinted_HU</p></td>
<td><p>NumberOfCopiesPrinted</p></td>
</tr>
<tr class="even">
<td><p>Printed_HU</p></td>
<td><p>HasOriginalBeenPrinted</p></td>
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
<td><p>ProjInvoiceJourPrint</p></td>
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
<td><p>ProjInvoiceJour</p></td>
<td><p>CopiesPrinted_HU</p></td>
</tr>
<tr class="even">
<td><p>ProjInvoiceJour</p></td>
<td><p>Printed_HU</p></td>
</tr>
</tbody>
</table>

  


