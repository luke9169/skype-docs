---
title: StartPropertiesType complexType (Schema D)
TOCTitle: StartPropertiesType complexType
ms:assetid: 963421e3-524b-0997-ce67-04875aafa72c
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171074(v=office.16)
ms:contentKeyID: 65855647
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# StartPropertiesType complexType (Schema D)

(Skype for Business SDN Interface 2.2, Schema "D")


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
<td><p>SDNInterface.Schema.D.XSD</p></td>
</tr>
<tr class="odd">
<td><p><strong>Extension base</strong></p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="StartPropertiesType">
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
<td><p><a href="bandwidth-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Bandwidth</a></p></td>
<td><p><a href="bandwidthtype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">BandwidthType</a></p></td>
<td><p>Describes the maximum and average amount of bandwidth needed by this stream. It takes the possible codecs and stream multiplexing into account.</p></td>
</tr>
<tr class="even">
<td><p><a href="codec-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Codec</a></p></td>
<td><p><a href="codectype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">CodecType</a></p></td>
<td><p>Codec and estimates for the bandwidth that the codecs will use. This list contains all codecs that are agreed upon by the two endpoints. Both end-points may decide to switch among these codecs at any time (without additional signalling).</p></td>
</tr>
<tr class="odd">
<td><p><a href="protocol-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Protocol</a></p></td>
<td><p><a href="protocoltypes-simpletype-skype-for-business-sdn-interface-2-2-schema-d.md">ProtocolTypes</a></p></td>
<td><p>Transmission protocol of the media stream such as TCP or UDP.</p></td>
</tr>
<tr class="even">
<td><p><a href="referredby-element-startpropertiestype-complextype-skype-sdn-2-2-d.md">ReferredBy</a></p></td>
<td><p>xs:string</p></td>
<td><p>Content of the REFERRED BY SIP tag.</p></td>
</tr>
<tr class="odd">
<td><p><a href="replaces-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Replaces</a></p></td>
<td><p>xs:string</p></td>
<td><p>Content of the REPLACES SIP tag.</p></td>
</tr>
<tr class="even">
<td><p><a href="via-element-startpropertiestype-complextype-skype-for-business-sdn-interface-2-2-schema-d.md">Via</a></p></td>
<td><p>xs:string</p></td>
<td><p>Content of the VIA SIP tags.</p></td>
</tr>
</tbody>
</table>


### Attributes

None.

