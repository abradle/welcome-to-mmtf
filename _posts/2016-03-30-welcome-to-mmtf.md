---
layout: post
date:   2016-04-01
---

## What is MMTF?

The **M**acro**m**olecular **T**ransmission **F**ormat (MMTF) is a new compact binary format to transmit and store biomolecular structural data quickly and accurately.  

#### What are the benefits of using structures in MMTF?

* **Small:** the entire PDB can be stored in less than 7GB. Meaning it can fit into RAM on a Desktop machine.
* **Fast:** the viral capsid (PDB code: 3J3Q) can be loaded and parsed in seconds in a web-broweser
* **Useful:** a simple, well documented API to the data is provided. Further, the format is extensible and contains the information required to understand the structure (e.g. bonding information).

#### How can I use MMTF?

* For visualization and interactive analysis of large PDB structures:  

![usecase1]({{ site.url }}/assets/1.png)  

<br />

* For large-scale structural calculations such as geometric queries or structural comparisons over the entire PDB archive:  

![usecase2]({{ site.url }}/assets/2.png)

#### How do I start?

* Review the [specification] [spec]
* Access a PDB structure in MMTF [using RESTful API] [apiexamples]
* Work through [examples] [readme]
* Explore the source code:  
 -- [java]  
 -- [javascript]  

### Development

Want to contribute? Great!  

Fork us: git@github.com:rcsb/mmtf-java.git  
Go to GitHub to [report bugs] [github]  

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
   [apiexamples]: <https://github.com/rcsb/mmtf-javascript/#api>
