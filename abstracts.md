---
layout: index
---

# Talks

--------

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

--------

{: .author}
Joscha Drechsler

{: .title}
Distributed REScala: An Update Propagation Algorithm for Distributed Reactive Programming

{: .abstract}
Reactive programming improves the design of reactive applications by relocating the logic for managing dependencies between dependent values away from the application logic to the language implementation. Many distributed applications are reactive. Yet, existing change propagation algorithms are not suitable in a distributed setting.  
We propose Distributed REScala, a reactive language with a change propagation algorithm that works without centralized knowledge about the topology of the dependency structure among reactive values and avoids unnecessary propagation of changes, while retaining safety guarantees (glitch freedom). Distributed REScala enables distributed reactive programming, bringing the benefits of reactive programming to distributed applications. We demonstrate the enabled design improvements by a case study. We also empirically evaluate the performance of our algorithm in comparison to other algorithms in a simulated distributed setting.

--------

{: .author}
Sebastian Erdweg

{: .title}
Capture-Avoiding and Hygienic Program Transformations

{: .abstract}
Program transformations in terms of abstract syntax trees compromise referential integrity by introducing variable capture. Variable capture occurs when in the generated program a variable declaration accidentally shadows the intended target of a variable reference. Existing transformation systems either do not guarantee the avoidance of variable capture or impair the implementation of transformations.  
We present an algorithm called *name-fix* that automatically eliminates variable capture from a generated program by systematically renaming variables. *name-fix* is guided by a graph representation of the binding structure of a program, and requires name-resolution algorithms for the source language and the target language of a transformation. *name-fix* is generic and works for arbitrary transformations in any transformation system that supports origin tracking for names. We verify the correctness of *name-fix* and identify an interesting class of transformations for which *name-fix* provides hygiene. We demonstrate the applicability of *name-fix* for implementing capture-avoiding substitution, inlining, lambda lifting, and compilers for two domain-specific languages.

--------

{: .author}
Oliver Bracevac

{: .title}
The Cloud Calculus

{: .abstract}
Over the last few years, cloud computing has emerged as the reference model for on-demand, fault-tolerant and scalable computations.
Despite the popularity of this model, little research has been devoted to the investigation of theoretical foundations.
We propose to fill this gap with a calculus that captures the essential aspects of cloud computing at the proper level of abstraction.
Our minimal cloud calculus is suitable for reasoning about cloud applications, can be easily extended to capture more semantic details
and is accompanied by a simple yet elegant metatheory.

<!--
--------

{: .author}

{: .title}

{: .abstract}
-->
