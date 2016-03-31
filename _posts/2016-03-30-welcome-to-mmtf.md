---
layout: post
date:   2016-03-30 13:30:09 -0700
categories: jekyll update
---

# MMTF: a new transmission format for biological molecules

#### What is MMTF?

The **M**acro**m**olecular **T**ransmission **F**ormat (MMTF) is a binary format to represent biomolecular structures. It holds the sequence information, atomic coordinates, topological descriptions, assosiated data such as number and order of chemical bonds, and axilary metadata. The format is optimised for efficient transmission over the Internet and fast decoding/parsing speed. In addition, the format aims to be easy to understand, use and integrate into development praojects that will facilitate its dissemination.

#### What are the benefits of transmitting structures in MMTF?

* **Speed:** efficient transmission of structures between memory and storage devices and over the Internet as well as fast decoding and parsing speed helps your application to load faster.
* **Compactness:** small size reduces your bandwidth needs and allows in memory management of large structures enabling interactive visualization and helping to overcome the storage-based performance bottleneck in large-scale structural bioinformatics analysis.
* **Utility:** it contains precalculates information such as secondary structure and chemical bonds that is useful in various analysis; it is easily extendable to include custom fields; it has a clear API, open source libraries and good documentation that makes it easy to use and enhances interoperability.

#### How do I start?
* Go through the [specification] [spec]
* Explore java [source code] [java]
* Work through [JAVA examples] [readme]
* Download structures in MMTF as a [hadoop sequence file] [hadoopfile]
* Look at examples of how to use a [RESTful API] [apiexamples]

### Development

Want to contribute? Great!  
Get a copy of a Git repository to make changes: git@github.com:rcsb/mmtf-java.git 
Go to GitHub to [report bugs] [github]  
[Contact us] [mailinglist] 

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
