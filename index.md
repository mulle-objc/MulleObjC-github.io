# MulleObjC

The root class library *MulleObjC* provides the base to write [mulle-objc](//mulle-objc.github.io)
Objective-C code. It's a lookalike of the Apple Foundation root classes and features classes such
as `NSObject` or `NSAutoreleasePool`. *MulleObjC* is based on *mulle-objc-runtime*,
the runtime library that is written in C.

*mulle-objc-compat* is a compatibility layer, that translates Apple runtime functions
such as `objc_getClass` into their *mulle-objc-runtime* equivalent, often at no 
additional cost.

The *mulle-objc-list* executable is used to create dependency information of *mulle-objc*
libraries. It is also needed for coverage-based link support.

Books                                                              | Description 
-------------------------------------------------------------------|----------------------
[De Re MulleObjC](//github.com/mulle-objc/De-Re-MulleObjC)         | A developer guide. Work in progress 
[MulleObjC Cheat Sheet](//github.com/mulle-objc/MulleObjC-Cheat-Sheet)   | A variation of the Objective-C CheatSheet, customized for MulleObjC. Work in progress

Library                                                            | Description 
-------------------------------------------------------------------|----------------------
[MulleObjC](//github.com/mulle-objc/MulleObjC)                     | A collection of Objective-C root classes for mulle-objc 
[mulle-objc-list](//github.com/mulle-objc/mulle-objc-list)         | Lists mulle-objc runtime information contained in executables.
[mulle-objc-compat](//github.com/mulle-objc/mulle-objc-compat)     | Compatibility layer with Apple Objective-C runtime functions  
[mulle-objc-runtime](//github.com/mulle-objc/mulle-objc-runtime)   | A fast, portable Objective-C runtime written 100% in C11
[mulle-objc-debug](//github.com/mulle-objc/mulle-objc-debug)       | Debugging support for the mulle-objc runtime


Library                                                            | Description 
-------------------------------------------------------------------|----------------------
[mulle-objc-runtime-startup](//github.com/mulle-objc/mulle-objc-runtime-startup) | Executables based on mulle-objc-runtime link with this 
[MulleObjC-startup](//github.com/mulle-objc/MulleObjC-startup) | Executables based on MulleObjC link with this 

The MulleObjC library collection is based on [mulle-concurrent](//mulle-core.github.io)
and [mulle-c](//mulle-c.github.io).
[MulleFoundation](//MulleFoundation.github.io) is based on *MulleObjC*


## mulle-sde support

Library                                                               | Description
----------------------------------------------------------------------|----------------------
[mulle-objc-developer](//github.com/mulle-objc/mulle-objc-developer)  | MulleObjC developer kit for mulle-sde 


## Install

See [mulle-objc-developer](//github.com/mulle-objc/mulle-objc-developer) for install instructions.

