---
title: Relay element (ByeEndPointType complexType) 
TOCTitle: Relay element (ByeEndPointType complexType)
ms:assetid: 2aa217f7-eff3-d4d5-efcd-24ebc0c06459
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170976(v=office.16)
ms:contentKeyID: 65855550
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# Relay element Schema D

(ByeEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

IP Address of the first relay used in the media traffic.


**In this article**  
Element information  
Definition  
Elements and attributes  

## Element information

<table>
<tbody>
<tr class="odd">
<td><p><strong>Element type</strong></p></td>
<td><p><a href="ipaddresspattern-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ipAddressPattern</a></p></td>
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

    <xs:element name="Relay"  type="ipAddressPattern" minOccurs="0">
    
    </xs:element>
  
```

## Elements and attributes

### Parent elements

<table>
<colgroup>
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

