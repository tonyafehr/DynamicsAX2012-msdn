﻿---
title: ReleaseUpdateDB60_Vend.createPurchTable_BR Upgrade Script
TOCTitle: ReleaseUpdateDB60_Vend.createPurchTable_BR Upgrade Script
ms:assetid: 4aa7d963-27d9-b715-b2a3-6378367f4702
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685376(v=AX.60)
ms:contentKeyID: 49708106
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateDB60\_Vend.createPurchTable\_BR Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateDB60_Vend</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>createPurchTable_BR</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Migrates Brazil country specific fields from the &lt;c&gt;PurchTable&lt;/c&gt; table to &lt;c&gt;PurchTable_BR&lt;/c&gt; table</p></td>
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
<td><p>Accounts payable</p></td>
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
<td><p>PurchTable</p></td>
</tr>
<tr class="even">
<td><p>PurchTable_BR</p></td>
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
<th><p>From Table: PurchTable</p></th>
<th><p>To Table: PurchTable_BR</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Authority_BR</p></td>
<td><p>Authority_BR</p></td>
</tr>
<tr class="even">
<td><p>CFPSId</p></td>
<td><p>CFPSId_BR</p></td>
</tr>
<tr class="odd">
<td><p>InvoiceRefRecId_BR</p></td>
<td><p>InvoiceRefRecId_BR</p></td>
</tr>
<tr class="even">
<td><p>RefProcessNo_BR</p></td>
<td><p>RefProcessNo_BR</p></td>
</tr>
<tr class="odd">
<td><p>SalesPurchOperationType_BR</p></td>
<td><p>SalesPurchOperationType_BR</p></td>
</tr>
<tr class="even">
<td><p>ServiceCodeOnDlvAddress</p></td>
<td><p>ServiceCodeOnDlvAddress_BR</p></td>
</tr>
<tr class="odd">
<td><p>TaxDirectImport</p></td>
<td><p>TaxDirectImport_BR</p></td>
</tr>
<tr class="even">
<td><p>VendFinalUser</p></td>
<td><p>VendFinalUser_BR</p></td>
</tr>
</tbody>
</table>

  


