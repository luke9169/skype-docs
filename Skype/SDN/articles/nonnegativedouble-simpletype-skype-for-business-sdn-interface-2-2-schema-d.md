---
title: NonNegativeDouble simpleType 
TOCTitle: NonNegativeDouble simpleType
ms:assetid: 2064bd04-273e-df5d-c7b7-9f55c1c62a41
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171049(v=office.16)
ms:contentKeyID: 65855623
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# NonNegativeDouble simpleType 

(Skype for Business SDN Interface 2.2, Schema "D")


## Type information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Base type</strong></p></td>
<td><p>xs:double</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
    <xs:simpleType  name="NonNegativeDouble">
    
      <xs:restriction base="xs:double">
    
      <xs:minInclusive value="0"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

