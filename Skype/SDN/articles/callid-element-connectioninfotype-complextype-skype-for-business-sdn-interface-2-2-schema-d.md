---
title: CallId element (ConnectionInfoType complexType) (Schema D)
TOCTitle: CallId element
ms:assetid: 82c8c8cf-0b08-daae-838a-1cc8d0d6fd29
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149440(v=office.16)
ms:contentKeyID: 65855388
description: Unique identifier for the SIP call. This field is used to correlate messages referring to the same call.
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# CallId element (Schema D)

(ConnectionInfoType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Unique identifier for the SIP call. This field should be used to correlate messages referring to the same call.

## Element information

<table>

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
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="CallId"  type="xs:string">
    
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
<td><p><a href="connectioninfo-element-messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ConnectionInfo</a></p></td>
<td><p><a href="connectioninfotype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ConnectionInfoType</a></p></td>
<td><p>Connection-related properties regardless of the media stream and end points.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

