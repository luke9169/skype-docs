---
title: ReflexiveIP element (ErrorEndPointType complexType) 
TOCTitle: ReflexiveIP element (ErrorEndPointType complexType)
ms:assetid: ad668abe-8550-8a6a-3f88-e55d735a0019
ms:mtpsurl: https://msdn.microsoft.com/library/Mt170964(v=office.16)
ms:contentKeyID: 65855538
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ReflexiveIP element Schema D

(ErrorEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")

IP used outside of the NAT.


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

    <xs:element name="ReflexiveIP"  type="ipAddressPattern" minOccurs="0">
    
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
<td><p><a href="endpoint-element-errortype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">EndPoint</a></p></td>
<td><p><a href="errorendpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">ErrorEndPointType</a></p></td>
<td><p>Endpoint involved in the ended SIP call.</p></td>
</tr>
</tbody>
</table>


### Child elements

None.

### Attributes

None.

