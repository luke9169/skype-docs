---
title: Learn about the connectivity element (ConnectionInfoType complexType) schema C
TOCTitle: Connectivity element
ms:assetid: 21c70c92-1c97-8a75-5f48-3ef96159d556
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404726(v=office.16)
ms:contentKeyID: 68250640
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Learn about the connectivity element (ConnectionInfoType complexType) schema C

(ConnectionInfoType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

(Obsolete) The inclusion of Relay Ip/port indicates that a particular endpoint uses a media relay (edge server) and if not access the remote address directly. It is provided only in QualityUpdate events.

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:string</p></td>
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

    <xs:element name="Connectivity"  type="xs:string" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
<col />
<col />
<col />
</colgroup>
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

