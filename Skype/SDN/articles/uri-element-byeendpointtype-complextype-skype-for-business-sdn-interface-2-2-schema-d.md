---
title: URI element (ByeEndPointType complexType) schema D
TOCTitle: URI element (ByeEndPointType complexType)
description: Information about the URI element (ByeEndPointType complexType) schema D. 
ms:assetid: 53afb829-203a-12fa-bde2-6cd6041c1064
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171019(v=office.16)
ms:contentKeyID: 65855592
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# URI element (ByeEndPointType complexType) schema D

(ByeEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

SIP URI of the user signed in via the endpoint as extracted from the SIP header.. This field is obfuscated unless hidepii is set to false in the Dialog Listener configuration file.


**In this article**  
Element information  
Definition  
Elements and attributes  

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

    <xs:element name="URI"  type="xs:anyURI" minOccurs="0">
    
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
<td><p><a href="endpoint-element-byetype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndPoint</a></p></td>
<td><p><a href="byeendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ByeEndPointType</a></p></td>
<td><p>Endpoint involved in the ended SIP call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

