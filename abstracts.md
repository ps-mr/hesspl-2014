---
layout: index
---

{: .author}
Edlira Kuci

{: .title}
Abstract Dependent Classes

{: .abstract}
Software reuse provides means to combine existing components to
implement new functionalities. Dependent Classes are a powerful solution that
combines a lot of desirable features, including dynamic composition,
feature selection and static type checking.  
However, several research questions are still open. An important
issue is that many interesting applications of Dependent Classes
involve the use of abstract classes. However the calculus of Dependent Classes
does not support them. Type checking of abstract
declarations for dependent classes is challenging, because it
requires completeness and uniqueness checks for classes dispatched
by dependent types. We envisage that the existing calculus of
Dependent Classes can support abstract classes, show the changes that
are necessary and provide a roadmap for further research in the
field.

--------

{: .author}
Yufei Cai

{: .title}
Nominal Functors

{: .abstract}
we present Nominal Functors, a concise, expressive DSL for traversable
functors in Scala. Users write the type constructor of the functor,
the system generates the corresponding `fmap` method. Every
n-constructor datatype has at least 2^n traversable functors
associated with it; the DSL grants the user easy access to all of
them. This allows us to find a unifying connection between generic
programming techniques such as scrap-your-boilerplate,
almost-compositional-functions and biplate: Each technique essentially
creates a different traversable functor from a given datatype.

<!--
--------

{: .author}

{: .title}

{: .abstract}
-->
