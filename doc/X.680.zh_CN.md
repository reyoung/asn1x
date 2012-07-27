#ITU标准文档X.680--ASN.1基本符号说明#
##Introduction 简介##
##信息技术--ASN.1基本符号说明##
###Scope 范围###
这篇标准提供了一种叫做抽象语法符号--(ASN.1)的符号描述。这种符号描述可以用来定义数据类型,值以及数据类型的约束。

这篇标准:
* 定义了一系列简单类型。并定义了这些简单类型的名称，引用这些简单类型的记号和这些简单类型的取值。
* 定义了一种从简单类型中构造新类型的机制。指定了构造的类型，定义新类型名称，对新类型设置取值范围的语法记号。
* 定义了在ASN.1中使用的字符集(引用了其他标准)。

ASN.1符号可以用在任何需要定义信息的抽象语法的地方。
ASN.1符号被定义ASN.1类型的编码规范的其他标准引用.
###Normative references 规范的引用###
下面的这些国际标准包含了一些构成本国际保准的条款文本的一些条款.发布的时候,所有的版本都是可用的.所有的国际标准都会做出修订,在本协议基础上达成共同意见的各方将尽可能列出下面国际标准的最新版本.ISO和IEC的成员维护当前的可用的国际标准版本,ITU的电信标准化局维护当前可用的ITU-T建议版本.

####Identical Recommendations | International Standards ####
* CCITT Recommendation X.660 (1992) | ISO/IEC 9834-1:1993, Information technology – Open Systems Interconnection – Procedures for the operation of OSI Registration Authorities: General procedures: (plus amendments).
* ITU-T Recommendation X.681 (2002) | ISO/IEC 8824-2:2002, Information technology – Abstract Syntax Notation One (ASN.1): Information object specification.
* ITU-T Recommendation X.682 (2002) | ISO/IEC 8824-3:2002, Information technology – Abstract Syntax Notation One (ASN.1): Constraint specification.
* ITU-T Recommendation X.683 (2002) | ISO/IEC 8824-4:2002, Information technology – Abstract Syntax Notation One (ASN.1): Parameterization of ASN.1 specifications.
* ITU-T Recommendation X.690 (2002) | ISO/IEC 8825-1:2002, Information technology – ASN.1 encoding Rules: Specification of Basic Encoding Rules (BER), Canonical Encoding Rules (CER) and Distinguished Encoding Rules (DER).
* ITU-T Recommendation X.691 (2002) | ISO/IEC 8825-2:2002, Information technology – ASN.1 encoding rules: Specification of Packed Encoding Rules (PER).
* ITU-T Recommendation X.692 (2002) | ISO/IEC 8825-3:2002, Information technology – ASN.1 encoding rules: Specification of Encoding Control Notation (ECN).
* ITU-T Recommendation X.693 (2001) | ISO/IEC 8825-4:2002, Information technology – ASN.1 encoding rules: XML Encoding Rules (XER).

#### Additional references####
* ITU-R Recommendation TF.460-5 (1997), Standard-frequency and time-signal emissions.
* CCITT Recommendation T.100 (1988), International information exchange for interactive videotex.
* ITU-T Recommendation T.101 (1994), International interworking for videotex services.
* ISO International Register of Coded Character Sets to be used with Escape Sequences.
* ISO/IEC 646:1991, Information technology – ISO 7-bit coded character set for information interchange.
* ISO/IEC 2022:1994, Information technology – Character code structure and extension techniques.
* ISO/IEC 6523:1998, Data interchange – Structures for the identification of organizations.
* ISO/IEC 7350:1991, Information technology – Registration of repertoires of graphic characters from ISO/IEC 10367.
* ISO 8601:2000, Data elements and interchange formats – Information interchange – Representation of dates and times.
* ISO/IEC 10646-1:2000, Information technology – Universal Multiple-Octet Coded Character Set (UCS) – Part 1: Architecture and Basic Multilingual Plane.
* The Unicode Standard, Version 3.2.0:2002. The Unicode Consortium. (Reading, MA, Addison-Wesley)
NOTE 1 – The above reference is included because it provides names for control characters.
* W3C XML 1.0:2000, Extensible Markup Language (XML) 1.0 (Second Edition), W3C Recommendation, Copyright c [6 October 2000] World Wide Web Consortium, (Massachusetts Institute of Technology, Institut National de Recherche en Informatique et en Automatique, Keio University), http://www.w3.org/TR/2000/REC-xml-20001006.
NOTE 2 – The reference to a document within this Recommendation | International Standard does not give it, as a stand-alone document, the status of a Recommendation or International Standard.

###Definitions 定义###
由于该标准的用途，如下定义被使用。

####Information object specification 信息对象说明####
这篇国际标准使用了定义在ITU-T Rec. X.681 | ISO/IEC 8824-2中的术语。
* information object;(信息对象)
* information object class;(信息对象类)
* information object set;(信息对象集合)
* instance-of type;(实例化类型)
* object class field type.(对象类域类型)

####Constraint specification 约束说明

