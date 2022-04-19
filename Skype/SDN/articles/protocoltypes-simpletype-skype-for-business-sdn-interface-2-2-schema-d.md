---
title: ProtocolTypes simpleType 
TOCTitle: ProtocolTypes simpleType
ms:assetid: 45c7a603-1559-14bb-32f5-17a93e5e9b49
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171053(v=office.16)
ms:contentKeyID: 65855626
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ProtocolTypes simpleType 

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
<td><p>xs:string</p></td>
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
    <xs:simpleType  name="ProtocolTypes">
    
      <xs:restriction base="xs:string">
    
      <xs:enumeration value="UDP"/>
    
      <xs:enumeration value="tcp-pass"/>
    
      <xs:enumeration value="TCP-PASS"/>
    
      <xs:enumeration value="tcp-act"/>
    
      <xs:enumeration value="TCP-ACT"/>
    
      </xs:restriction>
      
    </xs:simpleType>
  
```

