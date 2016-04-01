---
layout: post
date:   2016-03-30 13:30:09 -0700
categories: jekyll update
---

#### What is MMTF?

The **M**acro**m**olecular **T**ransmission **F**ormat (MMTF) is a compact binary format to represent biomolecular structures from Protein Data Bank (PDB). It holds the sequence information, atomic coordinates, bonds, biological assembly information, secondary structure and auxiliary metadata. The format is optimized for efficient transmission over the Internet and demonstrate fast speed of decoding and parsing. In addition, the format aims to be easy to understand, use and integrate into development projects that will facilitate its dissemination.

#### What are the benefits of using structures in MMTF?

* **Speed:** efficient access to PDB structures over the Internet for laptop/desktop and mobile applications.
* **Compactness:** small size reduces your bandwidth needs and allows in memory management of large structures enabling interactive visualization and helping to overcome the storage-based performance bottleneck in large-scale structural bioinformatics analysis.
* **Utility:** it has a simple API, open source libraries and good documentation that makes it easy to integrate into your molecular visualization or structural analysis applications; it contains precalculated information such as secondary structure, number and order of chemical bonds useful in various analysis; it is easily extendable to include custom fields that makes it ...

#### How can I use MMTF?

#### How do I start?

* Review the [specification] [spec]
* Explore java [source code] [java]
* Work through [JAVA examples] [readme]
* Download structures in MMTF as a [hadoop sequence file] [hadoopfile]
* Look at examples of how to use a [RESTful API] [apiexamples]

### Development

Want to contribute? Great!  

Get a copy of a Git repository to make changes: git@github.com:rcsb/mmtf-java.git  
Go to GitHub to [report bugs] [github]  
[Contact us] [mailinglist]

### Founding

This project is supported by NIH BD2K Award 1 U01 CA198942-01

License
----
Apache License, Version 2.0

   [github]: <https://github.com/rcsb/mmtf/>
   [java]: <https://github.com/rcsb/mmtf-java>
   [javascript]: https://github.com/rcsb/mmtf-javascript
   [git-repo-url]: <git@github.com:rcsb/mmtf-java.git>
   [readme]: <https://github.com/rcsb/mmtf-java/blob/master/README.md>
   [spec]: <https://github.com/rcsb/mmtf/blob/master/spec.md>
   [apiexamples]: <>
   [hadoopfile]: <>
   [mailinglist]: <>
