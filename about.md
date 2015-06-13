---
layout: page
title: About
permalink: /about/
---


Hopes is a prototype interpreter for a higher-order PROLOG-like language.

The syntax of the language extends that of PROLOG by supporting higher-order
constructs (such as higher-order predicate variables, partial application and
lambda terms). In particular, the syntax allows clauses (and queries) that
contain uninstantiated predicate variables. The interpreter implements a
higher-order top-down SLD-resolution proof procedure.

In the case of uninstantiated predicate variables, the proof procedure will
systematically (and in a sophisticated way) investigate all finite instantiations
of these variables. In other words, Hopes has all the advantages of a higher-order
system but continues to keep the flavor of classical Prolog programming.

