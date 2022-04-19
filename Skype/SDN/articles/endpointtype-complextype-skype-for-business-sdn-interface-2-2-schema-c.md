---
title: EndPointType complexType (Schema C)
TOCTitle: EndPointType complexType
ms:assetid: dadd849f-7969-80b7-9753-5e70029ab597
ms:mtpsurl: https://msdn.microsoft.com/library/Mt429353(v=office.16)
ms:contentKeyID: 68250795
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# EndPointType complexType (Schema C)

(Skype for Business SDN Interface 2.2, Schema "C")

**In this article**  
Type information  
Definition  
Elements and attributes  

## Type information

<table>
<colgroup>
<col />
<col />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Namespace</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Schema file</strong></p></td>
<td><p>SDNInterface.Schema.C.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="EndPointType">
      </xs:complexType>
      
```

## Elements and attributes

### Child elements

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
<td><p><a href="contact-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Contact</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user as extracted from the Contact header of the underlying SIP message. This field is obfuscated unless hidepii is set to false in the DialogListener configuration file.</p></td>
</tr>
<tr class="even">
<td><p><a href="epid-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">EPId</a></p></td>
<td><p>xs:string</p></td>
<td><p>Endpoint Id of the endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="eptype-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">EPType</a></p></td>
<td><p>xs:string</p></td>
<td><p>Indicates that this endpoint is of the Skype for Business Room System type or not.</p></td>
</tr>
<tr class="even">
<td><p><a href="id-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Id</a></p></td>
<td><p>xs:string</p></td>
<td><p>Identifier of the endpoint.</p></td>
</tr>
<tr class="odd">
<td><p><a href="incallenabled-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">IncallEnabled</a></p></td>
<td><p>xs:boolean</p></td>
<td><p>Whether the endpoint (Skype for Business client) is capable to send incall quality update messages. This flag does not indicate whether the client is configured to send incall QoE reports.</p></td>
</tr>
<tr class="even">
<td><p><a href="ip-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">IP</a></p></td>
<td><p>xs:string</p></td>
<td><p>IP address of the the media stream source or destination.</p></td>
</tr>
<tr class="odd">
<td><p><a href="port-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Port</a></p></td>
<td><p>xs:unsignedInt</p></td>
<td><p>Port number of the destination or source of the media stream used by this endpoint.</p></td>
</tr>
<tr class="even">
<td><p><a href="reflexiveip-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ReflexiveIP</a></p></td>
<td><p>Not defined</p></td>
<td><p>IP used outside of the NAT.</p></td>
</tr>
<tr class="odd">
<td><p><a href="reflexiveport-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">ReflexivePort</a></p></td>
<td><p>Not defined</p></td>
<td><p>Port used on the NAT.</p></td>
</tr>
<tr class="even">
<td><p><a href="relay-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">Relay</a></p></td>
<td><p>Not defined</p></td>
<td><p>IP Address of the first relay used in the media traffic.</p></td>
</tr>
<tr class="odd">
<td><p><a href="relayport-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">RelayPort</a></p></td>
<td><p>Not defined</p></td>
<td><p>Port number of the relay.</p></td>
</tr>
<tr class="even">
<td><p><a href="uri-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">URI</a></p></td>
<td><p>xs:anyURI</p></td>
<td><p>SIP URI of the user signed in via the endpoint as extracted from the SIP header.. This field is obfuscated unless hidepii is set to false in the DialogListener configuration file.</p></td>
</tr>
<tr class="odd">
<td><p><a href="useragent-element-endpointtype-complextype-skype-for-business-sdn-interface-2-2-schema-c.md">UserAgent</a></p></td>
<td><p>xs:string</p></td>
<td><p>Skype for Business client name and version.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

