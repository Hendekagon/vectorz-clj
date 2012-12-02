vectorz-clj
===========

Fast mutable vector library for Clojure, building on the vectorz library (https://github.com/mikera/vectorz).

Specifically designed for games, simulations and machine learning.

### Usage

Install with Leiningen / Maven from Clojars

### Purpose

vectorz-clj design goals:

 - Pure JVM code (i.e. no native dependencies)
 - Very fast, mutable vectors ("as fast as you can get on the JVM")
 - Different concrete vector types, e.g. primitive vectors for 2D/3D graphics (Vector2 and Vector3)
 - DSL for vector manipulation that can do useful things like vector subranges etc.
 
 vectorz-clj is implemented as a wrapper over the vectorz library, which provides the underlying data structures as well as a set of APIs that can be used from Java.