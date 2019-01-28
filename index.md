# MulleObjC

The MulleObjC library collection is based on [mulle-concurrent](//mulle-core.github.io)
and [mulle-c](//mulle-c.github.io).

The provided root class library *MulleObjC* provides a the base to write Objective-C
code. It's a lookalike of the Apple Foundation root classes and features classes such
as `NSObject` or `NSAutoreleasePool`. *MulleObjC* is based on *mulle-objc-runtime*,
the runtime library that is written in C.

*mulle-objc-compat* is a compatibility layer, that translates Apple runtime functions
such as `objc_getClass` into their *mulle-objc-runtime* equivalent, often at no 
additional cost.

The *mulle-objc-list* executable is used to create dependency information of *mulle-objc*
libraries. It is also needed for coverage-based link support.

[MulleFoundation](//MulleFoundation.github.io) is based on *MulleObjC*


Library                                                            | Description 
-------------------------------------------------------------------|----------------------
[MulleObjC](//github.com/mulle-objc/MulleObjC)                     | A collection of Objective-C root classes for mulle-objc 
[mulle-objc-list](//github.com/mulle-objc/[mulle-objc-list)        | Lists mulle-objc runtime information contained in executables.
[mulle-objc-compat](//github.com/mulle-objc/mulle-objc-compat)     | Compatibility layer with Apple Objective-C runtime functions  
[mulle-objc-runtime](//github.com/mulle-objc/mulle-objc-runtime)   | A fast, portable Objective-C runtime written 100% in C11

## mulle-sde support

Library                                                               | Description
----------------------------------------------------------------------|----------------------
[mulle-objc-developer](//github.com/mulle-objc/mulle-objc-developer)  | MulleObjC developer kit for mulle-sde 


## Install

See [mulle-objc-developer](//github.com/mulle-objc/mulle-objc-developer) for install instructions.

