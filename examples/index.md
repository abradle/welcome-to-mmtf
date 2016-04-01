---
layout: page
---

This example gives a quick overview of the MMTF RESTful API  

PDB structures in MMTF format are exposed to programmatically access via an URL such as:
<http://mmtf.rcsb.org/full/4cup> - to get the structure with all atoms <br/>   
<http://mmtf.rcsb.org/reduced/4cup> - to get only Ca atoms <br/>   

This will return Uint8Array containing an encoded structure as a msgpack bin.
Decode and access the structural data from the decoded mmtf object:

```javascript
var mmtfObject = decodeMmtf( bin );
var structure = new SimpleStructure( mmtfObject );
```
