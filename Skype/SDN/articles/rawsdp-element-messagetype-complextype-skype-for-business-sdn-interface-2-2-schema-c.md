---
title: RawSDP element (MessageType complexType) (Schema C)
TOCTitle: RawSDP element
ms:assetid: e26c05ef-e809-02db-70ab-97b552488be0
ms:mtpsurl: https://msdn.microsoft.com/library/Mt404821(v=office.16)
ms:contentKeyID: 68250733
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# RawSDP element (Schema C)

(MessageType complexType) (Skype for Business SDN Interface 2.2, Schema "C")

Raw Session Description Protocol (SDP) data that is included as the payload of the underlying SIP messages of the Invite, LRSInvite and StartOrUpdate type, if the sendrawsdp entry is set to True in the DialogListener configuration file.

**In this article**  
Element information  
Definition  
Elements and attributes  

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
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
</tbody>
</table>


## Definition

```xml

    <xs:element name="RawSDP"  type="xs:string" minOccurs="0">
    
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
<td><p><a href="lyncdiagnostics-element-skype-for-business-sdn-interface-2-2-schema-c.md">LyncDiagnostics</a></p></td>
<td><p><a href="messagetype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">MessageType</a></p></td>
<td><p>The root element for output from the Skype for Business SDN Manager.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

