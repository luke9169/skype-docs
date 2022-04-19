---
title: ResponseCodeType complexType (Schema D)
TOCTitle: ResponseCodeType complexType
ms:assetid: 5e7155e9-7fb2-4e50-e765-e863d1a60596
ms:mtpsurl: https://msdn.microsoft.com/library/Mt171071(v=office.16)
ms:contentKeyID: 65855645
ms.date: 08/24/2015
mtps_version: v=office.16
dev_langs:
- xml
---

# ResponseCodeType complexType (Schema D)

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
<td><p>xs:string</p></td>
</tr>
</tbody>
</table>


## Definition

```xml
      <xs:complexType name="ResponseCodeType">
        <xs:complexContent>
 
        <xs:extension base="xs:string">
      
         <xs:attribute name="Code" type="xs:unsignedShort" use="required"/>
  
        </xs:extension>
 
        </xs:complexContent>
 
      </xs:complexType>
      
```

## Elements and attributes

### Child elements

None.

### Attributes

<table>
<colgroup>
<col />
<col />
<col />
<col />
<col />
</colgroup>
<thead>
<tr class="header">
<th><p>Attribute</p></th>
<th><p>Type</p></th>
<th><p>Required</p></th>
<th><p>Description</p></th>
<th><p>Possible values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Code</p></td>
<td><p>xs:unsignedShort</p></td>
<td><p>required</p></td>
<td><p>SIP error code for this error.</p></td>
<td><p>Values of the xs:unsignedShort type.</p></td>
</tr>
</tbody>
</table>

