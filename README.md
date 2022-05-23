# Two-level Hybrid: A System for Reasoning Using Higher-Order Abstract Syntax

Hybrid is a system designed for reasoning using higher-order abstract syntax representations of object logics. It is implemented in both Isabelle and Coq.

Mirror of HybridCoqV0.2.2 available from https://www.site.uottawa.ca/~afelty/HybridCoq/

## Meta

- Author(s):
  - [Amy Felty](https://www.site.uottawa.ca/~afelty/)
- Homepage: https://www.site.uottawa.ca/~afelty/HybridCoq/
- Compatible Coq versions: 8.13.1 or later
- Additional dependencies:
  - [dune](https://opam.ocaml.org/packages/dune/)
- Related publication(s):
  - Felty, A., Momigliano, A. Hybrid: A Definitional Two-Level Approach to Reasoning with Higher-Order Abstract Syntax. *J Autom Reasoning* **48,** 43--105 (2012). ([DOI](https://doi.org/10.1007/s10817-010-9194-x), [pdf](https://www.site.uottawa.ca/~afelty/dist/jar10.pdf)).

## Build instructions

``` shell
dune build
```

## Description
The Hybrid System in Coq

### Syntax and Specification Logic(s)
- Hybrid.v
- sl.v

### Equality Reasoning on Lambda Terms
- EqualUntypedR.v
- EqualUntypedG.v
- EqualUntypedR_ITP10.v
- EqualUntypedG_ITP10.v
- EqualPolyR.v
- EqualPolyG.v

### Uniqueness of Types for Simply-Typed Lambda Terms
- TypingSimple.v

### Reasoning about Shapes of Lambda Terms
- Shapes.v
- ShapesR.v
- ShapesG.v

### Reasoning about "Smaller" Relation on Lambda Terms
- StructUntyped.v

### Subject Reduction for Mini-ML
- MiniML.v
- SR_MiniML_eval.v
- SR_MiniML_meval.v
