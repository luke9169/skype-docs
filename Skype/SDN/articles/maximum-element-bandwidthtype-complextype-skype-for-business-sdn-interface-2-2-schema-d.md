---
title: Maximum element (BandwidthType complexType) (Schema D)
TOCTitle: Maximum element
ms:assetid: a989552a-972f-ab92-daa7-a914b9abf6b0
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170915(v=office.16)
ms:contentKeyID: 65855490
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Maximum element (Schema D)

(BandwidthType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

Estimated upper limit of the bandwidth needed by this stream.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>

<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p>xs:long</p></td>
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

    <xs:element name="Maximum"  type="xs:long" minOccurs="0">
    
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
<td><p><a href="bandwidth-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Bandwidth</a></p></td>
<td><p><a href="bandwidthtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">BandwidthType</a></p></td>
<td><p>Describes the maximum and average amount of bandwidth needed by this stream. It takes the possible codecs and stream multiplexing into account.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

