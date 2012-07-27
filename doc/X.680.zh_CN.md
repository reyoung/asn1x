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

这篇国际标准中使用了定义在ITU-T Rec. X.682 | ISO/IEC 8824-3中的术语:
* component relation constraint;(组件关联约束)
* table constraint.(表约束)

####Parameterization of ASN.1 specification ASN.1的的参数说明

这篇国际标准中使用了定义在ITU-T Rec. X.683 | ISO/IEC 8824-4中的术语:
* parameterized type;(参数化类型)
* parameterized value.(参数化值)

####Structure for identification of organizations 组织标识结构
这篇国际标准中使用了定义在ISO/IEC 6523中的术语:
* issuing organization;
* organization code;
* International Code Designator.

####Universal Multiple-Octet Coded Character Set (UCS) 通用多字节字符集
这篇国际标准中使用了定义在ISO/IEC 10646-1中的术语:
* Basic Multilingual Plane (BMP);
* cell;
* combining character;
* graphic symbol;
* group;
* limited subset;
* plane;
* row;
* selected subset.

####附加的定义
##### abstract character 抽象字符
抽象字符是用来组织，控制和表示文本数据的。

*NOTE*-[附录F](#附录F)提供了关于抽象字符的更完整的描述.

##### abstract value 抽象值
一个值，这个值的定义仅仅基于用于表达语义的类型，与它在任何编码中如何表达无关。

*NOTE*-抽象值的例子是整型,布尔型,字符串类型或者是整型、布尔型的序列(或候选)的值.

####ASN.1 character set ASN.1字符集
[第十条](#TODO_填入第十条地址)中描述的用在ASN.1符号中的字符的集合.

####ASN.1 specification ASN.1说明
一个或多个ASN.1模块的集合。

####associated type 关联类型
关联类型是一个仅仅用于定义值或定义一种类型的子类型符号。

*NOTE*-<span stype="color:red">关联类型在本标准中定义，仅仅是因为必须说明ASN.1中类型的定义与编码之间的显著差别。关联类型的定义并未出现在用户说明中。</span>


##附录F##