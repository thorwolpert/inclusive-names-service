# Techniques for Dealing with Unicode Data
This repository includes code and tips that will be useful to systems developers and maintainers who need to ensure that their computer systems can properly input, store, process, and display/export Unicode characters.

### Programming Languages
Some older programming languages assume an equivalence between characters and bytes (i.e., one character requires exactly one byte of storage). With these languages, handling multi-byte or variable length encodings such as UTF-8 requires special libraries or techniques. The following link provides the details.

[Programming Languages](.\programming_languages\README.md)

### Database Management Systems
Systems that process Unicode data and use database management systems (DBMS) need to have those DBMS's configured to store data using a Unicode encoding. The following link provides guidance for configuring a DBMS to use the UTF-8 encoding.

[Databases](.\databases\README.md)

### Some Test Data
The following link points to a directory containing data files that have Unicode data.

[Test Data](.\test_data\README.md)

### File Formats
This section provides guidance on handling Unicode data using various file formats (e.g., CSV, Excel)

[File Formats](.\file_formats\README.md)

### Data Transfer Protocols
This section provides guidance on handling Unicode data when using various data transfer protocols (e.g., ftp)
[Data Transfer Protocols](.\data_transfer_protocols\README.md)

### Data Flow Analysis Primer and Example
This section introduces the subject of data flow analysis, which can be used to evaluate whether a particular system might encounter issues when working with Unicode data.

[Data Flow Analysis](.\data_flow_analysis\README.md)

### How to Learn More

#### Some excellent articles:

[W3C Internationalization Working Group Blog](https://www.w3.org/blog/international/)

"The W3C Internationalization (I18n) Activity works with W3C working groups and liaises with other organizations to make it possible to use Web technologies with different languages, scripts, and cultures. From this page you can find articles and other resources about Web internationalization, and information about the groups that make up the Activity. "


[Migrating to Unicode](https://www.w3.org/International/articles/unicode-migration/)

This is a comprehensive article from W3C, covering many of the issues that one will find when adapting an existing system to work with Unicode data.

[The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](http://www.joelonsoftware.com/articles/Unicode.html)

The author says: "In this article I'll fill you in on exactly what _every working programmer_ should know. All that stuff about "plain text = ascii = characters are 8 bits" is not only wrong, it's hopelessly wrong, and if you're still programming that way, you're not much better than a medical doctor who doesn't believe in germs. Please do not write another line of code until you finish reading this article."

[What Every Programmer Absolutely, Positively Needs To Know About Encodings And Character Sets To Work With Text](https://kunststube.net/encoding/)

"This article is about encodings and character sets. An article by Joel Spolsky entitled [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!)](http://www.joelonsoftware.com/articles/Unicode.html) is a nice introduction to the topic and I greatly enjoy reading it every once in a while. I hesitate to refer people to it who have trouble understanding encoding problems though since, while entertaining, it is pretty light on actual technical details. I hope this article can shed some more light on what exactly an encoding is and just why all your text screws up when you least need it. This article is aimed at developers (with a focus on PHP), but any computer user should be able to benefit from it."

[More articles](./references.md)