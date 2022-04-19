---
title: CSEQ element (ConnectionInfoType complexType) (Schema C)
TOCTitle: CSEQ element
ms:assetid: 41a5392e-80d7-faa9-74a6-270bb6e23bf5
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404736(v=office.16)
ms:contentKeyID: 68250649
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# CSEQ element (ConnectionInfoType complexType) (Schema C)

(ConnectionInfoType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Call sequence number as part of SIP standard that needs to be used to filter for unrelated error messages. This field is not provided for QualityUpdates. 

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

    <xs:element name="CSEQ"  type="xs:string" minOccurs="0">
    
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

