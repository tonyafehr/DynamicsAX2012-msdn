﻿---
title: ReleaseUpdateTransform40_InventPurchAcc.validateMissingLedgerJournalName Upgrade Script
TOCTitle: ReleaseUpdateTransform40_InventPurchAcc.validateMissingLedgerJournalName Upgrade Script
ms:assetid: 50db2d71-c70e-1b2f-6fe3-4987a0780f31
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/JJ685532(v=AX.60)
ms:contentKeyID: 49708235
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ReleaseUpdateTransform40\_InventPurchAcc.validateMissingLedgerJournalName Upgrade Script 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Class</strong></p></td>
<td><p>ReleaseUpdateTransform40_InventPurchAcc</p></td>
</tr>
<tr class="even">
<td><p><strong>Method</strong></p></td>
<td><p>validateMissingLedgerJournalName</p></td>
</tr>
<tr class="odd">
<td><p><strong>Description</strong></p></td>
<td><p>Verifies that the LedgerJournalName table record with a continuous number sequence exists.</p></td>
</tr>
<tr class="even">
<td><p><strong>Script Type</strong></p></td>
<td><p>Upgrade readiness scripts</p></td>
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
<td><p>Cost accounting</p></td>
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
<td><p>LedgerJournalName</p></td>
</tr>
<tr class="even">
<td><p>NumberSequenceTable</p></td>
</tr>
</tbody>
</table>


<table xmlns="http://www.w3.org/1999/xhtml">
              <tr><th colspan="2">
		
   <p>
   
	 Validation Issues
  </p>
  </th></tr>
              <tr><td>
		
   <p>
   
	 
            Validation Issues Description
          
  </p>
  </td><td>
		
   <p>
   
	 There should be a ledger journal name with a continuous number sequence associated.
  </p>
  </td></tr>
              <tr><td>
		
   <p>
   
	 
            Checked Conditions
          
  </p>
  </td><td>
		
   <p>
   
	 The existence of a ledger journal name with a continuous number sequence associated is validated.
  </p>
  </td></tr>
              <tr><td>
		
   <p>
   
	 
            Mitigation/How-to-fix
          
  </p>
  </td><td>
		
   <p>
   
	 Run missing ledger journal name correction job.
  </p>
  </td></tr>
            </table>

  


