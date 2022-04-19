---
title: Learn about the ConferenceURI element (ConnectionInfoType complexType) schema D
TOCTitle: ConferenceURI element
ms:assetid: 9df0b395-0489-b03e-2b31-b97da484d7d9
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149448(v=office.16)
ms:contentKeyID: 65855395
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Learn about the ConferenceURI element (ConnectionInfoType complexType) schema D

(ConnectionInfoType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

(Deprecated - use ConferenceId instead) Sip URI used for the conference. This field is obfuscated unless hidepii is set to false in configuration.

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:anyURI</p></td>
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

    <xs:element name="ConferenceURI"  type="xs:anyURI" minOccurs="0">
    
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

