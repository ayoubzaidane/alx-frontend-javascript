# JavaScript Data Structures Overview
===================================

This document provides an overview of various data structures in JavaScript, including Arrays, Typed Arrays, Sets, Maps, and WeakMaps.

## Array
---------

Arrays in JavaScript are used to store multiple values in a single variable. They are indexed collections of data where each element can be accessed via its index.

### Key Points:

- Mutable and can contain elements of different data types.
- Use various methods like `push`, `pop`, `shift`, and `unshift` for manipulation.
- Common operations include iteration, slicing, and mapping.

## Typed Array
--------------

Typed Arrays are array-like objects that provide a mechanism for reading and writing raw binary data. They offer better performance and memory efficiency for handling large data sets.

### Key Points:

- Available types include `Int8Array`, `Uint8Array`, `Float32Array`, etc.
- Useful for tasks involving numerical computations or interfacing with APIs like WebGL.

## Set
------

Sets are collections of unique values, allowing you to store distinct values of any type.

### Key Points:

- Automatically removes duplicate values.
- Methods include `add`, `delete`, `has`, and `clear`.
- Iteration is straightforward using `forEach` or `for...of` loops.

## Map
------

Maps are collections of key-value pairs where each key can be of any type.

### Key Points:

- Provides an easy way to associate data with keys.
- Methods include `set`, `get`, `delete`, `has`, and `clear`.
- Iteration can be done using `forEach` or `for...of` loops.

## WeakMap
----------

WeakMaps are collections of key-value pairs where keys are weakly referenced. This means that if there are no other references to a key stored in a WeakMap, the key-value pair can be garbage-collected.

### Key Points:

- Keys must be objects, and values can be arbitrary.
- Useful for scenarios requiring additional metadata without affecting object lifecycle.

