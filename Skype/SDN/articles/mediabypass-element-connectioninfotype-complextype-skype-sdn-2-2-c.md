---
title: MediaBypass element (ConnectionInfoType complexType) (Schema C)
TOCTitle: MediaBypass element
ms:assetid: e7fad1d2-57f1-97b9-fc6e-dca35c59f299
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404791(v=office.16)
ms:contentKeyID: 68250701
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# MediaBypass element (Schema C)

(ConnectionInfoType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Denotes media bypass. It is provided only in QualityUpdate message when mediabypass was part of the call.

**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:boolean</p></td>
</tr>
<tr class="even">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="MediaBypass"  type="xs:boolean" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>

<thead>
<tr class="header">
<th><p>Element</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="connectioninfo-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ConnectionInfo</a></p></td>
<td><p><a href="connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ConnectionInfoType</a></p></td>
<td><p>Connection-related properties regardless of the media stream and end points.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

