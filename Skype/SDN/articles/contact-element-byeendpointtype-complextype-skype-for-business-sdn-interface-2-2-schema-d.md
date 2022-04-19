---
title: Contact element (ByeEndPointType complexType) (Schema D)
TOCTitle: Contact element (ByeEndPointType complexType)
ms:assetid: 9a724a72-cf75-d6a3-0ebf-65ef1eaead83
ms:mtpsurl: https://msdn.microsoft.com/library/Mt149451(v=office.16)
ms:contentKeyID: 65855398
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Contact element (ByeEndPointType complexType) (Schema D)

(ByeEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

SIP URI of the user as extracted from the Contact header of the underlying SIP message. This field is obfuscated unless hidepii is set to false in the Dialog Listener configuration file.

## Element information

<table>
<colgroup>
<col />
<col />
</colgroup>
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

    <xs:element name="Contact"  type="xs:anyURI" minOccurs="0">
    
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

