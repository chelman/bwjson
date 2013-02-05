bwjson
======

Custom JSON Library for use with Salesforce.com platform.

Introduction
============

This JSON Library was modified from Douglas Crockford's JSON Library implementation. It is intended to be use with Salesforce.com platform and other platforms that are compatible.

Quick Start
===========

* Upload BWJSON.js file to Static Resources folder in your Salesforce.com instance.
* Link the Library to the files that you want.

Example
=======

```
// Stringify Operation
var result = BWJSON.Stringify( Object );

// Parse Operation
var result = BWJSON.Parse( Object );

```

License
=======

MIT: http://rem.mit-license.org
